<script setup>
import BorderDesign from '@/components/BorderDesign.vue'
defineProps({
    skills: Array
})
</script>

<template>
    <section id="skills" class="pt-20 px-10 relative">
        <BorderDesign position="bottom-0 left-0 rotate-120" />
        <div class="container mx-auto w-full px-">
            <p class="text-4xl font-semibold mb-10">Skills</p>
            <div class="grid grid-cols-1 2xl:grid-cols-5 xl:grid-cols-4 lg:grid-cols-4 md:grid-cols-3 gap-10 ">
                <div v-for="(skill, index) in skills" :key="index"
                    class="card glass bg-base-100 shadow-2xl pt-6 group hover:bg-yellow-400 ease duration-300 hover:dark:text-gray-950">
                    <figure>
                        <img class="w-32 h-32 grayscale group-hover:grayscale-0 ease group-hover:scale-110 duration-300"
                            :src="skill.image" alt="Shoes" />
                    </figure>
                    <div class="card-body items-center text-center">
                        <h2 class="card-title font-bold">
                            {{ skill.name.toUpperCase() }}
                        </h2>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>