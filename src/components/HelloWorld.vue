<script setup>
import { ref } from "vue"

const count = ref(0)

function increment(){
  count.value++
}
</script>

<template>
  <p>{{ count }}</p>
  <button @click="increment">click me!</button>
</template>
