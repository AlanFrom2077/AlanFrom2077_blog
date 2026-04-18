<script setup>
import { ref } from 'vue'

const sum = ref(0)
function add1(){
  sum.value += 1
}
const content = 'click me +1'
</script>

<template>
  <p>{{ sum }}</p>
  <button @click="add1()">{{ content }}</button>
</template>
