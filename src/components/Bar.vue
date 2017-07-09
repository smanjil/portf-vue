<template>
    <div class="hello">
        <h1>{{ msg }}</h1>

        <router-link to="/foo"> <<<< </router-link>
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
