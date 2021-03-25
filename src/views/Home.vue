<template>
      <div class="content">
        <div class="header_Text">
            <header>
                <h1>Строительная компания</h1>
                <h2>ООО 'Берд-Строй'</h2>
                <h3>Мы выполняем кровельные работы в Москве и в Московсокй области</h3> 
            </header>
                <div class="mainText"> 
                    <p>
                    <p>Работаем в сфере строительства более 25 лет</p>
                    <p>За нашими плечами огромное количество выполненных работ, мы успешно выполняли работы на крышах множества учреждений - университетов, школ, детских садов, жилых зданий</p>
                    <p>За 25 лет работы мы выработали, и отточили лучшие практики работы на кровле, мы выполняем работу любой сложности связанную с мягкой кровлей.</p>
                    <p></p>
                </div>
                    <div class="container">
                        <h2 class="mb-5">Вы можете ознакомиться с типами выполнямых нами работ</h2> 
                        <div class="row">
                        
            <v-container fluid>
              <v-row dense>
                <!--           1 card                      -->
                  <v-col> 
                      <v-card>
                            <v-img
                              src="../assets/images/roof1.jpg"
                              width="350px"
                              height="250px"
                              >
                              </v-img>
                              <v-card-text>
                                     <strong class="black--text"><h3 class="card-title">Работа с наплавляемым битумным материалом</h3></strong> 
                                </v-card-text>
                                  <v-card-subtitle>    
                                        <p class="black--text">Установка и ремонт кровли с использованием рулонов на битумной основе.</p>
                                        <button class="button button1"> <router-link :to="{name: 'Work'}">Просмотр</router-link></button>
                                  </v-card-subtitle> 
                          </v-card>
                  </v-col> 

                <!--           2 card                      -->
                  <v-col> 
                          <v-card>
                            <v-img
                              src="../assets/images/roof2.jpg"
                              width="350px"
                              height="250px"
                              >
                              </v-img>
                                <v-card-text>
                                      <h3 class="black--text">Работа с полимерной кровельной мембраной ПВХ</h3>
                                </v-card-text>
                              <v-card-subtitle>
                                <p class="black--text">Установка и ремонт кровли с использованием мембранных рулонов.</p> 
                                <button class="button button1"> <router-link :to="{name: 'Work'}">Просмотр</router-link></button>  
                              </v-card-subtitle>   
                      </v-card>
                  </v-col>
              </v-row>   
            </v-container>
             
                        </div>
                    </div>
               
        </div>
    </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
   
  }
}
</script>
