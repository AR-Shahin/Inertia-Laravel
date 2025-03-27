<template>
    <GuestLayout>
        <h1 class="">This is home page</h1>
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
