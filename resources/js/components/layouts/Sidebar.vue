<template>
    <div class="main-menu menu-fixed menu-light menu-accordion menu-shadow" data-scroll-to-active="true">
        <div class="navbar-header">
            <ul class="nav navbar-nav flex-row">
                <li class="nav-item mr-auto"><a class="navbar-brand" href="">
                    <div class="brand-logo"></div>
                    <h2 class="brand-text mb-0">Vuexy</h2>
                </a></li>
                <li class="nav-item nav-toggle"><a class="nav-link modern-nav-toggle pr-0" data-toggle="collapse"><i class="feather icon-x d-block d-xl-none font-medium-4 primary toggle-icon"></i><i class="toggle-icon feather icon-disc font-medium-4 d-none d-xl-block collapse-toggle-icon primary" data-ticon="icon-disc"></i></a></li>
            </ul>
        </div>
        <div class="shadow-bottom"></div>
        <div class="main-menu-content">
            <ul class="navigation navigation-main" id="main-menu-navigation" data-menu="menu-navigation">
                <li class="nav-item"><router-link to="/"><i class="feather icon-home"></i><span class="menu-title" data-i18n="Dashboard">Dashboard</span></router-link></li>
                <li class="nav-item"><router-link to="/email"><i class="feather icon-mail"></i><span class="menu-title" data-i18n="Email">Email</span></router-link></li>
                <li class="nav-item"><router-link to="/users"><i class="feather icon-users"></i><span class="menu-title" data-i18n="Email">Users</span></router-link></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Sidebar",
        data() {
            return { is_active: false }
        }
    }
</script>

<style scoped>

</style>
