<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre de Gualaquiza</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal de Gualaquiza? Buscarfly les presenta un listado completo de los destinos y frecuencias de las diferentes cooperativas de transporte que prestan sus servicios en el Terminal Terrestre de Gualaquiza.<br/>
              En el terminal terrestre de Gualaquiza, en la actualidad, existen 10 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de Gualaquiza a Quito, de Gualaquiza a Cuenca o de Gualaquiza a Loja. 
            </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->                 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal de Gualaquiza</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Gualaquiza?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Llegar al terminal terrestre de Gualaquiza es fácil puesto que no es una ciudad muy grande y sus lugares se encuentran en distancias cercanas.<br/>
              Puede llegar a pie o también en tax; es posible tomar uno desde cualquier punto de la ciudad, por lo tanto, su tarifa varía de acuerdo con la distancia. 
            </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal Gualaquiza</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal Gualaquiza, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
            </blockquote>
          </v-flex>                          
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/16deagosto?name=16%20de%20Agosto">
            <span class="headline font-weight-bold">16 de Agosto</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa 16 de Agosto</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07-2780156<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="https://www.cooperativa16deagosto.com/">https://www.cooperativa16deagosto.com/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coop16deagosto/">https://www.facebook.com/coop16deagosto/</a><br>
               <span class="font-weight-bold">Correo electrónico: </span>cooperativa16deagosto@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa 16 de Agosto: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Cuenca<br>
              Gualaquiza - Loja<br>
              Gualaquiza - Macas
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

        <v-flex text-xs-center xs12 class="text-left">
            <router-link to="/search/schedule/centineladeloriente?name=Centinela%20del%20Oriente">
            <span class="headline font-weight-bold">Centinela del Oriente</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Centinela del Oriente</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07 2780156<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.centineladeloriente.com.ec/">http://www.centineladeloriente.com.ec/</a><br>
              <span class="font-weight-bold">Facebook:</span><a href="https://www.facebook.com/israel19985626135/">https://www.facebook.com/israel19985626135/</a><br>              
          </blockquote>
           </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde Gualaquiza de la cooperativa Centinela del Oriente: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            Gualaquiza - Quito
            </blockquote>
          </v-flex>  
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>  
                  <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/flotacenepa?name=Flota%20Cenepa">
            <span class="headline font-weight-bold">Flota Cenepa</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Flota Cenepa</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0995495609<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/flota.cenepa/"> https://www.facebook.com/flota.cenepa/</a><br>                  
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Flota Cenepa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Cuenca
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
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>             
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza  de la cooperativa Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza  - Loja 
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
              <span class="font-weight-bold">Teléfono: </span>072781810<br/>
              <span class="font-weight-bold">Página web: </span><a href=" http://www.cooperativanambija.com.ec/"> http://www.cooperativanambija.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopnambija">https://www.facebook.com/coopnambija</a><br>             
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Nambija: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Guayaquil<br> 
              Gualaquiza - Loja
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/orientrut?name=Orient%20Rut">
            <span class="headline font-weight-bold">Orient Rut</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Orient Rut</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0988984034<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Orient-Rut-SA-1219384671566585/">https://www.facebook.com/Orient-Rut-SA-1219384671566585/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>orientrut@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Orient Rut: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Limón - Méndez - Macas - Río Palora </br>
              Gualaquiza - Limón - Méndez - Macas - Taisha
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
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativasucua.com/">https://cooperativasucua.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coop.sucua?__tn__=%2Cd*F*F-R&eid=ARCJwssxncbEMRtKpL2dyOU4bqxcCICXF-XP5SJXHcTQJkhcLmk7ljYFKueYf6fCVkNKPEW1UnSsiEVl&tn-str=*F">https://www.facebook.com/coop.sucua?__tn__=%2Cd*F*F-R&eid=ARCJwssxncbEMRtKpL2dyOU4bqxcCICXF-XP5SJXHcTQJkhcLmk7ljYFKueYf6fCVkNKPEW1UnSsiEVl&tn-str=*F</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>coopsucua09@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Sucúa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Méndez - Limón - Macas<br>
              Gualaquiza - Yantzaza - Zamora
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
              <span class="font-weight-bold">Teléfono: </span>072782044<br/>
              <span class="font-weight-bold">Celular: </span>0991356000<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.tourisanfrancisco.com/ ">https://www.tourisanfrancisco.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/tourisanfrancisco">https://www.facebook.com/tourisanfrancisco</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Touris San Francisco: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Lago Agrio<br>
              Gualaquiza - Macas - Baños -  Quito Quitumbe
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/turismooriental?name=Turismo%20Oriental">
            <span class="headline font-weight-bold">Turismo Oriental</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Turismo Oriental</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Página web: </span><a href="http://www.turismooriental.ec/">http://www.turismooriental.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/TurismoOriental/">https://es-la.facebook.com/TurismoOriental/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Turismo Oriental: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Cuenca
            </blockquote>
            </v-flex> 
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
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/CooperativaDeTransporteUnionYantzaza/"> https://www.facebook.com/CooperativaDeTransporteUnionYantzaza/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Gualaquiza de la cooperativa Unión Yantzaza: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Gualaquiza - Loja
            </blockquote>
            </v-flex> 
          <v-flex xs12>
            </blockquote>
          </v-flex>                                


          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre de Gualaquiza</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de Gualaquiza podrás encontrar:
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
