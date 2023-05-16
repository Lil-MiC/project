<template>



<div class="second__body">
    <h1 class="sub__title__body">episode 1</h1>
    <h2 class="sub__title__body__two">LE CHIEN ET LA TRONCONNEUSE</h2> 
    <h3 class="sub__title__body__two__three">Chapitre 1 <br /> </h3>
    </div>
    <div class="img__second">
    <img class="sub__title__body__two__three__img" src="/Chain.jpg" alt="chain">
    

    </div>
    
    

    <div class="second__body__second">
    <h1 class="sub__title__body__second">episode 11</h1>
    <h2 class="sub__title__body__two__second">ARRIVEE A TOKYO</h2> 
    <h3 class="sub__title__body__two__threee__chab">Chapitres <br /> 2-3-4-5 <br /> </h3>
    </div>
    <div class="img__sline__second">
    <img class="sub__title__body__two__threee__img" src="/ChainsawAs.jpg" alt="chain">
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
    

    </div>

    
    </template>





<style lang="scss">

.second__body {
    background-color: gold;
    margin-top: 100px;
}
.second__body__second {
    background-color: gold;
}



.sub__title__body__two__threee__img {
    width: 90%;
    height: auto;
    position: relative;
    top:-150px;
    
  }
.img__sline__second {
  
  top: 160%;
  padding-left: 40%;

}
.sub__title__body__two__threee__img {
    padding-left: 0ch;
    font-size: 5ch;
    font-family: 'Allerta Stencil', sans-serif;
}
.sub__title__body__second {
    position: relative;
    padding-left: 80%;
    color: white;
    font-size: 6ch;
    
}
.sub__title__body__two__second {
    padding-bottom: 5%;
    font-size: 20ch;
    font-family: 'Sigmar', cursive;
    margin-bottom: 0px;
    padding-bottom: 0px;
    margin-top: 0px;
}
.sub__title__body__two {
    font-size: 13ch;
    font-family: 'Sigmar', cursive;
}

.sub__title__body__two__threee__chab {
    font-size: 10ch;
    font-family: 'Sigmar', cursive;
    

}
element.style {
    padding-bottom: 0px;
    margin-bottom: 0px;
    margin-top: 0px;
}
.prev, .next {
  cursor: pointer;
  padding: 20%;
  padding-left: 0%;

}
.prev {
    padding-right: 20%;
}
.next {
    padding-left: 20%;
}
</style>