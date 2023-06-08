<script>
	import ProductGridCard from "$lib/components/storefront/ProductGridCard.svelte";
</script>

<div class="main flex justify-center">
	<div class="grid grid-cols-1 md:grid-cols-5 gap-10 grid">
		<ProductGridCard
			Title="Minecraft"
			Price="$29.99"
			Link="https://www.minecraft.net/en-us"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sc8d2x.jpg"
			GIFURL="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWM0NGEzNWNkMDhmYmU1OTQ1MzZkMjU4M2Y2NDIzZGRiMDlkODI0YSZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/eoakrfrbdKRVu/giphy-downsized-large.gif"
		/>
		<ProductGridCard
			Title="Bloons TD 6"
			Price="$13.99"
			Link="https://store.epicgames.com/en-US/p/bloons-td-6-bf95a0"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sc5t1n.jpg"
		/>
		<ProductGridCard
			Title="Among Us"
			Price="$4.99"
			Link="https://store.epicgames.com/en-US/p/among-us"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sceeq6.jpg"
			GIFURL="https://media.tenor.com/IgjZeB1fS8oAAAAC/among-us-game.gif"
		/>
		<ProductGridCard
			Title="Barony"
			Price="$14.99"
			Link="https://store.epicgames.com/en-US/p/barony"
			ImageURL="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/clans/9110426/8b3aaa3496ff795fbf52f05f1380eae5937a3b1c.jpg"
			GIFURL="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/clans//9110426/a5d219ad9b3e69ca619e2023f8bba6a14fa991a3.gif"
		/>
		<ProductGridCard
			Title="Rust"
			Price="$39.99"
			Link="https://rust.facepunch.com/"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sc6vl7.jpg"
			GIFURL="https://media.giphy.com/media/OfSOUl3vvPBcwmWAdO/giphy.gif"
		/>
	</div>
</div>


<style>
	.main {
			background: linear-gradient(180deg, #F3F4F5, #235789 25%, #235789);
			@apply pt-40 pb-10;
	}
</style>