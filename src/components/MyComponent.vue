<template>
  <div>
    <h3>{{msg}}</h3>
  </div>
</template>

<script>
  export default{
    name: 'MyComponent',
    props: {
      msg: String
    }
  }
</script>

<style>
  h3{
    color: #80CBC4;
  }
</style>