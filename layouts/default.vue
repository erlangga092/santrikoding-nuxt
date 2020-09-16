<template>
	<div class="main_template">
		<Header/>
		<nuxt/>
	</div>
</template>

<script>
import Header from '../components/Header/Header';

export default {
	components: {
		'Header': Header
	}
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500&family=Quicksand:wght@400;500&display=swap');

.main_template {
	font-family: 'Poppins', sans-serif;
	color: #212529;
	background: #edf2f7;
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
</style>