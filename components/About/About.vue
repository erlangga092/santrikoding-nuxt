<template>
	<main class="about w-full bg-white flex items-center justify-center py-6">
		<section class="bg-white grid grid-cols-1 mb-4">
			<div class="header col-span-1 flex items-center justify-center">
				<h3 class="text-3xl text-gray-700 font-medium text-center">
					JUST REMINDER
				</h3>
			</div>
			<div class="avatar flex items-center justify-center">
				<div class="image py-4">
					<img src="~/assets/image/pram.png" alt="" class="image__remind h-48 w-48 rounded-full shadow bg-cover center">
				</div>
			</div>
			<div class="quote flex flex-col items-center justify-center py-2">
				<p class="text-xl font-semibold text-gray-700 mb-2">
					"Sudah Harus Adil Sejak Dalam Pikiran"
				</p>
				<p class="text-xl font-medium text-gray-700 italic">
					-- Pramoedya Ananta Toer --
				</p>
			</div>
		</section>
	</main>
</template>

<script>
export default {
	name: 'About'
}
</script>

<style scoped>
	.about {
		font-family: 'Quicksand', sans-serif;
	}
</style>