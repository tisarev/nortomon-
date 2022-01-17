<template>
    <nav class="menu">
        <div class="menu-description">
            Manage
        </div>
        <ul>
            <li>
                <nuxt-link to="/users" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-users">
                            <use xlink:href="#icon-users"/>
                        </svg>
                        Users
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/recording-points" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-recording-points">
                            <use xlink:href="#icon-recording-points"/>
                        </svg>
                        Recording points
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/reports" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-reports">
                            <use xlink:href="#icon-reports"/>
                        </svg>
                        Reports
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/payments" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-payments">
                            <use xlink:href="#icon-payments"/>
                        </svg>
                        Payments
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/tariff" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-tariff">
                            <use xlink:href="#icon-tariff"/>
                        </svg>
                        Tariff
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/promo-code" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-promo-code">
                            <use xlink:href="#icon-promo-code"/>
                        </svg>
                        Promo code
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/directory" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-directory">
                            <use xlink:href="#icon-directory"/>
                        </svg>
                        Directory
                    </div>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/mobile-users" active-class="active">
                    <div class="menu-link">
                        <svg class="icon-mobile-users">
                            <use xlink:href="#icon-mobile-users"/>
                        </svg>
                        Mobile users
                    </div>
                </nuxt-link>
            </li>
        </ul>
    </nav>
</template>

<script>
    
    export default ({

    })
</script>
