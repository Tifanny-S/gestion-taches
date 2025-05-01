<template>
    <div class="cards">
        <v-card>
            <v-card-title>Nom de la tâche</v-card-title>
            <v-card-subtitle>Etat</v-card-subtitle>
            <v-card-text>Détails</v-card-text>
            <v-card-text>Crée le 01/05/2025</v-card-text>
        </v-card>
    </div>
</template>

<script>
export default {
  name: 'TasksCard',
}

</script>

<style>
.cards {
    margin-top: 5%;
    margin-left: 10%;
    width: 50%;
    border-left: 5px solid #3B82F6;
}
</style>