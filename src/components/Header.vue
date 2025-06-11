<template>
    <header class="relative flex w-full px-12 py-6 md:px-24 md:py-8">
        <div class="grid grid-cols-2 md:grid-cols-3 justify-between items-center w-full">
            <h2 class="flex justify-start items-center text-xl font-bold">Backwaters</h2>
            <nav class="hidden md:inline-flex gap-8 justify-center">
                <RouterLink to="/" class="hover:text-gray-600">Home</RouterLink>
                <RouterLink to="#" class="hover:text-gray-600">About</RouterLink>
                <RouterLink to="#" class="hover:text-gray-600">Products</RouterLink>
                <RouterLink to="#" class="hover:text-gray-600">Projects</RouterLink>
                <RouterLink to="#" class="hover:text-gray-600">Contact</RouterLink>
            </nav>
            <div class="hidden md:flex justify-end items-center">
                <div class="relative">
                    <button class="absolute left-3 top-1/4 cursor-pointer"> 
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="size-5 stroke-gray-300 hover:stroke-gray-600">
                            <path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
                        </svg>
                    </button>
                    <input type="text" placeholder="Search" class="border border-gray-300 rounded-lg pl-9 pr-3 py-2.5 focus-within:outline-gray-600">
                </div>
            </div>
        </div>
    </header>
</template>