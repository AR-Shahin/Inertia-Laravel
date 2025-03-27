<template>
    <div>
        <Head title="Main Title" />
        <Navbar/>
        <div class="container px-5 py-10">
            <slot/>
        </div>
        <Footer/>
    </div>
</template>

<script setup>
    import Navbar from "@/Components/Custom/Navbar.vue";
    import Footer from "@/Components/Custom/Footer.vue";
    import { Head } from '@inertiajs/vue3'
</script>

<style lang="scss" scoped>

</style>
