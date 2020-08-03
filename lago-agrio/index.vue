<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre de Lago Agrio</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal de Lago Agrio? Buscarfly les presenta un listado completo de los destinos y frecuencias de las diferentes cooperativas de transporte que prestan sus servicios en el Terminal Terrestre de Nueva Loja.<br/>
              En el terminal terrestre de Nueva Loja, en la actualidad, existen 10 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de Lago Agrio a Quito o de Lago Agrio a Guayaquil. 
            </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->                 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal de Lago Agrio</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Lago Agrio?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Llegar al terminal terrestre de Nueva Loja es fácil puesto que Nueva Loja no es una ciudad muy grande y sus lugares se encuentran en distancias cercanas.<br/>
              Puede llegar a pie, bus urbano o también en taxi, es posible tomar un taxi desde cualquier punto de la ciudad, por lo tanto, su tarifa varía de acuerdo con la distancia. 
            </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal Lago Agrio</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal Lago Agrio, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
            </blockquote>
          </v-flex>                          
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/banos?name=Baños">
            <span class="headline font-weight-bold">Baños</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Baños</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span> 03 392 - 0215 ext. 4113  0986520213<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="http://www.cooperativabanos.com.ec">http://www.cooperativabanos.com.ec/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativadetransportesbanos">https://www.facebook.com/cooperativadetransportesbanos/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>info@cooperativabanos.com.ec
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Baños: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Quito Quitumbe </br>
              Lago Agrio - Quito Carcelén - Quito Quitumbe 
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
        <v-flex text-xs-center xs12 class="text-left">
            <router-link to="/search/schedule/carlosalbertoaray?name=Carlos%20Alberto%20Aray">
            <span class="headline font-weight-bold">Carlos Alberto Aray</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Carlos Alberto Aray</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0990698101<br/>
              

              <span class="font-weight-bold">Facebook:</span><a href="https://www.facebook.com/Transportes-de-Pasajeros-y-Encomiendas-Carlos-Alberto-Aray-101399428292118/">https://www.facebook.com/Transportes-de-Pasajeros-y-Encomiendas-Carlos-Alberto-Aray-101399428292118/</a><br>              
              
          </blockquote>
           </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Carlos Alberto Aray: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            Lago Agrio - Manta
            </blockquote>
          </v-flex>  
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
        <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Ciudad del Coca</span>
        </v-flex>    
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin información.
            </blockquote>
          </v-flex>  
         <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
                  <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/jumandy?name=Jumandy">
            <span class="headline font-weight-bold">Jumandy</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Jumandy</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              
              <span class="font-weight-bold">Página web: </span><a href="https://coopjumandy.webs.com/rutas">https://coopjumandy.webs.com/rutas</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopjumandy.jumandy">https://www.facebook.com/coopjumandy.jumandy/</a><br>              
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Jumandy: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Tena </br>
              Lago Agrio - Puyo
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/loja?name=Loja">
            <span class="headline font-weight-bold">Loja</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Loja</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>062831570<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>             
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Loja </br>
              Lago Agrio - Quito Quitumbe </br>
              Lago Agrio - Guayaquil
            </blockquote>
            </v-flex> 

           <v-flex xs12 my-3><v-divider></v-divider></v-flex>
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/petrolerashushufindi?name=Petrolera%20Shushufindi">
            <span class="headline font-weight-bold">Petrolera Shushufindi</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Petrolera Shushufindi</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>062839210 / 062839129 <br/>
              
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/petrolerashushufindi/">https://www.facebook.com/petrolerashushufindi/</a><br>             
              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Petrolera Shushufindi: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Sacha - Coca </br>
              Lago Agrio - Puerto El Carmen
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/putumayo?name=Putumayo">
            <span class="headline font-weight-bold">Putumayo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Putumayo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>062-833-819<br/>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-Putumayo-481755651878556/">https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-Putumayo-481755651878556//</a><br>             
                             <span class="font-weight-bold">Correo electrónico: </span>coop.putumayo@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Putumayo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Otavalo  - Ibarra - Tulcán </br>
              Lago Agrio - Quito Carcelén </br>
              Lago Agrio - Tena
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>
           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/tourissanfrancisco?name=Touris%20San%20Francisco">
            <span class="headline font-weight-bold">Touris San Francisco</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Touris San Francisco</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>062831211<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.tourisanfrancisco.com/">https://www.tourisanfrancisco.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://es-la.facebook.com/tourisanfrancisco/"> https://es-la.facebook.com/tourisanfrancisco/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Touris San Francisco: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Zamora
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>
           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/transesmeraldas?name=Transesmeraldas">
            <span class="headline font-weight-bold">Transesmeraldas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Transesmeraldas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>+593 23922300 ext. 475<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.transesmeraldas.com/">https://www.transesmeraldas.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/transesmeraldas/"> https://www.facebook.com/transesmeraldas/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Transesmeraldas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Quito Carcelén - Quito Quitumbe
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>
           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/zaracay?name=Zaracay">
            <span class="headline font-weight-bold">Zaracay</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Zaracay</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>062830681<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.transporteszaracay.com.ec/">http://www.transporteszaracay.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/oficialtransporteszaracay/"> https://es-la.facebook.com/oficialtransporteszaracay/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Lago Agrio de la cooperativa de transporte Zaracay: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Lago Agrio - Santo Domingo - Quinindé - La Concordia <br/>
              Lago Agrio - Santo Domingo - Chone - Manta <br/>
              Lago Agrio - Santo Domingo - Quevedo - Guayaquil
            </blockquote>
            </v-flex> 
          <v-flex xs12>
            </blockquote>
          </v-flex>                                


          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre de Lago Agrio</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de Lago Agrio podrás encontrar:
            </v-flex>
            <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Servicios de transporte</span>
          </v-flex>
          <v-flex xs12 class="blockquote">
              <ul>
                <li>Viajes interparroquiales</li>
                <li>Viajes intercantonales</li>
                <li>Viajes interprovinciales</li>
                <li>Taxi</li>
                <li>Servicio de transporte urbano</li>
              </ul>
          </v-flex> 
         <v-flex xs12 class="blockquote">
          Así mismo:
         </v-flex>   
          <v-flex xs12 class="blockquote">
          <ul>
                <li>Encomiendas</li>
                <li>Servicio de transporte de carga</li>
          </ul>   
          </v-flex>

            <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Locales Comerciales</span>
          </v-flex>
          <v-flex xs12 class="blockquote">
           Diferentes servicios que hacen de la espera un momento entretenido, entre ellos:
            </v-flex>
          <v-flex xs12 class="blockquote">
              <ul>
                <li>Restaurantes, cafeterías y comida rápida</li>
                <li>Bazar y almacenes</li>
              </ul>
          </v-flex> 

        </v-layout>
      </v-container>
    </div>
  </div>
