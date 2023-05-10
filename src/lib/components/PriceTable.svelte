<script>
	let package1 = 'Basic';
	let product1 = '475 VP';
	let price1 = '$3.99 / Monthly';
	let buttonText1 = 'Select';
	let item1 = 'Titles, key-chain buddies, banners';
	let item2 = '50 Radianite points';
	let item3 = 'Personal gameplay statistics';

	let package2 = 'Standard';
	let product2 = '1000 Valorant Points';
	let price2 = '$8.49 / Monthly';
	let buttonText2 = 'Select';
	let item4 = 'Basic package\'s perks & Revert skins\' upgrades';
	let item5 = '100 Radianite points only';
	let item6 = 'Public gameplay statistics';

	let package3 = 'Premium';
	let product3 = '2575 VP';
	let price3 = '$29.99 / Monthly';
	let buttonText3 = 'Select';
	let item7 = 'Standard package\'s perks & Night Market\'s dates';
	let item8 = '175 Radianite points';
	let item9 = 'Night Market includes discounted bundles';
</script>
<!-- Global Container -->
<div class="flex items-center justify-center min-h-screen color1">
	<!-- Inner Container -->
	<div
		class="flex flex-col my-6 space-y-6 md:space-y-0
md:space-x-6 md:flex-row md:my-0"
	>
		<!-- Col 1 -->
		<div class='bg-slate-700 rounded-xl text-white color3borderBorder'>
			<!-- Upper Container -->
			<div class="p-8 mx-3 mt-3 rounded-t-xl bg-slate-800 color2box">
				<div class="text-center uppercase">{package1}</div>
				<h2 class="mt-10 font-serif text-5xl

text-center">{product1}</h2>

				<h3 class="mt-2 text-center">{price1}</h3>
				<div class="flex justify-center">
					<a
						href="#"
						class='inline-block px-10 py-3 my-6 text-center

border border-violet-600 rounded-lg duration-200
hover:bg-violet-800 hover:border-violet-800 color3borderbutton'

					>{buttonText1}</a
					>
				</div>
			</div>

			<!-- Border -->
			<div class='border-t border-slate-700 color3borderBorder'></div>

			<!-- Lower Container -->
			<div class="p-8 mx-3 mb-3 rounded-b-xl bg-slate-800 color2box">
				<!-- List Container -->
				<div class="flex flex-col space-y-2">
					<!-- List Item 1 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item1}</span>
					</div>

					<!-- List Item 2 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"

							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item2}</span>
					</div>

					<!-- List Item 3 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>

						<span class="text-sm ml-1">{item3}</span>
					</div>
				</div>
			</div>
		</div>

		<!-- Col 2 -->
		<div class="bg-violet-600 rounded-xl text-white color3borderbutton">
			<!-- Upper Container -->
			<div class="p-8 mx-3 mt-3 rounded-t-xl bg-slate-800 color2box">
				<div class="text-center uppercase">{package2}</div>
				<h2 class="mt-10 font-serif text-5xl

text-center">{product2}</h2>

				<h3 class="mt-2 text-center">{price2}</h3>
				<div class="flex justify-center">
					<a
						href="#"
						class='inline-block px-10 py-3 my-6 text-center
border border-violet-600 rounded-lg duration-200 bg-violet-600
hover:bg-violet-800 hover:border-violet-800 color3borderbutton'

					>{buttonText2}</a
					>
				</div>
			</div>

			<!-- Border -->
			<div class="border-t border-slate-700 color3borderbutton"></div>

			<!-- Lower Container -->

			<div class="p-8 mx-3 mb-3 rounded-b-xl bg-slate-800 color2box">
				<!-- List Container -->
				<div class="flex flex-col space-y-2">
					<!-- List Item 1 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item4}</span>
					</div>

					<!-- List Item 2 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"

							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item5}</span>
					</div>

					<!-- List Item 3 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item6}</span>

					</div>
				</div>
			</div>
		</div>

		<!-- Col 3 -->
		<div class="bg-slate-700 rounded-xl text-white">
			<!-- Upper Container -->
			<div class="p-8 mx-3 mt-3 rounded-t-xl bg-slate-800 color2box">
				<div class="text-center uppercase">{package3}</div>
				<h2 class="mt-10 font-serif text-5xl text-center">{product3}</h2>

				<h3 class="mt-2 text-center">{price3}</h3>
				<div class="flex justify-center">
					<a
						href="#"
						class='inline-block px-10 py-3 my-6 text-center

border border-violet-600 rounded-lg duration-200
hover:bg-violet-800 hover:border-violet-800 color3borderbutton'

					>{buttonText3}</a
					>
				</div>
			</div>

			<!-- Border -->
			<div class="border-t border-slate-700"></div>

			<!-- Lower Container -->
			<div class="p-8 mx-3 mb-3 rounded-b-xl bg-slate-800 color2box">
				<!-- List Container -->

				<div class="flex flex-col space-y-2">
					<!-- List Item 1 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item7}</span>
					</div>

					<!-- List Item 2 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"

							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item8}</span>
					</div>

					<!-- List Item 3 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">{item9}</span>
					</div>
				</div>

			</div>
		</div>
	</div>
</div>
<style>
	.color1 {
			background-color: #235789;
	}
	.color2box {
			background-color: #F3F4F5;
	}
	.color3borderBorder {
      background-color: #801f21;
      border-color: #801f21;
	}
	.color3borderbutton {
			background-color: #EA3F45;
			border-color: #EA3F45;
	}
	p, h2, h3, div {
			color: #0C1115;
	}
  a {
      background-color: #EA3F45;
      color: #F3F4F5;
  }
  a:hover {
      background-color: #9d2c30;
  }
</style>
