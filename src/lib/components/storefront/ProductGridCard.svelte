<script>
	import RedButton from '$lib/components/storefront/RedButton.svelte';
	export let Title;
	export let Price;
	export let ImageURL;
	export let GIFURL;
</script>
<!-- Check the url last three letters -->
<!-- check if gif url is empty -->
{#if GIFURL}
	<div class="card flex" onmouseenter="">
		<img src={GIFURL}
				 alt="">
		<div class="content">
			<h2>{Title}</h2>
			<p>{Price}</p>
		</div>
	</div>
{:else}
<div class="card flex">

	<img src={ImageURL}
			 alt="">
	<div class="content">
		<h2>{Title}</h2>
		<p>{Price}</p>
	</div>
</div>
{/if}
<style>
	.card {
			background-color: blueviolet;
			position: relative;
			@apply w-72 h-72;

      border: 10px outset #ea3f45;
			@apply rounded-2xl overflow-hidden;
	}
	img {
			@apply object-cover;
	}
	img:hover {
	}
	.content {
			background: linear-gradient(180deg, rgba(243, 244, 245, 0), rgba(243,
			244, 245, 0.7) 30%, rgba(243, 244, 245) 90%);

			color: #0C1115;
			position: absolute;

			@apply left-0 right-0 bottom-0;
			@apply w-full h-auto mx-auto px-4 pb-2 pt-4;
	}
	h2 {
			@apply text-4xl;
	}
	p {
			@apply text-2xl;
	}
</style>