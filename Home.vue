<script>
import appStore from '../../public/imgs/app-store-badge.png';
import playStore from '../../public/imgs/play-store-badge.png';
export default {
    name: "Home",
    data: () => ({
      playStore: playStore,
      appStore: appStore,
    }) 
};
</script>

<template>
    <section class="">
        <h1><span class="fs-1">JANDY</span> SERVICIOS</h1>

        <p>Les damos la bienvenida a DV Chat, el chat "oficial" de la Escuela Da Vinci, donde vas a poder conectar con otros compañeros, así como docentes y personal de la Escuela.</p>
        
        <div>
            <router-link class="btn btn-primary" to="/trabajadores">¡Comunicate con nuestros profesionales!</router-link>
        </div>


        <section class="row justify-content-center container-fluid mt-5 p-0 mx-0">
              <div class="col-5">
                <h2 class="text-center">¿Que es Jandy?</h2>  
                  <ul class="mt-5">
                    <li> 
                      <p class="fs-6" >Jandy es una aplicación de servicios para el hogar o empresa que participa como intermediaria entre clientes y profesionales, donde los usuarios puedan elegir en base a sus necesidades y presupuestos los servicios que desean adquirir. El cliente dispone de diversas funcionalidades que buscan ayudarle a encontrar al profesional y servicio perfecto, estas funciones son: Filtros por tarifas, localización, calificación, horas de trabajo,etc.
                      </p> 
                    </li>
                    <li class="mt-4">
                      <p class="fs-6"> Por otro lado, los profesionales se pueden inscribir en la plataforma con diferentes requisitos en base al servicio que se quiera ofrecer, una vez inscriptos, podrán añadir diferentes servicios y establecer los precios de cada uno.
                      </p> 
                    </li>
                  </ul>
              </div>
              <div class="col-5">
                <h2 class="text-center mb-5">Servicios</h2>
                <div class="row text-center">
                  <div class="col mt-4">
                    <i class="fs-3 fa-solid fa-screwdriver-wrench"></i>
                    <p>Carpintería</p>
                  </div>
                  <div class="col mt-4">
                  <i class="fs-3 fa-regular fa-lightbulb"></i>
                    <p>Electricidad</p>
                  </div>
                  <div class="col mt-4">
                  <i class="fs-3 fa-solid fa-house"></i>
                    <p>Hogar</p>
                  </div>
                </div>
                <div class="row text-center mt-5">
                  <div class="col">
                  <i class="fs-3 fa-solid fa-certificate"></i>
                    <p>Trabajadores Certificados</p>
                  </div>
                  <div class="col">
                  <i class="fs-3 fa-solid fa-shield-halved"></i>
                    <p>Seguridad</p>
                  </div>
                  <div class="col">
                  <i class="fs-3 fa-solid fa-phone"></i>
                    <p>Soporte 24hs</p>
                  </div>
                </div>
              </div>
            
              <div class="mt-5">
                <h1 class="text-center mb-5">¿Por qué contratar Jandy?</h1>
                <p>Si necesitas un electricista, cambiar una lampara, revisar tableros electronicos, o hacer una instalación eléctrica completa Jandy es la mejor opción para que puedas encontrar al trabajador ideal. Sabemos que desea un servicio prolijo, rápido y a buen precio. 
                    Jandy lo conectara electricistas de alto nivel certificados y con experiencia y con lo que ustede esté buscando.
                    Te ayudamos a programar las tareas de tu casa relacionadas a la electricidad para que puedas ahorrarte ese tiempo de tu vida.
                </p>
            
            
                <div class="col">
                    
                    
                    <div class="row text-center mt-5">
                        <div class="col">
                            <i class="fs-3 fa-solid fa-certificate"></i>
                            <h4>Trabajadores Certificados</h4>
                            <p>Los servicios ofrecidos por Jandy son realizados por profesionales que estan en constante evaluacion por parte de clientes como usted. </p>
                        </div>
                        <div class="col">
                            <i class="fs-3 fa-solid fa-shield-halved"></i>
                            <h4>Seguridad</h4>
                            <p>Los posibles trabajadores de Jandy proporcionan información personal detallada. Además de que sus datos son validados como también su experiencia de servicio</p>
                        </div>
                        <div class="col">
                            <i class="fs-3 fa-solid fa-phone"></i>
                            <h4>Contamos con Soporte 24hs</h4>
                            <p> Si tiene un problema, comuníquese con nuestro equipo de Servicio al cliente 24/7.</p>
                        </div>
                    </div>
                </div>
            
                
              </div>
              <section class="section-garantia p-0 d-flex mb-5 container">
                <div class="row">
                  <div class="col-4 bg-primary p-0">
                      <h2 class="text-center text-light pt-5">Tu Felicidad, Garantizada</h2>
                      <p class="w-75 m-auto text-light mt-3">
                        Tú felicidad es nuestra meta. Si no estas satisfecho, trabajaremos para corregirlo. Nuestra atención al cliente está disponibles las 24 horas del día, los 7 días de la semana. La Jandy Happiness Guarantee solo se aplica cuando reserva y paga un servicio directamente a través de la plataforma de Jandy.
                      </p>
                  </div>
                  <div class="col-8 p-0">
                      <img class="" src="https://via.placeholder.com/1050x500" alt="">
                  </div>
                </div>
              </section>

              <section class="container section-garantia">
                <div class="row">
                  <div class="col-5 bg-danger pb-5">
                      <h2 class="text-center mt-5 pt-5 h2a">Descagar la App de Jandy</h2>
                      <p class="text-center mt-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate laboriosam porro assumenda?</p>
                      <div class="d-flex justify-content-around mt-5">
                        <div>
                          <img :src="appStore" alt="" width="200" height="75">
                        </div>
                        <div>
                          <img :src="playStore" alt="" width="200" height="75">
                        </div>
                      </div>
                  </div>
                  <div class="col-7 bg-success">

                  </div>
                </div>

              </section>
            </section>
    </section>
</template>

<style scoped>
  .btn-primary{
      background-color: #d99567;
      border: #d99567;
  }

  span{
    color: #8099c9;
  }

  i{
    color: #8099c9;
  }
  .section-garantia{
    height: 500px;
  }
  .section-garantia div{
    height: 500px;
  }
  
</style>