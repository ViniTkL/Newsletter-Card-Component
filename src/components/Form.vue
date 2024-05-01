<script setup>
    import Inputs from '@/components/Inputs.vue'
    import Header from './Header.vue';
</script>


<template>
    <form class="email-form">
        <Header />
        <inputs></inputs>
    </form>
</template>

<style scoped>
    .email-form{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 600px;
        height: 600px;
        background-color: red;
    }
</style>