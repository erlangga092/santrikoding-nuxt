<template>
	<main class="list__box w-full bg-white pb-16">
		<HeaderSection 
			text="BELAJAR APA HARI INI ?"
			descOne="Artikel berdasarkan kategori tertentu untuk mempermudah kamu belajar koding secara"
			descTwo="terstruktur dan terarah"
		/>
		<section class="p-2 grid grid-cols-4 sm:grid-cols-2 gap-12 items-center justify-center">
			<ListIcon 
				img="https://santrikoding.com/storage/categories/Z9WjttjEmct1FzwkFDwSVyKpvhTqBWkJUQA1CuLc.png"
				text="Adonis JS"
			/>	
			<ListIcon 
				img="https://santrikoding.com/storage/categories/zuwzKbAhb691lp2Q1CIYaFK2w0a5McE1mceDOsRs.png"
				text="Codeigniter"
			/>	
			<ListIcon 
				img="https://santrikoding.com/storage/categories/CK3rH3hhb7mL0JHkouw00LJVn8CLPIKNkxSqbUEa.png"
				text="DevOps"
			/>	
			<ListIcon 
				img="https://santrikoding.com/storage/categories/YoSpx2AAk65JI5z9wsiYMY5z7i3vWCe06VUP3FC0.png"
				text="Javascript"
			/>			
			<ListIcon 
				img="https://santrikoding.com/storage/categories/YoSpx2AAk65JI5z9wsiYMY5z7i3vWCe06VUP3FC0.png"
				text="Javascript"
			/>	
			<ListIcon 
				img="https://santrikoding.com/storage/categories/YoSpx2AAk65JI5z9wsiYMY5z7i3vWCe06VUP3FC0.png"
				text="Javascript"
			/>	
			<ListIcon 
				img="https://santrikoding.com/storage/categories/YoSpx2AAk65JI5z9wsiYMY5z7i3vWCe06VUP3FC0.png"
				text="Javascript"
			/>	
			<ListIcon 
				img="https://santrikoding.com/storage/categories/YoSpx2AAk65JI5z9wsiYMY5z7i3vWCe06VUP3FC0.png"
				text="Javascript"
			/>	
		</section>
	</main>
</template>

<script>
import HeaderSection from '../Items/HeaderSection';
import ListIcon from './ListIcon';

export default {
	name: 'ListBox',
	components: {
		'HeaderSection': HeaderSection,
		'ListIcon': ListIcon
	}
}
</script>