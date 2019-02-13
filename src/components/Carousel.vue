<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="require('item.src')""
    >
      <v-container fill-height>
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
</template>

<style scoped>
  .imgheadline {
    font: 32px Comfortaa;
    line-height: 400;
    text-shadow: 1px 1px 1px #333;
    opacity: 0.6;
  }
</style>


<script>
export default {
  data() {
    return {
      items: [
        {
          src: "'@/assets/img/paerchen-1000.png'"
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
