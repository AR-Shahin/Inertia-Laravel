<template>
    <nav class="bg-blue-600 p-4">
    <div class="container mx-auto flex justify-between items-center">
        <a href="#" class="text-white text-xl font-bold">Brand</a>
        <button id="menu-btn" class="md:hidden text-white focus:outline-none">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
            </svg>
        </button>
        <ul id="menu" class="hidden md:flex space-x-6 text-white">
            <li><a href="#" class="hover:text-gray-300">Home</a></li>
            <li><a href="#" class="hover:text-gray-300">About</a></li>
            <li><a href="#" class="hover:text-gray-300">Services</a></li>
            <li><a href="#" class="hover:text-gray-300">Contact</a></li>
        </ul>
    </div>
</nav>

</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>

</style>
