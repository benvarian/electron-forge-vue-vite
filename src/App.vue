<template>
    <navbar />
    <RouterView />
</template>

<script setup>
import navbar from './components/navbar.vue'
import { RouterView } from 'vue-router';
</script>
