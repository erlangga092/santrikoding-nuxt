<template>
	<footer class="w-full bg-white">
		<section class="h-1 w-full bg-red-500"></section>
		<section class="bg-white w-full grid grid-cols-7 gap-8 justify-evenly px-4 py-12 overflow-hidden lg:grid-cols-3 sm:grid-cols-2">
			<div class="col-span-3 lg:col-span-3 sm:col-span-2">
				<div class="">
					<div class="logo flex items-center mb-4">
						<h1 class="font-medium text-2xl">SANTRI KODING</h1>
					</div>
					<div class="pesan flex flex-wrap items-center">
						<p class="text-base">
							Belajar koding bahasa Indonesia terlengkap dan mudah dipahami seperti Laravel, Codeigniter, Rails, Vue JS, Javascript dan masih banyak lagi
						</p>
					</div>
				</div>
			</div>
			<div class="col-span-1 lg:col-span-1">
				<Informasi />
			</div>
			<div class="col-span-1 lg:col-span-1">
				<Resource />
			</div>
			<div class="col-span-2 lg:col-span-1">
				<Contact />
			</div>
		</section>
	</footer>
</template>

<script>
import Informasi from './Informasi';
import Resource from './Resource';
import Contact from './Contact';

export default {
	name: 'Footer',
	components: {
		'Informasi': Informasi,
		'Resource': Resource,
		'Contact': Contact
	}
}
</script>

<style scoped> 
	footer {
		font-family: 'Quicksand', sans-serif;
	}
</style>