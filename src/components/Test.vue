<template>
  <div class="test">
      <h1>{{title}}</h1>
      <p>{{user.firstName}}</p>
  </div>
</template>

<script>
    export default {
      name: 'test',
      data () {
        return {
          title: 'Hello World',
          user: {
            firstName: 'John',
            lastName: 'Doe'
          }
        }
      }
    }
</script>

<style scoped>

</style>
