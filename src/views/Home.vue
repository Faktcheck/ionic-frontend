<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title class="ion-text-center"> Faktcheck </ion-title>
      </ion-toolbar>
      <ion-toolbar>
        <ion-grid>
          <ion-row>
            <ion-col
              size-lg="6"
              offset-lg="3"
              class="ion-jusitfy-content-center"
            >
              <ion-searchbar
                placeholder="Bitte Suchbegriff eingeben"
              ></ion-searchbar>
            </ion-col>
          </ion-row>
        </ion-grid>
      </ion-toolbar>
    </ion-header>
    <ion-content fullscreen>
      <ion-grid>
        <ion-row>
          <ion-col size-lg="6" offset-lg="3" class="ion-justify-content-center">
            <ion-list>
              <ion-item lines="none">
                <ion-card class="centeredCard">
                  <ion-card-header>
                    <ion-card-subtitle>
                      Outlet - e.g. Volksverpetzer
                    </ion-card-subtitle>
                    <ion-card-title>Beispielüberschrift</ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-button size="small" color="primary"
                      >Coronavirus</ion-button
                    >
                    <ion-button size="small" color="secondary"
                      >Hurensohn</ion-button
                    >
                    <ion-button size="small" color="tertiary"
                      >Bhakdi</ion-button
                    >
                    <div class="card-text">
                      Keep close to Nature's heart... and break clear away, once
                      in awhile, and climb a mountain or spend a week in the
                      woods. Wash your spirit clean.
                    </div>
                    <ion-button
                      href="https://www.volksverpetzer.de/corona/stanford-ioannidis-covid/"
                      target="_blank"
                      size="big"
                      color="primary"
                      strong
                      expand="full"
                      >Zum Artikel</ion-button
                    >
                  </ion-card-content>
                </ion-card>
              </ion-item>

              <ion-item lines="none">
                <ion-card class="centeredCard">
                  <ion-card-header>
                    <ion-card-subtitle>
                      Outlet - e.g. Volksverpetzer
                    </ion-card-subtitle>
                    <ion-card-title>Beispielüberschrift</ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-button size="small" color="warning"
                      >querdenker</ion-button
                    >
                    <ion-button size="small" color="danger"
                      >Lockdown</ion-button
                    >
                    <ion-button size="small" color="light"
                      >Impfstoff</ion-button
                    >
                    <div class="card-text">
                      Keep close to Nature's heart... and break clear away, once
                      in awhile, and climb a mountain or spend a week in the
                      woods. Wash your spirit clean.
                    </div>
                    <ion-button
                      href="https://www.volksverpetzer.de/corona/stanford-ioannidis-covid/"
                      target="_blank"
                      size="big"
                      color="primary"
                      strong
                      expand="full"
                      >Zum Artikel</ion-button
                    >
                  </ion-card-content>
                </ion-card>
              </ion-item>

              <ion-item lines="none">
                <ion-card class="centeredCard">
                  <ion-card-header>
                    <ion-card-subtitle>
                      Outlet - e.g. Volksverpetzer
                    </ion-card-subtitle>
                    <ion-card-title>Beispielüberschrift</ion-card-title>
                  </ion-card-header>
                  <ion-card-content>
                    <ion-button size="small" color="light"
                      >Impfstoff</ion-button
                    >
                    <ion-button size="small" color="medium">Maske</ion-button>
                    <ion-button size="small" color="dark">MNS</ion-button>
                    <div class="card-text">
                      Keep close to Nature's heart... and break clear away, once
                      in awhile, and climb a mountain or spend a week in the
                      woods. Wash your spirit clean.
                    </div>
                    <ion-button
                      href="https://www.volksverpetzer.de/corona/stanford-ioannidis-covid/"
                      target="_blank"
                      size="big"
                      color="primary"
                      strong
                      expand="full"
                      >Zum Artikel</ion-button
                    >
                  </ion-card-content>
                </ion-card>
              </ion-item>
            </ion-list>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonHeader,
  IonGrid,
  IonRow,
  IonCol,
  IonContent,
  IonPage,
  IonTitle,
  IonToolbar,
  IonSearchbar,
  IonList,
  IonItem,
  IonCard,
  IonCardHeader,
  IonCardSubtitle,
  IonCardContent,
  IonCardTitle,
  IonButton,
} from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
  components: {
    IonHeader,
    IonGrid,
    IonRow,
    IonCol,
    IonContent,
    IonPage,
    IonTitle,
    IonToolbar,
    IonSearchbar,
    IonList,
    IonItem,
    IonCard,
    IonCardHeader,
    IonCardSubtitle,
    IonCardContent,
    IonCardTitle,
    IonButton,
  },
});
</script>

<style scoped>
.centeredCard {
  margin-left: auto;
  margin-right: auto;
}
.list-md {
  background: transparent;
}
ion-item {
  --background: transparent;
}
ion-searchbar {
  padding-left: 16px;
  padding-right: 16px;
  --icon-color: #121212;
  --placeholder-color: #121212;
  --color: #121212;
}
.card-text {
  margin-top: 16px;
  margin-bottom: 16px;
}
</style>