<template>
  <div class = "home">
    <div id = "container">
      <div class = "alert alert-primary" role = "alert">
        <br>
        <h3>{{ msg }}</h3>
        <p>Welcome to our Online Shop! <br> Please feel free to check what we may offer to you.</p>
        <h4>{{author}}</h4>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'This is the Home Section',
      author: 'By: Gabrielle Delos Santos'
    }
  }
}
</script>

<style scoped>
</style>
