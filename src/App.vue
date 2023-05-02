<!-- HEADER -->
<template>
  <v-app>
    <v-app-bar app> 
      <v-toolbar-title>LOGO</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn>Home</v-btn>
      <div class="drop">
        <v-btn>Productos</v-btn>
        <div class="drop-content">
          <a href="#">Hombres</a>
          <a href="#">Mujeres</a>
          <a href="#">Unisex</a>
        </div>
      </div>
      <v-btn>Nosotros</v-btn>
      <v-btn>Contacto</v-btn>
    </v-app-bar>
  
<!-- HEADER -->

    <!-- Banner -->
    <v-container fluid>
      <v-card  class="banner" :img="require('@/assets/banner.jpg')">
        <v-row align="center" justify="center">
          <v-col cols="12"  md="3" class="banner-col">
            <v-card-title class="white--text2">¡Promoción especial!</v-card-title>
            <v-card-text class="white--text">Compra 2 productos y obtén un 10% de descuento en tu compra.</v-card-text>
          </v-col>
        </v-row>
      </v-card>
    </v-container>
<!-- Banner -->
    


<!-- CAROUSEL1-->

<v-carousel class="carousel1" style="height: 400px; width: 100%;">
  <v-carousel-item>
        <img class="carousel-jordan" :src="jordan12">
      </v-carousel-item>
   ></v-carousel-item>  


  <v-carousel-item
    src="https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
    cover
  ></v-carousel-item>

  <v-carousel-item
    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
    cover
  ></v-carousel-item>
</v-carousel>
<!-- CAROUSEL1 -->


<!-- PRODUCTOS (ARREGLAR) -->
<v-card>
  <v-card-title class="text-center">Categorías de productos</v-card-title>
</v-card>
  <v-row>
    <v-col cols="12" sm="6" md="4" lg="3"> 
      <v-card class="producto1" max-width="260">
        <v-img src="https://via.placeholder.com/100x100" height="200px"></v-img>
        <v-card-text>
          <div class="text-h4 text--primary">Zapatilla 1</div>
          <p>Talles (40-44)</p>
          <div class="text--center"> $100.000 </div>
        </v-card-text>
          <v-card-actions class="text-center">
          <v-btn variant="text" color="light-green">Comprar</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
    
    <v-col cols="12" sm="6" md="4" lg="3"> 
      <v-card class="producto1" max-width="260">
        <v-img src="https://via.placeholder.com/100x100" height="200px"></v-img>
        <v-card-text>
          <div class="text-h4 text--primary">Remera</div>
          <p>Talles (40-44)</p>
          <div class="text--center"> $20.000 </div>
        </v-card-text>
        <v-card-actions class="text-center">
          <v-btn variant="text" color="light-green">Comprar</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
    
    <v-col cols="12" sm="6" md="4" lg="3"> 
      <v-card class="producto1" max-width="260">
        <v-img src="https://via.placeholder.com/100x100" height="200px"></v-img>
        <v-card-text>
          <div class="text-h4 text--primary">Remera</div>
          <p>Talles (40-44)</p>
          <div class="text--center"> $20.000 </div>
        </v-card-text>
        <v-card-actions class="text-center">
          <v-btn variant="text" color="light-green">Comprar</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6" md="4" lg="3"> 
      <v-card class="producto1" max-width="260">
        <v-img src="https://via.placeholder.com/100x100" height="200px"></v-img>
        <v-card-text>
          <div class="text-h4 text--primary">Remera</div>
          <p>Talles (40-44)</p>
          <div class="text--center"> $20.000 </div>
        </v-card-text>
        <v-card-actions class="text-center">
          <v-btn variant="text" color="light-green">Comprar</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

  </v-row>
</v-container>

<!-- PRODUCTOS (ARREGLAR) -->



<!--TESTIMONOS-->

<div class="testimonials">
  <div class="testimonial">
    <p>Me encanta la calidad de los productos de esta tienda, siempre compro aquí.</p>
    <p class="author">Juan Pérez</p>
  </div>
  <div class="testimonial">
    <p>Excelente atención al cliente y precios muy competitivos.</p>
    <p class="author">María López</p>
  </div>
  <div class="testimonial">
    <p>Los productos llegaron en perfecto estado y en el plazo acordado.</p>
    <p class="author">Pedro González</p>
  </div>
</div>




<!--TESTIMONIOS-->








<!-- FOOTER --> 
<!--new Date().getFullYear()      PROBAR-->
<template>
  <div>
    <v-footer color="grey lighten-3">
      <span>&copy; {{ new Date().getFullYear() }} Pagina realizada por Franco Maldonado , Braian Maresca, Gabriel Zambrano. <b>(Footer de prueba)</b></span>
    </v-footer>
  </div>
</template>

</v-app>
</template>
<!-- FOOTER SCRIPT -->




<!-- FOTOS CAROUSEL-->
<script>

import jordan12 from "@/assets/jordan12.png";

export default {
  name: "foto",
  data() {
    return {
      jordan12: jordan12,
    };
  },
};




</script>

<!-- SCRIPT COMENTARIOS -->


<!-- SCRIPT COMENTARIOS -->



<!--FOTOS CAROUSEL-->



<!-- STYLE -->
<style>


.text-center {
  text-align: center;
}
  
.mx-auto {
  margin-left: auto;
  margin-right: auto;
}


.carousel1{
  margin-top: 10px;
  
}


.carousel-jordan {
    height: 70%;
    width: 100%;
    object-fit: contain;
    object-position: center center;
  }

  .carousel-allstar {
    height: 70%;
    width: 100%;
    object-fit: contain;
    object-position: center center;
  }

  .carousel-tatum {
    height: 70%;
    width: 100%;
    object-fit: contain;
    object-position: center center;
  }

.white--text2 {
  color: white;
  height: 50px;
}

.banner {
  margin-top: 60px;
  background-size: cover;
  background-position: center; 
}

.categorias_vcard{
  margin-top: 10px;
  

}

.text-center{
  margin-left: 44%;
}

.drop {
  position: relative;
  display: inline-block;
}
.drop-content {
  display: none;
  position: absolute;
  z-index: 1;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
}
.drop-content a {
  color: black;
  padding: 6px 12px;
  text-decoration: none;
  display: block;
}
.drop-content a:hover {
  background-color: #ddd;
};


.testimonials {
  max-width: 800px;
  margin: 0 auto;
  padding: 10px;

  background-color: #f5f5f5;
}

.testimonial {
  margin-top: 20px;
  background-color: #fff;
  border-radius: 5px;
  padding: 10px;
  margin-bottom: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.testimonial p.author {
  font-style: italic;
  text-align: right;
  margin-top: 5px;
  color: #666;
}

.testimonial:nth-child(odd) {
  background-color: #f8f8f8;
}

.testimonial:nth-child(odd) p.author {
  color: #999;
}

.testimonial:nth-child(even) {
  background-color: #fdfdfd;
}

.testimonial:nth-child(even) p.author {
  color: #aaa;
}

h2 {
  color: #333;
  font-size: 16px;
  margin-bottom: 10px;
}


</style>


