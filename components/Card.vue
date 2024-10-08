<template lang="pug">
div(class="bg-white text-black p-4 border-2 rounded-md w-1/2 min-h-64")
  a {{ (props.msg.fileInput) }}
</template>

<script setup>
import { ref, reactive, onMounted, watch, computed } from 'vue'
const props = defineProps({
  msg: Object
})

</script>