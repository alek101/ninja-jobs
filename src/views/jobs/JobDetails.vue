<template>
  <h1>Job Details Page</h1>
  <p>The Job id is {{ $route.params.id}}</p>
</template>

<script>
export default {
    props: ['id'],
    //becuase we accepted props in router, as props:true, now we can use props insted of data
    // data() {
    //     return {
    //         id: this.$route.params.id
    //     }
    // }
}
</script>

<style>

</style>