<template>
  <!DOCTYPE html>
  <html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://necolas.github.io/normalize.css/8.0.1/normalize.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Portfolio</title>
  </head>
  <body>
    <div class="contenedor-header">
    <header>
        <div class="logo">
          <a href="#">Yasser bv</a>
        </div>
     <nav id="nav">
       <ul>

        <li><a href="#inicio">INICIO</a></li>
        <li><a href="#sobremi">SOBRE MI</a></li>
        <li><a href="#skills">SKILLS</a></li>
        <li><a href="#curriculum">CURRICULUM</a></li>
        <li><a href="#portfolio">PORTFOLIO</a></li>
        <li><a href="#contacto">CONTACTO</a></li>
       </ul>
     </nav>
   <div class="nav-responsive">
    <i class="fa-solid fa-bars"></i>
   </div>
    </header>
    </div>
    <selection id="inicio" class="inicio">
      <div class="contenido-banner">
        <div class="contenerdor-img">

          <img src="@/assets/hero_3.png" alt="">
        </div>
        <h1>YASSER BRACHO</h1>
        <h2>Ingeniero de sistemas - Frontend Developer </h2>
        <div class="redes">
          <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
          <a href="#"><i class="fa-brands fa-twitter"></i></a>
          <a href="#"><i class="fa-brands fa-linkedin"></i></a>
          <a href="#"><i class="fa-brands fa-github"></i></a>
        </div>
      </div>
    </selection>
     <section id="sobremi" class="sobremi">
      <div class="contenido-seccion">
        <h2>Sobre Mi</h2>
        <p><span>Hola, soy yasser bracho.</span>desarrollador frontend con 2 años de experiencia especializado en Vue.js. He trabajado tanto en proyectos profesionales como freelance, siempre buscando crear interfaces web dinámicas y atractivas. Me apasiona seguir aprendiendo y creciendo en esta industria</p>

          <div class="fila">
            <div class="col">
              <h3>Datos Personales</h3>
              <ul>
                <li>
                  <strong>Cumpleaños</strong>
                  13-12-1997
                </li>
                <li>
                  <strong>Telefonos</strong>
                  320 884 0876
                </li>
                <li>
                  <strong>Email</strong>
                  bracho.yasser@gmail.com
                </li>
                <li>
                  <strong>Direccion</strong>
                  Calle 13 #30-12 Maicao Laguajira Colombia
                </li>
                <li>
                  <strong>Cargos</strong>
                    <span> FREELANCE</span>
                </li>
              </ul>
            </div>
            <div class="col">
             <h3>Intereses</h3>
             <div class="contenedor-intereses">
              <div class="interes">
                <i class="fa-solid fa-guitar"></i>
                <span>MUSICA</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-dumbbell"></i>
                <span>GYM</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-plane"></i>
                <span>VIAJAR</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-microchip"></i>
                <span>ELECTRONICA</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-cubes"></i>
                <span>IMPRECION 3D</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-book"></i>
                <span>LIBROS</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-motorcycle"></i>
                <span>MOTOS</span>
              </div>
              <div class="interes">
                <i class="fa-solid fa-camera"></i>
                <span>FOTOS</span>
              </div>
             </div>
            </div>
          </div>
          <BUtton>
            Descargar CV <i class="fa-solid fa-download"></i>
            <span class="overlay">
            </span>
          </BUtton>
      </div>
    </section>
    

  </body>
  </html>

</template>



<script setup>



</script>


<style scoped>


@import url('https://fonts.googleapis.com/css2?family=Righteous&family=Work+Sans:wght@100;200;300;400;600;800&display=swap');

*{

  box-sizing: border-box;
  font-family: 'Work Sans';
  margin: 0;
  padding: 0;
}

html{
scroll-behavior: smooth;
}
.contenedor-header{
  background-color: #1e2326;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 99;
}
.contenedor-header header{

  max-width: 1100px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items:center;
  padding: 15px 20px;
}
.contenedor-header header .logo a{

  font-family:'Righteous';
  font-size: 36px;
  color: #1CB698;
  text-decoration: none;
}

