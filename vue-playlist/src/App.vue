<template>
  <div id="app">
    <app-header></app-header>
    <users></users>
    <app-footer></app-footer>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
//局部
import users from './components/users'
import Header from './components/Header'
import Footer from './components/Footer'
export default {
  name: 'App',
  data(){
    return{
      title:'这是我的第一个Vue脚手架!'
    }
  },
  components:{
    'users':users,
    'app-header':Header,
    'app-footer':Footer
  }
}
</script>

<style scoped>
h1{
  color:green;
}
</style>
