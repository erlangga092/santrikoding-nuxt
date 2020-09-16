<template>
	<main class="set w-full bg-gray-300">
		<HeaderSection 
			text="TUTORIAL SET"
			descOne="Kumpulan rangkaian tutorial teknologi tertentu untuk mempermudah"
			descTwo="kamu belajar koding dengan cepat dan terstruktur"
		/>
		<section class="px-8 pt-4 pb-16 grid grid-cols-4 gap-8 justify-center md:grid-cols-2 lg:grid-cols-3 sm:grid-cols-1">
			<CardSet />
			<CardSet />
			<CardSet />
			<CardSet />
			<CardSet />
			<CardSet />
			<CardSet />
			<CardSet />
		</section>
	</main>
</template>

<script>
import HeaderSection from '../Items/HeaderSection';
import CardSet from './CardSet';

export default {
	name: 'TutorialSet',
	components: {
		'HeaderSection': HeaderSection,
		'CardSet': CardSet
	}
}
</script>

<style scoped>
	.set {
		font-family: 'Quicksand', sans-serif;
	}
</style>