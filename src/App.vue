<template>
  <div class="name">{{ greet }}</div>
</template>

<script>
export default ({
  setup() {
    const name = 'Kim jiae';

    const greeting = (name) => {
      return 'Hello, ' + name;
    }

    const greet = greeting(name);

    return {
      greet
    }
  },
})
</script>

<style scoped>
  .name {
    color:blue;
  }
</style>