<template>
    <Child>
        <template v-slot:header> 
            <h1>Vuejs</h1>
        </template>
        <template v-slot:main> 
            <p>A vue js product</p>
        </template>
        <template v-slot:footer> 
            <button>Buy now</button>
        </template>
    </Child>
     <Child>
        <template v-slot:header> 
            <h1>Angular</h1>
        </template>
        <template v-slot:main> 
            <p>A Angularproduct</p>
        </template>
        <template v-slot:footer> 
            <!-- <button>Buy now</button> -->
        </template>
    </Child>
    <!-- <Child data="vijay mane"/> -->
    <!-- <Child><h1>Welcome to Bangalore</h1></Child>
    <Child><a href="">Welcome</a></Child>
    
    <Child><img src="../assets/download.png" ></Child>
     -->
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