<script setup>
// Featured Products Section
const products = [
    {
        id: 1, image: '/images/armchair-1.png', alt: 'Product image', url: '#', name: 'Armchair with Soft Foam', sale: false, price_final: 58, price_initial: 0
    },
    {
        id: 2, image: '/images/armchair-2.png', alt: 'Product image', url: '#', name: 'Armchair with Soft Foam', sale: true, price_final: 58, price_initial: 65
    },
    {
        id: 3, image: '/images/armchair-3.png', alt: 'Product image', url: '#', name: 'Armchair with Soft Foam', sale: true, price_final: 58, price_initial: 65
    },
    {
        id: 4, image: '/images/armchair-4.png', alt: 'Product image', url: '#', name: 'Armchair with Soft Foam', sale: true, price_final: 58, price_initial: 65
    },
    {
        id: 5, image: '/images/sofa-1.png', alt: 'Product image', url: '#', name: 'Wooden Sofa with Soft Foam', sale: false, price_final: 58, price_initial: 0
    },
    {
        id: 6, image: '/images/sofa-2.png', alt: 'Product image', url: '#', name: 'Wooden Sofa with Soft Foam', sale: true, price_final: 49, price_initial: 56
    },
    {
        id: 7, image: '/images/sofa-3.png', alt: 'Product image', url: '#', name: 'Wooden Sofa with Soft Foam', sale: true, price_final: 49, price_initial: 56
    },
    {
        id: 8, image: '/images/sideboard-1.png', alt: 'Product image', url: '#', name: 'Sideboard', sale: true, price_final: 32, price_initial: 38
    },
    {
        id: 9, image: '/images/sideboard-2.png', alt: 'Product image', url: '#', name: 'Sideboard', sale: true, price_final: 32, price_initial: 38
    },
    {
        id: 10, image: '/images/sideboard-3.png', alt: 'Product image', url: '#', name: 'Sideboard', sale: true, price_final: 32, price_initial: 38
    },
    {
        id: 11, image: '/images/sideboard-4.png', alt: 'Product image', url: '#', name: 'Sideboard', sale: true, price_final: 32, price_initial: 38
    },
    {
        id: 12, image: '/images/daybed-1.png', alt: 'Product image', url: '#', name: 'Wooden Daybed', sale: false, price_final: 58, price_initial: 0
    },
    {
        id: 13, image: '/images/stool-1.png', alt: 'Product image', url: '#', name: 'Stool', sale: false, price_final: 58, price_initial: 0
    },
    {
        id: 14, image: '/images/table-1.png', alt: 'Product image', url: '#', name: 'Wooden Table', sale: false, price_final: 58, price_initial: 0
    },
];
</script>
<template>
    <div class="relative flex flex-col w-full px-12 md:px-24">
        <!-- Section #1 Featured Products -->
        <div class="relative w-full my-20">
            <div class="grid grid-cols-1 md:grid-cols-2 w-full h-full justify-between items-center mb-10">
                <h3 class="font-medium text-center text-4xl md:text-6xl md:text-left">
                    Our Products
                </h3>
            </div>
            <div class="relative flex w-full h-full md:max-h-80 rounded-lg overflow-hidden">
                <figure class="w-full h-full">
                    <img src="/images/banner-1.jpg" alt="" class="object-cover object-center w-full h-full">
                </figure>
                <div class="absolute inset-0 flex flex-col justify-center w-1/2 px-6 md:px-12">
                    <h3 class="font-bold text-4xl md:text-6xl text-gray-50 mb-4">
                        Get 25% Cash Back <br>On $350
                    </h3>
                    <p class="hidden md:block text-xs md:text-sm text-gray-50">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Beatae sequi fugiat aliquid ab est veniam cum neque harum expedita, libero eos commodi. Dolorum, modi!
                    </p>
                </div>
            </div>
        </div>
        <!-- Section #2 Featured Products -->
        <div class="relative w-full mb-20">
            <div class="grid grid-cols-1 md:grid-cols-4 not-md:space-y-5 md:space-x-10">
                <!-- List Filters -->
                <div class="flex flex-col justify-start">
                    <div class="flex justify-between w-full font-semibold text-xs md:text-sm mb-6">
                        <span>Filter</span>
                        <button class="hover:text-red-400 transition-colors cursor-pointer">
                            Reset
                        </button>
                    </div>
                    <div class="flex flex-col items-start w-full space-y-3 mb-6">
                        <button type="button" class="text-xs md:text-sm hover:text-gray-600 transition-colors cursor-pointer">
                            View All Products
                        </button>
                        <button type="button" class="text-xs md:text-sm hover:text-gray-600 transition-colors cursor-pointer">
                            New Arrivals
                        </button>
                        <button type="button" class="text-xs md:text-sm hover:text-gray-600 transition-colors cursor-pointer">
                            Best Sellers
                        </button>
                    </div>
                    <details class="group relative overflow-hidden rounded-lg border border-gray-300 mb-3">
                        <summary class="flex items-center justify-between gap-2 p-3 text-gray-700 transition-colors hover:text-gray-900 [&::-webkit-details-marker]:hidden">
                            <span class="font-medium text-xs md:text-sm"> Seating </span>
                            <span class="transition-transform group-open:-rotate-180">
                                <svg class="size-4 fill-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M233.4 406.6c12.5 12.5 32.8 12.5 45.3 0l192-192c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L256 338.7 86.6 169.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l192 192z"/>
                                </svg>
                            </span>
                        </summary>
                        <div class="divide-y divide-gray-300 border-t border-gray-300 bg-white">
                            <fieldset class="p-3">
                                <legend class="sr-only">Seating</legend>
                                <div class="flex flex-col items-start text-sm text-gray-500 gap-3">
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Benches
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Dining Chairs
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Lounge Chairs
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Stools
                                    </button>
                                </div>
                            </fieldset>
                        </div>
                    </details>
                    <details class="group relative overflow-hidden rounded-lg border border-gray-300 mb-3">
                        <summary class="flex items-center justify-between gap-2 p-3 text-gray-700 transition-colors hover:text-gray-900 [&::-webkit-details-marker]:hidden">
                            <span class="font-medium text-xs md:text-sm"> Tables </span>
                            <span class="transition-transform group-open:-rotate-180">
                                <svg class="size-4 fill-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M233.4 406.6c12.5 12.5 32.8 12.5 45.3 0l192-192c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L256 338.7 86.6 169.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l192 192z"/>
                                </svg>
                            </span>
                        </summary>
                        <div class="divide-y divide-gray-300 border-t border-gray-300 bg-white">
                            <fieldset class="p-3">
                                <legend class="sr-only">Tables</legend>
                                <div class="flex flex-col items-start text-sm text-gray-500 gap-3">
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Coffee Tables
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Console Tables
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Desks & Writing Tables
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Dining Tables
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Nightstands
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Side Tables
                                    </button>
                                </div>
                            </fieldset>
                        </div>
                    </details>
                    <details class="group relative overflow-hidden rounded-lg border border-gray-300 mb-3">
                        <summary class="flex items-center justify-between gap-2 p-3 text-gray-700 transition-colors hover:text-gray-900 [&::-webkit-details-marker]:hidden">
                            <span class="font-medium text-xs md:text-sm"> Storage </span>
                            <span class="transition-transform group-open:-rotate-180">
                                <svg class="size-4 fill-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M233.4 406.6c12.5 12.5 32.8 12.5 45.3 0l192-192c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L256 338.7 86.6 169.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l192 192z"/>
                                </svg>
                            </span>
                        </summary>
                        <div class="divide-y divide-gray-300 border-t border-gray-300 bg-white">
                            <fieldset class="p-3">
                                <legend class="sr-only">Storage</legend>
                                <div class="flex flex-col items-start text-sm text-gray-500 gap-3">
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Bookcases & Shelving
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Buffets & Sideboards
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Dressers & Armoires
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Storage Cupboards
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        TV Stands & Media Consoles
                                    </button>
                                </div>
                            </fieldset>
                        </div>
                    </details>
                    <details class="group relative overflow-hidden rounded-lg border border-gray-300 mb-3">
                        <summary class="flex items-center justify-between gap-2 p-3 text-gray-700 transition-colors hover:text-gray-900 [&::-webkit-details-marker]:hidden">
                            <span class="font-medium text-xs md:text-sm"> Beds </span>
                            <span class="transition-transform group-open:-rotate-180">
                                <svg class="size-4 fill-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M233.4 406.6c12.5 12.5 32.8 12.5 45.3 0l192-192c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L256 338.7 86.6 169.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l192 192z"/>
                                </svg>
                            </span>
                        </summary>
                        <div class="divide-y divide-gray-300 border-t border-gray-300 bg-white">
                            <fieldset class="p-3">
                                <legend class="sr-only">Beds</legend>
                                <div class="flex flex-col items-start text-sm text-gray-500 gap-3">
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Canopy Bed
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Sleigh Bed
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Four Poster Bed
                                    </button>
                                    <button type="button" class="text-xs md:text-sm hover:text-gray-700 cursor-pointer">
                                        Panel Bed
                                    </button>
                                </div>
                            </fieldset>
                        </div>
                    </details>
                    <details class="group relative overflow-hidden rounded-lg border border-gray-300">
                        <summary class="flex items-center justify-between gap-2 p-3 text-gray-700 transition-colors hover:text-gray-900 [&::-webkit-details-marker]:hidden">
                            <span class="font-medium text-xs md:text-sm"> Price </span>
                            <span class="transition-transform group-open:-rotate-180">
                                <svg class="size-4 fill-gray-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M233.4 406.6c12.5 12.5 32.8 12.5 45.3 0l192-192c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L256 338.7 86.6 169.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3l192 192z"/>
                                </svg>
                            </span>
                        </summary>
                        <div class="divide-y divide-gray-300 border-t border-gray-300 bg-white">
                            <div class="flex items-center justify-between text-xs md:text-sm text-gray-700 px-3 py-2">
                                <span> Max price is $1.200 </span>
                                <button type="button" class="hover:text-red-400 transition-colors cursor-pointer">
                                    Reset
                                </button>
                            </div>
                            <div class="flex items-center text-xs md:text-sm gap-3 p-3">
                                <label for="MinPrice" class="w-full">
                                    <span class="text-sm text-gray-700"> Min </span>
                                    <input type="number" id="MinPrice" value="0" min="0" max="1199" class="w-full rounded-lg border border-gray-300 focus-within:border-gray-500 outline-none mt-1 p-2" />
                                </label>
                                <label for="MaxPrice" class="w-full">
                                    <span class="text-sm text-gray-700"> Max </span>
                                    <input type="number" id="MaxPrice" value="1200" min="1" max="1200" class="w-full rounded-lg border border-gray-300 focus-within:border-gray-500 outline-none mt-1 p-2" />
                                </label>
                            </div>
                        </div>
                    </details>
                </div>
                <!-- List Products -->
                <div class="flex flex-col transition-transform duration-300 ease-in-out col-span-3">
                    <div class="w-full flex-shrink-0 grid grid-cols-2 md:grid-cols-4 gap-6">
                        <div v-for="item in products" :key="item.id" class="group block w-full h-full">
                            <RouterLink to="product-details" class="relative w-full h-full aspect-square">
                                <figure class="border border-gray-300 group-hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                                    <img :src="item.image" :alt="item.name" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                                </figure>
                                <div v-if="item.sale" class="absolute top-0 left-0 right-0 px-3 pt-3">
                                    <div class="flex justify-start items-center w-fit h-full bg-red-600 py-1 px-2 rounded-lg">
                                        <span class="text-xs md:text-sm text-white font-semibold">SALE</span>
                                    </div>
                                </div>
                            </RouterLink>
                            <div class="flex justify-between w-full mt-5">
                                <div class="w-full overflow-hidden">
                                    <RouterLink to="product-details">
                                        <p class="w-5/6 font-normal text-sm text-gray-500 truncate hover:text-gray-700 transition-colors mb-2">{{ item.name }}</p>
                                    </RouterLink>
                                    <div class="relative inline-flex items-start">
                                        <span class="font-semibold text-2xl mr-1">${{ item.price_final }}</span>
                                        <span v-if="item.sale" class="font-normal text-sm text-gray-400 line-through pt-0.5">${{ item.price_initial }}</span>
                                    </div>
                                </div>
                                <button class="block h-fit bg-gray-800 rounded-lg p-2 md:p-3 cursor-pointer hover:bg-gray-800/95 transition-colors">
                                    <svg class="size-4 md:size-5 fill-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                        <path d="M0 24C0 10.7 10.7 0 24 0L69.5 0c22 0 41.5 12.8 50.6 32l411 0c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3l-288.5 0 5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5L488 336c13.3 0 24 10.7 24 24s-10.7 24-24 24l-288.3 0c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5L24 48C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/>
                                    </svg>
                                </button>
                            </div>
                        </div>
                    </div>
                    <ul class="flex justify-center gap-1.5 mt-6">
                        <li>
                            <a href="#" class="grid size-8 place-content-center rounded border border-gray-300 transition-colors hover:bg-gray-100" aria-label="Previous page">
                                <svg class="size-2.5 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                                    <path d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l192 192c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L77.3 256 246.6 86.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-192 192z"/>
                                </svg>
                            </a>
                        </li>
                        <li>
                            <a href="#" class="block size-8 rounded border border-gray-300 text-center text-sm/8 font-medium transition-colors hover:bg-gray-100">
                                1
                            </a>
                        </li>
                        <li class="block size-8 rounded border border-gray-500 bg-gray-500 text-center text-sm/8 font-medium text-white">
                            2
                        </li>
                        <li>
                            <a href="#" class="block size-8 rounded border border-gray-300 text-center text-sm/8 font-medium transition-colors hover:bg-gray-100">
                                3
                            </a>
                        </li>
                        <li>
                            <a href="#" class="block size-8 rounded border border-gray-300 text-center text-sm/8 font-medium transition-colors hover:bg-gray-100">
                                4
                            </a>
                        </li>
                        <li>
                            <a href="#" class="grid size-8 place-content-center rounded border border-gray-300 transition-colors hover:bg-gray-100" aria-label="Next page">
                                <svg class="size-2.5 fill-gray-800"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                                    <path d="M310.6 233.4c12.5 12.5 12.5 32.8 0 45.3l-192 192c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L242.7 256 73.4 86.6c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0l192 192z"/>
                                </svg>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>