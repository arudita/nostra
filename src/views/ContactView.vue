<template>
    <div class="relative flex flex-col w-full px-12 md:px-24">
        <!-- Section #4 Limited Offer & Subscribe to our Newsletter -->
        <div class="relative w-full mb-20">
            <div class="relative w-full grid grid-cols-1 md:grid-cols-12 overflow-hidden rounded-lg mb-20">
                <div class="block md:col-span-5 bg-white">
                    <figure class="w-full h-full">
                        <img src="/images/hero-image-5.jpg" alt="Bed" class="object-cover object-center w-full h-full group-hover:scale-105 transition-transform">
                    </figure>
                </div>
                <div class="flex flex-col flex-1 items-stretch w-full h-full md:col-span-7 bg-gray-900 text-white p-10 xl:p-15">
                    <p class="font-normal text-sm text-center md:text-left uppercase mb-2">Limited Offer</p>
                    <h2 class="font-semibold text-3xl text-center md:text-left md:text-5xl xl:text-6xl mb-12 xl:max-w-5/6">35% off only this friday and get special gift</h2>
                    <a href="#" class="group/link flex justify-between items-center w-fit gap-3 mt-auto not-md:mx-auto bg-white border border-gray-300 hover:border-gray-500 transition-colors py-3.5 px-5 rounded-lg">
                        <span class="font-medium text-base text-gray-800">Grab it now</span>
                        <svg class="size-5 fill-gray-800 -translate-x-1 group-hover/link:translate-x-0 transition-transform" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                            <path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="relative w-full">
                <h2 class="font-semibold text-3xl text-gray-800 text-center max-w-2xl mx-auto mb-4">
                    Subscribe to our newsletter to get updates to our latest collections
                </h2>
                <p class="font-normal text-sm text-gray-800 text-center max-w-xl mx-auto mb-8">
                    Get 20% off on your first order just by subscribing to our newsletter
                </p>
                <form class="flex justify-center mb-5">
                    <div class="inline-flex gap-2">
                        <label for="email" class="relative inline-flex items-center py-3.5 pl-12 pr-4 border border-gray-100 bg-gray-50 rounded-lg">
                            <input type="email" id="email" placeholder="Enter Your Email" class="w-full focus:outline-0 text-gray-800" />
                            <svg class="absolute left-4 size-5 fill-gray-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                <path d="M64 112c-8.8 0-16 7.2-16 16l0 22.1L220.5 291.7c20.7 17 50.4 17 71.1 0L464 150.1l0-22.1c0-8.8-7.2-16-16-16L64 112zM48 212.2L48 384c0 8.8 7.2 16 16 16l384 0c8.8 0 16-7.2 16-16l0-171.8L322 328.8c-38.4 31.5-93.7 31.5-132 0L48 212.2zM0 128C0 92.7 28.7 64 64 64l384 0c35.3 0 64 28.7 64 64l0 256c0 35.3-28.7 64-64 64L64 448c-35.3 0-64-28.7-64-64L0 128z"/>
                            </svg>
                        </label>
                        <button type="submit" class="w-fit text-white bg-gray-800 py-3.5 px-4 rounded-lg cursor-pointer hover:bg-gray-800/90 transition-colors duration-300">Subscribe</button>
                    </div>
                </form>
                <p class="font-normal text-sm text-gray-800 text-center mx-auto">
                    You will be able to unsubscribe at any time. <br> Read our Privacy Policy <a href="#" class="font-semibold hover:underline transition duration-300">here</a>.
                </p>
            </div>
        </div>
    </div>
</template>