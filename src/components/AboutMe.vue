<script setup>
import BorderDesign2 from '@/components/BorderDesign2.vue'
</script>
<template>
    <section id="about" class="relative pt-20">
        <BorderDesign2 position="top-0 bottom-[40%]" />
        <div class="container mx-auto px-6">
            <div class="flex items-center flex-col sm:flex-row justify-center gap-6">
                <div class="sm:w-[50%] w-full flex items-center justify-center h-72 relative">
                    <div
                        class="px-4 pt-4 pb-10 shadow-xl border-2 h-60 w-52 bg-white absolute top-0 left-0 -rotate-12 hover:rotate-0 hover:z-10 linear duration-500">
                        <img class="h-full w-full object-cover" src="/photo1.jpg" alt="">
                    </div>
                    <div
                        class="px-4 pt-4 pb-10 shadow-xl border-2 h-60 w-52 bg-white absolute top-0 right-[5%] rotate-12 hover:rotate-0 hover:z-10 linear duration-500">
                        <img class="h-full w-full object-cover" src="/photo3.jpg" alt="">
                    </div>
                    <div
                        class="px-4 pt-4 pb-10 shadow-xl border-2 h-60 w-52 bg-white absolute top-6 left-26 transform-translate hover:-translate-y-6 linear duration-500">
                        <img class="h-full w-full object-cover" src="/photo2.jpg" alt="">
                    </div>
                </div>
                <div class="sm:w-[50%] flex w-full">
                    <div class=" flex flex-col w-full">
                        <p class="text-4xl font-semibold mb-4">About Me</p>
                        <p class="text-base mb-4">Hi, my name is Rheyvince Lawrence Napay. I'm 26 years old, and I work
                            as a Frontend Web Developer, focusing on creating
                            user-friendly and visually appealing websites.</p>
                        <p class="text-base">In my free time, I enjoy watching movies—especially thrillers and action
                            films—and playing online games to unwind. I'm always looking for new ways to improve my
                            coding skills and stay updated with the latest web development trends.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>