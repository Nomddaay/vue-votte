<template>
    <v-app-bar color="black" class="px-8">
        <v-btn class="logo">
            VOTTE
        </v-btn>

        <v-spacer></v-spacer>
        <v-text-field ></v-text-field>
    </v-app-bar>
    <v-app-bar app color="#eb4343">
        <v-btn>SONGS</v-btn>
        <v-btn>SPORTS</v-btn>
        <v-btn>MOVIES</v-btn>
        <v-btn>BOOKS</v-btn>
        <v-btn>BLOGS</v-btn>
    </v-app-bar>
</template>

<script setup>

</script>

<style>
.logo {
    font-size: 20px;
    font-weight: 700;
}

.logo:hover {
    cursor: pointer;
}
</style>