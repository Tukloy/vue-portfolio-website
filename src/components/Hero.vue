<script setup>
import BorderDesign from '@/components/BorderDesign.vue'
</script>

<template>
    <section id="home" class="min-h-screen flex items-center justify-center px-10 py-20 w-full relative">
        <BorderDesign position="top-0 left-0" />
        <div class="flex flex-row items-center container relative flex-wrap justify-center gap-6 ">
            <div class="flex flex-col justify-center flex-1">
                <p class="text-4xl font-semibold mb-4">Hi, I'm Rheyvince Napay</p>
                <p class="text-yellow-500 font-semibold text-3xl">Frontend Web Developer</p>
                <p class="my-6 text-base">A skilled and experienced website developer specializing in modern web
                    development practices, with a strong focus on utilizing Vue.js 3's Composition API for building
                    dynamic, scalable, and efficient web applications. Well-versed in using Tailwind CSS to create
                    responsive, visually appealing, and highly customizable user interfaces, ensuring a seamless and
                    engaging user experience across various devices</p>
                <div class="flex gap-x-4 mt-4">
                    <button class="btn bg-yellow-500 dark:text-gray-900 dark:hover:text-yellow-500">Hire Me</button>
                    <button class="btn">Let's Talk</button>
                </div>
            </div>
            <div class="flex-1">
                <div class="flex items-center h-full justify-center relative w-full">
                    <div
                        class="overflow-hidden max-h-96 max-w-96 min-w-48 rounded-full border-8 border-yellow-500 hover:bg-yellow-500 linear duration-300 group flex items-center justify-center">
                        <img class="w-[80%] h-full object-cover grayscale-[50%] group-hover:grayscale-0"
                            src="/heroProfile.png" alt="">
                        <div class="absolute pointer-events-none">
                            <div
                                class="max-h-96 max-w-96 min-w-48 border-8 border-yellow-500 rounded-full border-opacity-100 group-hover:animate-ping group-hover:border-opacity-100">
                                <img class="w-[80%] h-full object-cover opacity-0" src="/heroProfile.png" alt="">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="absolute hidden lg:flex -right-10 flex flex-col items-center gap-y-8">
                <p class="text-semibold text-yellow-500 rotate-90 mb-3">follow me in:</p>
                <a href=""
                    class="pi pi-facebook p-2 bg-yellow-500 rounded-lg hover:bg-opacity-80 linear duration-200 dark:text-gray-900"></a>
                <a href=""
                    class="bg-yellow-500 p-2 rounded-lg pi pi-instagram hover:bg-opacity-80 linear duration-200 dark:text-gray-900"></a>
                <a href=""
                    class="bg-yellow-500 p-2 rounded-lg pi pi-linkedin hover:bg-opacity-80 linear duration-200 dark:text-gray-900"></a>
                <a href=""
                    class="bg-yellow-500 p-2 rounded-lg pi pi-github hover:bg-opacity-80 linear duration-200 dark:text-gray-900"></a>
            </div>
            <div class="absolute block lg:hidden -bottom-10 right-0 flex items-center gap-x-3">
                <p class="text-semibold text-yellow-500 whitespace-nowrap">follow me in:</p>
                <a href=""
                    class="pi pi-facebook p-2 bg-yellow-500 rounded-lg hover:bg-opacity-80 linear duration-200 dark:text-gray-900 mr-2"></a>
                <a href=""
                    class="bg-yellow-500 p-2 rounded-lg pi pi-instagram hover:bg-opacity-80 linear duration-200 dark:text-gray-900 mr-2"></a>
                <a href=""
                    class="bg-yellow-500 p-2 rounded-lg pi pi-linkedin hover:bg-opacity-80 linear duration-200 dark:text-gray-900"></a>
                <a href=""
                    class="bg-yellow-500 p-2 rounded-lg pi pi-github hover:bg-opacity-80 linear duration-200 dark:text-gray-900"></a>
            </div>
        </div>
        <BorderDesign position="bottom-0 right-0 rotate-180" />
    </section>
</template>