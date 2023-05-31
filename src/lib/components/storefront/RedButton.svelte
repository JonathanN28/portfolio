<script>
	export let buttonText;
	export let px = 4;
	export let py= 2;
</script>

<a class="px-{px} py-{py}">{buttonText}</a>

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
</style>