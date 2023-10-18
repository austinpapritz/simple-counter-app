<template>
    <div>
      <h1>Simple Counter</h1>
      <p>{{ count }}</p>
      <button @click="increment">Increment</button>
      <button @click="decrement">Decrement</button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        count: 0,
      };
    },
    methods: {
      increment() {
        this.count++;
      },
      decrement() {
        this.count--;
      },
    },
  };
  </script>
  
  <style scoped>
  /* Add any styles you want here. */
  </style>
  