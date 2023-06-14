<script>
	import Form from "$lib/assets/form.jpg";
	import Product from "$lib/assets/product.jpg";
	import Storefront from "$lib/assets/storefront.jpg";
	import Tribute from "$lib/assets/tribute.jpg";
	export let Name;
	export let Title = "Hello World";
	export let Description = "This is a description";
	let ImageURL = "";
	export let Link = "";
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
<a href={Link}>
	<div class="{customCSS} main flex justify-center ">
		<img src={ImageURL}>
		<div class="content">
			<h1>{Title}</h1>
			<p>{Description}</p>
		</div>
	</div>
</a>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
    .main {
				cursor: pointer;
				transition: height;
				@apply w-full h-48 overflow-hidden duration-200;
		}
		.main:hover {
				@apply h-96;
		}
		img {
				position: relative;
				filter: blur(14px);
				@apply object-cover w-full h-full;
		}
		img:hover {
				filter: blur(0px);
		}
		.content {
				position: absolute;
        color: #0C1115;
				background-color: #F3F4F5;
				left:0;
				right:0;
				@apply px-4 py-2;
		}
		h1 {
				font-family: 'Skranji', cursive;
				@apply text-5xl text-center;
		}
		p {
				font-family: 'Hind Madurai', sans-serif;
				@apply text-2xl text-center;
		}
</style>