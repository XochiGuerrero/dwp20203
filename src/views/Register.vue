<template>
    <ion-card>
        <ion-card-header>
            <ion-card-subtitle>Datos personales</ion-card-subtitle>
            <ion-card-title>Registro de usuarios</ion-card-title>
        </ion-card-header>
        <ion-card-content>
            <ion-item>
                <ion-label position="floating">Nombre</ion-label>
                <ion-input name="nombre"></ion-input>
            </ion-item>
            <ion-item>
                <ion-label position="floating">Email</ion-label>
                <ion-input name="email"></ion-input>
            </ion-item>
            <ion-item>
                <ion-label position="floating">Username</ion-label>
                <ion-input name="Username"></ion-input>
            </ion-item>
            <ion-item>
                <ion-label position="floating">Password</ion-label>
                <ion-input name="Password"></ion-input>
            </ion-item>
            <ion-item>
                <ion-label position="floating">Confirm Password</ion-label>
                <ion-input name="password2"></ion-input>
            </ion-item>
            <IonButton expand="block" color="primary" @click="onRegistrarClick()">Registrar</IonButton>
        </ion-card-content>
    </ion-card>
</template>
<script lang="ts">
import { alertController, IonButton } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'Register',
    components: {
        IonButton
    },
    methods: {
        async onRegistrarClick() {
            const alert = await alertController
                .create({
                    header: 'Alert',
                    message: 'Se ha registrado con exito',
                    buttons: ['OK'],
                });
            return alert.present();
        }
    }
});
</script>