<template>
	<div class="tags">
		<div class="card__category p-6 shadow-md bg-white border-solid border-gray-400">
			<div class="header__card text-lg border-b border-solid border-gray-400 pt-0 py-3">
				<h4 class="text-gray-700 font-medium text-2xl">TAGS</h4>
			</div>
			<div class="category grid grid-cols-1 mt-4 gap-4 text-lg">
				<div class="col-span-1 bg-gray-100 p-4 shadow">
					<h4>Adonis JS</h4>
				</div>
				<div class="col-span-1 bg-gray-100 p-4 shadow">
					<h4>Codeigniter</h4>
				</div>
				<div class="col-span-1 bg-gray-100 p-4 shadow">
					<h4>Laravel</h4>
				</div>
				<div class="col-span-1 bg-gray-100 p-4 shadow">
					<h4>Vue JS</h4>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Tags'
}
</script>

<style scoped>
	.tags {
		font-family: 'Quicksand', sans-serif;
	}
</style>