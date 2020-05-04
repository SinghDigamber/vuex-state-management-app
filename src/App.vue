<template>
  <div class="container">
    <AddUser />
    <Users />
  </div>
</template>

<script>
import AddUser from '../src/components/AddUser'
import Users from '../src/components/Users'

export default {
  name: 'App',
  components: {
    AddUser,
    Users
  }
}
</script>

<style>
  .container {
    max-width: 500px;
    padding-top: 50px;
  }
</style>