<script setup>
import Card from './Card.vue'
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Blazzer Mid Suede"
      :price="1200"
    />
    <Card />
    <Card />
    <Card />
  </div>
</template>
