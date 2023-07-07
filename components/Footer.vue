<template>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sigmar&display=swap" rel="stylesheet">

    <footer class="bot">
        <h1 class="footer__title">
            CEDEG</h1>
        <div class="container">
  <ul class="bot__links">
    <li><a class="link" href="http://localhost:3000">Accueil</a></li>
    <li><nuxt-link class="link" to="entreprise">entreprise</nuxt-link></li>
    <li><nuxt-link class="link" to="formation">Formation</nuxt-link></li>
    <li><nuxt-link class="link" to="personnages">Stage</nuxt-link></li>
    <li><nuxt-link class="link" to="developpement professionnel">Developpement professionnel</nuxt-link></li>
    <li><nuxt-link class="link" to="Contact">Contact</nuxt-link></li>
  </ul>
  <img class="footer__img" src="/cedeg.png" alt="Your image description">
</div>
    </footer>
</template>




<style lang="scss">

.bot__header {
    background-color: rgb(255, 255, 255);
    list-style-type: none;
    padding-left: 5%;
    font-family: 'Inter', sans-serif;
    font-family: 'DM Sans', sans-serif;
    
}
.bot__img {
    
    margin-left: 70%;
    padding-bottom: ch;
    
    
}

.footer__title {
    font-size: 15ch;
    color: rgb(0, 0, 0);
    background-color: rgb(174, 242, 255);
    font-family: 'Inter', sans-serif;
    font-family: 'DM Sans', sans-serif;
    padding-left: 5%;

}
.container {
  display: flex;
  background-color: rgb(174, 242, 255);
}

.bot__links {
  list-style: none;
  padding: 0;
  margin-right: 20px; 
  padding-left: 5%;
  font-family: 'Inter', sans-serif;
    font-family: 'DM Sans', sans-serif;
}

.bot__links li {
  margin-bottom: 10px; 
}

.links {
  display: block;
  color: #333; 
  text-decoration: none; 
}

img {
  max-width: 100%;
  height: auto;
  
}
.footer__img {
    
    border-radius: 500ch;
    margin-left: 60%;
    
    
    
}
.bot {
    background-color: rgb(174, 242, 255);
}



</style>