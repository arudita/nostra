<script setup>
// Featured Products Section
const products = [
    {
        id: 1, image: '/images/armchair-2.png', alt: 'Product image 1', url: '#', name: 'Wooden Armchair Soft Foam (Grey)', sale: true, price_final: 58, price_initial: 65
    },
    {
        id: 2, image: '/images/sofa-1.png', alt: 'Product image 2', url: '#', name: 'Wooden Sofa with Soft Foam (Grey)', sale: false, price_final: 58, price_initial: 0
    },
    {
        id: 3, image: '/images/sideboard-1.png', alt: 'Product image 3', url: '#', name: 'Sideboard 3 Storage', sale: true, price_final: 32, price_initial: 38
    },
    {
        id: 4, image: '/images/sofa-2.png', alt: 'Product image 4', url: '#', name: 'Wooden Sofa with Soft Foam (Peach)', sale: true, price_final: 49, price_initial: 56
    },
    {
        id: 5, image: '/images/armchair-1.png', alt: 'Product image 5', url: '#', name: 'Armchair with Soft Foam', sale: false, price_final: 58, price_initial: 0
    },
    {
        id: 6, image: '/images/daybed-1.png', alt: 'Product image 6', url: '#', name: 'Wooden Daybed', sale: false, price_final: 58, price_initial: 0
    },
];
</script>
<template>
    <div class="relative flex flex-col w-full px-12 md:px-24">
        <!-- Section #3 Featured Products -->
        <div class="relative w-full mb-20">
            <div class="relative inline-flex w-full h-full justify-between items-center mb-10">
                <h3 class="text-3xl font-semibold">
                    Featured Products
                </h3>
            </div>
            <div class="relative overflow-hidden w-full mb-12 md:mb-15">
                <div class="flex transition-transform duration-300 ease-in-out">
                    <div class="w-full flex-shrink-0 grid grid-cols-2 md:grid-cols-3 gap-6">
                        <div v-for="product in products" :key="product.id" class="group block w-full h-full">
                            <a href="#" class="relative w-full h-full aspect-square">
                                <figure class=" border border-gray-300 group-hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                                    <img :src="product.image" :alt="product.name" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                                </figure>
                                <div v-if="product.sale" class="absolute top-0 left-0 right-0 px-3 pt-3">
                                    <div class="flex justify-start items-center w-fit h-full bg-red-600 border border-gray-500 transition-colors py-1.5 px-2.5 rounded-lg">
                                        <span class="text-white text-sm font-semibold">SALE</span>
                                    </div>
                                </div>
                            </a>
                            <div class="flex justify-between w-full mt-5">
                                <div class="w-full overflow-hidden">
                                    <a href="#">
                                        <p class="w-5/6 font-normal text-sm text-gray-600 truncate mb-2">{{ product.name }}</p>
                                    </a>
                                    <div class="relative inline-flex items-start">
                                        <span class="font-semibold text-2xl mr-1">${{ product.price_final }}</span>
                                        <span v-if="product.sale" class="font-normal text-sm text-gray-400 line-through pt-0.5">${{ product.price_initial }}</span>
                                    </div>
                                </div>
                                <button class="block h-fit bg-gray-800 rounded-lg p-4 cursor-pointer hover:bg-gray-800/95 transition-colors">
                                    <svg class="size-5 fill-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                        <path d="M0 24C0 10.7 10.7 0 24 0L69.5 0c22 0 41.5 12.8 50.6 32l411 0c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3l-288.5 0 5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5L488 336c13.3 0 24 10.7 24 24s-10.7 24-24 24l-288.3 0c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5L24 48C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/>
                                    </svg>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Pagination Indicators -->
            <div class="block w-1/3 h-1.5 mx-auto border border-gray-800 rounded-full">
                <div class="w-1/2 block h-full bg-gray-800"></div>
            </div>
        </div>
    </div>
</template>