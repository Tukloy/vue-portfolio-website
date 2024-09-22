<script setup>
defineProps({
    position: String
})
</script>

<template>
    <div :class="position" class="absolute -z-10 right-0 left-0 bg-yellow-100 dark:bg-gray-900">
        <div class="relative h-full w-full overflow-hidden">
            <div class="absolute top-0 -right-10 rotate-12">
                <div class="h-40 w-40 bg-yellow-300"></div>
            </div>
            <div class="absolute bottom-0 left-0 -rotate-12">
                <div class="h-40 w-40 bg-yellow-200"></div>
            </div>
            <div class="absolute -top-20 left-[40%] -rotate-12">
                <div class="h-40 w-40 bg-yellow-200"></div>
            </div>
            <div class="absolute top-40 right-[20%] rotate-12">
                <div class="h-40 w-40 bg-yellow-300 animate-spin-slow-2"></div>
            </div>
            <div class="absolute -top-10 left-[20%] rotate-12">
                <div class="h-24 w-24 bg-yellow-300 animate-spin-slow-2"></div>
            </div>
            <div class="absolute -top-10 right-[20%]">
                <div class="h-16 w-16 bg-yellow-300 animate-spin-slow-2"></div>
            </div>
            <div class="absolute top-10 left-[5%]">
                <div class="h-8 w-8 bg-yellow-300 animate-spin-slow"></div>
            </div>
            <div class="absolute top-10 right-[5%]">
                <div class="h-8 w-8 bg-yellow-200 animate-spin-slow"></div>
            </div>
        </div>
    </div>
</template>