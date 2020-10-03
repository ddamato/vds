<template functional>
  <button v-bind="data.attrs" v-on="listeners"><slot/></button>
</template>

<style scoped>
  button {
    background-color: blue;
    color: white;
  }
</style>