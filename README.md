# trabajo
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>SIST LOW</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,700&display=swap" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>

<body>
    <header>
        <nav>
            <section class="contenedor nav">
               
                    
                </div>
                <div class="enlaces-header">
                    <a href="#inicio">Inicio</a>
                    <a href="#12345">servicio</a>
                    
            
                </div>
                <div class="hamburguer">
                    <i class="fas fa-bars"></i>
                </div>
            </section>
        </nav>
        <div class="contenedor">
            <section class="contenido-header">
                <section class="textos-header">
                    <h1>LA ROCA</h1>
                    <p>esta pagina se redacta para el proceso de informacion de una micro empresa</p>
                   
                </section>
                <img src="img/primeraIlustracion.svg" alt="">
            </section>
        </div>
    </header>
    <section class="about-us" id="inicio">
        <div class="contenedor1">
            <center><h2 class="titulo">SISTEMA</h2></center>
            <div class="contenedor-articulo">
                <div class="articulo" data-aos="zoom-in-right">
                    <i class="fas fa-pen-fancy"></i>
                    <h3>GESTION </h3>
                 <br>
                    <ul>
                        <li>sistema de almacenamiento</li>
                        <li>proceso de informacion</li>
                        <li>datos y formulas </li>
                    </ul>
                    
                </div>
                <div class="articulo" data-aos="zoom-in-right">
                    <i class="fas fa-code"></i>
                    <h3>PROCESO WEB</h3>
                    <br>
                    <ul>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>JAVASCRIPT</li>
                    </ul>
                </div>
                <div class="articulo" data-aos="zoom-in-right">
                    <i class="fas fa-cog"></i>
                    <h3>PRODUCCION </h3>
                    <p>Los aspectos más comunes que provocan el fracaso de una microempresa es la mala ubicación, escasez de inversión, falta de experiencia, mal manejo de inventarios, inversiones excesivas en el activo fijo, problemas de comercialización, mala contratación del personas entre otras.</p>
                  
                </div>
                <div class="articulo" data-aos="zoom-in-right">
                    <i class="fas fa-chart-pie"></i>
                    <h3>pregunta frecuente</h3>
                    <p>¿Cómo hallar el estado de  equilibrio de las ventas y compras de una microempresa por medio de una aplicación web?</p>
                   
                </div>
                <div class="articulo" data-aos="zoom-in-right">
                    <i class="fas fa-comments"></i>
                    <h3>Marketing</h3>
                    <p>•    Calculadora punto de equilibrio para pymes: Es una herramienta web
diseñada por el Administrador Financiero José Didier Váquiro, disponible en el link inferior, por medio de la cual una empresa puede calcular su punto de equilibrio ingresando los datos correspondientes a las unidades a producir, costo fijo total, costo
variable unitario y precio de venta unitario.</p>
                    <a href="http://www.pymesfuturo.com/puntodequilibrio.php" target="_blank">Read more ---></a>
                </div>
               
            </div>
        </div>
    </section>
    <section class="questions contenedor" >
        <section class="textos-questions">
            <h1>Sistemas de Gestión de Bases de Datos </h1>
            <p></p>
            <a href="https://www.tecnologias-informacion.com/gestionbasedatos.html." target="_blank">Learn more</a>
        </section>
        <img src="img/segundaIlustracion.svg" alt="" data-aos="zoom-out-up" data-aos-duration="2000">
    </section>
    

    <footer id="12345">
       
        <div class="partFooter">
            <h4>Servicios</h4>
            <a href="http://www.pymesfuturo.com/puntodequilibrio.php"  target="_blank">administracion financiera</a>
            <a href="http://exceltotal.com/punto-de-equilibrio-en-excel/" target="_blank">sistema explicativo de exel</a>
            <a href="indes.html">registro de producto</a>
            
        </div>
        
        <div class="partFooter">
            <h4>Redes sociales</h4>
            <div class="social-media">
                    <i class="fab fa-facebook-f" ></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-instagram"></i>
                    <i class="fab fa-youtube"></i>
            </div>
        </div>
    
    </footer>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://kit.fontawesome.com/c15b744a04.js" crossorigin="anonymous"></script>
    <script src="js/main.js"></script>
</body>

</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: 'Roboto', sans-serif;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    color: #1d273b;
    font-weight: 300;
}

.contenedor {
    width: 90%;
    max-width: 1000px;
    margin: auto;
    overflow: hidden;
}


.contenedor1 {
    width: 90%;
    max-width: 1000px;
    margin: auto;
    overflow: hidden;
    padding: 60px 0;
}


h1 {
    font-size: 50px;
}


