<template>
<v-card>


    <div class="content">
        <div class="header_Text">
            <h2>Виды работ</h2>
        </div>

        <div class="membran">
            <h3>Монтаж мембранной кровли</h3>
            <v-card-text>
                <p> ПВХ мембрана - это самый надежный и лучший вариант.   </p>
                <p>Инновационный гидроизоляционный материал, сваривается горячим воздухом из специальных фенов - ручных и автоматических. </p>
                <p>Получив такую кровлю, вы на долгие годы забудете про ремонт и восстановление. Надежность мембраны обусловлена, эластичностью, герметичностью и высокими показателями стойкости к низким и высоким температурам.</p>
                <p>Срок годности мембранной кровли - до 40 лет, в зависимости от качества рулона.
                Также, одним из достоинств мембранной кровли является вес, значительно снижающий нагрузку на крышу. 
                </p>

            </v-card-text>
           

    <v-carousel
        cycle
        height="400"
        hide-delimiter-background
        show-arrows-on-hover
        class="mb-16"
    >
    <template v-slot:prev="{ on, attrs }">
      <v-btn
        color="success"
        v-bind="attrs"
        v-on="on"
      >Назад</v-btn>
    </template>
    <template v-slot:next="{ on, attrs }">
      <v-btn
        color="info"
        v-bind="attrs"
        v-on="on"
      >Вперед</v-btn>
    </template>
            <v-carousel-item
            >
            <v-sheet
                height="100%"
            >
                <v-row
                class="fill-height"
                align="center"
                justify="center"
                >
                <div class="display-3">
                <v-img
                                class="white--text align-end"
                                src="../assets/images/memb1.jpg"
                                height="250px"
                                
                    >
                    </v-img>
                </div>
                </v-row>
            </v-sheet>
            </v-carousel-item>

             <v-carousel-item
            >
            <v-sheet
                height="100%"
            >
                <v-row
                class="fill-height"
                align="center"
                justify="center"
                >
                <div class="display-3">
                <v-img
                                class="white--text align-end"
                                src="../assets/images/roof2.jpg"
                                height="250px"
                                
                    >
                    </v-img>
                </div>
                </v-row>
            </v-sheet>
            </v-carousel-item>

             <v-carousel-item
            >
            <v-sheet
                height="100%"
            >
                <v-row
                class="fill-height"
                align="center"
                justify="center"
                >
                <div class="display-3">
                <v-img
                                class="white--text align-end"
                                src="../assets/images/memb2.jpg"
                                height="250px"
                                
                    >
                    </v-img>
                </div>
                </v-row>
            </v-sheet>
            </v-carousel-item>

  </v-carousel>
          
          
        </div>     

        <div class="bitum ">
            <h3>Восстановление старой кровли с помощью термохимической обработки</h3>
            <p>
                В нашем арсенале есть электровоздушный нагреватель АП - 1, с помощью этого аппарата, мы можем восстановить старый гидроизоляционный слой. 
                Аппарат разогревает все слои старой кровли, имеющаяся влага между слоями выпаривается и по горячему слою мы проходим тяжелым катком, который создает из старых слоев один маннолитный слой.
                После этого на слой наносится мастика, на которую покрывается стеклоткань.
            </p>
        
            <v-carousel
            cycle
            height="400"
            hide-delimiter-background
            show-arrows-on-hover
           
            >
            <template v-slot:prev="{ on, attrs }">
            <v-btn
                color="success"
                v-bind="attrs"
                v-on="on"
            >Назад</v-btn>
            </template>
            <template v-slot:next="{ on, attrs }">
            <v-btn
                color="info"
                v-bind="attrs"
                v-on="on"
            >Вперед</v-btn>
            </template>
            <v-carousel-item
            >
            <v-sheet
                height="100%"
            >
                <v-row
                class="fill-height"
                align="center"
                justify="center"
                >
                <div class="display-3">
                <v-img
                                class="white--text align-end"
                                src="../assets/images/app1.jpg"
                                height="250px"
                                
                    >
                    </v-img>
                </div>
                </v-row>
            </v-sheet>
            </v-carousel-item>

             <v-carousel-item
            >
            <v-sheet
                height="100%"
            >
                <v-row
                class="fill-height"
                align="center"
                justify="center"
                >
                <div class="display-3">
                <v-img
                                class="white--text align-end"
                                src="../assets/images/roof1.jpg"
                                height="250px"
                                
                    >
                    </v-img>
                </div>
                </v-row>
            </v-sheet>
            </v-carousel-item>

             <v-carousel-item
            >
            <v-sheet
                height="100%"
            >
                <v-row
                class="fill-height"
                align="center"
                justify="center"
                >
                <div class="display-3">
                <v-img
                                class="white--text align-end"
                                src="../assets/images/ap1.jpg"
                                height="250px"
                                
                    >
                    </v-img>
                </div>
                </v-row>
            </v-sheet>
            </v-carousel-item>

        </v-carousel>
          
        </div>
    </div>
    </v-card>
</template>
