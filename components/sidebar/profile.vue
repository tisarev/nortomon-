<template>
    <div class="block-profile">
        <div class="block-profile__wrapper">
            <nuxt-link to="/authorization">
                <picture>
                    <source :srcSet="require('~/assets/img/user.jpg?webp')" type="image/webp" />
                    <source :srcSet="require('~/assets/img/user.jpg')" type="image/jpeg" />
                    <img :src="require('~/assets/img/user.jpg')" />
                </picture>
            </nuxt-link>
            <div class="block-profile__text">
                <nuxt-link to="/authorization">
                    <div class="block-profile__user">Tisarev Alexey</div>
                </nuxt-link>
                <div class="text-description">Administrator</div>
            </div>
        </div>
        <div class="block-profile__exit">
            <svg class="icon-exit">
                <use xlink:href="#icon-exit"/>
            </svg>
        </div>
    </div>
</template>
<style>
    .block-profile{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 15px 10px 15px var(--pl-20);
        background: var(--color-white);
        margin-top: var(--pt20);
    }
    .block-profile__wrapper{
        display: flex;
        align-items: center;
        gap: 10px;
    }
    .block-profile__exit{
        height: 20px;
        cursor: pointer;
    }
    svg.icon-exit{
        fill: transparent;
        width: 20px;
        height: 20px;
        stroke: var(--color-gray-400);
    }
    svg.icon-exit:hover{
        stroke: var(--color-gray-600);
    }
    .block-profile__wrapper picture img{
        width: 40px;
        height: 40px;
        border-radius: 50%;
    }
</style>