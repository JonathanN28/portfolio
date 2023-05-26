<script>
	import RedButton from "$lib/components/storefront/RedButton.svelte";
	let Title = "Valorant";
	let Description =
		"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.";
	let ButtonText = "";
	let Caption = "";
	let ImageURL = "https://99designs-blog.imgix.net/blog/wp-content/uploads/2016/08/featured.png?auto=format&q=60&w=2060&h=1158.75&fit=crop&crop=faces";
	export let buttonText = "Default";
</script>

<!-- Background -->
<div class="main">


	<!-- The object, flexbox -->
	<div class="inside flex">


		<!-- Background for Image -->
		<img class="" src={ImageURL} alt="">


		<!-- Background for description -->
		<div class="content">
			<h2>{Title}</h2>
			<p>{Description}</p>
			<RedButton buttonText={buttonText}/>
		</div>


	</div>
</div>

<style>
		.main {
				background-color: #F3F4F5;
				@apply min-h-screen pt-10;
		}
		.inside {
				border-radius: 8rem;
				@apply w-2/3 mx-auto overflow-hidden;
		}
		img {
				@apply w-1/2 h-96 object-cover;
		}
		.content {
				color: #F3F4F5;
				background-color: #0c1115;
				@apply inline h-96 px-10 py-20;
		}
</style>