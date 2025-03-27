<template>
    <GuestLayout>
        <!-- Hero Section -->
<section class="bg-blue-600 text-white text-center py-20 px-6">
    <div class="max-w-3xl mx-auto">
        <h1 class="text-4xl md:text-5xl font-bold">Welcome to Our Platform</h1>
        <p class="mt-4 text-lg">The best solution for your business needs.</p>
        <button class="mt-6 bg-white text-blue-600 px-6 py-3 rounded-full font-semibold hover:bg-gray-200 transition">Get Started</button>
    </div>
</section>

<!-- Features Section -->
<section class="py-16 px-6">
    <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-white shadow-md rounded-lg text-center">
            <h3 class="text-xl font-semibold text-blue-600">Feature 1</h3>
            <p class="mt-2 text-gray-600">Description of feature 1.</p>
        </div>
        <div class="p-6 bg-white shadow-md rounded-lg text-center">
            <h3 class="text-xl font-semibold text-blue-600">Feature 2</h3>
            <p class="mt-2 text-gray-600">Description of feature 2.</p>
        </div>
        <div class="p-6 bg-white shadow-md rounded-lg text-center">
            <h3 class="text-xl font-semibold text-blue-600">Feature 3</h3>
            <p class="mt-2 text-gray-600">Description of feature 3.</p>
        </div>
    </div>
</section>

<!-- Call to Action -->
<section class="bg-gray-900 text-white text-center py-16 px-6">
    <h2 class="text-3xl font-bold">Ready to Get Started?</h2>
    <p class="mt-4 text-lg">Join us today and take your business to the next level.</p>
    <button class="mt-6 bg-blue-500 px-6 py-3 rounded-full font-semibold hover:bg-blue-400 transition">Sign Up Now</button>
</section>

    </GuestLayout>
</template>

<script setup>
    import { usePage } from '@inertiajs/vue3';
    import GuestLayout from '@/Layouts/Custom/GuestLayout.vue';
    usePage().props.title = 'dd';

    console.log(usePage().props);

</script>

<style lang="scss" scoped>

</style>
