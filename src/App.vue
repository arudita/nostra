<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Announcement from '@/components/Announcement.vue'
import Header from '@/components/Header.vue'
import Footer from './components/Footer.vue';
</script>

<template>
    <Announcement />
    <Header />
    
    <router-view v-slot="{ Component }">
        <transition name="fade" mode="out-in" appear>
            <component :is="Component"/>
        </transition>
    </router-view>

    <Footer />
</template>

<style scoped>
.fade-enter-active, .fade-leave-active {
    transition: opacity 0.5s ease;
}
.fade-enter-from, .fade-leave-to {
    opacity: 0;
}
</style>