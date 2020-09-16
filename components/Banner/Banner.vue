<template>
	<div class="pt-24 bg-red-500">
		<main class="main__banner w-full bg-red-500 px-4 flex items-center">
			<div class="w-full grid grid-cols-5 items-center justify-center">
				<section class="col-span-3 sm:col-span-5 md:col-span-5">
					<div class="header__banner mb-6 flex">
						<h3 class="text__banner text-white">
							SANTRI
						</h3>
						<h3 class="text__banner text-red-500 bg-white rounded-lg">
							KODING
						</h3>
					</div>
					<div class="header__text px-3 text-lg font-normal mb-8">
						<p class="text-white">
							Belajar koding bahasa Indonesia terlengkap dan mudah dipahami seperti
						</p>
						<p class="text-white">
							Laravel, Codeigniter, Vue JS, Javascript dan masih banyak lagi
						</p>
					</div>
					<div class="input__banner px-3">
						<div class="bg-white px-6 py-4 rounded-lg w-11/12 shadow-md md:w-full sm:w-full">
							<input 
								type="text" 
								class="bg-white outline-none text-lg w-full"
								placeholder="Belajar Apa Hari Ini ?" 
							>
						</div>
					</div>
				</section>
				<section class="col-span-2 sm:col-span-5 md:col-span-5">
					
				</section>
			</div>
		</main>
		<svg style="pointer-events: none;margin-top: -50px;position:absolute;" class="wave" width="100%" height="50px" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 1920 75">
      <defs>
        <style>
          .a {
            fill: none;
          }

          .b {
            clip-path: url(#a);
          }

          .c,
          .d {
            fill: #ffffff;
          }

          .d {
            opacity: 0.5;
            isolation: isolate;
          }
        </style>
        <clipPath id="a">
          <rect class="a" width="1920" height="75"></rect>
        </clipPath>
      </defs>
      <title>wave</title>
      <g class="b">
        <path class="c" d="M1963,327H-105V65A2647.49,2647.49,0,0,1,431,19c217.7,3.5,239.6,30.8,470,36,297.3,6.7,367.5-36.2,642-28a2511.41,2511.41,0,0,1,420,48"></path>
      </g>
      <g class="b">
        <path class="d" d="M-127,404H1963V44c-140.1-28-343.3-46.7-566,22-75.5,23.3-118.5,45.9-162,64-48.6,20.2-404.7,128-784,0C355.2,97.7,341.6,78.3,235,50,86.6,10.6-41.8,6.9-127,10"></path>
      </g>
      <g class="b">
        <path class="d" d="M1979,462-155,446V106C251.8,20.2,576.6,15.9,805,30c167.4,10.3,322.3,32.9,680,56,207,13.4,378,20.3,494,24"></path>
      </g>
      <g class="b">
        <path class="d" d="M1998,484H-243V100c445.8,26.8,794.2-4.1,1035-39,141-20.4,231.1-40.1,378-45,349.6-11.6,636.7,73.8,828,150"></path>
      </g>
	  </svg>
	</div>
</template>

<script>
export default {
	name: 'Banner'
}
</script>

<style scoped>
	.header__banner .text__banner {
		font-family: 'Quicksand', sans-serif;
		font-size: 3.5rem;
		font-weight: 600;
		padding: 0 .75rem;
	}

	.main__banner {
		padding-top: 3rem;
		padding-bottom: 7rem;
	}
</style>