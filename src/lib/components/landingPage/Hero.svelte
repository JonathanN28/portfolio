<script>
	import Form from "$lib/assets/form.jpeg";
	import HeroCard from "$lib/components/landingPage/HeroCard.svelte";
</script>

<div class="grid grid-cols-1">
	<HeroCard Name="Me" />
	<HeroCard Name="Form"	ImageURL={Form} />
	<HeroCard Name="Tribute"	ImageURL="" />
	<HeroCard Name="Product"	ImageURL="" />
	<HeroCard Name="Storefront"	ImageURL="" />

</div>