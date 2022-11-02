<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <div>
        <ion-grid>
          <ion-row>
            <ion-col class="ion-padding">
              <h1>Home</h1>
            </ion-col>
          </ion-row>

          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title>Kolam</ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1><strong>10</strong></h1>
                </ion-card-content>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title>Kolam Aktif</ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1><strong>8</strong></h1>
                </ion-card-content>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title>Ikan Hidup</ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><strong>182</strong></h1> Ekor
                </ion-card-content>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title>Ikan Mati</ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><strong>89</strong></h1> Ekor
                </ion-card-content>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title>Panen 2022</ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><strong>109</strong></h1> Kg
                </ion-card-content>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title>Total Pakan</ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><strong>223</strong></h1> Kg
                </ion-card-content>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col class="ion-padding">
              <h1>Total Berat Ikan</h1>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <swiper :slides-per-view="2" :loop="true">
                <swiper-slide>
                  <ion-card color="dark">
                    <ion-card-header>
                      <ion-img src="img/lele.png"></ion-img>
                    </ion-card-header>
                    <ion-card-content>
                      <h1><strong>Lele</strong></h1>
                      <ion-text color="primary">
                        <h1>200 Kg</h1>
                      </ion-text>
                    </ion-card-content>
                  </ion-card>
                </swiper-slide>
                <swiper-slide>
                  <ion-card color="dark">
                    <ion-card-header>
                      <ion-img src="img/nila.png"></ion-img>
                    </ion-card-header>
                    <ion-card-content>
                      <h1><strong>Nila Merah</strong></h1>
                      <ion-text color="primary">
                        <h1>200 Kg</h1>
                      </ion-text>
                    </ion-card-content>
                  </ion-card>
                </swiper-slide>
              </swiper>
            </ion-col>
          </ion-row>
        </ion-grid>

      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonPage, IonGrid, IonCol, IonRow, IonImg } from '@ionic/vue';
import { defineComponent } from 'vue';
import 'swiper/css';
import '@ionic/vue/css/ionic-swiper.css';
import { Swiper, SwiperSlide } from 'swiper/vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonContent, IonPage, IonGrid, IonCol, IonRow, IonImg, Swiper, SwiperSlide
  },
  setup() {
    // Optional parameters to pass to the swiper instance. See https://swiperjs.com/swiper-api for valid options.
    return { }
  }
});
</script>

<style scoped>
#inline {
  display: inline;
}

</style>
