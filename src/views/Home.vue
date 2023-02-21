<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>

  <div class="card">
    <h1>home</h1>
    <p>
      new home
    </p>
  </div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
