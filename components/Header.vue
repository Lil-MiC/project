
<template >
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ultra&display=swap" rel="stylesheet">
    
    <header class="header">
       
        <h1 class="text">
            CEDEG
        </h1>
        
        <h2 class="sub__title">
            <center></center>
            
        </h2>
        <li class="links">
            <center>
                <a class="link" href="http://localhost:3000/">Accueil</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="entreprise">Entreprise</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="formation">Formation</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="stage">Stage</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="http://localhost:3000/Developpement professionnel">Developpement professionnel</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <nuxt-link class="link" to="Contact">Contact</nuxt-link>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            </center>
            
            
        </li>

        <div class="topnav">
  <input type="text" placeholder="Search..">

</div>
        
        
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
    color: rgb(0, 0, 0);
    font-size: 2ch;
    display:inline-flex;
    
    border-radius: 50px;
    
    
    
    
}
.link:hover {
  background-color: rgb(250, 152, 152);
}


  .header {
    
    font-family: 'Inter', sans-serif;
    font-family: 'DM Sans', sans-serif;
      background-color : rgb(174, 242, 255);
      padding: 6%;
      color: rgb(0, 0, 0) ;
      max-width: 100%;
     height: auto;
    
     justify-content: center;
     margin-bottom: 1%;
     
    
  }
  .text {
    
    font-size: 8ch;
    font-weight: bold;
    text-transform: uppercase;
    text-align: center;
  }
 









/* Style the search box inside the navigation bar */
.topnav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin-top: 8px;
  margin-right: 16px;
  font-size: 17px;
}
.topnav {
    margin-right: -7%;
}


  









</style>