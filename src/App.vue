<template>
  <div class="name">{{ name }}</div>
  <button class="btn btn-primary" v-on:click="consoleLog">
  Click
  </button>
</template>

<script>
export default ({
  setup() {
    const name = 'Kim jiae';

    // const greeting = (name) => {
    //   return 'Hello, ' + name;
    // }

    // const greet = greeting(name);

    const consoleLog = () => {
      console.log('hello world');
    };

    return {
      name,
      consoleLog,
    };
  },
})
</script>

<style scoped>
  .name {
    color:blue;
  }
</style>