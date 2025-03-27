<template>
    <div>
        <Head title="Main Title" />
        <Navbar/>
        <div class="">
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
