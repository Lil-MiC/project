<template>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sigmar&display=swap" rel="stylesheet">

    <header class="bot">
        <h1 class="footer__title">
            PowerUp</h1>
        <div class="container">
  <ul class="bot__links">
    <li><a class="link" href="http://localhost:3000">Accueil</a></li>
    <li><a class="link" href="http://localhost:3000/page2">A-propos</a></li>
    <li><a class="link" href="http://localhost:3000/page5">Contact</a></li>
    <li><a class="link" href="http://localhost:3000/page4">liste-des-episodes</a></li>
    <li><a class="link" href="http://localhost:3000/page2">Personnages</a></li>
  </ul>
  <img class="footer__img" src="/back.png" alt="Your image description">
</div>
    </header>
</template>




<style lang="scss">

.bot__header {
    background-color: gold;
    list-style-type: none;
    padding-left: 5%;
    font-family: 'Sigmar', cursive;
    
}
.bot__img {
    
    margin-left: 70%;
    padding-bottom: ch;
    
    
}

.footer__title {
    font-size: 15ch;
    color: orangered;
    background-color: gold;
    font-family: 'Sigmar', cursive;
    padding-left: 5%;

}
.container {
  display: flex;
  background-color: gold;
}

.bot__links {
  list-style: none;
  padding: 0;
  margin-right: 20px; 
  padding-left: 5%;
  font-family: 'Sigmar', cursive;
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
    padding-left: 40%;
    
    
}
.bot {
    background-color: gold;
}



</style>