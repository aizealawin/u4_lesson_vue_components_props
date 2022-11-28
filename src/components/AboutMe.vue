<template>
  <div>
    <h4>{{msg}}</h4>
  </div>
</template>

<script>
  export default{
    name: 'AboutMe',
    props: {
      msg: String
    }
  }
</script>

<style>
  h4{
    color: #80CBC4;
  }
</style>