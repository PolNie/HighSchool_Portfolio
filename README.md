Portfoli

<head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="preload" href="fonts/NightLightSquare.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
        <link rel="stylesheet" href="css/main.css">
        <link rel="stylesheet" href="css/fuente.css">
        <link rel="shortcut icon" href="img/rhcp_favicon.png" type="image/x-icon">
        <title>Pol Nieto Martínez</title>
        <style>
                *{
    margin: auto;
    font-family: RHCP;
    color: white;
    overflow-y: hidden;
    scrollbar-width: thin;
    scrollbar-color: rgb(22, 5, 5) rgb(22, 5, 5);
}

body{
    background: linear-gradient( black 19%, rgb(96, 11, 11), rgb(149, 15, 15), rgb(216, 14, 14), rgb(225, 9, 9), rgb(18, 17, 17));
}

header{
    width: 100%;
    height: 14vh;
    /*border: 1px solid blue;*/
    overflow: visible;
}

nav{
    width: 100%;
    height: 14vh;
    float: left;
    padding-bottom: 13px;
    padding-top: 8px;
    /*border: 1px solid blue;*/
}

main{
    width: 100%;
    height: 55vh;
    float: left;
    /*border: 1px solid blue;*/
    overflow: hidden;
}

footer{ 
    width: 100%;
    height: 14vh;
    float: left;
    /*border: 1px solid blue;*/
}


/*---HEADER---*/

.div-logo{
    width: 20%;
    height: auto;
    float: left;
    text-align: center;
}

.div-nombre{
    width: 80%;
    height: 100%;
    float: left;
    font-size: 34px;
    /*---CENTRAR TEXTO---*/
        display: flex;
        align-items: center;
        align-content: center;
        text-align: center;
}

header img{
    margin-top: 4px;
    height: 13vh;
    width: auto;
}


/*---NAV---*/

.nav-div{
    text-align: center;
    width: 100%;
}

nav div{
    display: flex;
    align-items: center;
    align-content: center;
    text-align: center;
    /*border: 1px solid blue;*/
    float: left;
    width: 33.3%;
    height: 100%;
}

nav div a{
    font-size: 27px;
    text-decoration: none;
}

.boton{
    display: flex;
    text-align: center;
    float: left;
    width: 15%;
    height: 70%;
    align-items: center;
    align-content: center;
    text-shadow: 0 0 1px rgb(255 255 255 / 42%),
    0 0 2px rgb(255 255 255 / 71%),
    0 0 4px #fff, 0 0 10px #fff, 0 0 20px #fff;
    box-shadow: 0px 0px 15px #fff;
    -moz-box-shadow: 0px 0px 15px #fff;
    -webkit-box-shadow: 0px 0px 15px #fff;
    border: 1px solid white;
}


/*---MAIN---*/

main div{
    /*border: 1px solid blue;*/
    width: 100%;
    height: 41vh;
    align-items: center;
    align-content: center;
    text-align: center;
}

main img{
    width: 32vw;
    height: 95%;
}

main p{
    /*border: 1px solid blue;*/
    height: 14vh;
    font-size: 18px;
}


/*---FOOTER---*/

footer div{
    /*border: 1px solid blue;*/
    width: 100%;
    height: 14vh;
    display: flex;
    align-items: center;
    align-content: center;
    text-align: center;
    font-size: 25px;
}
        </style>
    </head>
    <body>
        <header>
            <div class="div-logo">
                <a href="index.html"><img src="img/rhcp_logo.png" class="logo-img"></a>
            </div>
            <div class="div-nombre">
                <h2 class="glow-red">Red Hot Chili Peppers</h2>
            </div>
        </header>
        <nav>
            <div class="nav-div">
                <div class="glow-white boton">
                    <a href="galeria_imagenes.html">Galeria d'imatges</a>
                </div>
                <div class="glow-white boton">
                    <a href="enlaces.html">Enllaços</a>
                </div>
                <div class="glow-white boton">
                    <a href="noticias.html">Notícies</a>
                </div>
            </div>
        </nav>
        <main>
                <div>
                    <img src="img/foto-main.jpg">
                    <img src="img/foto-main2.jpg">
                    <img src="img/foto-main3.jpg">
                </div>
                <div>
                    <p>
                        <b>Red Hot Chili Peppers</b> és un grup de <b>rock alternatiu</b> format a Los Angeles (Califòrnia), el 1983. 
                        Els membres actuals de la banda són el cantant <b>Anthony Kiedis</b>, el guitarrista <b>John Frusciante</b>, el baixista <b>Michael 
                        "Flea" Balzary</b>, i el bateria <b>Chad Smith</b>. 
                        
                        <br>L'estil musical variat barreja rock tradicional amb elements d'altres gèneres 
                        com funk, funk rock, punk funk i rock psicodèlic.

                        <br>Els Red Hot Chili Peppers han guanyat set Premis Grammy i ha venut uns cinquanta milions de còpies arreu del món. 
                        A més a més, el 2011 van ser escollits per a entrar al Rock and Roll Hall of Fame.
                    </p>
                </div>
        </main>
        <footer>
            <div>
                <p>
                    Pol Nieto Martínez Curs 22-23
                </p>
            </div>
        </footer>
    </body>
