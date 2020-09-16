<template>
	<div class="app">
		<Home />
	</div>
</template>

<script>
import Home from '../components/Pages/Home';
import { createClient } from '~/plugins/contentful.js';

const client = createClient();

export default {
	components: {
		'Home': Home
	},
	async asyncData({ env }) {
		const rawEntry = await client.getEntries({
			'content_type': 'article'
		})
		return {
			props: {
				entries: rawEntry.items
			}
		}
	}
}
</script>