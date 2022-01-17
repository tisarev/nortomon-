<template>
    <nuxt-link to="/" class="logo">

            <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                <rect width="50" height="50" rx="25" fill="#111827"/>
            </svg>
            <div class="logo__text">
                <div class="logo__text-heading">Nortomon</div>
                <div class="text-description">Description</div>
            </div>

    </nuxt-link>
</template>
<script>
export default {

}
</script>
<style>
    a.logo{
        background-color: var(--color-white);
        display: flex;
        align-items: center;
        gap: 10px;
        padding: 10px 10px 10px var(--pl-20);
    }
    a.logo:hover{
        box-shadow: var(--shadow-base);
    }
    .logo__text-heading{
        font-weight: bold;
    }
    .text-description{
        font-size: var(--font-smalltext);
        color: var(--color-gray-500);
    }
</style>