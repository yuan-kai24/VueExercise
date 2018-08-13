<template>
	<footer>
		<p>{{copyright}}</p>
	</footer>
</template>

<script>
export default {
  name: 'app-footer',
  data () {
    return {
    	copyright:"Copyright 2018 vue Demo"
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
