<template>
    <section class="sidebar">
        <div class="sidebar__wrapper">
            <SidebarLogo />
            <div class="sidebar__menu">
                <SidebarMenuManage />
            </div>
        </div>
        <SidebarProfile />
    </section>
</template>

<script>

</script>

<style>
    .sidebar{
        flex: 0 0 auto;
        position: relative;
        background: var(--color-gray-200);
        border-right: 1px var(--color-gray-300) solid;
        width: 250px;
        overflow: hidden;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
</style>