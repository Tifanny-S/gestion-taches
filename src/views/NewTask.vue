<template>
    <v-container>
        <v-row>
            <v-btn color="#E5E7EB" link :to="{path: '/'}">Reout à la liste</v-btn>
        </v-row>
        <v-row>
            <h2>Modifier une tâche</h2>
            <v-form class="form">
            <v-text-field label="name"></v-text-field>
            <v-text-field label="Description"></v-text-field>
            <v-select label="Statut"></v-select>
            <v-btn type="submit">Annuler</v-btn>
            <v-btn type="submit" color="primary">Enregistrer</v-btn>
            </v-form>
        </v-row>
    </v-container>
</template>

<script>
export default {
  name: 'TaskDetails',
}

</script>

<style>
.form {
    width: 100%;
    margin-top: 30px;
}

h2 {
    margin-top: 30px;
}
</style>