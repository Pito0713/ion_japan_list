<template lang="pug">
div(class='flex justify-center items-center flex-col')
  a TextPage
  div
    input(placeText= 'asd' v-model="fileInput" )
    Button click
  Card(:msg="{fileInput}")
</template>

<script setup>
import { ref, reactive, onMounted, watch, computed } from 'vue'
import Card from '../../components/Card.vue'
const fileInput = ref(null);

watch(fileInput, (newVal, oldVal) => {
  console.log(newVal);
});
</script>