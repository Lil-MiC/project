
<template >
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ultra&display=swap" rel="stylesheet">
    
    <header class="header">
       
        <h1 class="text">
            PowerUp
        </h1>
        
        <h2 class="sub__title">
            <center>le fan site pas officiel du tout de Chainsaw man</center>
            
        </h2>
        <li class="links">
            <center>
                <a class="link" href="http://localhost:3000/">Accueil</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="A-props">A-propos</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="Contact">Contact</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="liste-des-episodes">liste-des-episodes</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="personnages">Personnages</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            </center>
            
            
        </li>
        
        
    </header>
</template>
<style lang="scss">
.sub__title {
    font-size: 4ch;
    justify-content: space-around;
    display: flex;
}
.link {
    justify-content: center;
    
    text-decoration: none;
    color: rgb(255, 68, 0);
    font-size: 2ch;
    display:inline-flex;
    
    
}
.link:hover {
  background-color: yellow;
}


  .header {
    
    font-family: 'Ultra', serif;
      background-color : gold;
      padding: 6%;
      color: rgb(188, 72, 0) ;
      max-width: 100%;
     height: auto;
    
     justify-content: center;
     
    
  }
  .text {
    
    font-size: 8ch;
    font-weight: bold;
    text-transform: uppercase;
    text-align: center;
  }
 








</style>