<template>
    <h1>Témoignage</h1>
    <div class="container">
        <div class="avis">
            <img src="../../public/assets/femme.svg" alt="objet" class="femme">
            <div class="avistxt">
                <h2>Lisa</h2>
                <p>Melodious a transformé ma manière d'explorer la musique. C'est comme avoir un ami musical toujours prêt à partager des anecdotes et des détails fascinants sur chaque genre.
                   Une expérience immersive et instructive que je recommande vivement!</p>

            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'SiteAvis'
}
</script>

<style scoped>

    p{
        margin-top: 2vh;
        font-size: 2.2vh;
        text-align: left;
        font-style: italic;
    }
    h2{
        margin-top: 4vh;
    }
    h1{
        text-align: center;
        margin-top: 10vh;
    }

    .avis{
        width: 130vh;
        height: 20vh;
        border-radius: 10px;
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);
        display: flex;
        
    }
    .container{
        display: flex;
        justify-content: center;
        width: 100vw;
        margin-top: 10vh;
    }
    .femme{
        margin: 3.5vh;
        width: 13vh;
        height: auto;
    }
</style>