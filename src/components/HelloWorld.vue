<script setup lang="ts">
defineProps<{
  nickname: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="primary">{{ nickname }}</h1>
    <h3>
      Cute programmer changes the world.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
  font-family: Lobster;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
