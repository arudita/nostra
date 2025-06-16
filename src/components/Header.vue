<script setup>
import { ref } from 'vue';

const isMenuOpen = ref(false);
</script>

<template>
    <header class="relative flex w-full px-12 py-6 md:px-24 md:py-8 z-50">
        <div class="grid grid-cols-2 md:grid-cols-3 justify-between items-center w-full">
            <h2 class="flex justify-start items-center text-xl font-bold">Backwaters</h2>
            <!-- Desktop Navigation -->
            <nav class="hidden md:inline-flex gap-8 justify-center">
                <RouterLink to="/" class="hover:text-gray-600">Home</RouterLink>
                <RouterLink to="/about" class="hover:text-gray-600">About</RouterLink>
                <RouterLink to="/products" class="hover:text-gray-600">Products</RouterLink>
                <RouterLink to="/contact" class="hover:text-gray-600">Contact</RouterLink>
            </nav>
            <!-- Desktop Search -->
            <div class="hidden md:flex justify-end items-center">
                <div class="relative group/search">
                    <button class="absolute left-3 top-1/4 cursor-pointer">
                        <svg class="size-4 fill-gray-300 mt-1 transition-colors group-focus-within/search:fill-gray-500 [:not(:placeholder-shown)+&]:fill-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z"/>
                        </svg>
                    </button>
                    <input type="text" placeholder="Search" class="font-normal text-base text-gray-800 border border-gray-300 rounded-lg pl-9 pr-3 py-2.5 transition-colors focus:outline-gray-500 peer">
                </div>
            </div>
            <!-- Mobile Hamburger Button -->
            <div class="flex md:hidden w-full items-center justify-end">
                <button @click="isMenuOpen = !isMenuOpen" class="block cursor-pointer">
                    <svg v-if="!isMenuOpen" class="size-5 fill-gray-800 transition-colors hover:fill-gray-800/80" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                        <path d="M0 96C0 78.3 14.3 64 32 64l384 0c17.7 0 32 14.3 32 32s-14.3 32-32 32L32 128C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32l384 0c17.7 0 32 14.3 32 32s-14.3 32-32 32L32 288c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32L32 448c-17.7 0-32-14.3-32-32s14.3-32 32-32l384 0c17.7 0 32 14.3 32 32z"/>
                    </svg>
                    <svg v-else class="size-5 fill-gray-800 transition-colors hover:fill-gray-800/80" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                        <path d="M342.6 150.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L192 210.7 86.6 105.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L146.7 256 41.4 361.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L192 301.3 297.4 406.6c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L237.3 256 342.6 150.6z"/>
                    </svg>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <Transition name="nested" :duration="550">
            <div v-if="isMenuOpen" class="outer md:hidden flex fixed inset-0 w-full h-full items-start bg-gray-800/90 z-40">
                <div class="inner-menu md:hidden block w-full h-fit bg-white px-12 py-6 md:px-24 md:py-8">
                    <div class="inline-flex w-full justify-between items-center mb-6 mt-9">
                        <h2 class="flex justify-start items-center text-xl font-bold">Backwaters</h2>
                        <div class="flex md:hidden w-full items-center justify-end">
                            <button @click="isMenuOpen = false" class="block cursor-pointer">
                                <svg class="size-5 fill-gray-800 transition-colors hover:fill-gray-800/80" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                                    <path d="M342.6 150.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L192 210.7 86.6 105.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L146.7 256 41.4 361.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L192 301.3 297.4 406.6c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L237.3 256 342.6 150.6z"/>
                                </svg>
                            </button>
                        </div>
                    </div>
                    <div class="flex flex-col gap-4">
                        <RouterLink to="/" class="hover:text-gray-600 py-2 border-b border-gray-100" @click="isMenuOpen = false">Home</RouterLink>
                        <RouterLink to="/about" class="hover:text-gray-600 py-2 border-b border-gray-100" @click="isMenuOpen = false">About</RouterLink>
                        <RouterLink to="/products" class="hover:text-gray-600 py-2 border-b border-gray-100" @click="isMenuOpen = false">Products</RouterLink>
                        <RouterLink to="/contact" class="hover:text-gray-600 py-2 border-b border-gray-100" @click="isMenuOpen = false">Contact</RouterLink>
                        <!-- Mobile Search -->
                        <div class="relative group/search mt-4">
                            <button class="absolute left-3 top-1/4 cursor-pointer">
                                <svg class="size-4 fill-gray-300 mt-1 transition-colors group-focus-within/search:fill-gray-500 [:not(:placeholder-shown)+&]:fill-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z"/>
                                </svg>
                            </button>
                            <input type="text" placeholder="Search" class="w-full font-normal text-base text-gray-800 border border-gray-300 rounded-lg pl-9 pr-3 py-2.5 transition-colors focus:outline-gray-500 peer">
                        </div>
                    </div>
                </div>
                <div class="inner-button fixed bottom-1/6 inset-x-0">
                    <button @click="isMenuOpen = !isMenuOpen" class="group block cursor-pointer mx-auto p-4 bg-white/30 rounded-full">
                        <svg class="size-5 fill-gray-800 group-hover:scale-120 transition-transform" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                            <path d="M342.6 150.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L192 210.7 86.6 105.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L146.7 256 41.4 361.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L192 301.3 297.4 406.6c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L237.3 256 342.6 150.6z"/>
                        </svg>
                    </button>
                </div>
            </div>
        </Transition>
    </header>
</template>

<style scoped>
.nested-enter-active, .nested-leave-active {
	transition: all 0.3s ease-in-out;
}
.nested-leave-active {
  transition-delay: 0.25s;
}
.nested-enter-from, .nested-leave-to {
  opacity: 0;
}
.nested-enter-active .inner-menu, .nested-leave-active .inner-menu { 
  transition: all 0.3s ease-in-out;
}
.nested-enter-active .inner-menu {
	transition-delay: 0.25s;
}
.nested-enter-from .inner-menu, .nested-leave-to .inner-menu {
  transform: translateY(-5px);
  opacity: 0.001;
}
.nested-enter-active .inner-button, .nested-leave-active .inner-button { 
  transition: all 0.3s ease-in-out;
}
.nested-enter-active .inner-button {
	transition-delay: 0.25s;
}
.nested-enter-from .inner-button, .nested-leave-to .inner-button {
  transform: scale(0);
  opacity: 0.001;
}
</style>