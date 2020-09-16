<template>
	<div class="card">
		<div class="col-span-1 items-center justify-center">
			<div class="card bg-white rounded overflow-hidden shadow-md">
				<div class="image bg-green-700 h-48"></div>
				<div class="preview flex flex-col p-4">
					<div class="tags mt-2 mb-2">
						<a href="" class="px-2 py-1 bg-green-700 rounded text-white">
							Javascript
						</a>
					</div>
					<div class="preview__content my-2 flex items-center justify-center">
						<p class="text-lg text-gray-700 font-medium">Tutorial Laravel Sanctum dan Vue JS Authentication - Menampilkan Halaman Dashboard</p>
					</div>
					<div class="footer border-t border-solid border-gray-400 mt-2 pt-3 flex">
						<div class="profile__img mr-3">
							<img src="~assets/image/profile.jpg" alt="" class="rounded-full h-10 w-10">
						</div>
						<div class="author__name flex items-center">
							<p class="text-lg">Erlangga</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'CardArticle'
}
</script>

<style scoped>
	.card {
		font-family: 'Quicksand', sans-serif;
	}
</style>