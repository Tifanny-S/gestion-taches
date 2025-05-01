<template>
    <v-container>
        <v-row justify="center">
            <v-col cols="auto">
                <v-btn color="primary" class="addTaskBtn" link :to="{path: '/tache'}">Ajouter une nouvelle tâche</v-btn>
            </v-col>
        </v-row>
        <v-row justify="center">
            <v-col cols="auto">
                <v-btn color="#E5E7EB" size="small">Toutes</v-btn>
            </v-col>
            <v-col cols="auto">
                <v-btn color="#E5E7EB" size="small">En attentes</v-btn>
            </v-col>
            <v-col cols="auto">
                <v-btn color="#E5E7EB" size="small">En cours</v-btn>
            </v-col>
            <v-col cols="auto">
                <v-btn color="#E5E7EB" size="small">Terminés</v-btn>
            </v-col>
            <v-col cols="auto">
                <v-btn color="#E5E7EB" size="small">Bloqués</v-btn>
            </v-col>
        </v-row>
        <TasksCard />
    </v-container>
</template>

<script>
import TasksCard from '@/components/TasksCard.vue'

export default {
  name: 'TaskList',
  components: {
    TasksCard
  }
}
</script>

<style>
.addTaskBtn {
    margin-left: 10%;
    margin-bottom: 30px;
}

</style>