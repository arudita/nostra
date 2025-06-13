<template>
    <header class="relative flex w-full px-12 py-6 md:px-24 md:py-8">
        <div class="grid grid-cols-2 md:grid-cols-3 justify-between items-center w-full">
            <h2 class="flex justify-start items-center text-xl font-bold">Backwaters</h2>
            <nav class="hidden md:inline-flex gap-8 justify-center">
                <RouterLink to="/" class="hover:text-gray-600">Home</RouterLink>
                <RouterLink to="/about" class="hover:text-gray-600">About</RouterLink>
                <RouterLink to="/products" class="hover:text-gray-600">Products</RouterLink>
                <RouterLink to="/contact" class="hover:text-gray-600">Contact</RouterLink>
            </nav>
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
        </div>
    </header>
</template>