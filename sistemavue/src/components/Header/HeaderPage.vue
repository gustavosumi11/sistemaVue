<template>
    <div id="nav">
        <nav> 
        <router-link id ="home" to="/">Home</router-link>
        <router-link id= "login" to="../../pages/Login">Login</router-link>
    </nav>
    </div>
</template>
<script>
export default {
    name: 'HeaderPage',
    props: {

    }
}
</script>


<style>
@import 'HeaderPage.css';
</style>
