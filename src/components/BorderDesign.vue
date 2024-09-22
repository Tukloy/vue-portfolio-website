<script setup>
defineProps({
    position: String
})
</script>

<template>
    <div :class="[position]" class="absolute h-[30%] w-[30%] -z-10 opacity-70">
        <div class="relative w-full h-full">
            <div class="absolute top-0 left-8 h-8 w-8 rounded-full bg-yellow-400">
            </div>
            <div class="absolute top-20 left-30 h-4 w-4 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-8 left-2 h-8 w-8 rounded-full bg-yellow-200">
            </div>
            <div class="absolute top-[40%] left-[50%] h-2 w-2 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[30%] left-[30%] h-6 w-6 rounded-full bg-yellow-400">
            </div>
            <div class="absolute top-[10%] left-[80%] h-2 w-2 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[80%] left-[20%] h-4 w-4 rounded-full bg-yellow-100">
            </div>
            <div class="absolute top-[80%] left-[10%] h-6 w-6 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[20%] left-[60%] h-4 w-4 rounded-full bg-yellow-200">
            </div>
            <div class="absolute top-[10%] left-[10%] h-6 w-6 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[90%] left-[0%] h-2 w-2 rounded-full bg-yellow-200">
            </div>
            <div class="absolute top-[50%] left-[0%] h-6 w-6 rounded-full bg-yellow-100">
            </div>
            <div class="absolute top-[40%] left-[50%] h-2 w-2 rounded-full bg-yellow-200">
            </div>
            <div class="absolute top-[40%] left-[50%] h-2 w-2 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[43%] left-[20%] h-10 w-10 rounded-full bg-yellow-200">
            </div>
            <div class="absolute top-[35%] left-[12%] h-8 w-8 rounded-full bg-yellow-400">
            </div>
            <div class="absolute top-[20%] left-[15%] h-4 w-4 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[64%] left-[4%] h-10 w-10 rounded-full bg-yellow-200">
            </div>
            <div class="absolute top-[20%] left-[40%] h-3 w-3 rounded-full bg-yellow-300">
            </div>
            <div class="absolute top-[10%] left-[30%] h-4 w-4 rounded-full bg-yellow-200">
            </div>
        </div>
    </div>
</template>