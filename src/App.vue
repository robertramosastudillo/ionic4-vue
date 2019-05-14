<template>
  <ion-app>
    <ion-toolbar color="dark">
      <ion-buttons slot="secondary">
        <ion-button><ion-icon name="logo-ionic"></ion-icon></ion-button>
      </ion-buttons>
      <ion-title>Robert Ramos - IonicVue</ion-title>
    </ion-toolbar>
    <!--<div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>-->
    <ion-content color="dark">
      <router-view/>
    </ion-content>
  </ion-app>
</template>
