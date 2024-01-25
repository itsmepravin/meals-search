<template>
    Home Page
    <p>{{ meals }}</p>
</template>

<script setup>
import { computed } from "vue"
import store from "../store";

const meals = computed(() => store.state.meals)
</script>