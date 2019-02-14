<template>
  <v-layout>
    <!-- xs -->

    <v-carousel 
      delimiter-icon="stop"
      class="hidden-sm-and-up"
      height="350px"
    >
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        lazy
      >
        <v-container>
          <v-layout column fill-height justify-center align-center>
            <v-flex xs12>
              <span v-if="i == 0" class="imgheadline xs">Portrait</span>
              <span v-if="i == 1" class="imgheadline xs">Hochzeit</span>
              <span v-if="i == 2" class="imgheadline xs">Pärchen</span>
              <span v-if="i == 3" class="imgheadline xs">Akt</span>
            </v-flex>
          </v-layout>
        </v-container>
      </v-carousel-item>
    </v-carousel>

    <!-- sm -->

    <v-carousel 
      delimiter-icon="stop"
      class="hidden-md-and-up hidden-xs-only"
      height="400px"
    >
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        lazy
      >
        <v-container>
          <v-layout column fill-height justify-center align-center>
            <v-flex xs12>
              <span v-if="i == 0" class="imgheadline sm">Portrait</span>
              <span v-if="i == 1" class="imgheadline sm">Hochzeit</span>
              <span v-if="i == 2" class="imgheadline sm">Pärchen</span>
              <span v-if="i == 3" class="imgheadline sm">Akt</span>
            </v-flex>
          </v-layout>
        </v-container>
      </v-carousel-item>
    </v-carousel>

    <!-- md -->

    <v-carousel 
      delimiter-icon="stop"
      class="hidden-sm-and-down hidden-lg-and-up"
      height="450px"
    >
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        lazy
      >
        <v-container>
          <v-layout column fill-height justify-center align-center>
            <v-flex xs12>
              <span v-if="i == 0" class="imgheadline md">Portrait</span>
              <span v-if="i == 1" class="imgheadline md">Hochzeit</span>
              <span v-if="i == 2" class="imgheadline md">Pärchen</span>
              <span v-if="i == 3" class="imgheadline md">Akt</span>
            </v-flex>
          </v-layout>
        </v-container>
      </v-carousel-item>
    </v-carousel>

    <!-- lg -->

    <v-carousel 
      delimiter-icon="stop"
      class="hidden-md-and-down hidden-xl-only"
    >
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        lazy
      >
        <v-container>
          <v-layout column fill-height justify-center align-center>
            <v-flex xs12>
              <span v-if="i == 0" class="imgheadline">Portrait</span>
              <span v-if="i == 1" class="imgheadline">Hochzeit</span>
              <span v-if="i == 2" class="imgheadline">Pärchen</span>
              <span v-if="i == 3" class="imgheadline">Akt</span>
            </v-flex>
          </v-layout>
        </v-container>
      </v-carousel-item>
    </v-carousel>    

    <!-- xl -->

    <v-carousel 
      delimiter-icon="stop"
      class="hidden-lg-and-down"
      height="550px"
    >
      <v-carousel-item
        v-for="(item, i) in items"
        :key="i"
        :src="item.src"
        lazy
      >
        <v-container>
          <v-layout column fill-height justify-center align-center>
            <v-flex xs12>
              <span v-if="i == 0" class="imgheadline xl">Portrait</span>
              <span v-if="i == 1" class="imgheadline xl">Hochzeit</span>
              <span v-if="i == 2" class="imgheadline xl">Pärchen</span>
              <span v-if="i == 3" class="imgheadline xl">Akt</span>
            </v-flex>
          </v-layout>
        </v-container>
      </v-carousel-item>
    </v-carousel>

  </v-layout>
</template>

<style scoped>
  .imgheadline {
    font: 38px Comfortaa;
    line-height: 452px;
    text-shadow: 1px 1px 1px #333;
    opacity: 0.4;
  }

  .xs {
    line-height: 318px;
  }

  .sm {
    line-height: 368px;
  }

  .md {
    line-height: 402px;
  }

  .xl {
    line-height: 502px;
  }
</style>


<script>
export default {
  data() {
    return {
      items: [
        // {
        //   src: "'@/assets/img/paerchen-1000.png'"
        // },
        {
          src: 'https://images.unsplash.com/photo-1531251445707-1f000e1e87d0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80'
        },
        {
          src: 'https://images.unsplash.com/photo-1521543269800-27e08780ced7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80'
        },
        {
          src: 'https://images.unsplash.com/photo-1505765052322-75804bb2e5f1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80'
        },
        {
          src: 'https://images.unsplash.com/photo-1519668752166-ebdbfe986afd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80'
        }
      ]
    }
  }
}
</script>
