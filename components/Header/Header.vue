<template>
	<div class="bg-white fixed t-0 w-full z-30">
		<header class="bg-white w-full items-center justify-center">
			<nav class="w-full h-1 bg-red-500"></nav>
			<nav class="h-20 bg-white w-full grid grid-cols-4 items-center justify-center">
				<section class="col-span-3 grid px-4 grid-cols-4 items-center justify-center lg:grid-cols-2 md:grid-cols-2 sm:grid-cols-2">
					<div class="col-span 1 flex items-center">
						<h1 class="text-center text-2xl font-medium text-gray-700">
							ERL_ANGGA
						</h1>
					</div>
					<div class="col-span-3 flex items-center justify-center w-full lg:hidden md:hidden sm:hidden">
						<ul class="flex items-center justify-evenly list-none w-full">
							<li><a href="">Codeigniter</a></li>
							<li><a href="">Laravel</a></li>
							<li><a href="">Vue JS</a></li>
							<li><a href="">Javascript</a></li>
							<li><a href="">Kelas Online</a></li>
							<li><a href="">More</a></li>
							<li><a href="">Produk</a></li>
							<li><a href="">Tutorial Set</a></li>
						</ul>
					</div>
				</section>
				<section class="col-span-1 flex items-center justify-center lg:hidden md:hidden sm:hidden">
					<div class="button_register">
						<button class="px-6 py-2 rounded bg-red-500 text-center text-white hover:bg-red-700 mr-3 shadow">
							Register
						</button>
					</div>
					<div class="button_login">
						<button class="px-6 py-2 rounded bg-red-500 text-center text-white hover:bg-red-700 shadow">
							Login
						</button>
					</div>
				</section>
			</nav>
		</header>
		<main class="promo w-full bg-indigo-900 flex items-center justify-center py-1">
			<p class="text-white text-md text-center">
				Ebook Laravel Livewire !
			</p>
		</main>
	</div>
</template>

<script>
export default {
	name: 'Header'
}
</script>

<style scoped>
	ul li a {
		font-family: 'Quicksand', sans-serif;
		font-weight: 600;
		color: #35495e;
	}

	ul li a:hover {
		opacity: .8;
	}

	h1 {
		font-family: 'Quicksand', sans-serif;
		font-weight: 600;
	}
</style>