</template>
<script>
require('~/static/css/style.css')
import app_menu from '~/components/Menu'
import { APP_NAME } from "~/app.config"

export default {
  head () {
    return {
      title: 'Acerca de nosotros',
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        { hid: 'description', name: 'description', content: 'My custom description' }
      ]
    }
  },  
  components: { app_menu },
  data() {
    return {
      APP_NAME: APP_NAME,
      isVisibleDetalles: false,
    }
  },
  created() {
    // Scrolls to top when view is displayed
    // window.scrollTo(0, 0);
  }
};

</script>
</script>
<style scoped>
.steps {
  background-image: url(~assets/img/ilustraciones/swoosh-background.svg);
  /*color: #484848 !important;*/
  background-repeat: no-repeat;
  min-height: 750px;
  background-size: cover;
  background-position: center;
  width: 100%;
  margin-top: -75px;
  font-weight: bold;
  line-height: 42px !important;
  letter-spacing: -0.8px !important;
}

.header-about {
  margin-top: -75px;
  padding: 0px ! important;
  background-color: #24292e !important;
}

/*color: #484848 !important;*/
.steps-box {
  max-width: 75%;
  text-align: left;
  margin: auto;
}

.text-why {
  font-size: 18px;
  line-height: 24px;
  color: #484848;
  font-weight: 300 !important;
  font-family: Circular, -apple-system, BlinkMacSystemFont, Roboto, Helvetica Neue, sans-serif !important;
  text-align: left;
}

.title-why {
  font-size: 30px;
  line-height: 24px;
  font-weight: ;
  color: #484848;
  font-weight: 600 !important;
  font-family: Circular, -apple-system, BlinkMacSystemFont, Roboto, Helvetica Neue, sans-serif !important;
  text-align: left;
}

.title-why-h2 {
  font-size: 40px;
  line-height: 24px;
  font-weight: ;
  color: #484848;
  font-weight: 600 !important;
  font-family: Circular, -apple-system, BlinkMacSystemFont, Roboto, Helvetica Neue, sans-serif !important;
  text-align: left;
}

a {
  text-decoration-line: none;
}

.color-caja-infocom {
  background-color: #4264fb !important
}

.blockquote {
  text-align: justify;
}

.title-head {
  font-size: 50px;
  line-height: 24px;
  color: #484848;
  font-weight: 500 !important;
  font-family: Circular, -apple-system, BlinkMacSystemFont, Roboto, Helvetica Neue, sans-serif !important;
}

.sub-title-head {
  font-size: 30px;
  line-height: 1.3 ! important;
  font-weight: 300 !important;
  font-family: Circular, -apple-system, BlinkMacSystemFont, Roboto, Helvetica Neue, sans-serif !important;
}

blockquote {
  margin-right: 20px
}

.container {
  max-width: 1012px !important;
}

</style>
