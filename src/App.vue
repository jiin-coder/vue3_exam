<template>
  <div class="name">{{ name }}</div>
  <div>Hi</div>
</template>

<script>
export default ({
  setup() {
    const name = 'Kim jiae';

    return {
      name
    }
  },
})
</script>

<style scoped>
  .name {
    color:blue;
  }
</style>