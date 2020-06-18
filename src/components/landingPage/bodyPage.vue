<!-- Desarrollado por: José luis casanova -->
<template>
  <v-layout row wrap>
    <v-flex layout justify-center></v-flex>
    <toolbar class="hidden-sm-and-down" />
    <ToolbarResponsive class="hidden-md-and-up" />
    <v-flex xs12 layout justify-center>
      <div style="width:70%">
        <v-carousel cycle>
          <v-carousel-item
            v-for="(item,i) in itemsCarousel"
            :key="i"
            :src="item.src"
            reverse-transition="fade-transition"
            transition="fade-transition"
          ></v-carousel-item>
        </v-carousel>
      </div>
    </v-flex>
    <v-flex xs12 layout justify-center style="padding-top:50px">
      <v-flex flex-column>
        <v-flex xs12 >
          <v-img src="../../../public/img/Desktop1904/nammu.io@2x.png" height="20" width="120" style="margin:auto;"/>
        </v-flex>
        <p align="center" style="font-size:27px; font-weight:500; margin-top:20px">Titulo de prueba</p>
        <p align="center" style="font-size:18px; font-weight:300; ">Texto de prueba</p>
      </v-flex>
    </v-flex>

    <v-flex xs12 flex-column style="background-color:rgb(54, 54, 54); color:white">
      <p align="center" id="secretPro">Titulo de prueba</p>

      <v-flex xs12 layout justify-center flex-column>
        <p align="center" id="secretProductsParagraph">Texto de prueba</p>
      </v-flex>
    </v-flex>

    <v-layout row wrap>
        <v-flex xs12 md4 layout justify-end id="imageColage" style="position:relative;">
          <v-flex style="display:flex; height:550px;">
            <p id="promotionalVideo">Prueba</p>
            <v-btn
              x-large
              style="color:white; position:absolute;bottom:5px;
              right:10%;"
              icon
              outlined
            >
              <v-icon dark small>fas fa-chevron-right</v-icon>
            </v-btn>
          </v-flex>
        </v-flex>
        <v-flex xs12 md4 layout justify-end id="imageColage" style="position:relative;">
          <div style="display:flex; height:500px;">
            <p id="promotionalVideo">Prueba</p>
            <v-btn
              x-large
              style="color:white; position:absolute;bottom:5px;
              right:10%;"
              icon
              outlined
            >
              <v-icon dark small>fas fa-chevron-right</v-icon>
            </v-btn>
          </div>
        </v-flex>
        <v-flex xs12 md4 layout justify-end id="imageColage" style="position:relative;">
          <div style="display:flex; height:500px;">
            <p id="promotionalVideo">Prueba</p>
            <v-btn
              x-large
              style="color:white; position:absolute;bottom:5px;
              right:10%;"
              icon
              outlined
            >
              <v-icon dark small>fas fa-chevron-right</v-icon>
            </v-btn>
          </div>
        </v-flex>
      
      <v-flex xs12 md12 flex-column justify-center style="background-color:#eceeed">
        <v-flex xs12 flex-column>
          <p align="center" id="conoce">Texto de prueba</p>
          <v-flex xs12 layout justify-center flex-column>
            <p align="center" id="secretPro">Titulo de prueba</p>
          </v-flex>
        </v-flex>
      </v-flex>

      <v-layout row wrap style="background-color:#eceeed; padding-top:100px" layout justify-center>     
      <v-flex xs12 md3 layout justify-center>
            <v-card width="400" height="350" style="margin-right:2%; background-color:transparent" elevation="0">
              <v-list-item three-line>
                <v-list-item-avatar tile size="80"><v-icon x-large>fas fa-feather-alt</v-icon></v-list-item-avatar>
                <v-list-item-content>
                  <div style="color: #C3A059" class="overline mb-4">Titulo</div>
                  <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
                </v-list-item-content>
              </v-list-item>

              <v-card-text>
                <p>Parrafo Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quasi itaque fugit unde blanditiis laboriosam, laudantium mollitia accusantium quae eum culpa beatae nulla amet rerum iure in, atque, doloremque voluptatibus?</p>
              </v-card-text>
              <v-card-actions>
                <v-flex layout justify-center>
                  <v-btn large  outlined>
                    <v-icon left>mdi-pencil</v-icon>
                    prueba
                  </v-btn>
                </v-flex>
              </v-card-actions>
            </v-card>
        </v-flex>
        <v-flex xs12 md3 layout justify-center>
          <v-card width="400" height="350" style="margin-right:2%; background-color:transparent" elevation="0">
            <v-list-item three-line>
              <v-list-item-avatar tile size="80"><v-icon x-large>fas fa-feather-alt</v-icon></v-list-item-avatar>
              <v-list-item-content>
                <div style="color: #C3A059" class="overline mb-4">Titulo</div>
                <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-card-text>
              <p>Parrafo Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quasi itaque fugit unde blanditiis laboriosam, laudantium mollitia accusantium quae eum culpa beatae nulla amet rerum iure in, atque, doloremque voluptatibus?</p>
            </v-card-text>
            <v-card-actions>
              <v-flex layout justify-center>
                <v-btn large outlined>
                   <v-icon left>mdi-pencil</v-icon>
                  prueba
                </v-btn>
              </v-flex>
            </v-card-actions>
          </v-card>
         </v-flex>
         <v-flex xs12 md3 layout justify-center>
          <v-card width="400" height="350" style="margin-right:2%; background-color:transparent" elevation="0">
            <v-list-item three-line>
              <v-list-item-avatar tile size="80" ><v-icon x-large>fas fa-feather-alt</v-icon></v-list-item-avatar>
              <v-list-item-content>
                <div style="color: #C3A059" class="overline mb-4">Titulo</div>
                <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-card-text>
              <p>Parrafo Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quasi itaque fugit unde blanditiis laboriosam, laudantium mollitia accusantium quae eum culpa beatae nulla amet rerum iure in, atque, doloremque voluptatibus?</p>
            </v-card-text>
            <v-card-actions>
              <v-flex layout justify-center>
                <v-btn large  outlined>
                   <v-icon left>mdi-pencil</v-icon>
                  prueba
                </v-btn>
              </v-flex>
            </v-card-actions>
          </v-card>
       </v-flex>
    </v-layout>
    </v-layout>
    <v-layout row wrap style="background-color: rgb(236, 238, 237); padding-top:100px">
      <v-flex xs12 md6>
        <v-flex layout justify-center flex-column>
          <v-flex layout justify-center>
            <v-progress-circular
              :rotate="360"
              :size="170"
              :width="5"
              :value="value"
              color="#69423D"
            >
              {{ value }}
            </v-progress-circular>
            <P  style="height:20px; margin-top:73px; margin-left: -63px">%</P>
          </v-flex>
          
            <p align="center" style="font-size:16px; color:black; padding-left:50px; margin-top:30px">Texto de prueba</p>
          <v-flex xs12 style=" padding-top:100px" layout justify-center row wrap>
            <v-form >
              <v-flex  xs12 style="width:80%; display:flex">
                <v-text-field
                :label="labels.name"
                placeholder="Nombre"
                outlined
                style="margin-right:4%"
              ></v-text-field>
              <v-text-field
                :label="labels.last_name"
                placeholder="Apellido"
                outlined
              ></v-text-field>
              </v-flex>
              <p style="font-size:13px; margin-top:-15px">
                Escribe en este primer cuadro tu nombre. Ej: daniel; y en el segundo cuadro tu apellido. Ej: carvajal
              </p>
              <v-flex style="width:100%; margin-top:50px">
                <v-text-field
                  :label="labels.email"
                  placeholder="Correo Electrónico"
                  outlined
                ></v-text-field>
              </v-flex>
              <p style="font-size:13px; margin-top:-15px">
                Escribe tu correo electrónico
              </p>
              <v-flex style="width:100%; margin-top:50px">
                <v-text-field
                  label="Numero de whatsApp"
                  placeholder="Numero de whatsApp"
                  outlined
                ></v-text-field>
              </v-flex>
              <p style="font-size:13px; margin-top:-15px">
                Escribe acá tu número de WhatsApp
              </p>
               <v-flex style="width:100%; margin-top:50px">
              <v-textarea
              style="margin-top:50px"
              label="Mensaje"
              placeholder="Escribe un mensaje aquí"
              outlined
              >
              </v-textarea>
              </v-flex>
             <v-flex xs7 style="margin-left:-12|px">
                <vue-recaptcha
                sitekey="6LfRvqsUAAAAAAQCWq3hL9tchVuiKST0iFFDILir"
                class="layout column align-center"
              ></vue-recaptcha>
             </v-flex>

             <v-btn large style="margin-top:20px; width:150px; border-radius:0" color="#EEEEEE">Texto</v-btn>
            </v-form>
          </v-flex>
          </v-flex>
      </v-flex>
      <v-flex xs12 md6 class="hidden-sm-and-down">
        <v-flex flex-column>
          <span style="color: rgb(105, 66, 61); font-size: 35px; line-height: 40px; height: auto;">
            prueba!!
          </span>
          <p style="font-size: 16px; color: #333333; margin-top:30px">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus earum explicabo voluptatem
                quae cupiditate ea corporis magnam
                laboriosam modi vero non optio amet repellendus illum, pariatur nisi quod esse deleniti.
          </p>

          <v-list flat style="margin-top:100px; background-color:transparent">
            <v-list-item-group v-model="itemList" color="primary">
              <v-list-item
                v-for="(item, i) in itemsList"
                :key="i"
              >
                <v-list-item-icon>
                  <v-icon v-text="item.icon"></v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title v-text="item.text"></v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-list-item-group>
          </v-list>
        </v-flex>
      </v-flex>
      <v-flex xs12 md6 class="hidden-md-and-up" mt-5>
        <v-flex flex-column mt-5>
          <v-flex layout justify-center >
          <span style="color: rgb(105, 66, 61); font-size: 35px; line-height: 40px; height: auto;">
            prueba!!
          </span>
          </v-flex>
          
          <p align="center" style="font-size: 16px; color: #333333; margin-top:30px">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus earum explicabo voluptatem
                quae cupiditate ea corporis magnam
                laboriosam modi vero non optio amet repellendus illum, pariatur nisi quod esse deleniti.
          </p>

          <v-list flat style="margin-top:100px; background-color:transparent">
            <v-list-item-group  v-model="itemList" color="primary">
              <v-list-item
                v-for="(item, i) in itemsList"
                :key="i"
                
              >
                <v-list-item-icon>
                  <v-icon v-text="item.icon"></v-icon>
                </v-list-item-icon>
                <v-list-item-content>
                  <v-list-item-title v-text="item.text"></v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-list-item-group>
          </v-list>
        </v-flex>
      </v-flex>
      <v-flex xs12 flex-column style="margin-top:100px">
          <p align="center" style="font-size:15px; color:#8D8D8D;">Texto</p>
          <p align="center" style="font-size:35px; color:#3A3A3A; margin-top:-10px">Texto</p>
          <v-flex xs12 layout justify-center>
              <div style="width:70%">
                <v-carousel cycle>
                  <v-carousel-item
                    v-for="(item,i) in itemsCarousel"
                    :key="i"
                    :src="item.src"
                    cycle
                  ></v-carousel-item>
                </v-carousel>
              </div>
           </v-flex>
          <p align="center" style="font-size:35px; color:#3A3A3A; margin-top:50px">Titulo</p>
          <p align="center" style="font-size:14px; color:#000000; margin-top:-15px">Texto</p>
      <v-flex xs12 layout justify-center>
        <v-btn color="#69423D" large  outlined style="border-radius:50px; width:300px; height:50px">
            <v-icon left>fas fa-phone-alt</v-icon>
                    ¡Quiero contactarlos!                
        </v-btn>
      </v-flex>

      <v-flex xs12 id="cover" row wrap>
        <v-flex xs12 md3  layout justify-center>
            <v-card height="380" style="margin-right:2%; background-color:transparent;" elevation="0">
            <v-list-item three-line>
              <v-list-item-avatar tile size="80"><v-icon x-large>fas fa-feather-alt</v-icon></v-list-item-avatar>
              <v-list-item-content>
                <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-card-text>
              <p style="color:black; font-weight:500">Parrafo Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quasi itaque fugit unde blanditiis laboriosam, laudantium mollitia accusantium quae eum culpa beatae nulla amet rerum iure in, atque, doloremque voluptatibus?</p>
            </v-card-text>
            <v-card-actions>
              <v-flex layout justify-center>
                <v-btn large  outlined>
                   <v-icon left>mdi-pencil</v-icon>
                  prueba
                </v-btn>
              </v-flex>
            </v-card-actions>
          </v-card>
        </v-flex>
        <v-flex xs12 md3  layout justify-center>
          <v-card class="vl" width="400" height="380" style="margin-right:2%; background-color:transparent" elevation="0">
            <v-list-item three-line>
              <v-list-item-content>
                <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-card-text>
              <p style="color:black; font-weight:500">Parrafo Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quasi itaque fugit unde blanditiis laboriosam, laudantium mollitia accusantium quae eum culpa beatae nulla amet rerum iure in, atque, doloremque voluptatibus?</p>
            </v-card-text>
           
          </v-card>
          </v-flex>
          <v-flex xs12 md3  layout justify-center> 
          <v-card class="vl" width="400" height="380" style="margin-right:2%; background-color:transparent" elevation="0">
            <v-list-item three-line>
              
              <v-list-item-content>
                <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-card-text>
              <p style="color:black; font-weight:500">Parrafo Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quasi itaque fugit unde blanditiis laboriosam, laudantium mollitia accusantium quae eum culpa beatae nulla amet rerum iure in, atque, doloremque voluptatibus?</p>
            </v-card-text>
            <v-card-actions>
              <v-flex xs8 layout justify-center >
                <v-text-field outlined label="Search" append-icon="fas fa-search" 
                 @click:append="false">
                </v-text-field>
              </v-flex>
            </v-card-actions>
          </v-card>
          </v-flex>
          <v-flex xs12 md3  layout justify-center>
          <v-card class="vl" width="400" height="380" style="margin-right:2%; background-color:transparent" elevation="0">
            <v-list-item three-line>
              <v-list-item-content>
                <v-list-item-title class="headline mb-1"><h5 style="font-size:20px; font-weight:700">texto</h5></v-list-item-title>
              </v-list-item-content>
            </v-list-item>

            <v-card-text>
                          <v-container fluid>
                            <v-row>
                              <v-col
                                v-for="n in 5"
                                :key="n"
                                class="d-flex child-flex"
                                cols="4"
                              >
                                <v-card flat tile class="d-flex">
                                  <v-img
                                    :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
                                    :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                                    aspect-ratio="1"
                                    class="grey lighten-2"
                                  >
                                    <template v-slot:placeholder>
                                      <v-row
                                        class="fill-height ma-0"
                                        align="center"
                                        justify="center"
                                      >
                                        <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                                      </v-row>
                                    </template>
                                  </v-img>
                                </v-card>
                              </v-col>
                            </v-row>
                          </v-container>           
            </v-card-text>
          </v-card>          
      </v-flex>
      </v-flex>

      <v-flex xs12 layout justify-center mt-5>
        <p align="center" style="font-size:13px; color:#8B8B8B">
          2020 © Nammu.io
        </p>
      </v-flex>
      <v-flex xs12 layout justify-center>
        <v-flex layout justify-center xs3 style="display:flex">
            <v-btn icon> <v-icon>fab fa-facebook-f</v-icon> </v-btn>
            <v-btn icon> <v-icon>fab fa-twitter</v-icon> </v-btn>
            <v-btn icon> <v-icon>fab fa-youtube</v-icon> </v-btn>
            <v-btn icon> <v-icon>fab fa-instagram</v-icon> </v-btn>
        </v-flex>
      </v-flex>
      </v-flex>
    </v-layout>
  </v-layout>
