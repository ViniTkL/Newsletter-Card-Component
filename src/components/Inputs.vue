<script setup>
</script>

<template>
    <div class="inputs-container">
        <div class="email-subscription">
            <input class="email-input" type="email" placeholder="Enter your email adress">
            <button class="Subscribe-btn">Subscribe</button>
        </div>
        <div class="email-tems">
            <input type="checkbox" id="terms">
            <label for="terms">adsadaasdasd</label>
        </div>
    </div>
</template>

<style scoped>
    .inputs-container{
        display: flex;
        flex-direction: column;
        width: 100%;
        justify-content: center;
        align-items: center;
        width: 100%;
    }

    .email-subscription{
        display: flex;
        justify-content: center;
        width: 100%;
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

    .email-tems{
        display: flex;
        flex-wrap: wrap;
    }
</style>