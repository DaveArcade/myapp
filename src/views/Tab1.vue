<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Home</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Home</ion-title>
        </ion-toolbar>
      </ion-header>
      <div id="bg">
        <ion-list>
          <ion-item>
            <ion-checkbox slot="start"></ion-checkbox>
            <ion-label>
              <h3>Recibir notificaciones</h3>
              <ion-note>de decuentos</ion-note>
            </ion-label>
          </ion-item>
        </ion-list>
        <HolaComp />
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
} from "@ionic/vue";
import HolaComp from "@/components/HolaComp.vue";

export default {
  name: "Tab1",
  components: {
    HolaComp,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonPage,
  },
  setup() {
    return {
    };
  },
};
</script>
<style scoped>
#bg {
  background-image: url("../../public/assets/img/bienvenido1.jpg");
  width: 100%;
  height: 100%;
  background-position-x: 20%;
  background-position-y: 20%;
}
.ic {
  padding-top: 40%;
  padding-left: 46%;
}
</style>
