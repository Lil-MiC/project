
<template >
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ultra&display=swap" rel="stylesheet">
    
    <header class="header">
        <div class="neon-wrapper">
        <span class="text">
            <center>PowerUp</center>
        </span>
        <span class="gradient"></span>
        <span class="dodge"></span>
        </div>
        <h2 class="sub__title">
            <center>le fan site pas officiel du tout de Chainsaw man</center>
            
        </h2>
        <li class="links">
            <center>
                <a class="link" href="http://localhost:3000/">Accueil</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a class="link" href="http://localhost:3000/page2">A-propos</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a class="link" href="http://localhost:3000/page3">Contact</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a class="link" href="http://localhost:3000/page4">liste-des-episodes</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a class="link" href="http://localhost:3000/page5">Personnages</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
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
     align-items: center;
    
  }
  .text {
    display: flex;
    font-size: 8ch;
    font-weight: bold;
    text-transform: uppercase;
    padding-left: 500px;
    padding-right: 500px;
  }
  .wrapper {
    display: flex;
    height: 800px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #000000; 
}
.txt::before {
    content: 'PowerUp';
    position: absolute;
    mix-blend-mode: difference;
    display: flex;
}

.neon-wrapper {
    display:inline-flex;
    filter: brightness(200%);

    overflow: hidden;
}
.gradient{
    background: linear-gradient(114.5793141156962deg, gold 4.927083333333334%,rgba(229, 151, 64,1) 97.84374999999999%);
    position: absolute;
    top: 0;
    left:0;
    width: 100%;
    height:100%;
    overflow: hidden;
    display: flex;

    mix-blend-mode: multiply;
}
.dodge {
    background: radial-gradient(circle,white,black 35%) center / 25% 25%;
    position: absolute;
    top:-100%;
    left:-100%;
    right:0;
    bottom:0;
    display: flex;
    mix-blend-mode: color-dodge;
    animation: dodge-area 3s linear infinite;
}
@keyframes dodge-area {
    to {
        transform: translate(50%,50%);
    }
    
}

</style>