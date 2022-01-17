<template>
<section class="section">
    <UiMenuTop />
    <div class="section-block">
        <div class="table-list">
            <ul class="table-list__block table-list__heading">
                <li>
                    <input type="checkbox">
                    Name
                </li>
                <li>
                    Company
                </li>
                <li>
                    Contacts
                </li>
                <li>
                    Group
                </li>
                <li>
                    Role
                </li>
                <li>
                </li>
            </ul>
            <ul class="table-list__block table-list__content">
                <li>
                    <input type="checkbox">
                    <div class="table-list__block__name">
                        <div class="table-list__block__name-img">F</div>
                        <div class="table-list__block__name-wrapper">
                            <div class="table-list__text">First Name</div>
                            <div class="table-list__text">Last Name</div>
                        </div>
                    </div>
                </li>
                <li>
                    <div class="table-list__text">Company name</div>
                    <div class="text-description">CIty, Street name 123</div>
                </li>
                <li>
                    <div class="table-list__text">8 800 123-45-67</div>
                    <div class="text-description">info@gmail.com</div>
                </li>
                <li>
                    <div class="table-list__text">Group name</div>
                </li>
                <li>
                    <div class="table-list__text">Owner</div>
                </li>
                <li>
                    <a href="#">
                        <svg class="icon-edit">
                            <use xlink:href="#icon-edit"/>
                        </svg>
                    </a>
                    <a href="#">
                        <svg class="icon-delete">
                            <use xlink:href="#icon-delete"/>
                        </svg>
                    </a>
                </li>
            </ul>
        </div>
    </div>
    
</section>
</template>
<script>
import SettingData from '@/assets/datatext/users.json'
    
    export default ({
        data: () => ({
            setting: SettingData
        }),
        mounted () {
        }
    })
</script>