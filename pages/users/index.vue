<template>
<section class="section">
    <UiMenuTop />
    <div class="section-block">
        <ul class="table-list">
            <li class="table-list__block table-list__heading">
                <ul>
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
            </li>
            <li class="table-list__block table-list__content" v-for="useritem in users.users" :key="useritem.id">
                <ul>
                    <li>
                        <input type="checkbox" class="table-list__input">
                        <div class="table-list__block__name">
                            <img :src="require(`~/assets/datatext/img/${useritem.img}.jpg`)" />
                            <!-- <div class="table-list__block__name-img">F</div> -->
                            <div class="table-list__block__name-wrapper">
                                <div class="table-list__text">{{useritem.firstName}}</div>
                                <div class="table-list__text">{{useritem.lastName}}</div>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="table-list__text">{{useritem.company}}</div>
                        <div class="text-description">{{useritem.address}}</div>
                    </li>
                    <li>
                        <div class="table-list__text">{{useritem.phone}}</div>
                        <div class="text-description">{{useritem.email}}</div>
                    </li>
                    <li>
                        <div class="table-list__text">{{useritem.group}}</div>
                    </li>
                    <li>
                        <div class="table-list__text">{{useritem.role}}</div>
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
            </li>
        </ul>
    </div>
    
</section>
</template>
<script>
import UserData from '@/assets/datatext/users.json'
    
    export default ({
        data: () => ({
            users: UserData
        }),
        mounted () {
        }
    })
</script>