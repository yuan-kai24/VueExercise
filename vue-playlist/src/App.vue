<template>
  <div id="app">
    <h1>{{title}}</h1>
    <users></users>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
//局部
import users from './components/users'

export default {
  name: 'App',
  data(){
    return{
      title:'这是我的第一个Vue脚手架'
    }
  },
  components:{
    'users':users
  }
}
</script>

<style>
h1{
  color:green;
}
</style>
