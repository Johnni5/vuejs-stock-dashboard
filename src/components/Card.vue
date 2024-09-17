<template>
  <div class="card">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Card-component',
};
</script>

<style scoped>
  .card {
    width: 90%;
    background-color: #001f35;
    border-radius: 16px;
    padding: 24px 32px;
  }
</style>
