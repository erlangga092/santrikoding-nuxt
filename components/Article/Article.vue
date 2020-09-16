<template>
	<main class="w-full bg-gray-300 px-2 py-2 pb-16 border-transparent">
		<section class="header w-full flex items-center">
			<h4 class="text-2xl font-medium p-4 text-gray-700">
				ARTIKEL TERBARU
			</h4>
		</section>
		<section class="article w-full grid grid-cols-3 justify-between gap-8 px-4 box-border md:grid-cols-2 sm:grid-cols-1">
			<div class="col-span-2 grid grid-cols-2 items-center justify-between box-border gap-8 sm:grid-cols-1 sm:col-span-1">
				<CardArticle />
				<CardArticle />
				<CardArticle />
				<CardArticle />
			</div>
			<div class="col-span-1 md:col-span-2 sm:col-span-1">
				<Kategori />
				<Tags />
			</div>
		</section>
	</main>
</template>

<script>
import CardArticle from './CardArticle';
import Kategori from './Kategori';
import Tags from './Tags';

export default {
	components: {
		'CardArticle': CardArticle,
		'Kategori': Kategori,
		'Tags': Tags
	},
	name: 'Article'
}
</script>