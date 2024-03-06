<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('KUKU')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Blazzer Mid Suede"
      :price="1200"
      :is-favorite="true"
      :on-click-add="onClickAdd"
    />
  </div>
</template>
