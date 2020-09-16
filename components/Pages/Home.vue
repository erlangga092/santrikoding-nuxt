<template>
	<div>
		<Banner />
		<About/>
		<Article />
		<ListBox />
		<TutorialSet />
		<Footer />
	</div>
</template>

<script>
import Banner from '../Banner/Banner';
import Article from '../Article/Article';
import About from '../About/About';
import ListBox from '../ListBox/ListBox';
import TutorialSet from '../TutorialSet/TutorialSet';
import Footer from '../Footer/Footer';

export default {
	name: 'Home',
	components: {
		'Banner': Banner,
		'Article': Article,
		'About': About,
		'ListBox': ListBox,
		'TutorialSet': TutorialSet,
		'Footer': Footer
	},
	props: ['entries'],
	created() {
		console.log(this.props)
	},
	head() {
		return {
			title: 'Home Page',
			meta: [
				{
					hid: 'description',
					name: 'description',
					content: 'Home Page'
				}
			]
		}
	}
}
</script>