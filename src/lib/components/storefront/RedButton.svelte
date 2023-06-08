<script>
	export let buttonText;
	export let Link;
	export let customCSS = "";
</script>

<a href={Link} target="_blank" class="px-4 py-2 {customCSS}">{buttonText}</a>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		a {
				font-family: 'Hind Madurai', sans-serif;
				background-color: #ea3f45;
				transition: background-color;
				@apply inline-block text-2xl rounded-2xl duration-200;
		}
		a:hover {
				background-color: #a22c30;
				cursor: pointer;
		}
    .ciajdw {
				background-color: #ea3f45;
		}
</style>