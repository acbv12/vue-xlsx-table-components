<template>
    <div id="app">
        <div>a simple demo for excel upload</div>
        <vueXlsxTable @on-select-file="handle">上传excel</vueXlsxTable>
    </div>
</template>

<script>
import vueXlsxTable from './components/vue-xlsx-table'
export default {
    components: {
        vueXlsxTable
    },
    name: 'app',
    data () {
        return {
            msg: 'Welcome to Your Vue.js App'
        }
    },
    methods: {
        handle: function(a){
            console.log(a);
        }
    }
}
</script>

<style lang="scss">
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

h1, h2 {
    font-weight: normal;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}
</style>
