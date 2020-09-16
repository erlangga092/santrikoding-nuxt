<template>
	<div class="section__head">
		<section class="header p-8 flex flex-col items-center justify-center">
			<div class="title flex items-center justify-center mb-4">
				<h3 class="text-3xl font-medium text-center">
					{{ text }}
				</h3>
			</div>
			<div class="desc flex items-center justify-center">
				<p class="text-center text-xl">
					{{ descOne }}
				</p>
			</div>			
			<div class="desc flex items-center justify-center mb-2">
				<p class="text-center text-lg">
					{{ descTwo }}
				</p>
			</div>
		</section>
	</div>
</template>

<script>
export default {
	name: 'HeaderSection',
	props: ['text', 'descOne', 'descTwo']
}
</script>

<style scoped>
	.section__head {
		font-family: 'Quicksand', sans-serif;
	}
</style>