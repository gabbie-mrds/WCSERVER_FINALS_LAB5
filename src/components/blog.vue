
<template>
    <div class = 'blog'>
        <div id = "container">
        <div class = "alert alert-primary" role = "alert">
            <br>
            <h3>{{ msg }}</h3>
            <p>Let's talk about dogs! <br> Dogs are considered as man's best friend as they give unconditional love and companionship to us humans. <br> And with that we get to build this special relationship with them. And even for better or for worse, they are always there for us!</p>
            <h4>{{author}}</h4>
        </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'blog',
  data () {
    return {
      msg: 'This is the Blog Section',
      author: 'By: Gabrielle Delos Santos'
    }
  }
}
</script>

<style scoped>
</style>
