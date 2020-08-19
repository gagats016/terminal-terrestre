<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre Cuenca</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal Terrestre Cuenca? Buscarfly, les presenta un listado completo de los destinos y frecuencias de las diferentes cooperativas de transporte que prestan sus servicios en el Terminal Terrestre Cuenca.<br/>
              En el terminal Cuenca, en la actualidad, existen 29 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de Cuenca a Guayaquil, de Cuenca a Loja o de Cuenca a Quito. Pero también se puede tomar un bus internacional para ir de Cuenca a Máncora o de Cuenca a Piura, en Perú. 
            </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->                 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal de Cuenca</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Cuenca?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El terminal de Cuenca, no se encuentra muy lejos del centro histórico, po eso que puede llegar a pie con facilidad. Además, se puede llegar en transporte público, tal como en bus urbano con las lineas 7, 8, 10 y 28 ; el pasaje de bus tiene un costo de 0,30$. Así mismo, puede llegar en tranvía con un precio de 0,30$.<br/>
              También se puede llegar en carro, que sea particular o en taxi. La carrera mínima de taxi de día es de 1,37$ y de noche de 1,67$. 
            </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal Cuenca</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal Cuenca, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
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
              <span class="font-weight-bold">Teléfono: </span>07-2838703<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.cooperativa16deagosto.com/">https://www.cooperativa16deagosto.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coop16deagosto/">https://www.facebook.com/coop16deagosto/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>cooperativa16deagosto@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa 16 de Agosto: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Chigüinda - Gualaquiza</br>
              Cuenca - San Juan Bosco - Gualaquiza</br>
              Cuenca - El Pangui</br>
            </blockquote>
          </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                   <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/alausi?name=Alausí">
            <span class="headline font-weight-bold">Alausí</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Alausí</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Página web: </span><a href="http://www.ctaalausi.com/">http://www.ctaalausi.com/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/interprovincial.alausicta"> https://www.facebook.com/interprovincial.alausicta/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>info@ctaalausi.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Alausí: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Alausí
            </blockquote>
          </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                            <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/alianza?name=Alianza">
            <span class="headline font-weight-bold">Alianza</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Alianza</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Alianza: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Parque Nacional Cajas - Guayaquil<br>
              Cuenca - La Troncal - Guayaquil
            </blockquote>
          </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/alpesorientales?name=Alpes%20Orientales">
            <span class="headline font-weight-bold">Alpes Orientales</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Alpes Orientales</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Alpes Orientales: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Guarumales<br>
              Cuenca - Jadán
            </blockquote>
          </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/amazonas?name=Amazonas">
            <span class="headline font-weight-bold">Amazonas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Amazonas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              
              <span class="font-weight-bold">Página web: </span><a href="http://transportesamazonas.com.ec/">http://transportesamazonas.com.ec/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/cooptransportesamazonas/"> https://www.facebook.com/cooptransportesamazonas/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>amazonascooperativa@yahoo.es
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Amazonas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Baños de Agua Santa - Riobamba – Puyo - Tena - Misahualli
 
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
                    <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/avilagonzales?name=Avila%20Gonzales">
            <span class="headline font-weight-bold">Avila Gonzales</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Avila Gonzales</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin información
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Avila Gonzales: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Progreso – Susudel - Oña<br>
              Cuenca – Progreso – Susudel<br>
              Cuenca – La Paz – Susudel - Oña
            </blockquote>
          </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                    <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/amazonas?name=Amazonas">
            <span class="headline font-weight-bold">Azuay Internacional</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Azuay Internacional</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
             <span class="font-weight-bold">Teléfono: </span>072823163 / 072839055<br/> 
              <span class="font-weight-bold">Página web: </span><a href="http://www.transportesazuay.com/">http://www.transportesazuay.com/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopazuayinternacional/"> https://www.facebook.com/coopazuayinternacional/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>gerencia@transportesazuay.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Azuay Internacional: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Pasaje – Machala<br>
              Cuenca – Zaruma<br>
              Cuenca – Máncora(Pe) - Piura(Pe) - Chiclayo(Pe)<br>
              Cuenca – Santa Rosa – Arenillas - Huaquillas
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
      
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/canar?name=Cañar">
            <span class="headline font-weight-bold">Cañar</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Cañar</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07-2844033 <br/>
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Cañar: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Azogues – Biblián – Cañar – El Tambo<br/>
              Cuenca – Azogues – Biblián – Cañar – El Tambo - Ingapirca
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
              <span class="font-weight-bold">Teléfono: </span>0959912777  y  0988850787<br/>
              <span class="font-weight-bold">Página web: </span><a href="www.centineladeloriente.com.ec">www.centineladeloriente.com.ec</a><br>
              <span class="font-weight-bold">Facebook:</span><a href="https://www.facebook.com/CentinelaDelOrienteCtco/">https://www.facebook.com/CentinelaDelOrienteCtco/</a><br>                    
          </blockquote>
           </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde Cuenca de la cooperativa Centinela del Oriente: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            Cuenca - Mendez - Sucúa – Macas - Puyo
            </blockquote>
          </v-flex>  
         <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="headline font-weight-bold">Chordeleg</span>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Chordeleg</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>073052803<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/companiadetransportes.chordeleg">https://www.facebook.com/companiadetransportes.chordeleg</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Chordeleg: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Chordeleg
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/citca?name=CITCA">
            <span class="headline font-weight-bold">CITCA</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa CITCA</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>(07) 224-3509<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/citcaazocue/">https://www.facebook.com/citcaazocue//</a><br>               
          </blockquote>
            <span class="title">Rutas desde Cuenca de la cooperativa CITCA: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Azogues
            </blockquote>
            </v-flex> 
           </v-flex> 
        <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/cuencaexpress?name=Cuenca%20Express">
            <span class="headline font-weight-bold">Cuenca Express</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Cuenca Express</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072822329<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Company/Transportes-Ejecutivo-Cuenca-Express-136104303073640/">https://www.facebook.com/pages/category/Company/Transportes-Ejecutivo-Cuenca-Express-136104303073640/</a><br>                          
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Cuenca Express: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Machala</br>
              Cuenca - Huaquillas
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/emtrocc?name=EMTROCC">
            <span class="headline font-weight-bold">EMTROCC</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa EMTROCC</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/Cooperativa-Interprovincial-Emtrocc-SA-154736308647415/"> https://www.facebook.com/Cooperativa-Interprovincial-Emtrocc-SA-154736308647415/</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa EMTROCC: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Parque Nacional Cajas<br>
              Cuenca – Parque Nacional Cajas – Troncal
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>


        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/expresssigsig?name=Express%20Sigsig">
            <span class="headline font-weight-bold">Express Sigsig</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Express Sigsig</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos             
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Express Sigsig: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Gualaceo - Chordeleg - Sigsig<br>
              Cuenca – San Bartolo
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/expresssucre?name=Express%20Sucre">
            <span class="headline font-weight-bold">Express Sucre</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Express Sucre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span> 0728357172<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Express-Sucre-Internacional-286646154724182/">https://www.facebook.com/Express-Sucre-Internacional-286646154724182//</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>expressucre@hotmail.com 
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Express Sucre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Santo Domingo <br>
              Cuenca - Milagro<br>
              Cuenca – Quito Quitumbe
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
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/flota.cenepa/">https://www.facebook.com/flota.cenepa/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Flota Cenepa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Gualaquiza
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/flotaimbabura?name=Flota%20Imbabura">
            <span class="headline font-weight-bold">Flota Imbabura</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Flota Imbabura</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072565620 / 072236940<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://flota-imbabura.com/ ">https://flota-imbabura.com/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/flotaimbaburaEC/">https://www.facebook.com/flotaimbaburaEC/</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Flota Imbabura: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca- Quito Quitumbe<br>
              Cuenca- Quito Carcelén<br>
              Cuenca-Tulcán
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/giron?name=Girón">
            <span class="headline font-weight-bold">Girón</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Girón</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0998228260<br/>
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Girón: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Girón 
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/jahuay?name=Jahuay">
            <span class="headline font-weight-bold">Jahuay</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Jahuay</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07-2823265<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/pages/category/Tour-Agency/Cooperativa-de-transportes-Jahuay-Internacional-201478247093026/"> https://www.facebook.com/pages/category/Tour-Agency/Cooperativa-de-transportes-Jahuay-Internacional-201478247093026/</a><br> 
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Jahuay: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Azogues – Biblián – Cañar – El Tambo<br>
              Cuenca – Quito Quitumbe
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
              <span class="font-weight-bold">Teléfono: </span>072844688<br/>   
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>             
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Loja <br>
              Cuenca – Shushufindi<br>
              Cuenca – Lago Agrio
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
              <span class="font-weight-bold">Teléfono: </span>072869983<br/> 
              <span class="font-weight-bold">Página web: </span><a href="https://coopmacas.com">https://coopmacas.com</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/Coop.Macas/"> https://www.facebook.com/Coop.Macas/</a><br>             
              <span class="font-weight-bold">Correo electrónico: </span>coop-macas-ltda@hotmail.com
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Macas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Guarumales- Macas </br>
              Cuenca – Limón – Macas</br>
              Cuenca – Guarumales – Mendez - Macas – Puyo
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/nabon?name=Nabón">
            <span class="headline font-weight-bold">Nabón</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Nabón</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Nabón: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Nabón 
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/panamericana?name=Panamericana">
            <span class="headline font-weight-bold">Panamericana</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Panamericana</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2"> 
              <span class="font-weight-bold">Teléfono: </span>072869983<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.panamericana.ec/">https://www.panamericana.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/servciointernacional/">   https://www.facebook.com/servciointernacional/</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span> info@panamericana.ec
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Panamericana: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Quito terminal terrestre Quitumbe
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

       <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/panamericano?name=Panamericano">
            <span class="headline font-weight-bold">Panamericano</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Panamericano</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2"> 
              <span class="font-weight-bold">Teléfono: </span>0998228260<br/>
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Panamericano: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Solano - Deleg<br/>
              Cuenca – La Raya - Deleg
            </blockquote>
          </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/patria?name=Patria">
            <span class="headline font-weight-bold">Patria</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Patria</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2"> 
              <span class="font-weight-bold">Teléfono: </span>072 832 729  y  0980 215 507<br/>              
              <span class="font-weight-bold">Página web: </span><a href="www.cooperativapatria.com/">www.cooperativapatria.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-de-Transportes-Patria-111904680521246/?ref=br_rs">https://www.facebook.com/Cooperativa-de-Transportes-Patria-111904680521246/?ref=br_rs</a><br>           
           </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Patria: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Quito Quitumbe<br>
              Cuenca - Riobamba
            </blockquote>
          </v-flex> 
        <v-flex xs12 my-3><v-divider></v-divider></v-flex>

        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/pinas?name=Piñas">
            <span class="headline font-weight-bold">Piñas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Piñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07 284 3940<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.cooppinas.com/">http://www.cooppinas.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-Pi%C3%B1as-Interprovincial-1385791315030626/">https://www.facebook.com/Cooperativa-Pi%C3%B1as-Interprovincial-1385791315030626/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>info@cooppinas.com               
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Piñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Zaruma
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/pullmansucre?name=Pullman%20Sucre">
            <span class="headline font-weight-bold">Pullman Sucre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Pullman Sucre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>702822329 y 0979590983<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Compa%C3%B1ia-Pullman-Sucre-555166131249531/">https://www.facebook.com/Compa%C3%B1ia-Pullman-Sucre-555166131249531/</a><br>   
              <span class="font-weight-bold">Correo electrónico: </span>pullman.sucre@yahoo.esm
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Pullman Sucre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Máncora(Pe) - Piura(Pe)</br>
              Cuenca – Machala</br>
              Cuenca - Huaquillas
            </blockquote>
          </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/quezadaaguirre?name=Quezada%20Aguirre">
            <span class="headline font-weight-bold">Quezada Aguirre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Quezada Aguirre</span>
          </v-flex>    
          <v-flex xs12>
          <blockquote class="blockquote mx-0 px-0 mb-2">
            Sin datos
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Quezada Aguirre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Cochapata</br>
              Cuenca – Nabón</br>
              Cuenca – Morasloma</br>
              Cuenca – Tiopamba</br>
              Cuenca - Buravalle</br>
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/riopaute?name=Rio%20Paute">
            <span class="headline font-weight-bold">Rio Paute</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rio Paute</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07 2250260<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/coopriopaute/">  https://www.facebook.com/coopriopaute/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>coop_riopaute1606@hotmail.com
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Rio Paute: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Paute
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasorenses?name=Rutas%20Orenses">
            <span class="headline font-weight-bold">Rutas Orenses</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Orenses</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072936386<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/pages/category/Tour-Agency/Rutas-Orenses-316038951894074/">  https://www.facebook.com/pages/category/Tour-Agency/Rutas-Orenses-316038951894074/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Rutas Orenses: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca- Machala
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutaspucarenas?name=Rutas%20Pucareñas">
            <span class="headline font-weight-bold">Rutas Pucareñas</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Pucareñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0992950971<br/> 
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Rutas Pucareñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Tablón – Pucará<br/>
              Cuenca – Tendales – Pucará<br/>
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/sanfernando?name=San%20Fernando">
            <span class="headline font-weight-bold">San Fernando</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa San Fernando</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa San Fernando: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Girón - San Fernando (Laguna de Busa)
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/tacaandina?name=TACA%20Andina">
            <span class="headline font-weight-bold">San Luis</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa San Luis</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072823230<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/EjecutivoSanLuis/"> https://www.facebook.com/EjecutivoSanLuis/</a><br>
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa San Luis: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Loja
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santa?name=Santa">
            <span class="headline font-weight-bold">Santa</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santa</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072822442  0987080825<br/> 
              <span class="font-weight-bold">Página web: </span><a href="http://cooperativasanta.ec/ ">http://cooperativasanta.ec/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopsantaoficial/">https://www.facebook.com/coopsantaoficial/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>info@cooperativasanta.ec
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Santa : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Quito Quitumbe
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santaisabel?name=Santa%20Isabel">
            <span class="headline font-weight-bold">Santa Isabel</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santa Isabel</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>072839163<br/>
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desdeCuenca de la cooperativa Santa Isabel: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Santa Isabel<br/>
              Cuenca- San Rafael – Pucará<br/>
              Cuenca – Tablón – Pucará<br/>
              Cuenca – Ponce Enriquez<br/>
              Cuenca – Susudel<br/>
              Cuenca – Asunción<br/>
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santiagodegualaceo?name=Santiago%20de%20Gualaceo">
            <span class="headline font-weight-bold">Santiago de Gualaceo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santiago de Gualaceo </span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Santiago de Gualaceo : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Gualaceo<br>
              Cuenca – San Bartolo<br>
              Cuenca – Jadán
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
              <span class="font-weight-bold">Teléfono: </span>072838051<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativasucua.com/">https://cooperativasucua.com//</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coop.sucua?fref=search&__tn__=%2Cd%2CP-R&eid=ARDLeeou_tEaDI9dhIIiyMO1GmuM6NvxekgFSZHtx-NXRReTBP6bRQ0nFvaql6OOrWckTxFx659Da-vm">https://www.facebook.com/coop.sucua?fref=search&__tn__=%2Cd%2CP-R&eid=ARDLeeou_tEaDI9dhIIiyMO1GmuM6NvxekgFSZHtx-NXRReTBP6bRQ0nFvaql6OOrWckTxFx659Da-vm/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>coopsucua09@hotmail.com               
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Sucúa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Guarumales – Mendez – Sucúa – Macas<br>
              Cuenca – Limón – Macas
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/supersemeria?name=Super%20Semeria">
            <span class="headline font-weight-bold">Super Semeria</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Super Semeria</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07 284 2044<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Super-Semeria-846401625493079/">https://www.facebook.com/Super-Semeria-846401625493079//</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Super Semeria: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca- Máncora (Pe) – Piura (Pe) - Chiclayo (Pe)<br>
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>


        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/supertaxicuenca?name=Super%20Taxi%20Cuenca">
            <span class="headline font-weight-bold">Super Taxi Cuenca</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Super Taxi Cuenca</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07284-2629 - 0987314698<br/>
              <span class="font-weight-bold">Página web: </span><a href="www.supertaxiscuenca.com.ec">www.supertaxiscuenca.com.ec</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Super-Taxis-Cuenca-325689370862319/">https://www.facebook.com/Super-Taxis-Cuenca-325689370862319/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>info@supertaxiscuenca.com.ec               
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Super Taxi Cuenca: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Quito Quitumbe
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/supertaxicuenca?name=Super%20Taxi%20Cuenca">
            <span class="headline font-weight-bold">Tac</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Tac</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>07 2847434<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativatac.com/ ">https://cooperativatac.com/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/tacestac/">https://www.facebook.com/tacestac/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>info@cooperativatac.com               
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Tac: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Zaruma
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
              <span class="font-weight-bold">Teléfono: </span>072868008<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.transesmeraldas.com/">https://www.transesmeraldas.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/transesmeraldas/"> https://www.facebook.com/transesmeraldas/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Transesmeraldas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Esmeraldas - Atacames
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
            <span class="font-weight-bold">Teléfono: </span>072823269  y 072824005<br/>
              <span class="font-weight-bold">Página web: </span><a href="www.turismooriental.ec">www.turismooriental.ec</a><br>            
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/TurismoOriental/">https://www.facebook.com/TurismoOriental/</a><br>
               <span class="font-weight-bold">Correo electrónico: </span>turismoorientalgerencia@gmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa de transporte Turismo Oriental: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Guarumales – Mendez – Macas<br>
              Cuenca – Limón – Macas<br>
              Cuenca – Chigüinda – Gualaquiza<br>
              Cuenca – Quito terminal terrestre Quitumbe<br>
              Cuenca – Loja
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
            <span class="font-weight-bold">Teléfono: </span>099 645 6556 / (07) 283-5535<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.viajerosinternacional.com/">https://www.viajerosinternacional.com/</a><br>            
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-Viajeros-417415642166516/">https://www.facebook.com/Cooperativa-Viajeros-417415642166516/</a><br>
               <span class="font-weight-bold">Correo electrónico: </span>reservas@viajerosinternacional.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa de transporte Viajeros Internacional: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca – Loja – Zamora - Yantzaza<br>
              Cuenca – Loja<br>
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/zhina?name=Zhiña">
            <span class="headline font-weight-bold">Zhiña</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Zhiña</span>
          </v-flex>    
          <v-flex xs12>
           <blockquote class="blockquote mx-0 px-0 mb-2">
            Sin datos
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Cuenca de la cooperativa Zhiña: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Cuenca - Zhiña
            </blockquote>
            </v-flex> 
          <v-flex xs12>
            </blockquote>
          </v-flex>                                


          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre de Cuenca</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de Cuenca podrás encontrar:
            </v-flex>
            <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Servicios de transporte</span>
          </v-flex>
          <v-flex xs12 class="blockquote">
              <ul>
                <li>Viajes interparroquiales</li>
                <li>Viajes intercantonales</li>
                <li>Viajes interprovinciales</li>
                <li>Viajes internacionales</li>
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
                <li>Farmacia</li>
                <li>Cajeros automáticos</li>
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
