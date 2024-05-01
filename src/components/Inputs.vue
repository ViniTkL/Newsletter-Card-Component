<script setup>
</script>

<template>
    <div class="inputs-container">
        <input class="email-input" type="email" placeholder="Enter your email adress">
        <button class="Subscribe-btn">Subscribe</button>
        <input type="checkbox" id="terms">
        <label for="terms">adsadaasdasd</label>
    </div>
</template>

<style scoped>
    .inputs-container{
        display: flex;
        width: 100%;
        justify-content: center;
        align-items: center;
        gap: 10px;
    }
    .email-input{
        width: 70%;
        height: 40px;
        border-radius: 4px;
        border: none;
        padding: 10px 5px 10px 5px;
    }

    .Subscribe-btn{
        height: 40px;
        width: 20%;
        color: #FFF;
        background-color: black;
        border-radius: 4px;
        border: none;
    }
</style>