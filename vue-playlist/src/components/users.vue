<template>
  <div id="users">
    <h1>hello users</h1>
    <ul>
      <li v-for="user in users">
        {{user}}
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'users',
  data(){
    return{
      users:["aa", "bb", "cc"]
    }
  }
}
</script>

<style>
h1{
  color:purple;
}

</style>
