<template>
    <div class="page__five__title">
    
    
    nous contacter
    
    </div>
    
    <div>
        <img class="page__five__img" src="" alt="">
        
    </div>
    
    <div class="input">
        <center>
        <form class="email">
  <label for="email">Email:</label><br>
<input type="email" id="email"
       pattern=".+@globex\.com" size="30" required>
        </form>

<form>
        <label for="description">Message:</label><br>
<input type="description" id="description"
       pattern=".+@globex\.com" size="30" required>
       
</form>
<button type="submit">send</button>
</center>
    </div>
    
    
    
    </template>
    
    
    <style lang="scss">
    .page__five__title {
        font-size: 5ch;
        font-family: 'Inter', sans-serif;
        font-family: 'DM Sans', sans-serif;
        text-align: center;
        padding-bottom: 10%;
    }
    
    .page__five__img {
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        background-image: url("");
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
    .page__five__sub__title {
        font-size: 5ch;
    }
    .description {
    
  font-size: 16px;
  resize: vertical;
}
input[type="Email"]{
        background-color: rgb(254, 245, 198);
        padding: 10px 15px;
        border-radius: 3px;
        
    }
    
    input[type="Description"]{
        background-color: rgb(255, 249, 215);
        padding: 10px 15px;
        border-radius: 3px;
        height: 30ch;
    }   
    
    
    </style>