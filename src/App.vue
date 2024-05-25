<script setup>
import { RouterView } from "vue-router";
import Header from "./components/Header.vue";
</script>

<template>
    <div class = "app">
        <Header />
        <RouterView />
    </div>
</template>

<style scoped>
.app {
    background: #a6c3d4;
    min-height: 100vh;
}
</style>
