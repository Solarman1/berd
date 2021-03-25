<template>
  <v-app id="inspire">
    <v-app-bar
      app
      color="white"
      flat
    >
      <v-container class="py-0 fill-height">


        <v-toolbar-title  to='/' link>
         
           
          
            БЕРД-СТРОЙ
         
        </v-toolbar-title>

        
        
        <v-btn
        text
        to='/work' link
        >
          Виды работы
        </v-btn>

        <v-btn
        text
        to='/contacts' link
        >
          Контакты
        </v-btn>

        <v-spacer></v-spacer>
      <strong class="text-decoration-none">
        <a href="tel:+79139657177" > 
         <span>Телефон: +7(913) 965-71-77</span>
        </a>
      </strong> 
     


      </v-container>
    </v-app-bar>

    <v-main class="grey lighten-3">
      <v-container>
         <v-row
          align="center"
          justify="center"
        >
          <v-col class="text-center">
            
            <router-view />

          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
  }),
};
</script>