</template>

<script>
import { labels, paragraphs } from "@/lang/lang.js";
import VueRecaptcha from "vue-recaptcha";
// import VuePerfectScrollbar from "vue-perfect-scrollbar";
import toolbar from "@/components/Toolbar.vue";
import ToolbarResponsive from "@/components/ToolbarResponsive.vue";
import { mapState, mapMutations } from "vuex";

export default {
  data: () => ({
    interval: {},
    value: 0,
    labels: labels,
    paragraphs: paragraphs,
    settings: {
      suppressScrollY: true,
      maxScrollbarLength: 800
    },
    itemList: 1,
      itemsList: [
        { text: 'texto', icon: 'fas fa-plus' },
        { text: 'texto', icon: 'fas fa-plus' },
        { text: 'texto', icon: 'fas fa-plus' },
        { text: 'texto', icon: 'fas fa-plus' },
        { text: 'texto', icon: 'fas fa-plus' },
        { text: 'texto', icon: 'fas fa-plus' },
      ],
    itemsCarousel: [
      {
        src: "https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg"
      },
      {
        src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg"
      },
      {
        src: "https://cdn.vuetifyjs.com/images/carousel/bird.jpg"
      },
      {
        src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg"
      }
    ],
  }),
  computed: {
    ...mapState(["day", "hour", "minutes", "seconds"])
  },
  components: {
    // VuePerfectScrollbar,
    toolbar,
    ToolbarResponsive,
    VueRecaptcha
  },
  methods: {
    ...mapMutations(["getDate"])
  },
  beforeMount() {
    setInterval(() => {
      this.getDate();
    }, 1000);
  },mounted(){
    let i=0;
    this.interval = setInterval(() => {
        if (this.value < 100) {
          this.value += 1
        }
      }, 20)       
  }
};
</script>
<style>
.vl {
  border-left: 2px solid black;
  height: 280px;
  margin-top: 40px;
}
#cover{
  margin-top:100px;
  background-image: linear-gradient(white), 
  url('../../../public/img/map-of-the-world-2401458_1920.jpg');    
  background-attachment: fixed;
  background-blend-mode: multiply; 
  background-position: center center; 
  background-size: cover
}
#imgFaceAcademy {
  background-image: url(../../../public/img/Desktop1904/image_faceAcademy@2x.jpg);
  background-size: cover;
  background-position: absolute;
  height: 20%;
}
.scroll-area {
  width: 100%;
  padding-bottom: 5%;
  position: relative;
}
#container {
  padding-top: 15%;
  background-image: url(../../../public/img/4kandUltra1888px/Hero@2x.jpg);
  background-size: cover;
  width: 100%;
  background-position: absolute;
}
#promotionalVideo {
  font-size: 25px;
  font-weight: 300;
  color: white;
  position: absolute;
  bottom: 48px;
  right: 
  5%;
}
#specialImage {
  background-image: url("../../../public/img/Desktop1904/BEC_image_3@2x.jpg");
  background-position: center;
  background-size: cover;
  margin-right: 2%;
}
#imageColage {
  background-image: url("../../../public/img/Desktop1904/BEC_image_1@2x.jpg");
  background-position: center;
  background-size: cover;
}
#pCard {
  width: 150px;
  margin-top: 100px;
  margin-left: 55%;
  padding-right: 2%;
  margin-top: -28%;
  color: white;
  font-size: 25px;
  font-family: "Roboto", sans-serif !important;
  z-index: 1;
}
#btnWatch {
  font-size: 18px;
  margin-top: 15px;
  margin-bottom: 230px;
  border-radius: 0;
  text-transform: none !important;
  width: 200px;
  height: 50px;
}
#secretPro {
  padding-top: 2%;
  font-size: 40px;
  font-weight: 600;
  font-family: "Roboto" !important;
  margin: auto;
}
#face {
  font-size: 65px;
  color: black;
  font-family: "Roboto" !important;
  font-weight: 900;
}
#academy {
  font-size: 65px;
  color: black;
  font-family: "Roboto" !important;
  font-weight: 300;
}
#bec {
  font-size: 65px;
  color: black;
  font-family: "Roboto" !important;
  font-weight: 900;
}
.inscriptionTime {
  font-size: 55px;
  color: black;
  font-family: "Roboto" !important;
  font-weight: 900;
}
.textTimes {
  margin-top: -10%;
  font-size: 18px;
  font-family: "Roboto" !important;
  color: black;
  font-weight: 600;
  line-height: 120%;
}
#verticalLine {
  font-size: 170px;
  font-weight: 200;
  color: black;
  margin-top: -4.2%;
}
#conference {
  font-size: 65px;
  color: black;
  font-family: "Roboto" !important;
  font-weight: 300;
}
#secretProducts {
  font-size: 28px;
  font-family: "Roboto" !important;
  font-weight: 300;
  margin: auto;
  margin-top: -1.5%;
}
#secretProductsParagraph {
  font-size: 15px;
  font-family: "Roboto" !important;
  font-weight: 400;
  
  margin: auto;
  margin-top: 1%;
  margin-bottom: 4%;
  line-height: 120%;
}
#conoce {
  font-size: 15px;
  font-family: "Roboto" !important;
  color: #8d8d8d;
  font-weight: 400;

  margin: auto;
  margin-top: 100px;
  margin-bottom: -20px;
  line-height: 120%;
}
#paragraphFaceAcademy {
  font-size: 25px;
  font-family: "Roboto" !important;
  font-weight: 400;
  margin: auto;
  padding-left: 12%;
  padding-right: 12%;
  width: 100%;
  line-height: 120%;
}
#paragraphBecConference {
  font-size: 25px;
  font-family: "Roboto" !important;
  font-weight: 400;
  margin: auto;
  width: 100%;
  padding-left: 15%;
  padding-right: 15%;
  text-align: justify;
  line-height: 120%;
}
#paragraphColage {
  margin-top: 2%;
  font-size: 25px;
  font-family: "Roboto" !important;
  color: black;
  font-weight: 500;
  width: 100%;
  text-align: justify;
  line-height: 120%;
}
.listFaceAcademy {
  font-size: 25px;
  font-family: "Roboto" !important;
  font-weight: 400;
  margin: auto;
  line-height: 120%;
}
#paragraphTime {
  font-size: 25px;
  font-family: "Roboto" !important;
  font-weight: 800;
  margin: auto;
  color: black;
  text-align: justify;
  line-height: 120%;
}
h2 {
  font-size: 55px;
  font-family: "Roboto", sans-serif !important;
  margin-top: 25px;
  padding-left: 50%;
}
</style>