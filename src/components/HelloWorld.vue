<template>
 
    <link rel="stylesheet" href="https://necolas.github.io/normalize.css/8.0.1/normalize.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    
 

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
          <a href="https://www.facebook.com/"><i class="fa-brands fa-facebook-f"></i></a>
          <a href="https://www.linkedin.com/in/yasser-bracho-a577331ba/"><i class="fa-brands fa-linkedin"></i></a>
          <a href="https://github.com/yasserbv"><i class="fa-brands fa-github"></i></a>
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
                  310 348 7741
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
                <span>IMPRESION 3D</span>
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

          <a href="@asseets/archivo/cv_yasser.pdf" download="cv">
            Descargar CV <i class="fa-solid fa-download"></i>
            <span class="overlay">
            </span>
          </a>
      </div>
    </section>

    <section class="skills" id="skills">
      <div class="contenedor-seccion">
        <h2>Skills</h2>
        <div class="fila">
          <div class="col">
            <h3>Technical Skills</h3>
            <div class="skills">

              <span>Python</span>
              <div class="barra-skills">
                <div class="progreso">
                  <span>75%</span>
                </div>
              </div>
            </div>
            <div class="skills">
              <span>HTML , CSS & JavaScript</span>
              <div class="barra-skills">
                <div class="progreso">
                  <span>89%</span>
                </div>
              </div>
            </div>
            <div class="skills">
              <span>Vue.js</span>
              <div class="barra-skills">
                <div class="progreso">
                  <span>60%</span>
                </div>
              </div>
            </div>
            
          </div>

          <div class="col">
            <h3>Professional Skills</h3>
            <div class="skills">
              <span>Comunicacion</span> 
              <div class="barra-skills">
                <div class="progreso">
                  <span>75%</span>
                </div>
              </div>
            </div>
            <div class="skills">
              <span>Trabajo en Equipo</span>
              <div class="barra-skills">
                <div class="progreso">
                  <span>70%</span>
                </div>
              </div>
            </div>
            <div class="skills">
              <span>Creatividad</span>
              <div class="barra-skills">
                <div class="progreso">
                  <span>90%</span>
                </div>
              </div>
            </div>
            
          </div>
        </div>
      </div>
    </section>
  
  <section class="curriculum" id="curriculum">
    <div class="contenido-section">
      <h2>curriculum</h2>
      <div class="fila">
        <div class="col izquierda">
          <div class="col izquierda">
          <h3>Educacion</h3>
          <div class="item izq">
            <h4>INGENIERIA DE SISTEMAS</h4>
            <span class="casa">Universidad de la guajira</span>
            <span class="fecha">2016 - 2023</span>
            <p>Durante mi tiempo en la Universidad de La Guajira, obtuve una formación integral en Ingeniería de Sistemas, donde adquirí conocimientos fundamentales en áreas como programación, diseño de software, bases de datos y seguridad informática. Participé activamente en proyectos académicos que me permitieron aplicar mis habilidades en entornos prácticos, desarrollando soluciones innovadoras para desafíos tecnológicos.</p>
            <div class="conectori">
              <div class="circuloi"></div>
            </div>
          </div>
        </div>
         </div>

         <div class="col derecha">
          <h3>Experiencia de trabajo</h3>
          <div class="item der">
            <h4>DESARROLLADOR FRONT END</h4>
            <span class="casa">FREE LANCE</span>
            <span class="fecha">2018 - 2024</span>
            <p>Como desarrollador web freelance, he tenido el privilegio de trabajar en una variedad de proyectos emocionantes y desafiantes, lo que me ha permitido expandir mis habilidades y conocimientos en el campo del desarrollo web. Durante este período, colaboré estrechamente con una diversidad de clientes, desde pequeñas empresas locales hasta startups en crecimiento y empresas internacionales.</p>
            <div class="conectord">
              <div class="circulod"></div>
            </div>
          </div>
         </div>
         </div>
         </div>
  </section>


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
.sobremi a{
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
text-decoration: none;
}
.sobremi a .overlay{
position: absolute;
top: 0;
left: 0;
width: 0;
height: 100%;
background-color: #1CB698;
z-index: -1;
transition: 1s;
}
.sobremi a:hover .overlay{
width: 100%;
}

.skills{
background-color: #252A2E;
color: #ffff;
padding: 0px 50px ;

}

.skills .contenido-seccion{
  max-width: 1100px;
  margin: auto;
}
.skills h2{
  font-size: 48px;
  font-family: 'Righteous';
  text-align: center;
  padding: 20px 0;
}

.skills .fila{
display: flex;
}
.skills .fila .col{
  width: 50%;
  padding: 0 20px;
}

.skills .fila .col h3{
  font-size:  28px;
  font-family: 'Righteous';
  margin-bottom: 25px;
  margin-left: 10%;
}

