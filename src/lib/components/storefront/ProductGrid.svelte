<script>
	import ProductGridCard from "$lib/components/storefront/ProductGridCard.svelte";
</script>

<div class="main flex justify-center">
	<div class="grid grid-cols-1 md:grid-cols-5 gap-10">
		<ProductGridCard
			Title="Minecraft"
			Price="$29.99"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sc8d2x.jpg";
		/>
		<ProductGridCard
			Title="Bloons TD 6"
			Price="$9.99"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sc5t1n.jpg";
		/>
		<ProductGridCard
			Title="Among Us"
			Price="$4.99"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_original/sceeq6.jpg";
		/>
		<ProductGridCard
			Title="Barony"
			Price="$14.99"
			ImageURL="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/clans/9110426/8b3aaa3496ff795fbf52f05f1380eae5937a3b1c.jpg";
			GIFURL="https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/clans//9110426/a5d219ad9b3e69ca619e2023f8bba6a14fa991a3.gif"
		/>
		<ProductGridCard
			Title="Rust"
			Price="$39.99"
			ImageURL="https://images.igdb.com/igdb/image/upload/t_screenshot_big/ar4cx.jpg";
		/>
	</div>
</div>


<style>
	.main {
			background: linear-gradient(180deg, #F3F4F5, #235789, #F3F4F5);
	}
</style>