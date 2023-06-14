<script>
	export let Title = "Jonathan Nguyen";
	export let Subtitle = "My portfolio";
</script>

<div>
	<h1>{Title}</h1>
	<h2>{Subtitle}</h2>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		div {
				color: #F3F4F5;
				background-color: #235789;
		}
		h1 {
				font-family: 'Skranji', cursive;
				@apply text-5xl text-center pt-10;
		}
		h2 {
				font-family: 'Skranji', cursive;
				@apply text-4xl text-center py-10;
		}
</style>