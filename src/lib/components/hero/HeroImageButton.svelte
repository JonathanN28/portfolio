<script>
	let bgImage = 'https://mdbcdn.b-cdn.net/img/new/slides/146.webp';
	export let title = 'Default';
	export let subtitle = 'Default';
	export let buttonText = 'Default';
</script>

<section class="mb-40">
	<div
		class="relative overflow-hidden bg-no-repeat bg-cover"
		style="background-image: url({bgImage}); height: 500px;"
	>
		<div
			class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed"
			style="background-color: rgba(0, 0, 0, 0.75);"
		>
			<div class="flex justify-center items-center h-full">
				<div class="text-center text-white px-6 md:px-12">
					<h1 class="text-5xl md:text-6xl xl:text-7xl font-bold tracking-tight mb-12">
						{title} <br /><span>{subtitle}</span>
					</h1>
					<button
						type="button"
						class="inline-block px-7 py-3 text-white font-medium text-sm leading-snug uppercase rounded hover:bg-opacity-25 focus:outline-none focus:ring-0 transition duration-150 ease-in-out"
					>
						{buttonText}
					</button>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
		h1 {
				color: #F3F4F5;
		}
		span {
        color: #EA3F45;
		}
		button {
				background-color: #EA3F45;
				color: #F3F4F5;
		}
		button:hover {
				background-color: #9d2c30;
		}


</style>