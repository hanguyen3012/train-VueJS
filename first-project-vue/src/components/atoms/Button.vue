<template>
  <div>
      <button @click="submit" :value="name"></button>
  </div>
</template>

<script>
export default {
   name: "Button",
   data() {
       return {
           submit:"",
           name:""
       }
   }
}
</script>

<style>

</style>