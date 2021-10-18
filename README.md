# COPS-SEG
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cops Seg Fort</title>
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>
   <header>
      <div class="line"></div>
      <div class="container header--area">
      <div class="header-left">
         <a href="/"><img src="assets/images/logo.png" /></a>
         <div class="header--right">
         <div class="header--search">
            <form>
               <input type="text" name="search" placeholder="search" />
               <button>
                  <img src="assets/images/loupe.png" />
               </button>
            </form>
         </div>
         <div class-"header--menu">
            <img src="assets/images/menu.png" />
         </div>
       </div>
      </div>
   </header>
   <section class="banner">
      <div class="container">
         <h1>COPS<br/>Seg Fort</h1>
         <span>'Segurança Operacional.</span>
         <div class="banner--images">
            <imag src="assets/images/c1.jpg" />
            <imag src="assets/images/c2.jpg" />
            <imag src="assets/images/c3.jpg" />
         
      </div>
      </div>
      </section>
      <section class="area1">
         <div class="area1--content">
            <div class="bar"></div>
            <h2>Fort em Segurança</h2>
            <div class="area1--quote">
               <em>"A segurança sempre vem em primeiro lugar."</em>Cops</div>
               <div class="area1--text"> Queridos clientes, partners e amigos, estamos acompanhando a situação atual do Brasil em relação ao COVID-19, focados na segurança e bem estar dos nossos partners (como chamamos os nossos colaboradores) e clientes. Seguimos os critérios de quarentena de cada munícipo que temos lojas. As lojas abertas ou com entrega via delivery, através do nosso parceiro Rappi, 
                  estão seguindo as orientações das autoridades de saúde.</div>
                  
                  <a href=""class="button">clique COPS</a>
            </div>
         </div>
         <div class="area1--img1">,,,</div>
         <div class="area1--img2">;;;</div>
      
   </section>

</section>
<section class="area2">
   <div class="area2--content">
      <div class="bar"></div>
      <h2>Equipamentos Eletronicos</h2>
      <div class="area2">
         <em>"O forte em tudo."</em>Cops</div>
         <div class="area2--text"> Queridos clientes, partners e amigos, estamos acompanhando a situação atual do Brasil em relação ao COVID-19, focados na segurança e bem estar dos nossos partners (como chamamos os nossos colaboradores) e clientes. Seguimos os critérios de quarentena de cada munícipo que temos lojas. As lojas abertas ou com entrega via delivery, através do nosso parceiro Rappi, 
            estão seguindo as orientações das autoridades de saúde.</div>
            
            <a href=""class="button">clique COPS</a>
      </div>
   </div>
   <div class="area2--img1">,,,</div>
   <div class="area2--img2">;;;</div>

</section>

   <section class="area3">
      <div class="area3--content"></div>
      <h2>Fazendo um site</h2>
      <div class="area2">
         <em>"O forte em tudo."</em>Cops</div>
         <div class="area2--text"> Enchendo linguiça 
            para ter conteudos <br>
            dentros das aplicações.....</div>
            <a href=""class="button">Saiba Mais</a>
         </ div >style.css
         <div class="are3--img1">coloque o conteúdo nesse espaço</div>
   </section>
</body>
</html>

body {
    font-family: 'Open Sans', sans-serif;
    margin: 0;
    }

    .container {
        max-width: 1140px;
        margin: auto;
        /*background-color: green;*/
    }
    .bar {
        background-color: #006341;
        width: 160px;
        height: 22px;
    }

    .h1{
        font-family: sans-seri'Oswald'; sans-serif;
        font-weight: bold;
        font-size: 90px;
        line-height: 100px;
        margin: 0;
        margin-bottom: 30px;
    }

    .h2 {
        font-family: 'oswald', sans-serif;
        font-weight: bold;
        font-size: 35px;
        line-height: 45px;
        margin: 20px 0;
        
    }

     .button {
         display: inline-block;
         border: 2px solid #454545;
         padding: 10px 30px;
         border-radius: 3px;
         color: #454545;
         text-decoration: none;
         background-color: #454545;
     }

     .button:hover {
         color: #fff;
     }


    header .line{
        background-color: #117050;
        height: 15px;
    }

    .header--area {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100px;
        /*background-color: green;
        
    }*/
***
    .header-left img{
        width: 64px;
        height: 64px;

    }
***
    .header--right {
        display: flex;
    }

    .header--search form{
        display: flex;
  /*      align-items: center;
    }*/

    .header--search input {
        font-size: 16px;
        padding: 9px 16px;
        border: 1px solid #999999;
        outline: 0;
        width: 100%;
        max-width: 250px;
    }

    .header--search button {
        border: 0;
        background: transparent;
        margin-left: -30px;
        cursor: pointer;
    }

    .header--search button img {
        width: 16px;
        height: 16px;
    }

    .header--menu {

        margin: 50px;
        cursor: pointer;

    }

    .header--menu {
        width: 24;
        height: 24;
    }

    ***
    .banner {
        background-image: url('../css/bg.jpg');
        background-position: center;
        background-size: cover;
        padding-top: 90px;
        padding-bottom: 90px;
    }
    .banner h1{
    }

    .banner--images img{
        margin-top: 60px;
        width: 148px;
        height: 148px;
        border: 6px #117050;
        border-radius: 50%;
        margin-right: 40px;
    }

    .area1 {
        display: grid;
        grid-template-columns: repeat(2, 1fr);

    }
    .area1-text{
        margin-bottom: 50px;
        line-height: 27.5px;
    }

    .area1--content{
       /* height: 300px; */
       padding: 80px;

    }

    .area1--quote {
        margin-bottom: 30px;
    }

    .area1--img1{
        background-color: #117050;
        height: 345px;
        background-image: url('../images/images1.png');
        background-size: cover;
        background-position: center;

    }

    .area1--img2{
        background-color: red;
        grid-column: 2 / 3;
        grid-row: 1 / 3;
        background-image: url('../images/c4.png');
        background-size: cover;
        background-position: center;
    }

    88888''''
    
    .area2 {
        display: grid;
        grid-template-columns: repeat(2, 1fr);

    }
    .area2-text{
        margin-bottom: 50px;
        line-height: 27.5px;
    }

    .area2--content{
       /* height: 300px; */
       padding: 80px;

    }

    .area2 {
        margin-bottom: 30px;
    }

    .area2--img1{
        background-color: #117050;
        height: 350px;
        background-image: url('../images/img1.png');
        background-size: cover;
        background-position: center;

    }

    .area2--img2{
        background-color: red;
        grid-column: 1 / 2;
        grid-row: 1 / 3;
        background-image: url('../images/f1.png');
        background-size: cover;
        background-position: center;
    }

    ***33333

    .area3 {
        display: grid;
        grid-template-columns: repeat(2, 1fr);

    }
    .area3-text{
        margin-bottom: 50px;
        line-height: 27.5px;
    }

    .area3--content{
       padding: 200px 80px;
       background-image: url('../images/copslogotop.png');
       background-size: cover;
       background-position: center;

    }

    .area3 {
        margin-bottom: 30px;
    }

    .area3--img1{
        background-image: url('../images/aguia.png');
        background-size: cover;
        background-position: center;

    }
