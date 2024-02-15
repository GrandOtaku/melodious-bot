<template>
    <footer>
      <div class="container">
        <div class="left">
           <img src="../../public/assets/logo_noir.svg" alt="">
           <p>6 Rue sainte Catherine <br> 69003 Lyon <br> contact@melodious.com </p>
        </div>
        <div class="reseaux">
        <img src="../../public/assets/twitter.svg" alt="">
        <img src="../../public/assets/youtube.svg" alt="">
        <img src="../../public/assets/instagram.svg" alt="">
      </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'SiteFooter'
  }
  </script>

<style scoped>


footer{
  margin-top: 7.5vh;
  padding-top: 20vh;;
  background-image:url("../../public/assets/vague.svg") ;
  background-size: cover;
  width: 100vw;
  height: 25vh;
  background-repeat: no-repeat;
}

p{
  margin-top: 2vh;
  color: white;
}
.container {
  display: flex;
  justify-content: space-between;
  padding: 0 5vw;
}   

.reseaux{
  display: flex;
}
.left{
  margin-top: 0vh;
  
}

</style>