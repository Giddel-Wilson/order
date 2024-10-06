<main class="container w-screen h-screen flex justify-center items-center">
	<div class="card main-card variant-filled w-96 h-max rounded-xl overflow-hidden">
		<div class="card-image w-full">
			<enhanced:img src="../lib/assets/illustration-hero.svg" alt="" class="w-full h-full object-cover">
		</div>
		<div class="pt-4 pb-7 px-6">
			<a href="./" class="card-header w-full flex justify-center text-2xl font-bold">Order Summary</a>
			<p class="card-content text-center my-3 text-base">You can now listen to millions of songs, audiobooks, and podcasts on any 
				device anywhere you like!</p>

				<div class="card flex justify-between items-center p-3 my-6 variant-glass-primary">
					<div class="flex justify-between items-center gap-5 bg-transparent">
							<enhanced:img src="../lib/assets/icon-music.svg" alt="" class="object-cover btn-icon variant-filled w-10 h-10">
						<div>
							<p class="font-bold">Annual Plan</p>
							<p class="text-surface-500">$59.99/year</p>
						</div>
					</div>
					<div>
						<p href="./" class="text-primary-700 text-sm font-semibold underline hover:no-underline hover:text-primary-500 hover:scale-90 hover:cursor-pointer">Change</p>
					</div>
				</div>
			
				<button type="button" class="btn variant-filled-primary w-full rounded-lg my-3 shadow-lg">
					<p class="text-white font-semibold">Proceed to Payment</p>
				</button>
			  <p class="text-center text-xs text-surface-600 font-bold mt-1 mb-3 hover:cursor-pointer hover:text-surface-700 hover:scale-105">Cancel Order</p>

		</div>
	</div>

</main>

<style>
	@media only screen and (max-width: 920px) {
		.main-card {
			width: 500px;
			height: max-content;
			overflow: auto;
		}
	}
	
	@media only screen and (max-width: 530px) {
		.main-card {
			width: 90%;
			overflow: auto;
		}
	}
</style>