<template>
  <div>
    <h2>News-Content [{{$route.params.id}}]</h2>
    <ul>
      <li><a href="/">Home</a></li>
    </ul>
  </div>
</template>
<style>

</style>
<script>
    export default{
        data(){
            return {}
        },
        components: {},
        mounted: function () {

        },
        methods: {},
        validate ({ params }) {
          // Must be a number
          return /^\d+$/.test(params.id)
        }
    }
</script>
