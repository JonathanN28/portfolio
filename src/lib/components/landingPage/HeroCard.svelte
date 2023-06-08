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
{:else}
{/if}
<div class="{customCSS} main flex justify-center">
	<img src={ImageURL}>
	<div class="content">
		<h1>{Title}</h1>
		<p>{Description}</p>
	</div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
    .main {
				@apply py-40 overflow-hidden;
		}
		img {
				@apply object-cover;
		}
		.content {
				background-color: white;
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