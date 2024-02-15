<template>
  <header>
    <div class="container">
      <img src="../../public/assets/logo.svg" class="logo" />
      <nav class="liste" style="font-size: 22px">
        <a class="navigationLink" href="./">Accueil</a>
        <a class="navigationLink" href="#histoire">À Propos</a>
        <a class="navigationLink" href="#fonctionnalité">Fonctionnalité</a>
      </nav>
      <img src="../../public/assets/robert.svg" class="robert" />
    </div>
  </header>
</template>
  
  <script>
export default {
  name: "SiteHeader",
};
</script>
  
  <style scoped>
header {
  background-color: #ffffff;
  padding: px 0;
  margin-top: 3vh;
}

h1 {
  margin: 0;
}

.container {
  display: flex;
  justify-content: space-evenly;
  /* align-items: center; */
  padding-bottom: 30px;
}

nav {
  display: flex;
  width: 25%;
  justify-content: space-around;
  margin: 0% 12.5%;
}

.navigationLink {
  display: flex;
  align-items: center;
  font-weight: bold;
  cursor: pointer;
  color: black;
  text-decoration: none;
}
</style>
