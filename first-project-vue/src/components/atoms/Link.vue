<template>
  <div><a :href="url">{{name}}</a></div>
</template>

<script>
export default {
    name: "Link",
    data(){
        return{
            url: "",
            name: "",
        }
    }
}
</script>

<style>

</style>