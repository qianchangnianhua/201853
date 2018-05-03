<template>
  <div class="hello">
   {{msg}}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- 内置了一个样式 -->
<style scoped>
	.hello{
		background: red;
	}
</style>
