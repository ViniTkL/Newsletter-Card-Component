<script setup>
    import { ref } from 'vue';

   let email = ref(''); 
   const alertUser = () =>{
        email.value.includes('@gmail.com') ? alert(`Sucessfuly subscribed email ${email.value} on our newsletter` ) : '';
   }
</script>

<template>
    <div class="inputs-container">
        <div class="email-subscription">
            <input class="email-input" type="email" placeholder="Enter your email adress" v-model="email">
            <button class="Subscribe-btn" @click="alertUser">Subscribe</button>
        </div>
        <div class="email-tems">
            <input type="checkbox" id="terms">
            <label for="terms">By checking this box, you agree to receive our weekly newsletter containing coding challenges, tips, and other related content. You may unsubscribe from the newsletter at any time</label>
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
        gap: 15px;
    }

    .email-subscription{
        display: flex;
        justify-content: center;
        width: 100%;
        gap: 10px;
    }

    .email-input{
        background-color: #FAFAFF;
        width: 70%;
        height: 50px;
        border-radius: 4px;
        border: 1px solid #B3B8D8;
        padding: 5px 10px 5px 10px;
        font-family: Poppins;
        font-size: 24px;
        font-weight: 400;
    }

    .Subscribe-btn{
        height: 50px;
        width: 15%;
        color: #FFF;
        background-color: #111827;
        border-radius: 4px;
        border: none;
        font-family: Poppins;
        font-weight: 500;
        font-size: 24px;
    }

    
    .Subscribe-btn:hover{
        cursor: pointer;
    }

    .email-tems{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 85%;
        gap: 10px;
    }

    .email-tems > input{
        margin-bottom: 2.5%;
    }

    .email-tems > label{
        font-family: Poppins;
        font-weight: 400;
        font-size: 14px;
        line-height: 21px;
        color: #111827;
    }


    @media (max-width: 1024px){
        .inputs-container{
            width: 90%;
        }

        .email-input{
            font-size: 12px;
        }

        .Subscribe-btn{
            width: 25%;
            font-size: 12px;
        }
    }
</style>