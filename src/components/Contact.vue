<script setup>
import BorderDesign from '@/components/BorderDesign.vue';
</script>
<template>
    <section id="contact" class="pt-20 relative">
        <BorderDesign position="bottom-0 right-0 rotate-180" />
        <div class="container mx-auto p-10">
            <div class="flex flex-col sm:flex-row gap-6">
                <div class="flex-1 flex flex-col gap-y-3">
                    <p class="text-4xl font-semibold mb-4">Contact Me</p>
                    <div class="flex items-center gap-x-4">
                        <i class="pi pi-envelope text-2xl font-bold text-yellow-500"></i>
                        <p>rheyvince.26@gmail.com</p>
                    </div>
                    <div class="flex items-center gap-x-4">
                        <i class="pi pi-phone text-2xl font-bold text-yellow-500"></i>
                        <p>09476948265</p>
                    </div>
                    <div class="flex items-center gap-x-4">
                        <i class="pi pi-map-marker text-2xl font-bold text-yellow-500"></i>
                        <p>Brgy. San Isidro Pagsanjan Laguna Philippines</p>
                    </div>
                </div>
                <div class="flex-1 flex flex-col gap-6 items-start">
                    <input type="text" placeholder="Your Name" class="input input-bordered w-full" />
                    <input type="text" placeholder="Your Email" class="input input-bordered w-full" />
                    <textarea class="textarea textarea-lg textarea-bordered w-full"
                        placeholder="Message Here...."></textarea>
                    <button
                        class="btn bg-yellow-500 text-gray-900 dark:text-gray-900 hover:dark:text-yellow-500">Submit</button>
                </div>
            </div>
        </div>
    </section>
</template>