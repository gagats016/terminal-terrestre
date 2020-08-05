<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre de Francisco de Orellana, El Coca</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal de Francisco de Orellana? Buscarfly les presenta un listado completo de los destinos y frecuencias de las diferentes cooperativas de transporte que prestan sus servicios en el Terminal Terrestre El Coca.<br/>
              En el terminal terrestre de Francisco de Orellana, en la actualidad, existen 10 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de El Cocao a Quito o de El Coca o a Guayaquil. 
            </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->   
            <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Datos de Contacto Terminal Terrestre de Francisco de Orellana</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>(593) 979 270 683<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/TerminalCoca/?rf=380139382063192">https://www.facebook.com/TerminalCoca/?rf=380139382063192</a><br>
            </blockquote>              
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal El Coca</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Francisco de Orellana?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Llegar al terminal terrestre del Coca es fácil puesto que Francisco de Orellana no es una ciudad muy grande y sus lugares se encuentran en distancias cercanas.
              Puede llegar a pie desde cualquier punto de la ciudad.</br>
              Puede llegar en bus: Hay varias líneas como la de Gran Sumaco y Huaoranis que se pueden tomar y el costo del pasaje es de $0,30 ctvs. </br>
              Puede llegar también en taxi: Es posible tomar un taxi desde cualquier punto de la ciudad, por lo tanto, su tarifa varía de acuerdo con la distancia.
            </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal El Coca</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal El Coca, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
            </blockquote>
          </v-flex>                          
          <v-flex text-xs-center xs12 class="text-left" mt-5>

            <span class="headline font-weight-bold">Alejandro Labaka</span>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Alejandro Labaka</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/companiadetransportesmons.alejandrolabaka">https://www.facebook.com/companiadetransportesmons.alejandrolabaka</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Alejandro Labaka: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - La joya de los Sachas</br>
              El Coca - Lago Agrio</br>
              El Coca - Limoncocha</br>
              El Coca - Porvenir</br>
              El Coca - San Pablo
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

            <router-link to="/search/schedule/banos?name=Baños">
            <span class="headline font-weight-bold">Baños</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Baños</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>03 392 - 0215 ext. 4106 / 4107 / 4108 / 4109<br>
              <span class="font-weight-bold">Página web: </span><a href="http://www.cooperativabanos.com.ec">http://www.cooperativabanos.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativadetransportesbanos">https://www.facebook.com/cooperativadetransportesbanos/</a><br>
               <span class="font-weight-bold">Correo electrónico: </span>info@cooperativabanos.com.ec
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Baños: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Loreto - Quito Quitumbe</br>
              El Coca - Lago Agrio - Quito Quitumbe  
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

        <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Ciudad del Coca</span>
        </v-flex>   
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Ciudad del Coca</span>
          </v-flex> 
          <v-flex xs12>    
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin información.
            </blockquote>
          </v-flex>
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde El Coca de la cooperativa Ciudad del Coca: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            El Coca - Tena</br>
            </blockquote>
          </v-flex>    
         <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

        <v-flex text-xs-center xs12 class="text-left">
            <router-link to="/search/schedule/eldorado?name=El%20Dorado">
            <span class="headline font-weight-bold">El Dorado</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa El Dorado</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">              
              <span class="font-weight-bold">Facebook:</span><a href="https://www.facebook.com/CooperativaDeTransportesElDorado/">https://www.facebook.com/CooperativaDeTransportesElDorado/</a><br>              
          </blockquote>
           </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde El Coca de la cooperativa El Dorado: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            El Coca - Ambato</br>
            El Coca - Chillanes
            </blockquote>
          </v-flex>   
         <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/flotapelileo?name=Flota%20Pelileo">
            <span class="headline font-weight-bold">Flota Pelileo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Flota Pelileo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0623700260<br>
              <span class="font-weight-bold">Página web: </span><a href="http://www.flotapelileo.com.ec/">http://www.flotapelileo.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/pages/category/Transportation-Service/FLOTA-PELILEO-03-189393681657647/"> https://es-la.facebook.com/pages/category/Transportation-Service/FLOTA-PELILEO-03-189393681657647/</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Flota Pelileo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Ambato</br>
              El Coca - Guayaquil</br>
              El Coca - Puyo</br>
              El Coca - Tena
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
            <span class="title">Rutas desde El Coca de la cooperativa Jumandy: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Puyo</br>
              El Coca - Tena
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
              <span class="font-weight-bold">Teléfono: </span>063068804<br/>    
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>                           
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa de transporte Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Santo Domingo - Quevedo - Machala - Loja</br>
              El Coca - Lago Agrio - Quito Quitumbe
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
              <span class="font-weight-bold">Teléfono: </span>062839210 / 062839129<br/>              
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/petrolerashushufindi/">https://www.facebook.com/petrolerashushufindi/</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Petrolera Shushufindi: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Lago Agrio </br>
              El Coca - Shushufindi </br>
              El Coca - Tulcán
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
              <span class="font-weight-bold">Teléfono: </span>3700660 ext. 2002<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-Putumayo-481755651878556/">https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-Putumayo-481755651878556//</a><br>             
              <span class="font-weight-bold">Correo electrónico: </span>coop.putumayo@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Putumayo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca Sacha Lago Agrio Carcelén
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
              <span class="font-weight-bold">Teléfono: </span>060368803<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.tourisanfrancisco.com/">https://www.tourisanfrancisco.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://es-la.facebook.com/tourisanfrancisco/"> https://es-la.facebook.com/tourisanfrancisco/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Touris San Francisco: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Tena - Puyo - Ambato
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
              <span class="font-weight-bold">Teléfono: </span>6 3 700 260<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.transesmeraldas.com/">https://www.transesmeraldas.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/transesmeraldas/"> https://www.facebook.com/transesmeraldas/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Cocao de la cooperativa Transesmeraldas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Quito Carcelén - Quito Quitumbe
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="headline font-weight-bold">Valle del Quijos</span>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Valle del Quijos</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>06 2858222<br/>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Valle del Quijos: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Tena
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
              <span class="font-weight-bold">Teléfono: </span>063068434<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.transporteszaracay.com.ec/">http://www.transporteszaracay.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/oficialtransporteszaracay/"> https://es-la.facebook.com/oficialtransporteszaracay/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde El Coca de la cooperativa Zaracay: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El Coca - Lago Agrio - Chone - Portoviejo - Manta<br/>
              El Coca - Lago Agrio - Santo Domingo - Quevedo - Guayaquil<br/>
              El Coca - Loreto - Santo Domingo - Quevedo - Guayaquil
            </blockquote>
            </v-flex> 
          <v-flex xs12>
            </blockquote>
          </v-flex>                                


          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre El Coca</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de El Coca podrás encontrar:
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
