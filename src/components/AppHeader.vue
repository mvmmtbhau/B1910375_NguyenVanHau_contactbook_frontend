<template>
    <nav class="navbar navbar-expend navbar-dark bg-dark">
        <a href="/" class="navbar-brand">Ứng dụng Quản lý danh bạ</a>
        <div class="mr-auto navbar-nav">
            <router-link :to="{ name: 'contactbook' }" class="nav-link">
                Danh bạ
                <i class="fas fa-address-book"></i>
            </router-link>
        </div>
    </nav>
</template>