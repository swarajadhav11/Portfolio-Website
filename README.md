# Portfolio-Website
This is my portfolio website project
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Swara - Portfolio</title>
  <style>
    *{
      margin: 0;
      padding: 0;
    }
    body{
      background-color: rgb(1, 0, 2);
      color: white;
      font-family: 'Times New Roman', Times, serif;
     

    }
    nav{
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 80px;
      background-color: rgb(8, 8, 42);
    }
    nav ul{
      display: flex;
      justify-content:center ;

    }
    nav ul li{
      list-style: none;
      margin: 0 23px; 
  
    }
    nav ul li a{
      text-decoration: none;
      color: white;
  
    }
    nav ul li a:hover{
      color: rgb(103, 103, 193);
      font-size: 1.04rem;
  
    
    }
    main hr {
      border: 0;
      background: #9c97f1;
      height: 1.2px;
      margin: 60px 84px ;
    }
    .left{
      font-size: 1.5rem;
    }
    .firstsection{
      display: flex;
      justify-content: space-around;
      align-items:center ;
      margin: 120px 0;
    }
    .firstsection > div {
      width: 30%;
    }
    .leftsection{
      font-size: 3rem;
      
    }
    .leftsection .buttons{
      padding: 23px;
    }
    .leftsection .btn{
      padding: 12px;
      background: rgb(1, 1, 57);
      color: white;
      border: 2px solid white;
      border-radius: 6px;
      font-size: 20px;
      cursor: pointer;
    }
    .rightsection img{
      width: 80%;
      margin: 50px 0;
      
    
    }
    .purple{
      color:rgb(97, 21, 168);
    }
    .secondsection{
      max-width: 80vw;
      margin: auto;
      height: 60vh;
        
    }
    .secondsection h1{
      font-size: 1.6rem;
        
    }
    .secondsection .box{
      background:white;
      width: 55vw;
      height: 2px;
      margin: 56px 0;
      display: flex;
    }
    .secondsection .vertical{
      height: 93px;
      width: 1px;
      background-color: white;
      margin:0 100px ;
    }
    .vertical-title{
      position: relative;
      top: 100px;
      width: 170px;
    }
    footer{
      background-color: rgb(22, 1, 22);
      
    }
    .footer{
      display: flex;
      padding: 23px 122px;
    }
    footer .footer-rights{
      text-align: center;
      color: gray;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class ="left">Swara's Portfolio</div>
      <div class ="right">
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/">About</a></li>
          <li><a href="/">Contact me</a></li>
        </ul>
      </div>
    </nav>
  </header>
  <main>
    <section class="firstsection">
      <div class="leftsection">My name is <span class ="purple">Swara </span>and I am a developer
  
  <div class="buttons">
    <button class="btn">Download Resume</button>
    <button class="btn">Visit Github</button>
  </div>
  </div> 
      <div class="rightsection">
        <img src="swara1.png" alt="">
      </div>
    </section>
    <hr>
    <section class="secondsection">
    <h1>
    Experience
    </h1>
    <div class="box">
      <div class="vertical">
        <div class="vertical-title">
          Studied in Ryan Global School (2012-2021)
        </div>
      </div>
      <div class="vertical">
        <div class="vertical-title">
          Studied for MHT CET EXAM (2022-2024)
        </div>
      </div>
      <div class="vertical">
        <div class="vertical-title">
          Pursuing B.Tech  (2025-2028)
        </div>
      </div>
      <div class="vertical">
        <div class="vertical-title">
          Learning Web Development(2025)
        </div>
      </div>

    </div>
  </section>
  <h1>
  </main>
  <footer>
    <div class="flex">
     <div class="footer">
      <h3>Swara's Portfolio</h3>
      </div>
      <div class="footer-rights">
        www.swarasportfolio.com | All rights reserved
      
     </div>
     


    </div>
  </footer>
  
</body>
</html>
