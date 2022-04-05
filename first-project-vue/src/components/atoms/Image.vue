<template>
  <div>
      <img :src="url"/>
  </div>
</template>

<script>
export default {
   name: "Image",
   data() {
       return{
           url: ""
       }
   }
}
</script>

<style>

</style>