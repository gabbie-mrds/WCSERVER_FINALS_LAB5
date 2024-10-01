
<template>
    <div class = 'contact'>
        <div id = "container">
        <div class = "alert alert-primary" role = "alert">
            <br>
            <h3>{{ msg }}</h3>
            <p> If you have inquiries <br><br> You may contact us through calling: <br> 0918-967-2000 <br><br> You may email us through: <br> petshop.gmailcom <br><br> Or you may visit us: <br> SM Clark </p>
            <h4>{{author}}</h4>
        </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'contact',
  data () {
    return {
      msg: 'This is the Contact Section',
      author: 'By: Gabrielle Delos Santos'
    }
  }
}
</script>

<style scoped>
</style>
