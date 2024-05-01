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
        width: 800px;
        height: 400px;
        border-radius: 10px;
        background-color: #CDCDCD;
    }
</style>