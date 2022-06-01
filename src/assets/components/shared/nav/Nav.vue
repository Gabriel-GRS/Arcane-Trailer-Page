<template>
    
    <div class="nav">
        <div class="img-riot">
            <img src="./riotGames.png" alt="">
            <img src="./leagueOfLegends.png" alt="">
        </div>
        <img src="./netflix.png" alt="">
    </div>
</template>

<script>

export default {

}

</script>

<style scoped>

    .img-riot {
        display: flex;
        justify-content: flex-start;
        gap: 200px;

    }

    img:hover {
        -moz-transform: scale(1.2);
        -webkit-transform: scale(1.2);
        transform: scale(1.2);
        transition: .5s;
        cursor: pointer;
    }

    .nav {
        display: flex;
        justify-content: space-evenly;
        margin: -8px;
        padding-bottom: 10px;
        padding-top: 40px;       
        height: 40px;
       
        
    }
</style>
