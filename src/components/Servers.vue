<template>
<div>

    <v-card
        max-width="344" class="mx-auto serverCards" v-for="index in 5" :key = "index">
        <v-card-title>Server #{{ index }}</v-card-title>
        <v-card-text>Info for server # {{ index }}</v-card-text>
    </v-card>

</div>
</template>

<script>

</script>

<style scoped>
.serverCards {
    color: #f1c031;
    margin: 3%;
    background-color: #f2f2f2;
}
</style>
