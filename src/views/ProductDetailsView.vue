<script setup>
// List Products
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
];
</script>
<template>
    <div class="relative flex flex-col w-full px-12 md:px-24">
        <!-- Section #1 Product Details -->
        <div class="relative w-full mb-20">
            <div class="grid grid-cols-1 md:grid-cols-2 w-full gap-8 lg:gap-12">
                <div class="flex flex-1 flex-col w-full">
                    <figure class="w-full h-full aspect-square bg-gray-100 rounded-lg overflow-hidden mb-4">
                        <img src="/images/armchair-3.png" alt="" class="object-cover object-center w-full h-full">
                    </figure>
                    <div class="grid grid-cols-3 gap-4">
                        <figure class="w-full h-full aspect-square bg-gray-100 rounded-lg overflow-hidden">
                            <img src="/images/armchair-3.png" alt="" class="object-cover object-center w-full h-full">
                        </figure>
                        <figure class="w-full h-full aspect-square bg-gray-100 rounded-lg overflow-hidden">
                            <img src="/images/armchair-3.png" alt="" class="object-cover object-center w-full h-full">
                        </figure>
                        <figure class="w-full h-full aspect-square bg-gray-100 rounded-lg overflow-hidden">
                            <img src="/images/armchair-3.png" alt="" class="object-cover object-center w-full h-full">
                        </figure>
                    </div>
                </div>
                <div class="flex flex-1 flex-col w-full">
                    <!-- Breadcrumb -->
                    <nav aria-label="Breadcrumb" class="mb-4">
                        <ol class="flex items-center gap-1 text-sm text-gray-700 dark:text-gray-200">
                            <li>
                                <RouterLink to="home" class="block transition-colors hover:text-gray-700">
                                    Home
                                </RouterLink>
                            </li>
                            <li>\</li>
                            <li>
                                <RouterLink to="#" class="block transition-colors hover:text-gray-700">
                                    Category
                                </RouterLink>
                            </li>
                            <li>\</li>
                            <li>
                                <span class="block transition-colors hover:text-gray-700">
                                    Armchair with Soft Foam
                                </span>
                            </li>
                        </ol>
                    </nav>
                    <h3 class="font-medium text-2xl md:text-4xl mb-1">
                        Armchair with Soft Foam
                    </h3>
                    <div class="flex flex-0 justify-start items-center w-full mb-4">
                        <div class="inline-flex gap-2 mr-3">
                            <div class="relative">
                                <!-- Rating Value (Full) -->
                                <svg class="absolute inset-0 size-4 fill-yellow-300 z-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                                <!-- Rating Base -->
                                <svg class="size-4 fill-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                            </div>
                            <div class="relative">
                                <!-- Rating Value (Full) -->
                                <svg class="absolute inset-0 size-4 fill-yellow-300 z-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                                <!-- Rating Base -->
                                <svg class="size-4 fill-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                            </div>
                            <div class="relative">
                                <!-- Rating Value (Full) -->
                                <svg class="absolute inset-0 size-4 fill-yellow-300 z-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                                <!-- Rating Base -->
                                <svg class="size-4 fill-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                            </div>
                            <div class="relative">
                                <!-- Rating Value (Half) -->
                                <svg class="absolute inset-0 size-4 fill-yellow-300 z-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M288 0c-12.2 .1-23.3 7-28.6 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3L288 439.8 288 0zM429.9 512c1.1 .1 2.1 .1 3.2 0l-3.2 0z"/>
                                </svg>
                                <!-- Rating Base -->
                                <svg class="size-4 fill-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                            </div>
                            <div class="relative">
                                <!-- Rating Base (Only) -->
                                <svg class="size-4 fill-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                    <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                </svg>
                            </div>
                        </div>
                        <span class="font-medium text-xs md:text-sm">1.5K Reviews</span>
                    </div>
                    <div class="relative inline-flex items-start w-full mb-4">
                        <span class="font-semibold text-2xl md:text-4xl mr-1">$49.99</span>
                        <span class="font-normal text-sm text-gray-400 line-through pt-0.5">$58</span>
                    </div>
                    <div class="block w-full mb-4">
                        <h3 class="font-medium text-sm md:text-base mb-2">
                            Product Description
                        </h3>
                        <p class="text-xs md:text-sm text-gray-500 w-full text-justify text-wrap">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium a est, asperiores, ipsam repellat rem earum eaque quo qui ipsum cumque in provident amet quam voluptatum? Illo dicta quos veniam aliquid recusandae velit neque possimus quod ipsa! Minima, laudantium, placeat suscipit corporis laboriosam voluptate asperiores quasi illum porro, alias minus?
                        </p>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 w-full mb-4 gap-4">
                        <div class="block border border-gray-300 rounded-lg p-4 space-y-2">
                            <div class="inline-flex items-center w-full gap-2">
                                <svg class="size-4 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M177.9 494.1c-18.7 18.7-49.1 18.7-67.9 0L17.9 401.9c-18.7-18.7-18.7-49.1 0-67.9l50.7-50.7 48 48c6.2 6.2 16.4 6.2 22.6 0s6.2-16.4 0-22.6l-48-48 41.4-41.4 48 48c6.2 6.2 16.4 6.2 22.6 0s6.2-16.4 0-22.6l-48-48 41.4-41.4 48 48c6.2 6.2 16.4 6.2 22.6 0s6.2-16.4 0-22.6l-48-48 41.4-41.4 48 48c6.2 6.2 16.4 6.2 22.6 0s6.2-16.4 0-22.6l-48-48 50.7-50.7c18.7-18.7 49.1-18.7 67.9 0l92.1 92.1c18.7 18.7 18.7 49.1 0 67.9L177.9 494.1z"/>
                                </svg>
                                <h3 class="font-medium text-sm md:text-base">
                                    Dimensions
                                </h3>
                            </div>
                            <div class="flex justify-between items-center w-full">
                                <span class="text-xs md:text-sm text-gray-500">Width</span>
                                <p class="font-medium text-xs md:text-sm">
                                    24 inches
                                </p>
                            </div>
                            <div class="flex justify-between items-center w-full">
                                <span class="text-xs md:text-sm text-gray-500">Height</span>
                                <p class="font-medium text-xs md:text-sm">
                                    40 inches
                                </p>
                            </div>
                        </div>
                        <div class="block border border-gray-300 rounded-lg p-4 space-y-2">
                            <div class="inline-flex items-center w-full gap-2">
                                <svg class="size-4 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path d="M78.6 5C69.1-2.4 55.6-1.5 47 7L7 47c-8.5 8.5-9.4 22-2.1 31.6l80 104c4.5 5.9 11.6 9.4 19 9.4l54.1 0 109 109c-14.7 29-10 65.4 14.3 89.6l112 112c12.5 12.5 32.8 12.5 45.3 0l64-64c12.5-12.5 12.5-32.8 0-45.3l-112-112c-24.2-24.2-60.6-29-89.6-14.3l-109-109 0-54.1c0-7.5-3.5-14.5-9.4-19L78.6 5zM19.9 396.1C7.2 408.8 0 426.1 0 444.1C0 481.6 30.4 512 67.9 512c18 0 35.3-7.2 48-19.9L233.7 374.3c-7.8-20.9-9-43.6-3.6-65.1l-61.7-61.7L19.9 396.1zM512 144c0-10.5-1.1-20.7-3.2-30.5c-2.4-11.2-16.1-14.1-24.2-6l-63.9 63.9c-3 3-7.1 4.7-11.3 4.7L352 176c-8.8 0-16-7.2-16-16l0-57.4c0-4.2 1.7-8.3 4.7-11.3l63.9-63.9c8.1-8.1 5.2-21.8-6-24.2C388.7 1.1 378.5 0 368 0C288.5 0 224 64.5 224 144l0 .8 85.3 85.3c36-9.1 75.8 .5 104 28.7L429 274.5c49-23 83-72.8 83-130.5zM56 432a24 24 0 1 1 48 0 24 24 0 1 1 -48 0z"/>
                                </svg>
                                <h3 class="font-medium text-sm md:text-base">
                                    Materials
                                </h3>
                            </div>
                            <div class="flex justify-between items-center w-full">
                                <span class="text-xs md:text-sm text-gray-500">Seat</span>
                                <p class="font-medium text-xs md:text-sm">
                                    Premium Leather
                                </p>
                            </div>
                            <div class="flex justify-between items-center w-full">
                                <span class="text-xs md:text-sm text-gray-500">Legs</span>
                                <p class="font-medium text-xs md:text-sm">
                                    Teak Wood & Metal
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="block w-full mb-4">
                        <div class="inline-flex w-full justify-between items-center mb-2">
                            <h3 class="font-medium text-sm md:text-base">
                                Reviews & Rating
                            </h3>
                            <a href="#" class="text-xs md:text-sm">View All Reviews</a>
                        </div>
                        <div class="flex flex-col w-full gap-4">
                            <div class="block w-full border border-gray-300 rounded-lg p-4">
                                <div class="inline-flex justify-between items-center w-full mb-4">
                                    <div class="inline-flex items-center w-full gap-3">
                                        <figure class="size-10 bg-gray-100 rounded-full overflow-hidden">
                                            <img src="/images/team-male.jpg" alt="" class="object-cover object-center w-full h-full">
                                        </figure>
                                        <div class="flex flex-col flex-1 text-xs md:text-sm">
                                            <span class="font-medium">Jacob Johnson</span>
                                            <span class="text-gray-500">June 15, 2025</span>
                                        </div>
                                    </div>
                                    <div class="inline-flex items-center gap-1">
                                        <svg class="size-4 fill-yellow-300 z-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                            <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                        </svg>
                                        <span class="font-medium text-sm md:text-base">4.5</span>
                                    </div>
                                </div>
                                <p class="text-xs md:text-sm text-gray-500 text-justify text-wrap">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem et amet aut deleniti pariatur excepturi blanditiis aperiam perferendis vero quas at ad ut, saepe ea in repudiandae sint, mollitia necessitatibus?
                                </p>
                            </div>
                            <div class="block w-full border border-gray-300 rounded-lg p-4">
                                <div class="inline-flex justify-between items-center w-full mb-4">
                                    <div class="inline-flex items-center w-full gap-3">
                                        <figure class="size-10 bg-gray-100 rounded-full overflow-hidden">
                                            <img src="/images/team-male.jpg" alt="" class="object-cover object-center w-full h-full">
                                        </figure>
                                        <div class="flex flex-col flex-1 text-xs md:text-sm">
                                            <span class="font-medium">Eva Caspian</span>
                                            <span class="text-gray-500">June 09, 2025</span>
                                        </div>
                                    </div>
                                    <div class="inline-flex items-center gap-1">
                                        <svg class="size-4 fill-yellow-300 z-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                            <path d="M316.9 18C311.6 7 300.4 0 288.1 0s-23.4 7-28.8 18L195 150.3 51.4 171.5c-12 1.8-22 10.2-25.7 21.7s-.7 24.2 7.9 32.7L137.8 329 113.2 474.7c-2 12 3 24.2 12.9 31.3s23 8 33.8 2.3l128.3-68.5 128.3 68.5c10.8 5.7 23.9 4.9 33.8-2.3s14.9-19.3 12.9-31.3L438.5 329 542.7 225.9c8.6-8.5 11.7-21.2 7.9-32.7s-13.7-19.9-25.7-21.7L381.2 150.3 316.9 18z"/>
                                        </svg>
                                        <span class="font-medium text-sm md:text-base">4.0</span>
                                    </div>
                                </div>
                                <p class="text-xs md:text-sm text-gray-500 text-justify text-wrap">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores amet aliquam odit molestias, tempore, dolorum reiciendis doloribus dolor quam vel dolores ratione perspiciatis similique enim officiis rerum cumque sit quaerat at provident!
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Section #2 Similar Products -->
        <div class="relative w-full mb-20">
            <div class="relative inline-flex w-full h-full justify-between items-center mb-10">
                <h3 class="text-3xl font-semibold">
                    You May Also Like
                </h3>
            </div>
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
                        <div class="block w-full mt-5 overflow-hidden">
                            <RouterLink to="product-details">
                                <p class="w-5/6 font-normal text-sm text-gray-500 truncate hover:text-gray-700 transition-colors mb-2">{{ item.name }}</p>
                            </RouterLink>
                            <div class="relative inline-flex items-start">
                                <span class="font-semibold text-2xl mr-1">${{ item.price_final }}</span>
                                <span v-if="item.sale" class="font-normal text-sm text-gray-400 line-through pt-0.5">${{ item.price_initial }}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>