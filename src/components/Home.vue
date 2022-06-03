<template>
    <h1>Slots in vue js</h1>
    <Child></Child>
    <!-- <Child data="vijay mane"/> -->
    <Child><h1>Welcome to Bangalore</h1></Child>
    <Child><a href="">Welcome</a></Child>
    
    <Child><img src="../assets/download.png" ></Child>
    
</template>

<script>

import Child from './Child.vue'

export default{
    name: "Home-page",
    components:
    {
    Child,
  
}
}
</script>

<style>
h1{
    color: orange;
}
</style>