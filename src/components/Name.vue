<template>
  <div>
    <h3>{{name}}</h3>
  </div>
</template>

<script>
  export default{
    name: 'Name',
    props: ['name']
  }
</script>

<style>
  h3{
    color: #80CBC4;
  }
</style>