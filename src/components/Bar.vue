<template>
    <div class="hello">
        <div class="container">
            <h2>{{ msg }}</h2>
        </div>
        <div class="navigation">
            <router-link to="/foo"><span class="glyphicon glyphicon-arrow-left"></span></router-link>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'bar',
        data () {
            return {
                msg: 'Welcome to Your Bar.js App'
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1, h2 {
      font-weight: normal;
    }
</style>
