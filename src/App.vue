<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Announcement from '@/components/Announcement.vue'
import Header from '@/components/Header.vue'
import Footer from './components/Footer.vue';
</script>

<template>
    <Announcement />
    <Header />
    <RouterView />
    <Footer />
</template>

<style scoped>
</style>
