<template>
	<div>
		{{animal}}
		<button v-on:click="$emit('party-event')">Click me</button>
	</div>
</template>

<script>
export default {
	props: ['animal']
}
</script>


<style scoped>
div {
	background-color: pink;
}
</style>
