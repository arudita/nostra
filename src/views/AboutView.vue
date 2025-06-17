<script setup>
import { ref } from 'vue';

const videoPlayer = ref(null);
const isPlaying = ref(false);

const togglePlay = () => {
  if (videoPlayer.value.paused) {
    videoPlayer.value.play();
    isPlaying.value = true;
  } else {
    videoPlayer.value.pause();
    isPlaying.value = false;
  }
};
</script>
<template>
    <div class="relative flex flex-col w-full px-12 md:px-24">
        <!-- Section #1 -->
        <div class="relative w-full my-20">
            <div class="grid grid-cols-1 md:grid-cols-2 w-full h-full justify-between items-center mb-10">
                <h3 class="font-medium text-center text-4xl md:text-6xl md:text-left">
                    About Us
                </h3>
                <div class="justify-self-end inline-flex items-center space-x-6">
                    <p class="text-xs md:text-sm text-center text-gray-500 md:text-left not-md:mt-4">
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Exercitationem iure optio nisi! Doloremque natus repellendus esse laborum nihil laboriosam voluptate rerum ad soluta doloribus.
                    </p>
                </div>
            </div>
            <div class="flex w-full md:h-[60dvh] rounded-lg overflow-hidden">
                <figure class="w-full h-full">
                    <img src="/images/team-1.jpg" alt="" class="object-cover object-center w-full h-full">
                </figure>
            </div>
        </div>
        <!-- Section #2 -->
        <div class="relative w-full mb-20">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="block text-center md:text-left">
                    <h3 class="font-medium text-4xl md:text-6xl">
                        1000+
                    </h3>
                    <p class="text-sm md:text-base text-gray-500 mt-2">
                        Clients helped globally
                    </p>
                </div>
                <div class="block text-center md:text-left">
                    <h3 class="font-medium text-4xl md:text-6xl">
                        200+
                    </h3>
                    <p class="text-sm md:text-base text-gray-500 mt-2">
                        Licensed professionals
                    </p>
                </div>
                <div class="block text-center md:text-left">
                    <h3 class="font-medium text-4xl md:text-6xl">
                        95%
                    </h3>
                    <p class="text-sm md:text-base text-gray-500 mt-2">
                        Client satisfaction rate
                    </p>
                </div>
                <div class="block text-center md:text-left">
                    <h3 class="font-medium text-4xl md:text-6xl">
                        15+
                    </h3>
                    <p class="text-sm md:text-base text-gray-500 mt-2">
                        Years of experience
                    </p>
                </div>
            </div>
        </div>
        <!-- Section #3 -->
        <div class="relative w-full mb-20">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <h3 class="font-medium text-center text-4xl md:text-6xl md:text-left">
                    Empowering Global Mental Health Access
                </h3>
                <div class="block w-full space-y-10">
                    <div class="text-center md:text-left border-b border-gray-300">
                        <h3 class="font-semibold text-sm md:text-base mb-2">
                            OUR VISION
                        </h3>
                        <p class="text-xs md:text-sm text-gray-500 mb-3">
                            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti possimus voluptatibus, minus non libero veritatis ut quos totam facere maxime.
                        </p>
                    </div>
                    <div class="text-center md:text-left border-b border-gray-300">
                        <h3 class="font-semibold text-sm md:text-base mb-2">
                            OUR MISSION
                        </h3>
                        <p class="text-xs md:text-sm text-gray-500 mb-3">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus, dolor aliquam. Quod aut nulla, explicabo ipsam esse odit. Magni asperiores qui voluptatum
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <!-- Section #4 -->
        <div class="relative w-full mb-20">
            <div class="grid grid-cols-1 md:grid-cols-2 w-full h-full justify-between items-center mb-10">
                <h3 class="font-medium text-center text-4xl md:text-6xl md:text-left">
                    Meet the team
                </h3>
                <div class="inline-flex items-center space-x-6">
                    <div class="hidden md:inline-block min-h-16 w-0.5 self-stretch bg-gray-800"></div>
                    <p class="text-xs md:text-sm text-gray-500 text-center md:text-left not-md:mt-4">
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora ea error molestias necessitatibus nesciunt unde nisi quia veniam.
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-4 p-8 bg-gray-200 rounded-lg gap-6">
                <div class="block bg-white rounded-lg p-4">
                    <figure class="aspect-square w-full rounded-lg overflow-hidden">
                        <img src="/images/team-2.jpg" alt="Meat our team" class="object-cover object-center w-full h-full grayscale hover:grayscale-50 transition duration-300">
                    </figure>
                    <div class="block w-full text-center pt-4">
                        <h3 class="font-semibold text-sm md:text-base">Jackson Fisher</h3>
                        <p class="text-xs md:text-sm text-gray-500">Director</p>
                    </div>
                </div>
                <div class="block bg-white rounded-lg p-4">
                    <figure class="aspect-square w-full rounded-lg overflow-hidden">
                        <img src="/images/team-3.jpg" alt="Meat our team" class="object-cover object-center w-full h-full grayscale hover:grayscale-50 transition duration-300">
                    </figure>
                    <div class="block w-full text-center pt-4">
                        <h3 class="font-semibold text-sm md:text-base">Jackson Fisher</h3>
                        <p class="text-xs md:text-sm text-gray-500">Project Manager</p>
                    </div>
                </div>
                <div class="block bg-white rounded-lg p-4">
                    <figure class="aspect-square w-full rounded-lg overflow-hidden">
                        <img src="/images/team-4.jpg" alt="Meat our team" class="object-cover object-center w-full h-full grayscale hover:grayscale-50 transition duration-300">
                    </figure>
                    <div class="block w-full text-center pt-4">
                        <h3 class="font-semibold text-sm md:text-base">Jackson Fisher</h3>
                        <p class="text-xs md:text-sm text-gray-500">Marketing</p>
                    </div>
                </div>
                <div class="block bg-white rounded-lg p-4">
                    <figure class="aspect-square w-full rounded-lg overflow-hidden">
                        <img src="/images/team-5.jpg" alt="Meat our team" class="object-cover object-center w-full h-full grayscale hover:grayscale-50 transition duration-300">
                    </figure>
                    <div class="block w-full text-center pt-4">
                        <h3 class="font-semibold text-sm md:text-base">Jackson Fisher</h3>
                        <p class="text-xs md:text-sm text-gray-500">Operational</p>
                    </div>
                </div>
            </div>
        </div>
        <!-- Section #5 -->
        <div class="relative w-full mb-20">
            <!-- Video Container -->
            <div class="flex w-full md:h-[60dvh] rounded-lg overflow-hidden bg-gray-100">
                <video ref="videoPlayer" class="object-cover object-center w-full h-full" poster="/images/hero-image-6.jpg" @click="togglePlay">
                    <source src="#" type="video/mp4">
                    <span class="text-xs md:text-sm text-red-400 text-center">Your browser does not support the video tag.</span>
                </video>
                <!-- Play/Pause Button -->
                <button @click="togglePlay" class="group absolute inset-0 flex items-center justify-center w-full h-full cursor-pointer" :class="{ 'opacity-0': isPlaying }">
                    <div class=" bg-gray-800/40 rounded-full transition-all group-hover:bg-gray-800/60">
                        <svg class="size-12 md:size-16 fill-white transition-transform group-hover:scale-110" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path v-if="!isPlaying" d="M464 256A208 208 0 1 0 48 256a208 208 0 1 0 416 0zM0 256a256 256 0 1 1 512 0A256 256 0 1 1 0 256zM188.3 147.1c7.6-4.2 16.8-4.1 24.3 .5l144 88c7.1 4.4 11.5 12.1 11.5 20.5s-4.4 16.1-11.5 20.5l-144 88c-7.4 4.5-16.7 4.7-24.3 .5s-12.3-12.2-12.3-20.9l0-176c0-8.7 4.7-16.7 12.3-20.9z"/>
                            <path v-else d="M464 256A208 208 0 1 0 48 256a208 208 0 1 0 416 0zM0 256a256 256 0 1 1 512 0A256 256 0 1 1 0 256zM224 192c-13.3 0-24 10.7-24 24V296c0 13.3 10.7 24 24 24s24-10.7 24-24V216c0-13.3-10.7-24-24-24zm80 0c-13.3 0-24 10.7-24 24V296c0 13.3 10.7 24 24 24s24-10.7 24-24V216c0-13.3-10.7-24-24-24z"/>
                        </svg>
                    </div>
                </button>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Smooth transitions */
button, svg {
  transition: all 0.3s ease;
}

/* Hide button when video is playing (but show on hover) */
video:hover + button, 
button:hover {
  opacity: 1 !important;
}
</style>