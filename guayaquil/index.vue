<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre de Guayaquil</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal de Guayaquil? Buscarfly les presenta un listado completo de los destinos y frecuencias de las diferentes cooperativas de transporte que prestan sus servicios en el Terminal Terrestre de Guayaquil.<br/>
              En el terminal terrestre de Guayaquil, en la actualidad, existen 82 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de Guayaquil a Quito o de Guayaquil a Montañita. Pero también se puede tomar un bus internacional para ir de Guayaquil a Máncora o de Guayaquil a Lima, en Perú. 
            </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->                 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal de Guayaquil</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Datos de contacto del terminal de Guayaquil</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Página web: </span><a href="http://ttg.ec/">http://ttg.ec/</a><br>
              <span class="font-weight-bold">twitter: </span><a href="https://twitter.com/terminalgye?lang=fr">https://twitter.com/terminalgye?lang=fr</a><br>
              </blockquote>
          </v-flex> 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Guayaquil?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El terminal Guayaquil, estando lejos del centro histórico, no es recomendado ir a pie, pero se puede llegar con facilidad en transporte público, tal como en bus urbano con las lineas : TRONCAL 1: Terminal Guasmo- Río Daule y TRONCAL 2: Río Daule - 25 De Julio; el pasaje de bus urbano tiene un costo de 0,30$.<br/>
              También se puede llegar en carro, que sea particular o en taxi.
              </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal Guayaquil</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal Guayaquil, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
            </blockquote>
          </v-flex>  
                   <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/16dejunio?name=16%20de%20Junio">
            <span class="headline font-weight-bold">16 de Junio</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa 16 de Junio</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2-750-120 / 2-130-237<br/>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte 16 de Junio: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Tenguel </br>
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

                    <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/17deseptiembre?name=17%20de%20Septiembre">
            <span class="headline font-weight-bold">17 de Septiembre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa 17 de Septiembre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin información
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte 17 de Septiembre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Milagro<br>
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/24deseptiembre?name=24%20de%20Septiembre">
            <span class="headline font-weight-bold">24 de Septiembre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa 24 de Septiembre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0992137902<br/>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte 24 de Septiembre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Paján </br>
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/7denoviembre?name=7%20de%20Noviembre">
            <span class="headline font-weight-bold">7 de Noviembre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa 7 de Noviembre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0969496056<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transporte-Interprovincial-7-de-Noviembre-142036596429808/">https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transporte-Interprovincial-7-de-Noviembre-142036596429808/</a><br> 
               <span class="font-weight-bold">Correo electrónico: </span>cooperativa7noviembre@hotmail.com              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte 7 de Noviembre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Paján </br>
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>


          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/aerotaxi?name=Aerotaxi">
            <span class="headline font-weight-bold">Aerotaxi</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Aerotaxi</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130067<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://transportesaerotaxi.com/index.php">http://transportesaerotaxi.com/index.php</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativa.transportes.aerotaxi/">https://www.facebook.com/cooperativa.transportes.aerotaxi/</a><br>      
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Aerotaxi: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Santo Domingo – Esmeraldas</br>
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
              <span class="font-weight-bold">Teléfono: </span>4 2130 157<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.ctaalausi.com/">http://www.ctaalausi.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/interprovincial.alausicta">https://www.facebook.com/interprovincial.alausicta</a><br>      
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Alausí: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Alausí </br>
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
              <span class="font-weight-bold">Teléfono: </span>2130015<br/>     
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Alianza: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            Guayaquil – Parque Nacional el Cajas – Cuenca</br>
            Guayaquil – La Troncal – Azogues - Cuenca
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

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
              <span class="font-weight-bold">Teléfono: </span>2130265<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.cooperativabanos.com.ec">http://www.cooperativabanos.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativadetransportesbanos">https://www.facebook.com/cooperativadetransportesbanos/</a><br> 
               <span class="font-weight-bold">Correo electrónico: </span>info@cooperativabanos.com.ec
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Baños: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Ambato - Baños<br>
              Guayaquil - Baños<br>
              Guayaquil - Baños – Tena<br>
              Guayaquil - Lago Agrio – Shushufindi<br>
              Guayaquil - Loreto - Coca
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/caluma?name=Caluma">
            <span class="headline font-weight-bold">Caluma</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Caluma</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130639<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/Cooperativa-De-Transportes-Interprovincial-De-Pasajeros-Caluma-501222859934591/"> https://www.facebook.com/Cooperativa-De-Transportes-Interprovincial-De-Pasajeros-Caluma-501222859934591/</a><br> 
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Caluma: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Caluma<br>
              Guayaquil - Guaranda<br>
              Guayaquil - Naves
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
              <span class="font-weight-bold">Teléfono: </span>0989296204<br/>
              <span class="font-weight-bold">Facebook:</span><a href="https://www.facebook.com/Transportes-de-Pasajeros-y-Encomiendas-Carlos-Alberto-Aray-101399428292118/">https://www.facebook.com/Transportes-de-Pasajeros-y-Encomiendas-Carlos-Alberto-Aray-101399428292118/</a><br>          
          </blockquote>
           </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Carlos Alberto Aray: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            Guayaquil - Chone<br>
            Guayaquil - Manta
            </blockquote>
          </v-flex>  
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/centineladelsur?name=Centinela%20del%20Sur">
            <span class="headline font-weight-bold">Centinela del Sur</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Centinela del Sur</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>7041859<br/>     
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativacentineladelsur/">https://www.facebook.com/cooperativacentineladelsur/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Centinela del Sur: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Tenguel
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/chunchi?name=Chunchi">
            <span class="headline font-weight-bold">Chunchi</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Chunchi</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>86787068/2130315<br/>     
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transporte-Chunchi-1462402990465880/">https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transporte-Chunchi-1462402990465880/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>transportechunchi@yahoo.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Chunchi: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Chunchi
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/cifa?name=CIFA">
            <span class="headline font-weight-bold">CIFA</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa CIFA</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130379<br/>  
              <span class="font-weight-bold">Página web: </span><a href="http://www.cifainternacional.com/">http://www.cifainternacional.com/</a><br>   
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopcifainternacional/">https://www.facebook.com/coopcifainternacional/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte CIFA: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Huaquillas<br/>
              Guayaquil – Machala<br/>
              Guayaquil – Santa Rosa<br/>
              Guayaquil – Máncora (Pe) - Piura (Pe)
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/citaexpress?name=CITA%20Express">
            <span class="headline font-weight-bold">CITA Express</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa CITA Express</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130668<br/>  
              <span class="font-weight-bold">Página web: </span><a href="http://transportescita.com/">http://transportescita.com/</a><br>   
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cita-Express-Internacional-1257980104215997/">https://www.facebook.com/Cita-Express-Internacional-1257980104215997/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte CITA Express: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Ambato
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/citim?name=CITIM">
            <span class="headline font-weight-bold">CITIM</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa CITIM</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130516<br/>  
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-CITIM-1843897242506069/"> https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-CITIM-1843897242506069/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte CITIM: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Naranjito
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>            

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/civa?name=CIVA">
            <span class="headline font-weight-bold">CIVA</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa CIVA</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0997367059<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.civa.com.pe/">https://www.civa.com.pe/</a><br>  
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/turismociva/"> https://www.facebook.com/turismociva/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>callcenter@turismociva.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte CIVA: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Máncora (Pe) - Piura (Pe)
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/coactur?name=COACTUR">
            <span class="headline font-weight-bold">COACTUR</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa COACTUR</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130078<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/cooperativacoactur.manabi/">  https://www.facebook.com/cooperativacoactur.manabi/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>coactur@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte COACTUR: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Jipijapa – Portoviejo – Bahía de Caráquez<br>
              Guayaquil – Jipijapa – Manta<br>
              Guayaquil – Jipijapa – Portoviejo – Tosagua – San Vicente – Pedernales<br>
              Guayaquil – Jipijapa – Portoviejo – San Vicente – Jama – Pedernales<br>
              Guayaquil – Jipijapa – Portoviejo
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/colta?name=COLTA">
            <span class="headline font-weight-bold">COLTA</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa COLTA</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130078<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/TRANSPORTECOLTA/">https://www.facebook.com/TRANSPORTECOLTA/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte COLTA: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Cajabamba <br>
              Guayaquil – Riobamba
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/costaazul?name=Costa%20azul">
            <span class="headline font-weight-bold">Costa azul</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Costa azul</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130175<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.cica-ec.com/">https://www.cica-ec.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cicacostaazul/">https://www.facebook.com/cicacostaazul/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Costa azul: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Santa Elena
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/cruzdelsur?name=Cruz%20del%20Sur">
            <span class="headline font-weight-bold">Cruz del Sur</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Cruz del Sur</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>00-593-4-2130179<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.cruzdelsur.com.pe/">http://www.cruzdelsur.com.pe/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cruzdelsurpe/">https://www.facebook.com/cruzdelsurpe/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Cruz del Sur: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Máncora (Pe) - Trujillo (Pe) - Lima (Pe) (martes, viernes, domingo)
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

            <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/ecuadorejecutivo?name=Ecuador%20Ejecutivo">
            <span class="headline font-weight-bold">Ecuador Ejecutivo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Ecuador Ejecutivo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130830<br/>
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Ecuador Ejecutivo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Riobamba
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/ecuatorianopullman?name=Ecuatoriano%20Pullman">
            <span class="headline font-weight-bold">Ecuatoriano Pullman</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Ecuatoriano Pullman</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130830<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.ecuatorianopullman.com/">http://www.ecuatorianopullman.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/ecuatoriano.pullman">https://www.facebook.com/ecuatoriano.pullman</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Ecuatoriano Pullman: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Huaquillas<br>
              Guayaquil - Machala<br>
              Guayaquil - Pasaje
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/eldorado?name=El%20Dorado">
            <span class="headline font-weight-bold">El Dorado</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa El Dorado</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>094975386<br/>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/CooperativaDeTransportesElDorado/">https://www.facebook.com/CooperativaDeTransportesElDorado/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte El Dorado: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Ambato<br>
              Guayaquil - Chillanes
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/expresomilagro?name=Expreso%20Milagro">
            <span class="headline font-weight-bold">Expreso Milagro</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Expreso Milagro</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130869<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/expreso.milagro/">https://www.facebook.com/expreso.milagro/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Expreso Milagro: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Milagro
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>            

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/expressatenas?name=Express%20Atenas">
            <span class="headline font-weight-bold">Express Atenas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Express Atenas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130869<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Transportes-Express-Atenas-113109930405553/">https://www.facebook.com/Transportes-Express-Atenas-113109930405553/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Express Atenas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Chillanes<br>
              Guayaquil - Guaranda<br>
              Guayaquil - San José del Tambo
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/fbiflotababahoyo?name=FBI%20Flota%20Babahoyo">
            <span class="headline font-weight-bold">FBI Flota Babahoyo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa FBI Flota Babahoyo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130595<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.cooperativa-fbi.com/">https://www.cooperativa-fbi.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/flotababahoyoi/?__tn__=%2Cd%2CP-R&eid=ARD27g1YlUfN-ax6ZLYRhfMwmZlhvswM47lBKTdLtcDGRmxy4Fk8SEJ55S8BMCRZmKgvyTAMiP2AvoEi">https://www.facebook.com/flotababahoyoi/?__tn__=%2Cd%2CP-R&eid=ARD27g1YlUfN-ax6ZLYRhfMwmZlhvswM47lBKTdLtcDGRmxy4Fk8SEJ55S8BMCRZmKgvyTAMiP2AvoEi</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte FBI Flota Babahoyo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Babahoyo<br>
              Guayaquil- Babahoyo - Baba
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/fifa?name=FIFA">
            <span class="headline font-weight-bold">FIFA</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa FIFA</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130614<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.cooperativa-fbi.com/">https://www.cooperativa-fbi.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/FIFAPIONERAENVINCES/">https://www.facebook.com/FIFAPIONERAENVINCES/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte FIFA: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Palenque<br>
              Guayaquil - Vinces
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/flordelosrios?name=Flor%20de%20los%20Rios">
            <span class="headline font-weight-bold">Flor de los Rios</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Flor de los Rios</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0969625199<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coop.flordelosrios.5">https://www.facebook.com/coop.flordelosrios.5</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Flor de los Rios: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Mocache
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

                      <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/flotabolivar?name=Flota%20Bolivar">
            <span class="headline font-weight-bold">Flota Bolivar</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Flota Bolivar</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130627<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/FlotaBolivarEc/">https://www.facebook.com/FlotaBolivarEc/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>flotabolivar@hotmail.es
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Flota Bolivar: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil – Guaranda
              Guayaquil - San Luis del Pambil
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
              <span class="font-weight-bold">Teléfono: </span>2130649<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://flota-imbabura.com/ ">https://flota-imbabura.com/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/flotaimbaburaEC/">https://www.facebook.com/flotaimbaburaEC/</a><br>     
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Flota Imbabura: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Quito Quitumbe
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
              <span class="font-weight-bold">Teléfono: </span>2130189<br>
              <span class="font-weight-bold">Página web: </span><a href="http://www.flotapelileo.com.ec/">http://www.flotapelileo.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/pages/category/Transportation-Service/FLOTA-PELILEO-03-189393681657647/"> https://es-la.facebook.com/pages/category/Transportation-Service/FLOTA-PELILEO-03-189393681657647/</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Flota Pelileo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Ambato</br>
              Guayaquil - Tena
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/jipijapa?name=Jipijapa">
            <span class="headline font-weight-bold">Jipijapa</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Jipijapa</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130540<br>           
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Jipijapa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Jipijapa</br>
              Guayaquil - Jipijapa - Puerto Lopez
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/kennedy?name=Kennedy">
            <span class="headline font-weight-bold">Kennedy</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Kennedy</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>7041823 - 090153138<br/>
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Kennedy: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Los Bancos <br>
              Guayaquil- Pedernales <br>
              Guayaquil - Quinindé<br>
              Guayaquil - Santo Domingo
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/lamana?name=La%20Maná">
            <span class="headline font-weight-bold">La Maná</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa La Maná</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130405<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.transportelamana.com/">http://www.transportelamana.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-de-Transportes-Interprovincial-La-Mana-107574114112168/">https://www.facebook.com/Cooperativa-de-Transportes-Interprovincial-La-Mana-107574114112168/</a><br> 
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa La Maná: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - El Corazón <br>
              Guayaquil - Quevedo
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

                   <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/latroncalena?name=La%20Troncaleña">
            <span class="headline font-weight-bold">La Troncaleña</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa La Troncaleña</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130046<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-de-Transporte-Interprovincial-Troncale%C3%B1a-259470851503283/">https://www.facebook.com/Cooperativa-de-Transporte-Interprovincial-Troncale%C3%B1a-259470851503283/</a><br> 
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa La Troncaleña: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - La Troncal
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/liberpesa?name=Liberpesa">
            <span class="headline font-weight-bold">Liberpesa</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Liberpesa</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130175<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.liberpesa.com.ec/">http://www.liberpesa.com.ec/</a><br> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/LiberpesaOficial/">https://www.facebook.com/LiberpesaOficial/</a><br> 
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Liberpesa: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Salinas
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/libertadpeninsular?name=Libertad%20Peninsular">
            <span class="headline font-weight-bold">Libertad Peninsular</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Libertad Peninsular</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130175<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://clp.com.ec/">https://clp.com.ec/</a><br> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/clpcooperativa/?eid=ARDgxd5BFG2sMvVYiOIitOtt5VNnhJ93sVDI1riJkwXcfIoA3Bs88PztH-WwhYz52_73gYcSYOQD6irS">https://www.facebook.com/clpcooperativa/?eid=ARDgxd5BFG2sMvVYiOIitOtt5VNnhJ93sVDI1riJkwXcfIoA3Bs88PztH-WwhYz52_73gYcSYOQD6irS</a><br> 
            </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Libertad Peninsular: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Montañita - Olón<br>
              Guayaquil - Salinas
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
              <span class="font-weight-bold">Teléfono: </span>2130311<br/>              
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>                           
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Cariamanga</br>
              Guayaquil - Lago Agrio</br>
              Guayaquil - Loja </br>
              Guayaquil - Mácara </br>
              Guayaquil - Shushusfindi </br>
              Guayaquil - Yantzaza </br>
              Guayaquil - Zapotillo
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
              <span class="font-weight-bold">Teléfono: </span>2130413<br/> 
              <span class="font-weight-bold">Página web: </span><a href="https://coopmacas.com">https://coopmacas.com</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/Coop.Macas/"> https://www.facebook.com/Coop.Macas/</a><br>             
              <span class="font-weight-bold">Correo electrónico: </span>coop-macas-ltda@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Macas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Macas </br>
              Guayaquil - Macas - Sucúa
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/marcelinomariduena?name=Marcelino%20Maridueña">
            <span class="headline font-weight-bold">Marcelino Maridueña</span>
          </router-link>
         </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Marcelino Maridueña</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130609<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-de-Transporte-de-Pasajeros-Marcelino-Maridue%C3%B1a-392197881387177/"> https://www.facebook.com/Cooperativa-de-Transporte-de-Pasajeros-Marcelino-Maridue%C3%B1a-392197881387177/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Marcelino Maridueña: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Marcelino Maridueña </br>
              Guayaquil - Milagro
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/mariscalsucre?name=Mariscal%20Sucre">
            <span class="headline font-weight-bold">Mariscal Sucre</span>
          </router-link>
         </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Mariscal Sucre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/mariscal.sucre.39/"> https://www.facebook.com/mariscal.sucre.39/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Mariscal Sucre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Durán - Milagro - Mariscal Sucre - Simón Bolívar - Recinto Matecacao
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/mipiedacita?name=Mi%20Piedacita">
            <span class="headline font-weight-bold">Mi Piedacita</span>
          </router-link>
         </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Mi Piedacita</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2704684<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Coop-Mi-Piedacita-104032357899396/">https://www.facebook.com/Coop-Mi-Piedacita-104032357899396/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Mi Piedacita: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Pedro Carbo
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
              <span class="font-weight-bold">Teléfono: </span>2130182<br/>
              <span class="font-weight-bold">Página web: </span><a href=" http://www.cooperativanambija.com.ec/"> http://www.cooperativanambija.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopnambija">https://www.facebook.com/coopnambija</a><br>             
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Nambija: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Loja - Zamora - Chinapintza<br> 
              Guayaquil - Loja - Zamora - El Pangui
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/nucallacta?name=Ñuca%20Llacta">
            <span class="headline font-weight-bold">Ñuca Llacta</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Ñuca Llacta</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">  
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/nucallactaoficial/">https://www.facebook.com/nucallactaoficial/</a><br>              
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Ñuca Llacta: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Cajabamba
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/occidentales?name=Occidentales">
            <span class="headline font-weight-bold">Occidentales</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Occidentales</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130618<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://occidentales.ec/">http://occidentales.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/transportes.occidentales/"> https://www.facebook.com/transportes.occidentales/</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span>info@ocidentales.ec
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Occidentales: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Esmeraldas<br>
              Guayaquil - Lago Agrio<br>
              Guayaquil - Los Bancos<br>
              Guayaquil - Muisne<br>
              Guayaquil - Quinindé<br>
              Guayaquil - San Lorenzo
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
              <span class="font-weight-bold">Teléfono: </span>2130210<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.panamericana.ec/">https://www.panamericana.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/servciointernacional/">   https://www.facebook.com/servciointernacional/</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span> info@panamericana.ec
            </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Panamericana: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Esmeraldas<br>
              Guayaquil - Loja<br>
              Guayaquil – Quito terminal terrestre Quitumbe
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
              <span class="font-weight-bold">Teléfono: </span>2130315<br/>              
              <span class="font-weight-bold">Página web: </span><a href="www.cooperativapatria.com/">www.cooperativapatria.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-de-Transportes-Patria-111904680521246/?ref=br_rs">https://www.facebook.com/Cooperativa-de-Transportes-Patria-111904680521246/?ref=br_rs</a><br>           
           </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Patria: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Riobamba
            </blockquote>
          </v-flex> 
        <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/pedrocarbo?name=Pedro%20Carbo">
            <span class="headline font-weight-bold">Pedro Carbo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Pedro Carbo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2"> 
              <span class="font-weight-bold">Teléfono: </span>2704586<br/>              
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/COOPERATIVA-DE-TRANSPORTES-PEDRO-CARBO-236974169672648/">https://www.facebook.com/COOPERATIVA-DE-TRANSPORTES-PEDRO-CARBO-236974169672648/</a><br>           
           </blockquote>
          </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Pedro Carbo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Pedro Carbo
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
            <span class="title">Rutas desde Guayaquil de la cooperativa Piñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Zaruma
            </blockquote>
            </v-flex> 
           <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/posorja?name=Posorja">
            <span class="headline font-weight-bold">Posorja</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Posorja</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130284<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Coop-Transporte-Posorja-1086265454737636/">https://www.facebook.com/Coop-Transporte-Posorja-1086265454737636/</a><br>       
              <span class="font-weight-bold">Correo electrónico: </span>ctransporteposorja@hotmail.com 
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Posorja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Posorja
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
              <span class="font-weight-bold">Teléfono: </span>2130121<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-Putumayo-481755651878556/">https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transportes-Putumayo-481755651878556//</a><br>             
              <span class="font-weight-bold">Correo electrónico: </span>coop.putumayo@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Putumayo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Lago Agrio - El Coca
            </blockquote>
            </v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/reinadelcamino?name=Reina%20del%20Camino">
            <span class="headline font-weight-bold">Reina del Camino</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Reina del Camino</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130757<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://reinadelcamino.ec/">https://reinadelcamino.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/ReinadelCaminoOficial/"> https://www.facebook.com/ReinadelCaminoOficial/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Reina del Camino: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Bahía de Caráquez<br>
              Guayaquil - Calceta<br>
              Guayaquil - Chone<br>
              Guayaquil - Flavio Alfaro<br>
              Guayaquil - Manta<br>
              Guayaquil - Pedernales<br>
              Guayaquil - Portoviejo<br>
              Guayaquil - San Vicente<br>
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/riobamba?name=Riobamba">
            <span class="headline font-weight-bold">Riobamba</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Riobamba</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/TransportesRiobamba/"> https://www.facebook.com/TransportesRiobamba/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>transportesriobamba62@gmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Riobamba: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Baños<br>
              Guayaquil - Macas<br>
              Guayaquil - Riobamba
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rircay?name=Rircay">
            <span class="headline font-weight-bold">Rircay</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rircay</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130519<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.rircay.net/">http://www.rircay.net/</a><br>              
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooprircay/">https://www.facebook.com/Cooprircay/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rircay: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - La Troncal
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasbalzarenas?name=Rutas%20Balzareñas">
            <span class="headline font-weight-bold">Rutas Balzareñas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Balzareñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130136<br/>           
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Rutas-Balzare%C3%B1as-219309261424626/">https://www.facebook.com/Rutas-Balzare%C3%B1as-219309261424626/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Balzareñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Balzar
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>  


          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasempalmenas?name=Rutas%20Empalmeñas">
            <span class="headline font-weight-bold">Rutas Empalmeñas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Empalmeñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130635<br/>           
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Rutas-Empalme%C3%B1as-119836742755759/">https://www.facebook.com/Rutas-Empalme%C3%B1as-119836742755759/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Empalmeñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - El Empalme
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>    

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasmilagrenas?name=Rutas%20Milagreñas">
            <span class="headline font-weight-bold">Rutas Milagreñas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Milagreñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Milagreñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Milagro
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>    

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasempalmenas?name=Rutas%20Empalmeñas">
            <span class="headline font-weight-bold">Rutas Orenses</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Orenses</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130657<br/>           
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/SomosRutasOrenses/">https://www.facebook.com/SomosRutasOrenses/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Orenses: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Huaquillas<br>
              Guayaquil - Machala<br>
              Guayaquil - Pasaje<br>
              Guayaquil - Santa Rosa
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

                    <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasportovejenses?name=Rutas%20Portovejenses">
            <span class="headline font-weight-bold">Rutas Portovejenses</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Portovejenses</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130799<br/>           
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooprutasportovejenses/">https://www.facebook.com/cooprutasportovejenses/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Portovejenses: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Manta<br>
              Guayaquil - Portoviejo
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

            <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutassalitrenas?name=Rutas%20Salitreñas">
            <span class="headline font-weight-bold">Rutas Salitreñas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Salitreñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2792381<br/>           
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/rutas.salitrenas/timeline?lst=100001081038509%3A100007109316767%3A1597961825">https://www.facebook.com/rutas.salitrenas/timeline?lst=100001081038509%3A100007109316767%3A1597961825</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Salitreñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Junquillal<br>
              Guayaquil - Salitre<br>
              Guayaquil - Vinces 
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

            <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/rutasvincenas?name=Rutas%20Vinceñas">
            <span class="headline font-weight-bold">Rutas Vinceñas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Rutas Vinceñas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130436<br/>           
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/rutas.salitrenas/timeline?lst=100001081038509%3A100007109316767%3A1597961825">https://www.facebook.com/rutas.salitrenas/timeline?lst=100001081038509%3A100007109316767%3A1597961825</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Rutas Vinceñas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Vernaza<br>
              Guayaquil - Vinces 
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/salitre?name=Salitre">
            <span class="headline font-weight-bold">Salitre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Salitre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130754<br/>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Salitre: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Baba<br/>
              Guayaquil - Junquillal<br/>
              Guayaquil - Salitre<br>
              Guayaquil - Vinces 
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

         <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/san?name=S.%20A.%20N.">
            <span class="headline font-weight-bold">S. A. N.</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa S. A. N.</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130872<br/>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte S. A. N.: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Naranjal 
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/sancristobal?name=San%20Cristobal">
            <span class="headline font-weight-bold">San Cristobal</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa San Cristobal</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130734<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://microsancristobal.com/">http://microsancristobal.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/sancristobal.tulcan/"> https://www.facebook.com/sancristobal.tulcan/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>microsc71@gmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte San Cristobal: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Quito<br>
              Guayaquil - Tulcán
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/sanpedrito?name=San%20Pedrito">
            <span class="headline font-weight-bold">San Pedrito</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa San Pedrito</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CooperativaSanPedrito/">https://www.facebook.com/CooperativaSanPedrito/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte San Pedrito: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Guaranda - Guanujo
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
              <span class="font-weight-bold">Teléfono: </span>2130507<br/> 
              <span class="font-weight-bold">Página web: </span><a href="http://cooperativasanta.ec/ ">http://cooperativasanta.ec/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/coopsantaoficial/">https://www.facebook.com/coopsantaoficial/</a><br>
              <span class="font-weight-bold">Correo electrónico: </span>info@cooperativasanta.ec
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Santa : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Ambato<br/>
              Guayaquil - Latacunga<br/>
              Guayaquil – Quito Quitumbe
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santaana?name=Santa%20Ana">
            <span class="headline font-weight-bold">Santa Ana</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santa Ana</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Santa Ana : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Salitre<br/>
              Guayaquil - Samboróndon
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santalucia?name=Santa%20Lucia">
            <span class="headline font-weight-bold">Santa Lucia</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santa Lucia</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130569<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CooperativadetransporteSantaLucia/">https://www.facebook.com/CooperativadetransporteSantaLucia/</a><br>
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Santa Lucia : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Laurel<br/>
              Guayaquil - Santa Lucía
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santamartha?name=Santa%20Martha">
            <span class="headline font-weight-bold">Santa Martha</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santa Martha</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130858<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopFlotaSantaMartha/">https://www.facebook.com/CoopFlotaSantaMartha/</a><br>
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Santa Martha : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Bucay<br/>
              Guayaquil - El Triunfo
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/santarosadecolimes?name=Santa%20Rosa%20De%20Colimes">
            <span class="headline font-weight-bold">Santa Rosa De Colimes</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Santa Rosa De Colimes</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130328<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-Interprovincial-Santa-Rosa-de-Colimes-100282624895535/">https://www.facebook.com/Cooperativa-Interprovincial-Santa-Rosa-de-Colimes-100282624895535/</a><br>
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Santa Rosa De Colimes : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Colimes
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/senordelosmilagros?name=Señor%20de%20los%20Milagros">
            <span class="headline font-weight-bold">Señor los Milagros</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Señor de los Milagros</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130863<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-Interprovincial-Santa-Rosa-de-Colimes-100282624895535/">https://www.facebook.com/Cooperativa-Interprovincial-Santa-Rosa-de-Colimes-100282624895535/</a><br>
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Señor de los Milagros : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Daule<br>
              Guayaquil - Limonal
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/sucre?name=Sucre">
            <span class="headline font-weight-bold">Sucre</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Sucre</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130672<br/> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Cooperativa-de-Transporte-Sucre-267171656654124/">https://www.facebook.com/Cooperativa-de-Transporte-Sucre-267171656654124/</a><br>
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa Sucre : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Pinchincha<br>
              Guayaquil - Quevedo<br>
              Guayaquil - Santo Domingo
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/tac?name=TAC">
            <span class="headline font-weight-bold">TAC</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa TAC</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130236<br/> 
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativatac.com/ ">https://cooperativatac.com/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/tacestac/">https://www.facebook.com/tacestac/</a><br>  
              <span class="font-weight-bold">Correo electrónico: </span>info@cooperativatac.com  
              </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa TAC : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Marcabelli<br>
              Guayaquil - Zaruma
            </blockquote>
            </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/tia?name=T.%20I.%20A.">
            <span class="headline font-weight-bold">T. I. A.</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa T. I. A.</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130596<br/>
              </blockquote> 
          </v-flex> 
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa T. I. A. : </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Quevedo<br>
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
              <span class="font-weight-bold">Teléfono: </span>2130174<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.tourisanfrancisco.com/">https://www.tourisanfrancisco.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://es-la.facebook.com/tourisanfrancisco/"> https://es-la.facebook.com/tourisanfrancisco/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Touris San Francisco: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
             Guayaquil - Baños - Puyo<br>
             Guayaquil - Puyo
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
              <span class="font-weight-bold">Teléfono: </span>2130642<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.transesmeraldas.com/">https://www.transesmeraldas.com/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/transesmeraldas/"> https://www.facebook.com/transesmeraldas/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Transesmeraldas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Atacames - Muisne <br>
              Guayaquil - Borbón<br>
              Guayaquil - Esmeraldas<br>
              Guayaquil - San Lorenzo
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/transportesecuador?name=Transportes%20Ecuador">
            <span class="headline font-weight-bold">Transportes Ecuador</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Transportes Ecuador</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130040<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://transportesecuador.com.ec/">https://transportesecuador.com.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/TransportesEcuadorOficial/">https://www.facebook.com/TransportesEcuadorOficial/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Transportes Ecuador: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Quito Quitumbe
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/trasandinaexpress?name=Trasandina%20Express">
            <span class="headline font-weight-bold">TrasAndina Express</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa TrasAndina Express</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130060<br/>
              <span class="font-weight-bold">Página web: </span><a href="http://www.trasandinaexpress.com.ec/index.php/">http://www.trasandinaexpress.com.ec/index.php/ </a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/Trasandina-express-01-1537235243229985/">https://www.facebook.com/Trasandina-express-01-1537235243229985/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte TrasAndina Express: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Ambato
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

           <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/valencia?name=Valencia">
            <span class="headline font-weight-bold">Valencia</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Valencia</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130893<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pg/Cooperativa-de-Transporte-Valencia-111284053957650/about/?ref=page_internal">https://www.facebook.com/pg/Cooperativa-de-Transporte-Valencia-111284053957650/about/?ref=page_internal</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Valencia: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - El Vergel<br/>
              Guayaquil - Mocache<br/>
              Guayaquil - Quevedo
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/ventanas?name=Ventanas">
            <span class="headline font-weight-bold">Ventanas</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Ventanas</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130613<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/COOPERATIVA-DE-TRANSPORTES-VENTANAS-413266485444019/">https://www.facebook.com/COOPERATIVA-DE-TRANSPORTES-VENTANAS-413266485444019/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Ventanas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Echeandía<br/>
              Guayaquil - Ventanas
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/villamil?name=Villamil">
            <span class="headline font-weight-bold">Villamil</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Villamil</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>2130879<br/>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativavillamil/">https://www.facebook.com/cooperativavillamil/</a><br>
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Villamil: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - Playas
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
            <span class="title">Rutas desde Guayaquil de la cooperativa de transporte Zaracay: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Guayaquil - El Coca <br/>
              Guayaquil - Pedernales <br/>
              Guayaquil - Quito<br/>
              Quevedo - Santo Domingo
            </blockquote>
            </v-flex> 
          <v-flex xs12>
            </blockquote>
          </v-flex>                                
          <v-flex xs12 my-3><v-divider></v-divider></v-flex>

          <v-flex text-xs-center xs12 class="text-left">
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre de Guayaquil</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de Guayaquil podrás encontrar:
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
                <li>Oficina turística</li>
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
