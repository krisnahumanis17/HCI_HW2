<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <ion-item>
        <ion-label>
          <h1><strong>Kolam</strong></h1>
        </ion-label>
        <ion-icon src="img/swap.svg" slot="end" color="dark"></ion-icon>
        <ion-icon src="img/sort.svg" slot="end" color="dark"></ion-icon>
      </ion-item>

      <ion-fab vertical="bottom" horizontal="end" slot="fixed">
        <ion-fab-button>
          <ion-icon src="img/add.svg" size="large"></ion-icon>
        </ion-fab-button>
      </ion-fab>

      <ion-infinite-scroll>
        <ion-infinite-scroll-content>
          <ion-card color="dark">
            <ion-item id="line" lines="inset" color="dark" class="ion-margin-horizontal">
              <ion-label class="ion-padding-vertical"><strong>Alpha</strong></ion-label>
              <ion-button slot="end" size="small" color="success">
                <ion-text color="dark">
                  Aktif
                </ion-text>
              </ion-button>
            </ion-item>
            <ion-card-content>
              <ion-grid>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/calendar.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>01-09-2022</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/alarm.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>90 hari</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/fish.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>209 ekor</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card-content>
          </ion-card>

          <ion-card color="dark">
            <ion-item id="line" lines="inset" color="dark" class="ion-margin-horizontal">
              <ion-label class="ion-padding-vertical"><strong>Beta</strong></ion-label>
              <ion-button slot="end" size="small" color="danger">
                Tidak Aktif
              </ion-button>
            </ion-item>
            <ion-card-content>
              <ion-grid>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/calendar.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>01-09-2022</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/alarm.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>90 hari</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/fish.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>209 ekor</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card-content>
          </ion-card>

          <ion-card color="dark">
            <ion-item id="line" lines="inset" color="dark" class="ion-margin-horizontal">
              <ion-label class="ion-padding-vertical"><strong>Charlie</strong></ion-label>
              <ion-button slot="end" size="small" color="success">
                <ion-text color="dark">
                  Aktif
                </ion-text>
              </ion-button>
            </ion-item>
            <ion-card-content>
              <ion-grid>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/calendar.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>01-09-2022</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/alarm.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>90 hari</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/fish.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>209 ekor</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card-content>
          </ion-card>

          <ion-card color="dark">
            <ion-item id="line" lines="inset" color="dark" class="ion-margin-horizontal">
              <ion-label class="ion-padding-vertical"><strong>Delta</strong></ion-label>
              <ion-button slot="end" size="small" color="success">
                <ion-text color="dark">
                  Aktif
                </ion-text>
              </ion-button>
            </ion-item>
            <ion-card-content>
              <ion-grid>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/calendar.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>01-09-2022</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/alarm.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>90 hari</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/fish.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>209 ekor</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card-content>
          </ion-card>

          <ion-card color="dark">
            <ion-item id="line" lines="inset" color="dark" class="ion-margin-horizontal">
              <ion-label class="ion-padding-vertical"><strong>Epsilon</strong></ion-label>
              <ion-button slot="end" size="small" color="success">
                <ion-text color="dark">
                  Aktif
                </ion-text>
              </ion-button>
            </ion-item>
            <ion-card-content>
              <ion-grid>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/calendar.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>01-09-2022</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/alarm.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>90 hari</p>
                  </ion-col>
                </ion-row>
                <ion-row class="ion-justify-content-start">
                  <ion-col size="1">
                    <ion-icon src="img/fish.svg" id="inline"></ion-icon>
                  </ion-col>
                  <ion-col size="auto">
                    <p>209 ekor</p>
                  </ion-col>
                </ion-row>
              </ion-grid>
            </ion-card-content>
          </ion-card>
        </ion-infinite-scroll-content>
      </ion-infinite-scroll>
      <div>
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonPage, IonInfiniteScroll, IonInfiniteScrollContent, IonCol, IonRow, IonFab, IonFabButton, IonText } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonContent, IonPage, IonInfiniteScroll, IonInfiniteScrollContent, IonCol, IonRow, IonFab, IonFabButton, IonText
  }
});
</script>

<style scoped>
#inline {
  display: inline;
}

ion-card{
  border-radius: 15px;
}

#line {
  border-bottom: 3px solid black;
}

</style>
