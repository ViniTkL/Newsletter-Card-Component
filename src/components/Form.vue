<script setup>
    import Inputs from '@/components/Inputs.vue'
    import Header from './Header.vue';
</script>


<template>
    <form class="email-form" @submit.prevent="">
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
        width: 1094px;
        height: 432px;
        border-radius: 10px;
        gap: 20px;
        box-shadow: 10px 10px  #FFFFFF66;
        background-color: #FFF;
    }

    @media (max-width: 1024px){
        .email-form{
            width: 100%;
            height: 600px;
        }
    }
</style>