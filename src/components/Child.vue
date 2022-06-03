<template>
  <!-- <h1>{{data}}</h1> -->
  <!-- <slot><h1>Child components</h1></slot> -->
  <!-- <slot><h1>Default Data</h1></slot>
    <slot><h1>Default Data</h1></slot>
    <slot><h1>Default Data</h1></slot> -->

  <!-- multiple slots -->
  <div class="divs">
    <header>
      <slot name="header"></slot>
    </header>
    <content>
      <slot name="main"></slot>
    </content>
    <footer>
      <slot name="footer"><button>Click me</button></slot>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Child-page",
  //   props:{
  //       data:String
  //   }
};
</script>
<style scoped>
.divs{
    border: 1px solid;
    width: 170px;
    text-align: center;
    padding:20px
}
</style>