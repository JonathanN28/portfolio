<script>
	export let Title;
	export let Price;
	export let ImageURL;
</script>
<div class="flex">
	<img src={ImageURL}
			 alt="Minecraft Alex, Steve, Pig, Sheep, Wolf, Creeper, Spider, & Zombie on a mountain.">
	<h2>{Title}</h2>
	<p>{Price}</p>
</div>

<style>
	div {
			background-color: blueviolet;
			@apply w-56 h-56;
	}
	h2 {
			@apply text-4xl;
	}
</style>