/* Header */
header::before {
    content: "";
    display: block;
    margin-bottom: 80px;
}


nav {
    width: 100%;
    height: 80px;
    background: #fff;
    border-bottom: 1px solid transparent;
    box-shadow: 1px 1px 10px 0 rgba(0, 0, 0, .2);
    position: fixed;
    top: 0;
    z-index: 100;
    transition: ease-in-out 0.5s;
}

.nav {
    display: flex;
    justify-content: space-between;
    height: 80px;
    width: 100%;
    align-items: center;
    padding: 0 40px;
}

.nav .logo {
    height: 80px;

}

.nav .logo img {
    height: 100%;
    vertical-align: top;
}

.enlaces-header {
    font-weight: 300;
    transition: ease-in-out 0.5s;
}

.nav .enlaces-header a {
    color: #5D6678;
    text-decoration: none;
    margin-left: 20px;
}

.hamburguer {
    width: 80px;
    height: 80px;
    display: none;
    text-align: center;
    z-index: 100;
    cursor: pointer;
    transition: color 0.5s ease-in;
}

.hamburguer>i {
    font-size: 25px;
    line-height: 80px;
}

.contenido-header {
    width: 100%;
    height: 600px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.contenido-header>img {
    width: 550px;
    animation: ease-in animat 1s;
}

@keyframes animat {
    0% {
        transform: scale(0);
    }

    100% {
        transform: scale(1);
    }
}


.textos-header {
    margin: 0 0 0 30px;
}

.contenido-header p {
    font-weight: 100;
    margin-top: 14px;
    color: #5D6678;
}


.contenido-header a {
    margin: 28px 0 0 0;
    width: 130px;
    display: inline-block;
    background: #1FDE82;
    text-align: center;
    color: #fff;
    padding: 12px 0;
    text-decoration: none;
    font-weight: 400;
    text-transform: uppercase;
    font-size: 14px;
    border-radius: 5px;
    box-shadow: 0 8px 32px rgba(31, 222, 130, .46);
}

.titulo {
    font-size: 50px;
}

/* About us */

.about-us {
    background:#5a90f5;
}

.contenedor-articulo {
    display: flex;
    flex-wrap: wrap;
    margin-top: 60px;
    justify-content: space-around;
}

.articulo {
    width: 29%;
    background: #fff;
    margin-bottom: 30px;
    border-radius: 10px;
    padding: 45px 30px 60px 30px;
    transition: 0.5s;
}

.articulo:hover {
    box-shadow: 0 4px 10px rgba(17, 29, 48, .26);
}

.articulo>i {
    font-size: 30px;
    color: #fff;
    background: #1FDE82;
    display: inline-block;
    width: 70px;
    height: 70px;
    text-align: center;
    padding-top: 20px;
    border-radius: 50%;
    box-shadow: 0 8px 32px rgba(31, 222, 130, .46);
}

.articulo>h3 {
    font-size: 24px;
    margin-top: 30px;
}

.articulo>p {
    font-weight: 100;
    color: #5D6678;
    margin-top: 15px;
    padding-bottom: 20px;
}

.articulo>a {
    color: #5D6678;
    font-weight: 400;
    text-decoration: none;
}

.articulo>a:hover {
    color: #1FDE82;
    transition: color .5s;
}

/* Questions */


.questions {
    height: 600px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.questions>img {
    width: 550px;
}

.textos-questions {
    margin: 0 0 0 30px;
}

.textos-questions p {
    font-weight: 100;
    margin-top: 14px;
    color: #5D6678;
}


.textos-questions a {
    margin: 28px 0 0 0;
    width: 130px;
    display: inline-block;
    background: #1FDE82;
    text-align: center;
    color: #fff;
    padding: 12px 0;
    text-decoration: none;
    font-weight: 400;
    text-transform: uppercase;
    font-size: 14px;
    border-radius: 5px;
    box-shadow: 0 8px 32px rgba(31, 222, 130, .46);
}

/* Results */

.results {
    background: #2570ff;
    padding-top: 30px;
}

.conten-results {
    display: flex;
    justify-content: space-evenly;
}

.numbers {
    width: 60%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
}

.numbers .number {
    width: 45%;
    background: rgba(255, 255, 255, .2);
    color: #fff;
    border-radius: 10px;
    padding: 40px 35px;
    margin-bottom: 20px;
}

.numbers .number h4 {
    color: #fff;
    font-size: 50px;
    font-weight: 500;
    margin-bottom: 20px;
}

.numbers .number p {
    color: #f2f5fc;
    font-weight: 300;
}

.results-text {
    width: 37%;
}

.results-text h4 {
    color: #fff;
    font-size: 40px;
}

.results-text p {
    color: #fff;
    font-weight: 300;
    margin: 20px 0;
}


.results-text>a {
    color: #fff;
    text-decoration: none;
    display: inline-block;
    border: 1px solid #fff;
    padding: 10px 0;
    width: 120px;
    text-align: center;
    border-radius: 5px;
}

/* Services */

.services {
    display: flex;
    justify-content: space-between;
}

.services>img {
    width: 500px;
}

.box-skills {
    margin: 30px 30px 0 0;
}

.box-skills h4 {
    font-size: 24px;
    background: #f2f2f2;
    width: 350px;
    border-radius: 6px;
    padding: 10px 0 10px 15px;
    margin-bottom: 10px;
}

.box-skills i {
    color: #1FDE82;
    font-size: 20px;
}

/* footer */

footer {
    background: #f2f2f2;
    padding: 60px 0;
    overflow: hidden;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    margin: auto;
}

.partFooter {
    width: 20%;
    text-align: center;
}

.partFooter h4 {
    color: #1d273b;
    font-size: 20px;
    font-weight: 400;
    margin-bottom: 30px;
}

.partFooter a {
    display: block;
    text-decoration: none;
    color: #5D6678;
    font-weight: 300;
    transition: color .3s ease-in-out;
    margin-bottom: 10px;
}


.partFooter a:hover {
    color: #1FDE82;
}

.partFooter img {
    width: 70%;
}

.social-media i {
    font-size: 20px;
    display: inline-block;
    color: #adb6c7;
    border: 1px solid #adb6c7;
    border-radius: 50%;
    width: 38px;
    height: 38px;
    line-height: 36px;
    cursor: pointer;
    margin-top: 20px;
    text-align: center;
    transition: all ease-in-out .3s;
    margin-right: 5px;
}

.social-media i:hover {
    color: #fff;
    background-color: #1FDE82;
    border-color: #1FDE82;
}

/* Breakpoints responsive */

@media screen and (max-width:800px) {
    .titulo {
        font-size: 45px;
    }

    .contenido-header {
        flex-direction: column;
        justify-content: space-evenly;
        height: 720px;
    }

    .contenido-header>img {
        width: 400px;
    }

    .textos-header {
        margin: 0;
    }

    /* About us */

    .articulo {
        width: 45%;
    }

    /* Questions */

    .questions {
        height: 720px;
        justify-content: space-evenly;
        flex-direction: column;
    }

    .questions>img {
        width: 400px;
    }

    /* results */

    .conten-results {
        flex-direction: column-reverse;
    }

    .results-text>a {
        margin-bottom: 60px;
    }

    .numbers {
        width: 100%;
        /* justify-content: space-between; */
    }

    .results-text {
        width: 100%;
    }

    /* Services */

    .services {
        flex-direction: column-reverse;
        align-items: center;
    }

    .box-skills {
        margin: 0 0 40px 0;

    }

    .box-skills h4 {
        width: 500px;
    }

    .services>img {
        width: 400px;
    }

    /* Footer */

    footer {
        justify-content: space-evenly;
    }

    .partFooter {
        width: 40%;
        margin-bottom: 40px;
    }
}

@media screen and (max-width:600px) {
    .titulo {
        font-size: 35px;
    }

    h1 {
        font-size: 40px;
    }

    .contenido-header {
        height: 650px;
    }

    .nav {
        padding: 0 10px;
    }

    .contenido-header>img {
        width: 200px;
    }

    .enlaces-header {
        position: fixed;
        background: #667db6;
        /* fallback for old browsers */
        background: -webkit-linear-gradient(to right, #667db6, #0082c8, #0082c8, #667db6);
        /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to right, #667db6, #0082c8, #0082c8, #667db6);
        /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        top: 0;
        right: 0;
        width: 100%;
        height: 100vh;
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: space-evenly;
        clip-path: circle(0.0% at 100% 0);
    }

    .nav .menudos {

        -webkit-clip-path: circle(150% at 100% 0);
        clip-path: circle(150% at 100% 0);

    }

    .nav .enlaces-header a {
        color: #fff;
    }

    .hamburguer {
        display: block;
    }

    /* About us */

    .articulo {
        width: 95%;
    }

    /* Questions */

    .questions>img {
        width: 200px;
    }

    /* results */

    .numbers .number {
        width: 95%;
    }

    .results-text h4 {
        font-size: 35px;
    }

    /* Services */

    .services>img {
        width: 200px;
    }

    .box-skills h4 {
        width: 100%;
    }

    /* Footer */
    .partFooter {
        width: 95%;
        margin-bottom: 40px;
    }
}
