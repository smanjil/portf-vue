<template>
    <div class="hello">
        <h1>{{ msg }}</h1>

        <router-link to="/bar"> >>>> </router-link> &nbsp; &nbsp;
        <router-link to="/"> <<<< </router-link>
    </div>
</template>

<script>
    export default {
        name: 'foo',
        data () {
            return {
                msg: 'Welcome to Your Foo.js App'
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
