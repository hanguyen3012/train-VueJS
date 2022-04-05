<template>
  <div>
      <input type="text" :value="name"/>
  </div>
</template>

<script>
export default {
   name: "Input",
      data() {
       return {
           name: ""
       }
   }
}
</script>

<style>

</style>