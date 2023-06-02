<script>
	import RedButton from "$lib/components/storefront/RedButton.svelte";
	export let Title = "Valorant";
	export let Description =
		"Test";
	export let ButtonText = "";
	export let ImageURL = "";
	export let LogoURL = "";
	export let buttonText = "Default";
</script>

<!-- Background -->
<div class="main">


	<!-- The object, flexbox -->
	<div class="inside flex">


		<!-- Background for Image -->
		<img class="image" src={ImageURL}
				 alt="Valorant's Omen and Sage holding a Radiant-Entertainment-System Phantom.">


		<!-- Background for description -->
		<div class="content">
			<div class="logoInside">
				<img class="logo" src={LogoURL}>
			</div>
			<h2 class="mb-2">{Title}</h2>
			<p>{Description}</p>
			<RedButton customCSS="mt-6"
								 buttonText={ButtonText}/>
		</div>


	</div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		.main {
				background-color: #F3F4F5;
				@apply min-h-screen pt-10;
		}
		.inside {
				border-radius: 8rem;
				@apply w-2/3 mx-auto overflow-hidden;
		}
		.image {
				@apply w-1/2 object-cover;
		}
		.logoInside {
				vertical-align: middle;
				@apply inline-block bg-white w-12 h-12 mr-2 rounded-2xl overflow-hidden;
		}
		.logo {
				@apply object-cover w-full h-full;
		}
		.content {
				color: #F3F4F5;
				background-color: #0c1115;
				@apply inline px-10 py-10;
		}
		h2 {
				vertical-align: middle;
				font-family: 'Skranji', cursive;
				color: #FD4556;
				@apply inline text-4xl;
		}
		p	{
				font-family: 'Hind Madurai', sans-serif;
				@apply text-2xl;
		}

</style>