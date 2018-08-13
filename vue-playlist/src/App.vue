<template>
  <div id="app">
    <app-header v-bind:title="title"></app-header>
    <users v-bind:users="users"></users>
    <users v-bind:users="users"></users>
    <app-footer v-bind:title="title"></app-footer>

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
      users:[
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
        {name:"Henry",position:"Web开发",show:false},
      ],
      title:"  传递值非引用"
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
