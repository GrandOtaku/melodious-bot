<template>
    <div id="histoire" class="txt">
        <h1>  Notre Histoire  </h1>
        <p class="para"> Rorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu turpis molestie, dictum est a, mattis tellus. Sed dignissim, metus nec fringilla accumsan, risus sem sollicitudin lacus, ut interdum tellus elit sed risus. Maecenas eget condimentum velit, sit amet feugiat lectus. 
            Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Praesent auctor purus luctus enim egestas, ac scelerisque ante pulvinar. Donec ut rhoncus ex. 
            Suspendisse ac rhoncus nisl, eu tempor urna. Curabitur vel bibendum lorem. Morbi convallis convallis diam sit amet lacinia. Aliquam in elementum tellus.
        </p>
    </div>

    <div class="container">
        <div class="card">
            <img src="../../public/assets/alexis.svg" alt="alexis"  class="photo">
            <p class="name">Alexis Crocilla</p>
            <p class="role">Chef de projet</p>
        </div>
        <div class="card">
            <img src="../../public\assets\enzo.svg" alt="enzo"  class="photo">
            <p class="name">Enzo Boucherand</p>
            <p class="role">Spécialiste IA</p>
        </div>
        <div class="card">
            <img src="../../public\assets\axel.svg" alt="axel"  class="photo">
            <p class="name">Axel Point</p>
            <p class="role">Développeur</p>
        </div>
        <div class="card">
            <img src="../../public\assets\jimmy.svg" alt="jimmy" class="photo">
            <p class="name">Jimmy Cassarino</p>
            <p class="role">UX/UI designer</p>
        </div>

    </div>

</template>

<script>
    export default {
  name: 'SiteHistoire'
}
</script>

<style scoped>

    h1{
        text-align: center;
        font-size: 6vh;
    }
    
    .para{
      font-size: 3vh;
      padding: 6vh;
      text-align: center;
    }

    .container{
        display: flex;
        justify-content: space-evenly;
        margin-top: 10vh;
    }

    .name{
        font-size: 3vh;
        display: flex;
        justify-content: space-evenly;
        padding-top: 2vh;
        font-weight: bold;
        text-align: center;
    }

    .role{
        font-size: 2vh;
        text-align: center;
    }

</style>