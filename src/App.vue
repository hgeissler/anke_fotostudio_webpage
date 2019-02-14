<template>
  <v-app dark>
   
    <v-container 
      fill-height 
      class="pa-2"
    >
      <v-layout 
        align-center justify-center
      >
        <v-flex xl8 lg9 md10 sm11 xs12>
          <v-img
            app
            :src="require(`@/assets/header-img.png`)"
            height="25vh"
          >
            <v-layout 
              pa-2 column fill-height class="lightbox white--text" 
              justify-center align-center
            >
              <v-spacer></v-spacer>
              <v-flex>
                <div class="comfortaa text-xs-center" id="subheader">
                  Photography by
                </div>
                <div class="pacifico text-xs-center" id="header">
                  Anke Marsolin
                </div>
              </v-flex>
            </v-layout>
          </v-img>
          
          <!-- Navigation Drawer -->

          <v-navigation-drawer
            v-model="drawer"
            app
            fixed
            temporary
            clipped
            right
            class="hidden-lg-and-up"
            width="200"
          >
            <v-list>
              <v-list-tile @click="">
                <v-list-tile-action>
                  <v-icon>home</v-icon>
                </v-list-tile-action>
                <v-list-tile-content>
                  <v-list-tile-title>Home</v-list-tile-title>
                </v-list-tile-content>
              </v-list-tile>
              <v-list-tile @click="">
                <v-list-tile-action>
                  <v-icon>photo_library</v-icon>
                </v-list-tile-action>
                <v-list-tile-content>
                  <v-list-tile-title>Portfolio</v-list-tile-title>
                </v-list-tile-content>
              </v-list-tile>
              <v-list-tile @click="">
                <v-list-tile-action>
                  <v-icon>message</v-icon>
                </v-list-tile-action>
                <v-list-tile-content>
                  <v-list-tile-title>Kontakt</v-list-tile-title>
                </v-list-tile-content>
              </v-list-tile>
            </v-list>
          </v-navigation-drawer> 
          

          <!-- Toolbar -->

          <v-toolbar 
            class="sticky" 
            app 
            clipped-right
          >
            <v-toolbar-title class="pacifico">
              <v-icon class="pb-1">camera_alt</v-icon>
              A. Marsolin
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-sm-and-down">
              <v-btn flat>
                <v-icon>home</v-icon>
                Home
              </v-btn>
              <v-btn flat>
                <v-icon>photo_library</v-icon>
                Portfolio
              </v-btn>
              <v-btn flat class="pr-0">
                <v-icon>message</v-icon>
                Kontakt
              </v-btn>
            </v-toolbar-items>

            <!-- Menu -->

            <v-toolbar-side-icon
              @click.stop="drawer = !drawer"
              class="hidden-md-and-up ma-3"
              large
            >
              Menu
              <v-icon>menu</v-icon>
            </v-toolbar-side-icon>
          </v-toolbar>

          <!-- Main -->

          <v-content class="pa-0">
            <Carousel />

            <!-- quote -->

            <v-layout 
              row reverse 
              class="mt-4"
            >
              <v-flex xl5 lg6 md7 sm8 xs12>
                <v-card class="teal">
                  <v-card-text class="kalam">
                    „Auf einem guten Foto sehen wir die Welt so, wie wir sie kennen. <br>
                    Ein klasse Foto zeigt die Welt, wie wir sie noch nie gesehen haben.”
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>

            <v-layout>
              <v-flex>
                <v-card>

                </v-card>
              </v-flex>
            </v-layout>

          </v-content>

          <!-- Footer -->

          <v-footer class="pa-0 mt-3" height="auto" dark>
            <v-card
              class="flex"
              flat
              tile
            >
              <v-card-title class="teal">
                <v-spacer></v-spacer>
                <v-btn
                  dark
                  icon
                >
                  <v-icon size="24px">fab fa-facebook</v-icon>
                </v-btn>
                <v-btn
                  class="mx-3"
                  dark
                  icon
                >
                  <v-icon size="24px">fab fa-instagram</v-icon>
                </v-btn>
                <v-spacer></v-spacer>
              </v-card-title>

              <v-card-actions
                class="grey darken-3 justify-center"
              >
                &copy; {{ new Date().getFullYear() }} by Anke Marsolin
              </v-card-actions>
            </v-card>
          </v-footer>
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Comfortaa|Pacifico|Kalam');

  .pacifico {
    font-family: Pacifico;
  }

  .comfortaa {
    font-family: Comfortaa;
  }

  .kalam {
    font: 22px 'Kalam';
  }

  .sticky {
    position: sticky;
  }

  #subheader {
    font-size: 24px;
    text-shadow: 1px 2px 1px #333;
  }

  #header {
    font-size: 44px;
    text-shadow: 2px 3px 2px #333;
  }

  @media (max-width: 600px) {
   #header {
     font-size: 32px;
   }
   
   #subheader {
     font-size: 16px;
   }
  }
</style> 

<script>
import Carousel from './components/Carousel'

export default {
  name: 'App',
  components: {
    Carousel
  },

  data: () => ({
    drawer: false
  })
}
</script>
