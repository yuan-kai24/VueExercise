<template>
	<footer>
		<p>{{title}}</p>
	</footer>
</template>

<script>
export default {
  name: 'app-footer',
  props:{
  	title:{
  		type:String
  	}
  },
  data () {
    return {
    	
    }
  }
}
</script>


<style scoped>
footer{
	background:#222;
	padding: 10px;
}
p{
	color: lightgreen;
	text-align: center;
}

</style>
