<script setup>
import PostItem from "./components/PostItem.vue";
import MainHeader from "./components/MainHeader.vue";
</script>

<template>
  <MainHeader />
  <div class="container">
    <PostItem />
  </div>
</template>

<style scoped>
.container {
  display: flex;
  margin: 0 auto;
  max-width: 600px;
}
</style>
