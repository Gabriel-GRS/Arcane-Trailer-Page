<template>
    <div>
        <img class="conteudo-principal" src="./arcane.png" alt="">
        <a href="https://www.youtube.com/watch?v=3MB3OK3Xnvs&ab_channel=NetflixBrasil"><button class="btn">Assista ao Trailer</button></a>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,500;1,300&display=swap');
    
    .btn {
        position: absolute;
        top: 70%;
        left: 50%;
        margin-right: -50%;
        transform: translate(-50%, -50%);
        background: #c7b8a4; 
        border-style: none;
        width: 400px;
        height: 80px;
        
        color: #0c0d13;;
        font-family: 'Roboto', sans-serif;
        font-style: normal;
        font-weight: 400;
        font-size: 34px;
        line-height: 30px;
        text-align: center;
        border-radius: 50px;
        box-sizing: border-box;
    }

    .btn:hover {
        background: #837869; 
        transition: 0.3s;
        color: #101325;
        cursor: pointer;
    }
   

    .conteudo-principal {
        position: absolute;
        top: 50%;
        left: 50%;
        margin-right: -50%;
        transform: translate(-50%, -50%) 
    }
    
</style>