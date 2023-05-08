<script>
	export let title = 'Default';
	export let subtitle = 'Default';
	export let buttonText1 = 'Default';
	export let imageUrl = 'https://mdbootstrap.com/img/new/ecommerce/horizontal/048.jpg'
</script>
<div>

	<!-- Section: Design Block -->
	<section class="mb-40 background-radial-gradient">
		<style>
        .background-radial-gradient {
            background-color: hsl(218, 41%, 15%);
            background-image: radial-gradient(
                    650px circle at 0% 0%,
                    hsl(218, 41%, 35%) 15%,
                    hsl(218, 41%, 30%) 35%,
                    hsl(218, 41%, 20%) 75%,
                    hsl(218, 41%, 19%) 80%,
                    transparent 100%
            ),
            radial-gradient(
                    1250px circle at 100% 100%,
                    hsl(218, 41%, 45%) 15%,
                    hsl(218, 41%, 30%) 35%,
                    hsl(218, 41%, 20%) 75%,
                    hsl(218, 41%, 19%) 80%,
                    transparent 100%
            );
        }
		</style>
		<div class="px-6 py-12 md:px-12 text-center lg:text-left">
			<div class="container mx-auto xl:px-32">
				<div class="grid lg:grid-cols-2 gap-12 flex items-center">
					<div class="mt-12 lg:mt-0">
						<h1
							class="text-5xl md:text-6xl xl:text-7xl font-bold tracking-tight mb-12">{title}<br /><span>{subtitle}</span></h1>
						<a
							class="inline-block px-7 py-3 mr-2 bg-gray-200 text-gray-700 font-medium text-sm leading-snug uppercase rounded shadow-md hover:bg-gray-300 hover:shadow-lg focus:shadow-lg focus:outline-none focus:ring-0 active:shadow-lg transition duration-150 ease-in-out" data-mdb-ripple="true" data-mdb-ripple-color="light" href="#!" role="button">{buttonText1}</a>
					</div>
					<div class="mb-12 lg:mb-0">
						<img
							src={imageUrl}
							class="w-full rounded-lg shadow-lg"
							alt=""
						/>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- Section: Design Block -->

</div>
<!-- Container for demo purpose -->

<style>
		h1 {
				color: #F3F4F5;
		}
		span {
				color: #235789;
		}
    a {
        background-color: #EA3F45;
        color: #F3F4F5;
    }
		a:hover {
        background-color: #9d2c30;
		}
</style>