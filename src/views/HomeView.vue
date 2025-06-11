<template>
    <div class="relative flex flex-col w-full px-12 md:px-24">
        <!-- Hero Section -->
        <figure class="relative w-full h-[60dvh] md:h-[80dvh] rounded-lg overflow-hidden border border-gray-300 mb-20">
            <img src="" alt="hero images" class="object-cover object-center w-full h-full min-w-full">
            <div class="absolute inline-flex items-center top-6 right-6 bg-gray-50 z-10 border border-gray-300 rounded-lg">
                <button class="group cursor-pointer p-4">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="size-5 stroke-gray-300 group-hover:stroke-gray-600">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5 8.25 12l7.5-7.5" />
                    </svg>
                </button>
                <div class="inline-block min-h-full w-0.5 self-stretch bg-gray-100"></div>
                <button class="group cursor-pointer p-4">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="size-5 stroke-gray-300 group-hover:stroke-gray-600">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m8.25 4.5 7.5 7.5-7.5 7.5" />
                    </svg>
                </button>
            </div>
        </figure>
        <!-- Section #1 -->
        <div class="relative w-full mb-20">
            <div class="relative inline-flex w-full h-full justify-between items-center mb-10">
                <h3 class="text-3xl font-semibold">
                    We provide best <br>customer experiences
                </h3>
                <div class="inline-flex items-center space-x-6">
                    <div class="inline-block min-h-16 w-0.5 self-stretch bg-gray-800"></div>
                    <p class="text-sm font-normal">We ensure our customers have the best shopping experience</p>
                </div>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4">
                <div class="block w-full pr-14">
                    <div class="block w-fit p-3 rounded-lg border border-gray-300 mb-4">
                        <svg class="size-4 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                            <path d="M160 0c17.7 0 32 14.3 32 32l0 35.7c1.6 .2 3.1 .4 4.7 .7c.4 .1 .7 .1 1.1 .2l48 8.8c17.4 3.2 28.9 19.9 25.7 37.2s-19.9 28.9-37.2 25.7l-47.5-8.7c-31.3-4.6-58.9-1.5-78.3 6.2s-27.2 18.3-29 28.1c-2 10.7-.5 16.7 1.2 20.4c1.8 3.9 5.5 8.3 12.8 13.2c16.3 10.7 41.3 17.7 73.7 26.3l2.9 .8c28.6 7.6 63.6 16.8 89.6 33.8c14.2 9.3 27.6 21.9 35.9 39.5c8.5 17.9 10.3 37.9 6.4 59.2c-6.9 38-33.1 63.4-65.6 76.7c-13.7 5.6-28.6 9.2-44.4 11l0 33.4c0 17.7-14.3 32-32 32s-32-14.3-32-32l0-34.9c-.4-.1-.9-.1-1.3-.2l-.2 0s0 0 0 0c-24.4-3.8-64.5-14.3-91.5-26.3c-16.1-7.2-23.4-26.1-16.2-42.2s26.1-23.4 42.2-16.2c20.9 9.3 55.3 18.5 75.2 21.6c31.9 4.7 58.2 2 76-5.3c16.9-6.9 24.6-16.9 26.8-28.9c1.9-10.6 .4-16.7-1.3-20.4c-1.9-4-5.6-8.4-13-13.3c-16.4-10.7-41.5-17.7-74-26.3l-2.8-.7s0 0 0 0C119.4 279.3 84.4 270 58.4 253c-14.2-9.3-27.5-22-35.8-39.6c-8.4-17.9-10.1-37.9-6.1-59.2C23.7 116 52.3 91.2 84.8 78.3c13.3-5.3 27.9-8.9 43.2-11L128 32c0-17.7 14.3-32 32-32z"/>
                        </svg>
                    </div>
                    <h4 class="font-semibold text-base mb-2">
                        Original Products
                    </h4>
                    <p class="text-wrap">
                        We provide money back guarantee if the product are not original
                    </p>
                </div>
                <div class="block w-full pr-14">
                    <div class="block w-fit p-3 rounded-lg border border-gray-300 mb-4">
                        <svg class="size-5 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path d="M464 256A208 208 0 1 0 48 256a208 208 0 1 0 416 0zM0 256a256 256 0 1 1 512 0A256 256 0 1 1 0 256zm177.6 62.1C192.8 334.5 218.8 352 256 352s63.2-17.5 78.4-33.9c9-9.7 24.2-10.4 33.9-1.4s10.4 24.2 1.4 33.9c-22 23.8-60 49.4-113.6 49.4s-91.7-25.5-113.6-49.4c-9-9.7-8.4-24.9 1.4-33.9s24.9-8.4 33.9 1.4zM144.4 208a32 32 0 1 1 64 0 32 32 0 1 1 -64 0zm192-32a32 32 0 1 1 0 64 32 32 0 1 1 0-64z"/>
                        </svg>
                    </div>
                    <h4 class="font-semibold text-base mb-2">
                        Satisfaction Guarantee
                    </h4>
                    <p class="text-wrap">
                        Exchange the product you’ve purchased if it doesn’t fit on you
                    </p>
                </div>
                <div class="block w-full pr-14">
                    <div class="block w-fit p-3 rounded-lg border border-gray-300 mb-4">
                        <svg class="size-5 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                            <path d="M290.8 48.6l78.4 29.7L288 109.5 206.8 78.3l78.4-29.7c1.8-.7 3.8-.7 5.7 0zM136 92.5l0 112.2c-1.3 .4-2.6 .8-3.9 1.3l-96 36.4C14.4 250.6 0 271.5 0 294.7L0 413.9c0 22.2 13.1 42.3 33.5 51.3l96 42.2c14.4 6.3 30.7 6.3 45.1 0L288 457.5l113.5 49.9c14.4 6.3 30.7 6.3 45.1 0l96-42.2c20.3-8.9 33.5-29.1 33.5-51.3l0-119.1c0-23.3-14.4-44.1-36.1-52.4l-96-36.4c-1.3-.5-2.6-.9-3.9-1.3l0-112.2c0-23.3-14.4-44.1-36.1-52.4l-96-36.4c-12.8-4.8-26.9-4.8-39.7 0l-96 36.4C150.4 48.4 136 69.3 136 92.5zM392 210.6l-82.4 31.2 0-89.2L392 121l0 89.6zM154.8 250.9l78.4 29.7L152 311.7 70.8 280.6l78.4-29.7c1.8-.7 3.8-.7 5.7 0zm18.8 204.4l0-100.5L256 323.2l0 95.9-82.4 36.2zM421.2 250.9c1.8-.7 3.8-.7 5.7 0l78.4 29.7L424 311.7l-81.2-31.1 78.4-29.7zM523.2 421.2l-77.6 34.1 0-100.5L528 323.2l0 90.7c0 3.2-1.9 6-4.8 7.3z"/>
                        </svg>
                    </div>
                    <h4 class="font-semibold text-base mb-2">
                        New Arrival Everyday
                    </h4>
                    <p class="text-wrap">
                        we updates our collections almost everyday
                    </p>
                </div>
                <div class="block w-full pr-14">
                    <div class="block w-fit p-3 rounded-lg border border-gray-300 mb-4">
                        <svg class="size-5 fill-gray-800" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512">
                            <path d="M48 0C21.5 0 0 21.5 0 48L0 368c0 26.5 21.5 48 48 48l16 0c0 53 43 96 96 96s96-43 96-96l128 0c0 53 43 96 96 96s96-43 96-96l32 0c17.7 0 32-14.3 32-32s-14.3-32-32-32l0-64 0-32 0-18.7c0-17-6.7-33.3-18.7-45.3L512 114.7c-12-12-28.3-18.7-45.3-18.7L416 96l0-48c0-26.5-21.5-48-48-48L48 0zM416 160l50.7 0L544 237.3l0 18.7-128 0 0-96zM112 416a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm368-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/>
                        </svg>
                    </div>
                    <h4 class="font-semibold text-base mb-2">
                        Fast & Free Shipping
                    </h4>
                    <p class="text-wrap">
                        We offer fast and free shipping for our loyal customers
                    </p>
                </div>
            </div>
        </div>
        <!-- Section #2 Currated Picks -->
        <div class="relative w-full mb-20">
            <div class="relative inline-flex w-full h-full justify-between items-center mb-10">
                <h3 class="text-3xl font-semibold">
                    Currated picks
                </h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-6">
                <div href="#" class="relative group block w-full h-full auto-rows-fr aspect-square border border-gray-300 hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                    <figure class="w-full h-full">
                        <img src="/images/category-armchair.jpg" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                    </figure>
                    <div class="absolute bottom-0 left-0 right-0 px-7 pb-7">
                        <a href="#" class="group/link flex justify-between items-center w-full h-full bg-white/70 border border-gray-300 hover:border-gray-500 transition-colors py-3.5 px-5 rounded-lg">
                            <span class="text-base font-medium">Armchair</span>
                            <svg class="size-5 fill-gray-800 -translate-x-1 group-hover/link:translate-x-0 transition-transform" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                                <path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                <div href="#" class="relative group block w-full h-full auto-rows-fr aspect-square border border-gray-300 hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                    <figure class="w-full h-full">
                        <img src="/images/category-sideboard.jpg" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                    </figure>
                    <div class="absolute bottom-0 left-0 right-0 px-7 pb-7">
                        <a href="#" class="group/link flex justify-between items-center w-full h-full bg-white/70 border border-gray-300 hover:border-gray-500 transition-colors py-3.5 px-5 rounded-lg">
                            <span class="text-base font-medium">Sideboard</span>
                            <svg class="size-5 fill-gray-800 -translate-x-1 group-hover/link:translate-x-0 transition-transform" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                                <path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                <div href="#" class="relative group block w-full h-full auto-rows-fr aspect-square border border-gray-300 hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                    <figure class="w-full h-full">
                        <img src="/images/category-sofa.jpg" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                    </figure>
                    <div class="absolute bottom-0 left-0 right-0 px-7 pb-7">
                        <a href="#" class="group/link flex justify-between items-center w-full h-full bg-white/70 border border-gray-300 hover:border-gray-500 transition-colors py-3.5 px-5 rounded-lg">
                            <span class="text-base font-medium">Sofa</span>
                            <svg class="size-5 fill-gray-800 -translate-x-1 group-hover/link:translate-x-0 transition-transform" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                                <path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                <div href="#" class="relative group block w-full h-full auto-rows-fr aspect-square border border-gray-300 hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                    <figure class="w-full h-full">
                        <img src="/images/category-table.jpg" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                    </figure>
                    <div class="absolute bottom-0 left-0 right-0 px-7 pb-7">
                        <a href="#" class="group/link flex justify-between items-center w-full h-full bg-white/70 border border-gray-300 hover:border-gray-500 transition-colors py-3.5 px-5 rounded-lg">
                            <span class="text-base font-medium">Table</span>
                            <svg class="size-5 fill-gray-800 -translate-x-1 group-hover/link:translate-x-0 transition-transform" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                                <path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/>
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <!-- Section #3 Featured Products -->
        <div class="relative w-full mb-20">
            <div class="relative inline-flex w-full h-full justify-between items-center mb-10">
                <h3 class="text-3xl font-semibold">
                    Featured Products
                </h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-15">
                <div class="group block w-full h-full">
                    <a href="#" class="relative w-full h-full aspect-square">
                        <figure class=" border border-gray-300 group-hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                            <img src="/images/armchair-2.png" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                        </figure>
                        <div class="absolute top-0 left-0 right-0 px-3 pt-3">
                            <div class="flex justify-start items-center w-fit h-full bg-red-600 border border-gray-500 transition-colors py-1.5 px-2.5 rounded-lg">
                                <span class="text-white text-sm font-semibold">SALE</span>
                            </div>
                        </div>
                    </a>
                    <div class="flex justify-between w-full mt-5">
                        <div class="w-full overflow-hidden">
                            <a href="#">
                                <p class="w-5/6 font-normal text-sm text-gray-600 truncate mb-2">Armchair Soft Foarm</p>
                            </a>
                            <div class="relative inline-flex items-start">
                                <span class="font-semibold text-2xl mr-1">$58</span>
                                <span class="font-normal text-sm text-gray-400 line-through pt-0.5">$65</span>
                            </div>
                        </div>
                        <button class="block h-fit bg-gray-800 rounded-lg p-4 cursor-pointer hover:bg-gray-800/95 transition-colors">
                            <svg class="size-5 fill-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                <path d="M0 24C0 10.7 10.7 0 24 0L69.5 0c22 0 41.5 12.8 50.6 32l411 0c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3l-288.5 0 5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5L488 336c13.3 0 24 10.7 24 24s-10.7 24-24 24l-288.3 0c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5L24 48C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/>
                            </svg>
                        </button>
                    </div>
                </div>
                <div class="group block w-full h-full">
                    <a href="#" class="relative w-full h-full aspect-square">
                        <figure class=" border border-gray-300 group-hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                            <img src="/images/sofa-1.png" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                        </figure>
                    </a>
                    <div class="flex justify-between w-full mt-5">
                        <div class="w-full overflow-hidden">
                            <a href="#">
                                <p class="w-5/6 font-normal text-sm text-gray-600 truncate mb-2">Sofa Soft Foam</p>
                            </a>
                            <div class="relative inline-flex items-start">
                                <span class="font-semibold text-2xl mr-1">$58</span>
                            </div>
                        </div>
                        <button class="block h-fit bg-gray-800 rounded-lg p-4 cursor-pointer hover:bg-gray-800/95 transition-colors">
                            <svg class="size-5 fill-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                                <path d="M0 24C0 10.7 10.7 0 24 0L69.5 0c22 0 41.5 12.8 50.6 32l411 0c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3l-288.5 0 5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5L488 336c13.3 0 24 10.7 24 24s-10.7 24-24 24l-288.3 0c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5L24 48C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/>
                            </svg>
                        </button>
                    </div>
                </div>
                <div class="group block w-full h-full">
                    <a href="#" class="relative w-full h-full aspect-square">
                        <figure class=" border border-gray-300 group-hover:border-gray-500 transition-colors rounded-lg overflow-hidden">
                            <img src="/images/sideboard-1.png" alt="Bed" class="object-cover object-center w-full h-auto group-hover:scale-105 transition-transform">
                        </figure>
                        <div class="absolute top-0 left-0 right-0 px-3 pt-3">
                            <div class="flex justify-start items-center w-fit h-full bg-red-600 border border-gray-500 transition-colors py-1.5 px-2.5 rounded-lg">
                                <span class="text-white text-sm font-semibold">SALE</span>
                            </div>
                        </div>
                    </a>
                    <div class="flex justify-between w-full mt-5">
                        <div class="w-full overflow-hidden">
                            <a href="#">
                                <p class="w-5/6 font-normal text-sm text-gray-600 truncate mb-2">Wooden Sideboard 3 Storage</p>
                            </a>
                            <div class="relative inline-flex items-start">
                                <span class="font-semibold text-2xl mr-1">$58</span>
                                <span class="font-normal text-sm text-gray-400 line-through pt-0.5">$65</span>
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
            <div class=""></div>
        </div>
    </div>
</template>