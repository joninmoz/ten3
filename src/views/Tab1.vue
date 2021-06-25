<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Files</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-grid>
        <ion-row>
          <ion-col size="6">
            <img src="../../static/cat.jpg"><br>
            This is a cat 
          </ion-col>
          <ion-col>
            <img src="../../static/family.jpg"><br>
            This is a family
          </ion-col>
        </ion-row>
      </ion-grid>
      
    
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default  {
  name: 'Tab1',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}


</script>