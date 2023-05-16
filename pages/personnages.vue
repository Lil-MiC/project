<template>
<div class="main__three">

    <img class="pagethree" src="/idle.webp" alt="chain">
    <div class="pagethree__title"> MAKIMA</div>

</div>

<div class="main__three__two">

    <img class="pagethree" src="/idle2.png" alt="chain">
    <div class="pagethree__title__two"> DENJI</div>
    

</div>






</template>


<style lang="scss">

.main__three {
    position: relative;
   text-align: center;
   color: rgb(255, 255, 255);
   max-width: 100%;
   height: auto;
   display: flex;
   justify-content: center;
   align-items: center;
   width: 100%;
}

.pagethree__title {
    position: absolute;
  top: 8px;
  left: 16px;
  font-size: 10ch;
  color: rgb(255, 255, 255);
  font-family: 'Sigmar', cursive;
  padding-left: 5%;
  padding-top: 5%;
  }
  .main__three {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("idle.webp");
  }
  .main__three__two {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("idle2.png");
    position: relative;
   text-align: center;
   color: rgb(255, 0, 0);
   max-width: 100%;
   height: auto;
   display: flex;
   justify-content: center;
   align-items: center;
   width: 100%;
  }
  .pagethree__title__two {

    position: absolute;
  top: 8px;
  right: 50px;
  font-size: 10ch;
  color: rgb(255, 255, 255);
  font-family: 'Sigmar', cursive;
  padding-left: 5%;
  padding-top: 5%;
  }
  








</style>