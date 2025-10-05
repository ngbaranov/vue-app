<script setup>
import {ref} from "vue";
const currentDate = ref(new Date().toLocaleDateString());
</script>

<template>
<div>Текущая дата: {{currentDate}}</div>
</template>

<style scoped>

</style>
