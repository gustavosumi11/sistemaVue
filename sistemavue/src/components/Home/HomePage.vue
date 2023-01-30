<template>
<div id="page">
<h2>Café </h2>
<div id="imgPrincipal">
    <img :src= "info"  />
</div>

</div>
</template>
<script>
import axios from 'axios';
    export default {
        name: 'HomePage',
        data() {
            return{ 
                info:null
            }
        },
        mounted() {
        axios
        .get('http://localhost:8080/random.json')
        .then(response =>this.info = response.data.file)
    }
    }
   
</script>
<style>
    @import 'HomePage.css';
</style>