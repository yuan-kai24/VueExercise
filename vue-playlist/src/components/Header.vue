<template>
	<header>
		<h1>{{title}}</h1>
	</header>
</template>

<script>
export default {
  name: 'app-header',
  data () {
    return {
    	title:"vue .js demo"
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
