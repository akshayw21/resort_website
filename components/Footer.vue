<template>
<div class="footer">
  <v-footer
    color="primary lighten-1"
    padless
  >
    <v-row
      justify="center"
      no-gutters
      
    >
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        text
        rounded
        class="my-2 d-flex"
        :href='link.link'
      >
        {{ link.name }}
      </v-btn>
      <v-col
        class="primary lighten-2 py-4 text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-row>
  </v-footer>
  </div>
</template>

<script>
  export default {
    data: () => ({
      links: [
        {name: 'Home', link: '/'},
        {name:'About Us', link:'/about'},
    
        {name:'Contact Us', link:'/contact'}
      ],
    }),
  }
</script>

<style scoped>
.footer{
    border-radius: 30px;
}
</style>