<template>
    <nav class="menu">
        <div class="menu-description">
            Setting
        </div>
        <ul>
            <li v-for="settingitem in setting.setting" :key="settingitem.id">
                <nuxt-link :to="`${settingitem.menulink}`" active-class="active">
                    <div class="menu-link">
                        <img :src="settingitem.menuicon" />
                        {{ settingitem.menutext }}
                    </div>
                    <div v-if="settingitem.alert" class="menu-number">{{ settingitem.alert }}</div>
                </nuxt-link>
            </li>
        </ul>
    </nav>
</template>
<style>
    
</style>
<script>
import SettingData from '@/assets/datatext/setting.json'
    
    export default ({
        data: () => ({
            setting: SettingData
        }),
        mounted () {
        }
    })
</script>
