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
            background-color: hsl(209, 59%, 34%);
            background-image: radial-gradient(
                    650px circle at 0% 0%,
                    hsl(209, 59%, 34%) 15%,
                    hsl(209, 59%, 34%) 35%,
                    hsl(209, 59%, 34%) 75%,
                    hsl(209, 59%, 34%) 80%,
                    transparent 100%
            ),
            radial-gradient(
                    1250px circle at 100% 100%,
                    hsl(209, 59%, 34%) 15%,
                    hsl(210, 57%, 53%) 35%,
                    hsl(209, 56%, 61%) 75%,
                    hsl(209, 42%, 52%) 80%,
                    transparent 100%
            );
        }
		</style>
		<div class="px-6 py-12 md:px-12 text-center lg:text-left">
			<div class="container mx-auto xl:px-32">
				<div class="grid lg:grid-cols-2 gap-12 flex items-center">
					<div class="mt-12 lg:mt-0">
						<h1
							class="text-5xl md:text-6xl xl:text-7xl font-bold tracking-tight mb-12 ">{title}<br /><span>{subtitle}</span></h1>
						<a
							class="inline-block px-7 py-3 mr-2 bg-gray-200 text-gray-700 font-medium text-sm leading-snug uppercase rounded shadow-md hover:bg-gray-300 hover:shadow-lg focus:shadow-lg focus:outline-none focus:ring-0 active:shadow-lg transition duration-150 ease-in-out" data-mdb-ripple="true" data-mdb-ripple-color="light" href="#pricing" role="button">{buttonText1}</a>
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
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		h1 {
				line-height: 5rem;
				font-family: 'Skranji', cursive;
				color: #F3F4F5;
		}
		span {
				color: #EA3F45;
		}
    a {
				font-family: 'Hind Madurai', sans-serif;
        background-color: #EA3F45;
        color: #F3F4F5;
    }
		a:hover {
        background-color: #9d2c30;
		}
</style>