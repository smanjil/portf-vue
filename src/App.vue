
<template>
    <div id="app">
        <!-- <img src="./assets/logo.png"> -->
        <router-view></router-view>
    </div>
</template>

<script>
    export default {
        name: 'app'
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: white;
        margin-top: 60px;
    }

    .navigation{
        position: absolute;
        bottom: 0;
        width: 100%;
        /* Set the fixed height of the footer here */
        height: 50px;
        background-color: black;
        opacity: 0.3;
    }

    .navigation span{
        line-height: 1.5em;
        color: grey;
        font-size: 30px;
    }
</style>
