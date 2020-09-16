<template>
	<div class="col-span-1 flex flex-col items-center justify-center">
		<div class="image flex items-center justify-center mb-3">
			<img v-bind:src="img" alt="" class="h-24">
		</div>
		<div class="desc flex items-center justify-center">
			<p class="text-center">{{ text }}</p>
		</div>
	</div>
</template>

<script>
export default {
	name: 'ListIcon',
	props: ['img', 'text']
}
</script>