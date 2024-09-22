<script setup>
import BorderDesign from '@/components/BorderDesign.vue';
</script>
<template>
    <section id="education" class="pt-20 relative">
        <div class="container mx-auto flex flex-col">
            <p class="block text-center text-4xl font-semibold mb-4">Education & Experience</p>
            <div class="stats stats-vertical sm:flex w-full shadow bg-opacity-80 backdrop-blur-sm">
                <div class="stat place-items-center">
                    <div class="stat-title">ACTS Computer College</div>
                    <div class="stat-value text-2xl">BSIT</div>
                    <div class="text-xs stat-title">(Bachelor of
                        Science in Information Technology)</div>
                    <div class="stat-desc">JUNE 2015 - MAY 2019
                    </div>
                </div>

                <div class="stat place-items-center">
                    <div class="stat-title">Code Disruptors Inc.</div>
                    <div class="stat-value text-xl text-yellow-500"> Frontend Web
                        Developer</div>
                    <div class="stat-desc text-xs">AUGUST 2019 - AUGUST 2020</div>
                </div>

                <div class="stat place-items-center">
                    <div class="stat-title">Code Disruptors Inc</div>
                    <div class="stat-value text-xl">Basic ReactJS Bootcamp</div>
                    <div class="text-xs stat-title">(Training)</div>
                    <div class="stat-desc">April 7, 2019 - May 11, 2019</div>
                </div>
            </div>
        </div>
        <BorderDesign position="bottom-0 right-0 rotate-180" />
    </section>
</template>