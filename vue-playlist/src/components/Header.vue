<template>
	<header>
		<h1 @click="changeTitle">{{title}}</h1>
	</header>
</template>

<script>
export default {
  name: 'app-header',
  props:{
  	title:{
  		type:String
  	}
  },
  data () {
    return {
    }
  },
  methods:{
  	changed:function ()
  	{
  		this.title = "改变"
  	},
  	changeTitle:function (){
  		this.$emit("titleChanged","子向父组件传值")
  	}
  }
}
</script>


<style scoped>
header{
	background:lightgreen;
	padding: 10px;
}
h1{
	font-size: 24px;
	text-align: center;
	color: white;
}

</style>