.contenedor-header header ul{

  display: flex;
  list-style: none;
}
.contenedor-header header nav ul li a{
  text-align: none;
  color: #fff;
  margin: 0 15px;
  padding: 3px;
  transition: .5s;
  text-decoration: none;
}
.contenedor-header header nav ul li a:hover {
color:#1CB698;
}

.nav-responsive{

  background-color: #1CB698;
  color: #fff;
  padding: 5px;
  padding: 5px 10px;
  border-radius: 5px;
  cursor: pointer;
  display: none;
}

.inicio{

  background: linear-gradient(to top,rgba(30,35,38,.8),rgba(30,35,38,1)),
  url("@/assets/fondo.jpg");
  background-size: cover;
  height: 100vh;
  color: #ffff;
  display: flex;
  align-items: center;
}

.inicio .contenido-banner{
padding: 20px;
background-color: #1e2326;
max-width: 350px;
margin: auto;
margin-top: 8%;
text-align: center;
border-radius: 40px;

}

.inicio .contenido-banner img{
margin-top:40px;
border: 10px solid #1CB698;
display: block;
width: 80%;
margin: auto;
border-radius: 100%;
}
.inicio .contenido-banner h1{
margin-top:40px;
font-size: 30px;
font-family: 'Righteous';
}
.inicio .contenido-banner h2{
font-size: 15px;
font-weight: normal;
margin-top: 10px;
}

.inicio .contenido-banner .redes a{
color: #FFFF;
display: inline-block;
text-decoration:none;
border: 1px solid #fff;
border-radius: 100%;
width: 42px;
height: 42px;
line-height: 42px;
margin: 20px 5px;
font-size: 20px; 
transition: .3s;
}
.inicio .contenido-banner .redes a:hover{
 background-color: #1cb698;
}

.sobremi{
background-color: #1e2326;
color: #ffff;
padding: 50px 20px;
}

.sobremi .contenido-seccion{
  max-width: 1100px;
  margin: auto;
}
.sobremi h2{
  font-size: 49px;
  font-family: 'Righteous';
  text-align: center;
  padding: 20px;
}
.sobremi .contenido-seccion p{
font: 10px;
line-height: 22px;
margin-bottom: 20px;
}

.sobremi .contenido-seccion p span{
 color: #1cb698;
 font-weight: bold;
}

.sobremi .fila{
display: flex;
}
.sobremi .fila .col{
  width: 50%;
}
.sobremi .fila .col h3{
font-size: 28px;
font-family: 'Righteous';
margin-bottom: 25px;
}
.sobremi .fila .col ul{
 list-style: none;
}

.sobremi .fila .col ul li{
  margin: 12px 0;
}

.sobremi .fila .col ul li strong{
display: inline-block;
color: #1cb698;
width: 130px;
}
.sobremi .fila .col ul li span{
  background-color: #1cb698;
  padding: 3px;
  font-weight: bold;
  border-radius: 5px;
}
.sobremi .fila .col .contenedor-intereses{
display: flex;
flex-wrap: wrap;
}
.sobremi .fila .col .contenedor-intereses .interes{
width: 120px;
height: 120px;
background-color: #252a2e;
border-radius: 10px;
margin: 0 15px 15px 0;
display: flex;
flex-direction:column;
align-items: center;
justify-content:center;
transition: .3s;
}
.sobremi .fila .col .contenedor-intereses .interes:hover{
background-color: #1CB698;
cursor: pointer;
}
.sobremi .fila .col .contenedor-intereses .interes i{
  font-size: 30px;
  margin-bottom: 10px;
}
.sobremi button{
cursor: pointer;
background-color: transparent;
border: 2px solid #ffff;
width: fit-content;
display: block;
margin:20px auto;
padding: 10px 22px;
font-size: 16px;
color: #ffff;
position: relative;
z-index: 10;
}
.sobremi button .overlay{
position: absolute;
top: 0;
left: 0;
width: 0;
height: 100%;
background-color: #1CB698;
z-index: -1;
transition: 1s;
}
.sobremi button:hover .overlay{
width: 100%;

}
</style>







