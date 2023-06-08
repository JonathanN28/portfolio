<script>
	import Form from "$lib/assets/form.jpg";
	import Product from "$lib/assets/product.jpg";
	import Storefront from "$lib/assets/storefront.jpg";
	import Tribute from "$lib/assets/tribute.jpg";
	export let Name;
	export let Title = "Hello World";
	export let Description = "This is a description";
	export let ImageURL = "";
	export let customCSS;

	if (Name === "Form") {
		ImageURL = Form;
	} else if (Name === "Product") {
		ImageURL = Product;
	} else if (Name === "Storefront") {
		ImageURL = Storefront;
	} else if (Name === "Tribute") {
		ImageURL = Tribute;
	}
</script>
{#if Name === "Me"}
	<div class="{customCSS} main flex justify-center">
		<div class="content">
			<h1>{Title}</h1>
			<p>{Description}</p>
		</div>
	</div>
{:else}
	<div class="{customCSS} main flex justify-center">
		<img src={ImageURL}>
		<div class="content">
			<h1>{Title}</h1>
			<p>{Description}</p>
		</div>
	</div>
{/if}

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
    .main {
				@apply w-full h-72 overflow-hidden;
		}
		img {
				position: relative;
				filter: blur(14px);
				@apply object-cover w-full h-full;
		}
		.content {
				position: absolute;
				background-color: #F3F4F5;
        border: 10px outset #ea3f45;
		}
		h1 {
				font-family: 'Skranji', cursive;
				@apply text-5xl;
		}
		p {
				font-family: 'Hind Madurai', sans-serif;
				@apply text-2xl;
		}
</style>