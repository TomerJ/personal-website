<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>👋 Hey there!</h1>

  <div class="card">
    <p>
      I am Tomer, a hobby Full-Stack Typescript developer. I enjoy designing & integrating UI/UX for personal and community projects.
    </p>
    <p>
      I usually do my front-end work with Vue.js and tailwindcss and write back-end code using Node.js along with TypeScript.
    </p>
  </div>

  <div class="card">
    <h2>📡 Past Work</h2>
    <div>
      <h4>
        Dynasty Airlines
      </h4>
      <p>
        I have created a suite of automated tools for a Roblox roleplay airline. Features include an automatic group ranking system, 
      </p>
    </div>
  </div>
  
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
