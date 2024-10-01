
<template>
    <div class = 'about'>
        <div id = "container">
        <div class = "alert alert-primary" role = "alert">
            <br>
            <h3>{{ msg }}</h3>
            <p>We've been in the market since the year 2018. We have been able to give the pets from us a better shelter <br> and the best owners they can have! We also make sure that before we give them a better owner, we keep them healthy and love them like as our own.</p>
            <h4>{{author}}</h4>
        </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'This is the About Section',
      author: 'By: Gabrielle Delos Santos'
    }
  }
}
</script>

<style scoped>
</style>
