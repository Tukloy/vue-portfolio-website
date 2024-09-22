<script setup>
import { ref, onMounted } from 'vue'
const isDark = ref(false)

const setTheme = (theme) => {
    document.documentElement.setAttribute('data-theme', theme)
    localStorage.setItem('theme', theme)
}

const toggleTheme = () => {
    const theme = isDark.value ? 'dark' : 'light'
    setTheme(theme)
}

onMounted(() => {
    const savedTheme = localStorage.getItem('theme') || 'light'
    isDark.value = savedTheme === 'dark'
    setTheme(savedTheme)
})
</script>


<template>
    <div class="navbar bg-base-100 px-4 fixed bg-opacity-10 backdrop-blur-sm z-50">
        <div class="navbar-start">
            <div class="dropdown">
                <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h8m-8 6h16" />
                    </svg>
                </div>
                <ul tabindex="0"
                    class="menu menu-sm dropdown-content bg-base-100 rounded-box z-[1] mt-3 w-52 p-2 shadow">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="/files/Rheyvince Lawrence Napay - CV.pdf" download>Download CV</a></li>
                </ul>
            </div>
            <a class="text-xl font-semibold"><span class="text-yellow-500 text-2xl bg-">T</span>ukloy</a>
        </div>
        <div class="navbar-center hidden lg:flex">
            <ul class="menu menu-horizontal px-1">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
        <div class="navbar-end flex gap-x-4">
            <input id="theme-toggle" type="checkbox" class="toggle theme-controller" v-model="isDark"
                @change="toggleTheme" />
            <a href="/files/Rheyvince Lawrence Napay - CV.pdf" download
                class="btn hidden md:flex bg-yellow-500 dark:text-gray-900 dark:hover:text-yellow-500">Download CV</a>
        </div>
    </div>
</template>