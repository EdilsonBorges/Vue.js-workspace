<template>
  <div class="users">
      <h1>Users</h1>
      <ul>
        <li v-for="user in users">{{user.name}}: {{user.email}}</li>
      </ul>
  </div>
</template>

<script>
  export default {
    name: 'users',
    data () {
      return {
        users: [
          {
            name: 'John Doe',
            email: 'jdoe@gmail.com',
            contacted: false
          },
          {
            name: 'Steve smith',
            email: 'ssmith@gmail.com',
            contacted: false
          },
          {
            name: 'Tom White',
            email: 'tomwhite@gmail.com',
            contacted: false
          }
        ]
      }
    },
    methods: {

    }
}
</script>

<style scoped>

</style>
