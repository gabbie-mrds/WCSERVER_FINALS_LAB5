
<template>
    <div class = 'gallery'>
        <div id = "container">
        <div class = "alert alert-primary" role = "alert">
            <br>
            <h3>{{ msg }}</h3>
            <p>Meet these cuties that you may give a new shelter!</p>
            <div class = "row">
                <div class = "col"><img src = "../assets/corgi.png"></div>
                <div class = "col"><img src = "../assets/cat.png"></div>
                <div class = "col"><img src = "../assets/dog2.png"></div>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'gallery',
  data () {
    return {
      msg: 'This is the Gallery Section',
      author: 'By: Gabrielle Delos Santos'
    }
  }
}
</script>

<style scoped>
</style>
