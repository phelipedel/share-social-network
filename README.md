# share social network
 [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](http://phelipedel.com/)

![gif](https://cdn.discordapp.com/attachments/639869522387664896/949371759612821514/20220304_151257Edit_AdobeCreativeCloudExpress.gif )





Modelo simples e bonito para usar em suas rede social e poupar espaco .



## HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
     <link rel='stylesheet' href='https://use.fontawesome.com/releases/v5.2.0/css/all.css'><link rel="stylesheet" href="./style.css">
    <title>Redes Social</title>
</head>
<body>
    <div class="um">
        <span>Redes Social</span>
        <div class="container">
           
            <a href="http://twitter.com"  target="_blank"><i class="fab fa-twitter z"></i></a>
            <a href="http://facebook.com" target="_blank" ><i class="fab fa-facebook-f z"></i></a>
            <a href="http://instagram.com" target="_blank"><i class="fab fa-instagram z"></i></a>
            <a href="http://youtube.com" target="_blank"><i class="fab fa-youtube z"></i></a>
            <a href="http://github.com" target="_blank"><i class="fab fa-github z"></i></a>
            
        </div>
        
    </div>
</body>
</html>
```
```css
* {  
    margin: 0;  
    padding: 0;  
   
  }  
  body {  
    display: -webkit-box;  
    display: -ms-flexbox;  
    display: flex;  
    -webkit-box-pack: center;  
      -ms-flex-pack: center;  
        justify-content: center;  
    -webkit-box-align: center;  
      -ms-flex-align: center;  
        align-items: center;  
    height: 100vh;  
    background-color: bisque;
  }  
  i {  
    opacity: 0;  
    font-size: 28px;  
    color: #1F1E1E;  
    will-change: transform;  
    -webkit-transform: scale(.1);  
        transform: scale(.1);  
    -webkit-transition: all .3s ease;  
    transition: all .3s ease;  
  }  
  .um {  
    position: relative;  
    display: -webkit-box;  
    display: -ms-flexbox;  
    display: flex;  
    -webkit-box-pack: center;  
      -ms-flex-pack: center;  
        justify-content: center;  
    -webkit-box-align: center;  
      -ms-flex-align: center;  
        align-items: center;  
    overflow: hidden;  
    cursor: pointer;  
    width: 240px;  
    height: 72px;  
    background-color: bisque;
    border-radius: 80px;  
    padding: 0 18px;  
    will-change: transform;  
    -webkit-transition: all .2s ease-in-out;  
    transition: all .2s ease-in-out;  
  }  
  .um:hover {  
    /* transition-delay: .4s; */  
    -webkit-transform: scale(1.1);  
        transform: scale(1.1)  
  }  
  span {  
    position: absolute;  
    z-index: 99;  
    width: 240px;  
    height: 72px;  
    border-radius: 80px;  
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;  
    font-size: 20px;  
    text-align: center;  
    line-height: 70px;  
    letter-spacing: 2px;  
    color: #EEEEED;  
    background-color: #1F1E1E;  
    padding: 0 18px;  
    -webkit-transition: all 1.2s ease;  
    transition: all 1.2s ease;  
  }  
  .container {  
    display: -webkit-box;  
    display: -ms-flexbox;  
    display: flex;  
    -ms-flex-pack: distribute;  
      justify-content: space-around;  
    -webkit-box-align: center;  
      -ms-flex-align: center;  
        align-items: center;  
    width: 240px;  
    height: 64px;  
    border-radius: 80px;  
    background-color: #646463;
    box-shadow: 1px 2px 5px #0f0f0f9d;
  }  
  .container i:nth-of-type(1) {  
        -webkit-transition-delay: 1.1s;  
            transition-delay: 1.1s;  
  }  
  .container i:nth-of-type(2) {  
        -webkit-transition-delay: .9s;  
            transition-delay: .9s;  
  }  
  .container i:nth-of-type(3) {  
        -webkit-transition-delay: .7s;  
            transition-delay: .7s;  
  }  
  .container i:nth-of-type(4) {  
        -webkit-transition-delay: .4s;  
            transition-delay: .4s;  
  }  
  .um:hover span {  
    -webkit-transition-delay: .25s;  
        transition-delay: .25s;  
    -webkit-transform: translateX(-280px);  
        transform: translateX(-280px)  
  }  
  .um:hover i {  
    opacity: 1;  
    -webkit-transform: scale(1);  
        transform: scale(1);  
  }  
 
```

 
 

