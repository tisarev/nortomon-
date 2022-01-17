<template>
    <nav class="menutop">
        <ul>
            <li>
                <nuxt-link to="/users" active-class="active" exact>
                    All Users
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/users/roles" active-class="active">
                    Roles
                </nuxt-link>
            </li>
            <li>
                <nuxt-link to="/users/selected" active-class="active">
                    Selected
                </nuxt-link>
            </li>
        </ul>
    </nav>
</template>