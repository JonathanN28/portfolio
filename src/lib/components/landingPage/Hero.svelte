<script>
	import Form from "$lib/assets/form.jpeg";
	import HeroCard from "$lib/components/landingPage/HeroCard.svelte";
</script>

<div class="grid grid-cols-1">
	<HeroCard Name="Form"	Title="Form"
						Description="A survey or feedback form."
						Link="/form" />
	<HeroCard Name="Tribute" Title="Tribute"
						Description="A page dedicated to Marcel Marceau."
						Link="/tribute"/>
	<HeroCard Name="Product" Title="Product"
						Description="A page that is trying to sell you something. In this case, Valorant's currency."
						Link="/sales"/>
	<HeroCard Name="Storefront" Title="Storefront"
						Description="Marketing or selling videogames like Amazon, Ebay, and AliExpress."
						Link="/storefront"/>

</div>

<style>
	div {
			background-color: #F3F4F5;
	}
</style>