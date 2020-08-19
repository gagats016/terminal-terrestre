<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre de Zamora</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal Terrestre Zamora? Buscarfly, les presenta un listado completo de los destinos y frecuencias de las diferentes cooperativas de transporte que prestan sus servicios en el Terminal Terrestre Zamora.<br/>
              En el terminal Zamora, en la actualidad, existen 9 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de Zamora a Gualaquiza, de Zamora a Loja o de Zamora a Cuenca.
              </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->                 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal de Zamora</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Zamora?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Llegar al terminal terrestre de Zamora es fácil puesto que no es una ciudad muy grande y sus lugares se encuentran en distancias cercanas. </br>
              Puede llegar a pie desde cualquier punto de la ciudad.</br>
              Puede llegar también en taxi: es posible tomar un taxi desde cualquier punto de la ciudad, por lo tanto, su tarifa varía de acuerdo con la distancia.
            </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal Zamora</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal Zamora, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
            </blockquote>
          </v-flex> 
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
              <span class="font-weight-bold">Teléfono: </span>072605163<br/>   
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>             
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Gualaquiza<br>
              Zamora - Gualaquiza Macas<br>
              Zamora - Guayaquil<br>
              Zamora - Loja<br>
              Zamora - Machala<br>
              Zamora - Quito<br>
              Zamora - Yantzaza<br>
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/macas?name=Macas">
            <span class="headline font-weight-bold">Macas</span>
          </router-link>
         </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Macas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072624096<br/> 
              <span class="font-weight-bold">Página web: </span><a href="https://coopmacas.com">https://coopmacas.com</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/Coop.Macas/"> https://www.facebook.com/Coop.Macas/</a><br>             
              <span class="font-weight-bold">Correo electrónico: </span>coop-macas-ltda@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa Macas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Gualaquiza - Macas
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/nambija?name=Nambija">
            <span class="headline font-weight-bold">Nambija</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Nambija</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>02729018<br/> 
              <span class="font-weight-bold">Página web: </span><a href="http://www.cooperativanambija.com.ec/">http://www.cooperativanambija.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopnambija"> https://www.facebook.com/coopnambija</a><br>             
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa Nambija: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Quito Quitumbe - Quito Carcelén 
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/sucua?name=Sucua">
            <span class="headline font-weight-bold">Sucúa</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Sucúa</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072606861<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativasucua.com/">https://cooperativasucua.com//</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coop.sucua?fref=search&__tn__=%2Cd%2CP-R&eid=ARDLeeou_tEaDI9dhIIiyMO1GmuM6NvxekgFSZHtx-NXRReTBP6bRQ0nFvaql6OOrWckTxFx659Da-vm">https://www.facebook.com/coop.sucua?fref=search&__tn__=%2Cd%2CP-R&eid=ARDLeeou_tEaDI9dhIIiyMO1GmuM6NvxekgFSZHtx-NXRReTBP6bRQ0nFvaql6OOrWckTxFx659Da-vm/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>coopsucua09@hotmail.com               
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa Sucúa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Yantzaza - Gualaquiza<br>
              Zamora - Macas
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
              <span class="font-weight-bold">Teléfono: </span>072607191<br/>
              <span class="font-weight-bold">Celular: </span>0991354200<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.tourisanfrancisco.com/">https://www.tourisanfrancisco.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/tourisanfrancisco/">https://www.facebook.com/Super-Semeria-846401625493079//</a><br>             
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa Touris San Francisco: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Lago Agrio<br>
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>


        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/unioncariamanga?name=Unión%20Cariamanga">
            <span class="headline font-weight-bold">Unión Cariamanga</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Unión Cariamanga</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2571-340 / 2572-908<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.unioncariamanga.ec/ ">http://www.unioncariamanga.ec/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/UnionCariamanga">https://es-la.facebook.com/UnionCariamanga</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>unioncariamangaec@gmail.com               
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa Unión Cariamanga: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Loja
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/unionyantzaza?name=Unión%20Yantzaza">
            <span class="headline font-weight-bold">Unión Yantzaza</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Unión Yantzaza</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2605359<br/>
              <span class="font-weight-bold">Celular: </span>+593 96 004 2963<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CooperativaDeTransporteUnionYantzaza/">https://www.facebook.com/CooperativaDeTransporteUnionYantzaza/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>union.yantzaza@gmail.com              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Unión Yantzaza: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Bellavista<br>
              Zamora - El Pangui<br>
              Zamora - Gualaquiza<br>
              Zamora - Huaquillas<br>
              Zamora - Loja<br>
              Zamora - Machala<br>
              Zamora - Quito<br>
              Zamora - Tundayme<br>
              Zamora - Yacuambi<br>
              Zamora - Yantzaza<br>
              Zamora - Zumba
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/viajerosinternacional?name=Viajeros%20Internacional">
            <span class="headline font-weight-bold">Viajeros Internacional</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Viajeros Internacional</span>
          </v-flex>    
          <v-flex xs12>
           <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Página web: </span><a href="https://www.viajerosinternacional.com/">https://www.viajerosinternacional.com/</a><br>            
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-Viajeros-417415642166516/">https://www.facebook.com/Cooperativa-Viajeros-417415642166516/</a><br>
               <span class="font-weight-bold">Correo electrónico: </span>reservas@viajerosinternacional.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa de transporte Viajeros Internacional: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Zamora - Cuenca<br>
              Zamora - Yantzaza
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="headline font-weight-bold">Zamora Chinchipe</span>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Zamora Chinchipe</span>
          </v-flex>    
          <v-flex xs12>
           <blockquote class="blockquote mx-0 px-0 mb-2">
            <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/coop.zamorachinchipe/">https://www.facebook.com/coop.zamorachinchipe/</a><br>
          </blockquote>
          </v-flex> 
         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Zamora de la cooperativa de transporte Zamora Chinchipe: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin información
            </blockquote>
            </v-flex>   
          <v-flex xs12>
            </blockquote>
          </v-flex>                                


          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre de Zamora</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de Zamora podrás encontrar:
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
