<template>
		<svg v-if="name" aria-hidden="true">
			<use :xlink:href="`#gulu-${name}`"></use>
		</svg>
</template>

<script>
import './svg.js'
	export default {
		name:'icon',
		props:{
			name:{}
		}
	}
</script>

<style scoped>

</style>