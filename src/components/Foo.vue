<template>
    <div class="hello">
        <div class="container">
            <h2>{{ msg }}</h2>
        </div>
        <div class="navigation">
            <router-link to="/bar"><span class="glyphicon glyphicon-arrow-right"></span></router-link> &nbsp; &nbsp;
            <router-link to="/"><span class="glyphicon glyphicon-arrow-left"></span></router-link>
        </div>
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
