<template>
   <section class="s1">
       <div class="greeting-wrapper">
           <div class="greeting-wrapper">
                <h1>Hola, soy Juan José Rodríguez</h1>
            </div>
            <div class="intro-wrapper">
                <div class="nav-wrapper">
                    <div class="dots-wrapper">
                        <div id="dot-1" class="browser-dot"></div>
                        <div id="dot-2" class="browser-dot"></div>
                        <div id="dot-3" class="browser-dot"></div>
                    </div>
                    <ul id="navigation">
                        <li>
                            <a href="index.html#contact-form">Contacto</a>
                        </li>
                    </ul>
                </div>
                <div class="left-column">
                    <img :src="MyPhoto" id="profile_pic" >
                    <h5 style="text-align:center; line-height: 0"> 
                        Personalizar Tema 
                    </h5>
                    <div id="theme-options-wrapper">
                        <div data-mode="light" id="light-mode" class="theme-dot"></div>
                        <div data-mode="blue" id="blue-mode" class="theme-dot"></div>
                        <div data-mode="green" id="green-mode" class="theme-dot"></div>
                        <div data-mode="purple" id="purple-mode" class="theme-dot"></div>
                    </div>

                    <p id="settings-note">
                        * Las configuraciones del tema serán guardados 
                        <br> para tu próxima visita
                    </p> 
                </div>

                <div class="right-column">
                    <div id="preview-shadow">
                        <div id="preview">
                            <div id="corner-tl" class="corner"></div>
                            <div id="corner-tr" class="corner"></div>
	
                            <h3>¿Quién soy?</h3>
                            <p> Soy un Desarrollador Web FullStack,  
                              fanático de la tecnología y apasionado por 
                              el desarrollo web 👨‍💻.
                            </p>

                            <div id="corner-bl" class="corner"></div>
								<div id="corner-br" class="corner"></div>
                        </div>
                    </div>                            
                </div>
            </div>
       </div>
   </section>
</template>

<script setup>
import './Presentation.css';
import MyPhoto from '../../assets/my-image.jpg';
</script>
