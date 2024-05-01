<template>
    <div>
        <h1>Level Up Your frontend Skills</h1>
        <p>Sign up for free newsletter to receive weekly coding challenges that will help you improve your fromtemd development skills.</p>
    </div>
</template>

<style scoped>
    h1{
        font-family: Merriweather;
        font-size: 40px;
        line-height: 50.28px;
        font-weight: bold;
        color: #111827;
    }
    p{
        font-family: Poppins;
        font-size: 24px;
        line-height: 36px;
        font-weight: 400;
        color: #374151;
    }
    div{
        text-align: center;
        display: flex;
        flex-direction: column;
        padding: 10px;
        gap: 10px;
        width: 80%;
    }

    @media (max-width: 1024px){
        h1{
            font-size: 25px;
            line-height: 30px;
        }

        p{
            font-size: 18px;
            line-height: 25px;
        }
        div{
            width: 90%;
        }
    }
</style>