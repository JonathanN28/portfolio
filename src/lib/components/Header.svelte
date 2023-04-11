<script>
	import src from "$lib/assets/Jonathan.jpg";
	import src2 from "$lib/assets/Jonathan2.png";
	import src3 from "$lib/assets/Jonathan3.png";
</script>

<header
	class="backgroundcolor text-white flex place-content-center min-w-full sm:px-5">
	<div class="container flex items-center justify-center py-4 gap-x-8">
		<a href="/">
			<!-- Add svg image -->
			<img src={src} alt="Logo" class="max-h-12" />
		</a>
		<nav>
			<ul class="flex items-center justify-center gap-x-2">
				<li><a href="/" class="px-4 py-2 hover:text-gray-400">Home</a></li>
				<li><a href="/form" class="px-4 py-2 hover:text-gray-400">Form</a></li>
				<li><a href="/tribute" class="px-4 py-2 hover:text-gray-400">Tribute
				</a></li>
				<li><a href="/product" class="px-4 py-2 hover:text-gray-400">Product
				</a></li>

			</ul>
		</nav>
	</div>
</header>

<!-- Tribute-themed -->
<style>
	.backgroundcolor {
		background-color: #48485D;
	}
</style>

<!-- Style guide-themed -->
<!--<style>-->
<!--	.backgroundcolor {-->
<!--		background-color: #EA3F45;-->
<!--	}-->
<!--</style>-->

<!-- Portfolio-themed -->
<!--<style>-->
<!--		a {-->
<!--				background-color: #925047;-->
<!--				color: #F3F4F5;-->
<!--		}-->
<!--		.backgroundcolor {-->
<!--				background-color: #f0c14f;-->
<!--		}-->
<!--</style>-->