.skills .skills > span{
font-weight: bold;
display: block;
margin-bottom: 10px;
}
.skills .skills .barra-skills{
  height:8px;
  width: 80%;
  background-color: #131517;
  position: relative;
  margin-bottom: 30px;
}
.skills .skills .progreso{
  background-color: #1CB698;
  position:absolute;
  top: 0;
  left: 0;
  height: 8px;
}
.skills .skills .barra-skills span{
position:absolute;
height: 40px;
width: 40px;
background-color: #1CB698;
border-radius: 50px;
line-height: 40px;
text-align: center;
top:-17px;
right: -15px;
font-size: 14px;
}

.skills .skills .javascript{
  width: 0%;
  animation: 2s javascript forwards;
}
@keyframes javascript{
  0%{width: 0%;}
  100%{width: 75%;}
}

.skills .skills .htmlcss{
  width: 0%;
  animation: 2s htmlcss forwards;
}
@keyframes htmlcss{
  0%{width: 0%;}
  100%{width: 89%;}
}
.skills .skills .vuejs{
  width: 0%;
  animation: 2s vuejs forwards;
}
@keyframes vuejs{
  0%{width: 0%;}
  100%{width: 60%;}
}

.skills .skills .comunicacion{
  width: 0%;
  animation: 2s comunicacion forwards;
}
@keyframes comunicacion{
  0%{width: 0%;}
  100%{width: 75%;}
}

.skills .skills .trabajo{
  width: 0%;
  animation: 2s trabajo forwards;
}
@keyframes trabajo{
  0%{width: 0%;}
  100%{width: 70%;}
}

.skills .skills .Creatividad{
  width: 0%;
  animation: 2s Creatividadforwards;
}
@keyframes Creatividad{
  0%{width: 0%;}
  100%{width: 90%;}
}



.curriculum{
background-color: #1e2326;
color: #ffff;
padding: 0px 50px ;

}

.curriculum .contenido-seccion{
  max-width: 1100px;
  margin: auto;
}
.curriculum h2{
  font-size: 48px;
  font-family: 'Righteous';
  text-align: center;
  padding: 20px 0;
}

.curriculum .fila{
display: flex;
justify-content: space-between;
}
.curriculum .fila .col{
padding: 0 20px;
}

.curriculum .fila .col h3{
font-size: 28px;
font-family: 'Righteous';
margin-bottom: 25px;
}

.curriculum .fila .derecha{
  border-left:2px solid #252A2E ;
}


.curriculum .fila .item{
padding: 25px;
margin-bottom:30px;
background-color: #252A2E;
position: relative;
}

.curriculum .fila .item h4{
font-size: 20px;
margin-bottom: 10px;
}
.curriculum .fila .item .casa{
color: #1CB698;
font-size: 22px;
font-weight: bold;
display: block;
}

.curriculum .fila .item .fecha{
  display: block;
  color: #1CB698;
  margin-bottom:10px;
}

.curriculum .fila .item p{
  line-height: 24px;
}
.curriculum .fila .izq{
  border-right:2px solid #1CB698 ;
  margin-right: 20px;
}
.curriculum .fila .der{
  border-left:2px solid #1CB698 ;
  margin-left: 20px;
}

.curriculum .fila .item .conectori{
  height:  2px;
  background-color: #1CB698;
  width: 47px;
  position: absolute;
  top: 50%;
  right: -47px;
  z-index: 5;
}
.curriculum .fila .item .circuloi{
display: block;
height: 10px;
width: 10px;
border-radius: 50%;
background-color: #1CB698;
float: right;
position: relative;
bottom: 4px;
}

.curriculum .fila .item .conectord{
  height:  2px;
  background-color: #1CB698;
  width: 47px;
  position: absolute;
  top: 50%;
  left: -47px;
  z-index: 5;
}
.curriculum .fila .item .circulod{
display: block;
height: 10px;
width: 10px;
border-radius: 50%;
background-color: #1CB698;
float: left;
position: relative;
bottom: 4px;
}

.portfolio{
background-color: #1e2326;
color: #ffff;
padding: 0px 50px ;

}

.portfolio .contenido-seccion{
  max-width: 1100px;
  margin: auto;
}
.portfolio h2{
  font-size: 48px;
  font-family: 'Righteous';
  text-align: center;
  padding: 20px 0;
}

.portfolio .galeria{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
 .portfolio .galeria .proyecto{
  position: relative;
  max-width: 340px;
  height: fit-content;
  margin: 10px;
  cursor: pointer;
 }
 .portfolio .galeria .proyecto img{
  width: 100%;
  display: block;
 }
 .portfolio .galeria .proyecto .overlay{
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  text-align: center;
  background: linear-gradient(rgba(20,182,152,.8),rgba(28,182,152,.8));
  display: flex;
  flex-direction: column;
  justify-content: center;
  transition: 1%;
  font-size: 18px;
  letter-spacing: 3px;
  opacity: 0;
 }
 .portfolio .galeria .proyecto .overlay h3{
  margin-bottom: 20px;
  transition: 1s;
 }

 .portfolio .galeria .proyecto .overlay:hover{
  opacity: 1;
 }
 .portfolio .galeria .proyecto .overlay:hover h3{
 margin-bottom:0px;
 }
</style>







