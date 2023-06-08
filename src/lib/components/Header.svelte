<script>
	/*import src from "$lib/assets/Jonathan.jpg";
	import src2 from "$lib/assets/Jonathan2.png";
	import src3 from "$lib/assets/Jonathan3.png";
	import src4 from "$lib/assets/Jonathan4.png";*/
	import src5 from "$lib/assets/Jonathan5.png";
	import { page } from '$app/stores';
</script>
{#if $page.url.pathname === "/storefront"}
<header
	class="storefrontHeaderBg text-white flex place-content-center min-w-full sm:px-5">
	<div
		class="storefrontBg flex items-center justify-center py-4 px-4 gap-x-8">

		<!--		if on storefront page, show a different nav section-->

		<a href="/">
			<!-- Add svg image -->
			<img src={src5} alt="Logo" class="storefrontImg max-h-12 rounded-2xl " />
		</a>
		<nav>
			<ul class="flex items-center justify-center gap-x-2 flex-wrap">
				<li><a href="/"
							 class="storefrontLink px-1 md:px-4 py-2 text-xl md:text-2xl">Home
				</a></li>
				<li><a href="/form"
							 class="storefrontLink px-1 md:px-4 py-2 text-xl md:text-2xl">
					Form</a></li>
				<li><a href="/tribute"
							 class="storefrontLink px-1 md:px-4 py-2 text-xl md:text-2xl">Tribute
				</a></li>
				<li><a href="/product"
							 class="storefrontLink px-1 md:px-4 py-2 text-xl md:text-2xl">Product
				</a></li>
				<li><a href="/sales"
							 class="storefrontLink px-1 md:px-4 py-2 text-xl md:text-2xl">Sales
				</a></li>
				{#if $page.url.pathname === "/storefront"}
				<li><a href="/storefront"
							 class="storefrontLink2 storefrontVisited px-1 md:px-4 py-2 text-xl md:text-2xl">Storefront
				</a></li>
				{/if}
			</ul>
		</nav>
	</div>
</header>
{:else}
<header
	class="backgroundcolor text-white flex place-content-center min-w-full sm:px-5">
	<div
		class="container flex items-center justify-center py-4 gap-x-8">
		<a href="/">
			<!-- Add svg image -->
			<img src={src5} alt="Logo" class="max-h-12" />
		</a>
		<nav>
			<ul class="flex items-center justify-center gap-x-2 flex-wrap">
				<li><a href="/"
							 class="px-1 md:px-4 py-2 hover:text-gray-400 text-xl md:text-2xl">Home
				</a></li>
				<li><a href="/form" class="px-1 md:px-4 py-2 hover:text-gray-400 text-xl md:text-2xl">Form</a></li>
				<li><a href="/tribute"
							 class="px-1 md:px-4 py-2 hover:text-gray-400 text-xl md:text-2xl">Tribute
				</a></li>
				<li><a href="/sales"
							 class="px-1 md:px-4 py-2 hover:text-gray-400 text-xl md:text-2xl">Product
				</a></li>
				<li><a href="/storefront"
							 class="px-1 md:px-4 py-2 hover:text-gray-400 text-xl md:text-2xl">Storefront
				</a></li>
			</ul>
		</nav>
	</div>
</header>
{/if}

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		a {
				font-family: 'Hind Madurai', sans-serif;
				color: #F3F4F5;
		}
    .backgroundcolor {
        background-color:#ea3f45;
    }
		.storefrontHeaderBg {
        background-color: #F3F4F5;
		}
		.storefrontBg {
				background-color: #0c1115;
				@apply rounded-b-2xl;
		}
		.storefrontImg {
				transition: transform;
				@apply duration-200;
		}
		.storefrontImg:hover {
				transform: scale(1.4);
		}
		.storefrontLink {
				@apply rounded-2xl;

				transition: font-size;
				@apply duration-200;
		}
		.storefrontLink:hover {
        border-color: #ea3f45;
				@apply text-3xl border-4;
		}
    .storefrontLink2 {
        @apply rounded-2xl;
        @apply duration-200;
    }

		.storefrontVisited {
				border-color: #ea3f45;
				@apply border-4;
		}

</style>