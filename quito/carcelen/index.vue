<template>
  <div>
    <app_menu color="#431195"></app_menu>
    <div>
      <v-container fill-height style="max-width: 850px !important">
        <v-layout row wrap justify-center class="container-lg">
          <v-flex text-xs-center xs12 mt-5 class="text-center">
            <span class="display-2 secondary--text font-weight-bold">Terminal terrestre de Quito Carcelén</span>
          </v-flex>
          <v-flex xs12 m12 mt-5>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              ¿Necesitas saber el horario completo de salida de los buses del Terminal Terrestre Quito Carcelén? Buscarfly, les presenta un listado completo de los destinos y frecuencias de las diferentes Cooperativas de Transporte que prestan sus servicios en el Terminal Terrestre Quito Carcelén.<br/>
              En el terminal terrestre de Quito Carcelén, en la actualidad, existen 93 cooperativas de transporte. Desde el terminal se puede tomar buses interparroquiales o interprovinciales y así, ir de Quito a Guayaquil, de Quito a Loja o de Quito a Otavalo.  
            </blockquote>
          </v-flex>   
<!--            <v-flex xs12 md6 pl-4>
              <img width="100%" src="~/static/img/terminal-terrestre/terminal-terrestre-lago-agrio.jpg" style="border-radius: 50%"></img>
           </v-flex> -->                 
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Ubicación del terminal de Quito Carcelén</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              MAPA
            </blockquote>
          </v-flex>  
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">¿Cómo llegar al terminal terrestre de Quito Carcelén?</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              El terminal Quitumbe, estando lejos del centro histórico, no es recomendado ir a pie, pero se puede llegar con facilidad en transporte público, tal como en bus urbano con las lineas : T. Carcelén - T. Norte, T. La Ofelia - Terminal Carcelén, T. Río Coca  -  Eloy Alfaro - Carapungo o en metro.<br/>
              También se puede llegar en carro, que sea particular o en taxi. 
            </blockquote>
          </v-flex>       
          <v-flex text-xs-center xs12  class="text-left" mt-5>
            <span class="headline font-weight-bold">Destinos, frecuencias, y datos de las cooperativas de transporte del terminal Quito Carcelén</span>
          </v-flex>  
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              A continuación, le presentaremos todas las cooperativas de transporte del terminal Quito Carcelén, así que sus destinos y frecuencias (haga clic sobre la cooperativa para que aparezca sus horarios/turnos de salida de buses).
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
              <span class="font-weight-bold">Teléfono: </span>03 392 - 0215 ext. 3101<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="http://transportesaerotaxi.com/index.php/">http://transportesaerotaxi.com/index.php/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/cooperativa.transportes.aerotaxi/"> https://www.facebook.com/cooperativa.transportes.aerotaxi/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>coop.transporte.aerotaxi@gmail.com
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Aerotaxi: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Ibarra</br>
              Quito Carcelén - Guayaquil</br>
              Quito Carcelén - Santo Domingo
 
 
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/aloag?name=Aloag">
            <span class="headline font-weight-bold">Aloag</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Aloag</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>02 2389-652<br/>

              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/pages/category/Transit-System/Cooperativa-de-Transportes-interprovincial-ALOAG-368892643685915/"> https://www.facebook.com/pages/category/Transit-System/Cooperativa-de-Transportes-interprovincial-ALOAG-368892643685915/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>cooptransaloag1977@hotmail.com
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Aloag: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén Quinindé</br>
              Quito Carcelén Nanegal</br>
              Quito Carcelén Playa Rica</br>
              Quito Carcelén Santo Domingo</br>
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
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Amazonas: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Pacto</br>
              Quito Carcelén - Puyo</br>
 
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
              <span class="font-weight-bold">Teléfono: </span>03 392 - 0215 ext. 3101<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="http://www.cooperativabanos.com.ec">http://www.cooperativabanos.com.ec/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/cooperativadetransportesbanos">https://www.facebook.com/cooperativadetransportesbanos/</a><br>              
              
               <span class="font-weight-bold">Correo electrónico: </span>info@cooperativabanos.com.ec
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Baños: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Baños - Puyo - Macas
            </blockquote>
          </v-flex> 
          <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
        <v-flex text-xs-center xs12 class="text-left">
            <router-link to="/search/schedule/coactur?name=Coactur">
            <span class="headline font-weight-bold">Coactur</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Coactur</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>0987191610<br/>
              

              <span class="font-weight-bold">Facebook:</span><a href="https://www.facebook.com/cooperativacoactur.manabi/">https://www.facebook.com/cooperativacoactur.manabi/</a><br>              
              
          </blockquote>
           </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Coactur: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
            Quito Carcelén - Manta
            </blockquote>
          </v-flex>  
         <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
                  <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/transportesecuador?name=Transportes%20Ecuador">
            <span class="headline font-weight-bold"> Transportes Ecuador</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Transportes Ecuador</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>09-93710-128<br/>

              <span class="font-weight-bold">Página web: </span><a href="https://transportesecuador.com.ec/">https://transportesecuador.com.ec/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/TransportesEcuadorOficial/">https://www.facebook.com/TransportesEcuadorOficial/</a><br>               
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Transportes Ecuador: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Guayaquil
            </blockquote>
            </v-flex> 
            <v-flex xs12 my-3><v-divider></v-divider></v-flex> 
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/espejo?name=Espejo">
            <span class="headline font-weight-bold">Espejo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Espejo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/transportesespejo/">https://www.facebook.com/transportesespejo/</a><br>             
              
          </blockquote>
                      <span class="title">Rutas desde Quito Carcelén de la cooperativa Espejo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - El Angel </br>
            </blockquote>
            </v-flex> 
           </v-flex> 
        <v-flex xs12 my-3><v-divider></v-divider></v-flex>  
        <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/expresotulcan?name=Expreso%20Tulcán">
            <span class="headline font-weight-bold">Expreso Tulcán</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Expreso Tulcán</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>02-350-0091<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="https://www.expresotulcan.com/">https://www.expresotulcan.com//</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://es-la.facebook.com/pages/category/Cargo---Freight-Company/Expreso-Tulc%C3%A1n-208753763217264/">https://es-la.facebook.com/pages/category/Cargo---Freight-Company/Expreso-Tulc%C3%A1n-208753763217264/</a><br>            
              <span class="font-weight-bold">Correo electrónico: </span>info@expresotulcan.com
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Expreso Tulcán: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Tulcán </br>
              Quito Carcelén - Ibarra
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                 <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/expresoturismo?name=Expreso%20Turismo">
            <span class="headline font-weight-bold">Expreso Turismo</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Expreso Turismo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>(06) 295-5730<br/>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Charter-Bus-Service/Expreso-Turismo-DEL-NORTE-127833537388645/">https://www.facebook.com/pages/category/Charter-Bus-Service/Expreso-Turismo-DEL-NORTE-127833537388645/</a><br>
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Expreso Turismo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Tulcán 
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
              <span class="font-weight-bold">Teléfono: </span>2236940 Ext.: 1072<br/>

              <span class="font-weight-bold">Página web: </span><a href="https://flota-imbabura.com/ ">https://flota-imbabura.com/ </a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/flotaimbaburaEC/">https://www.facebook.com/flotaimbaburaEC/</a><br>
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Flota Imbabura: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Tulcán <br>
              Quito Carcelén - Ibarra <br>
              Quito Carcelén - Cuenca <br>
              Quito Carcelén - San Lorenzo
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
              Sin datos
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Kennedy: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Puerto Quito <br>
              Quito Carcelén - Santo Domingo
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
              <span class="font-weight-bold">Teléfono: </span>06 2831570<br/>
              
              <span class="font-weight-bold">Página web: </span><a href="https://cooperativaloja.com.ec/">https://cooperativaloja.com.ec/</a><br>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/CoopLoja/">https://www.facebook.com/CoopLoja//</a><br>             
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Loja: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Loja 
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                    <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/loslagos?name=Los%20Lagos">
            <span class="headline font-weight-bold">Los Lagos</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Los Lagos</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transporte-Los-Lagos-159431797564726/">https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-de-Transporte-Los-Lagos-159431797564726/</a><br>             
              <span class="font-weight-bold">Correo electrónico: </span>cooptranslagos@hotmail.com
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Los Lagos: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Otavalo </br>
              Quito Carcelén - Cotacachi 
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
              <span class="font-weight-bold">Página web: </span><a href="http://occidentales.ec/">http://occidentales.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/transportes.occidentales/"> https://www.facebook.com/transportes.occidentales/</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span>info@ocidentales.ec
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Occidentales: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Huaquillas 
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/orientalpimampiro?name=Oriental%20Pimampiro">
            <span class="headline font-weight-bold">Oriental Pimampiro</span>
          </router-link>
        </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Oriental Pimampiro</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Sin datos
              
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa Oriental Pimampiro: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Pimampiro
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                   <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/otavalo?name=Otavalo">
            <span class="headline font-weight-bold">Otavalo</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Otavalo</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Facebook: </span><a href=" https://www.facebook.com/cooperativatransotavalo/">  https://www.facebook.com/cooperativatransotavalo//</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span>coop.trans.otavalo@hotmail.com
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Otavalo: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Otavalo<br>
              Quito Carcelén - Pacto<br>
              Quito Carcelén - San José de Minas
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
              <span class="font-weight-bold">Teléfono: </span>0985512164<br/>
              <span class="font-weight-bold">Página web: </span><a href="https://www.panamericana.ec/">https://www.panamericana.ec/</a><br>
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/servciointernacional/">   https://www.facebook.com/servciointernacional/</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span> info@panamericana.ec
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Panamericana: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Machala - Santa Rosa - Huaquillas<br>
              Quito Carcelén - Portoviejo - Manta<br>
              Quito Carcelén - Guayaquil
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/primavera?name=Primavera">
            <span class="headline font-weight-bold">Primavera</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Primavera</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2"> 
              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-De-Transportes-De-Pasajeros-Primavera-Salcedo-Ecuador-355359718306311/">   https://www.facebook.com/pages/category/Cargo---Freight-Company/Cooperativa-De-Transportes-De-Pasajeros-Primavera-Salcedo-Ecuador-355359718306311/</a><br>           
              <span class="font-weight-bold">Correo electrónico: </span>cooperativatrasportesprimavera@gmail.com
          </blockquote>
           </v-flex>   

          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Primavera: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Puerto Quito
            </blockquote>
            </v-flex> 
         <v-flex xs12 my-3><v-divider></v-divider></v-flex>
                    <v-flex text-xs-center xs12 class="text-left" mt-5>
            <router-link to="/search/schedule/putumayo?name=Putumayo">
            <span class="headline font-weight-bold">Pullman Carchi</span>
          </router-link>
          </v-flex>    
          <v-flex text-xs-center xs12 class="text-left">
            <span class="title">Datos de contacto de la cooperativa Pullman Carchi</span>
          </v-flex>    
          <v-flex xs12>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              <span class="font-weight-bold">Teléfono: </span>(06) 298-0020<br/>

              <span class="font-weight-bold">Facebook: </span><a href="https://www.facebook.com/pages/category/Transportation-Service/Cooperativa-de-Transporte-Interprovincial-Pullman-Carchi-1993296074318780/">https://www.facebook.com/pages/category/Transportation-Service/Cooperativa-de-Transporte-Interprovincial-Pullman-Carchi-1993296074318780/</a><br>   
          </blockquote>
           </v-flex>   
          <v-flex text-xs-center xs12 class="text-left" mt-5>
            <span class="title">Rutas desde Quito Carcelén de la cooperativa de transporte Pullman Carchi: </span>
            <blockquote class="blockquote mx-0 px-0 mb-2">
              Quito Carcelén - Ibarra - Tulcán
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
            <span class="headline font-weight-bold">Servicios que presta el Terminal terrestre de Quito Carcelén</span>
          </v-flex>   
            <v-flex xs12 class="blockquote">
            Entre los servicios que puedes disfrutar en el Terminal de Quito Carcelén podrás encontrar:
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
