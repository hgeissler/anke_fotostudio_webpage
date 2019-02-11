<template>
  <v-app dark>
    <v-container fluid fill-height class="pa-2">
      <v-layout align-center justify-center>
        <v-flex lg8 md10 sm11 xs12>
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
          <v-toolbar class="sticky" app>
            <v-toolbar-title class="pacifico">
              <v-icon class="pb-1">camera_alt</v-icon>
              A. Marsolin
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-xs-only">
              <v-btn flat>
                <v-icon>home</v-icon>
                Home
              </v-btn>
              <v-btn flat>
                <v-icon>photo_library</v-icon>
                Portfolio
              </v-btn>
              <v-btn flat>
                <v-icon>message</v-icon>
                Kontakt
              </v-btn>
            </v-toolbar-items>
          </v-toolbar>
        
          <v-content class="pa-0">
            <Carousel />
          </v-content>

          <v-footer app class="pa-3">
            <v-spacer></v-spacer>
            <div>&copy; {{ new Date().getFullYear() }} by Anke Marsolin</div>
          </v-footer>
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Comfortaa|Pacifico');

  .pacifico {
    font-family: Pacifico;
  }

  .comfortaa {
    font-family: Comfortaa;
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
  data () {
    return {
      //
    }
  }
}
</script>
