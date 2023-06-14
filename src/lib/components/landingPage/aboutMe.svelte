<script>
	export let Title = "About Me";
	export let Description =
		"11th grader taking the Web Design elective and his pronouns are he/him. I took Game Design 1 & 2 because I want a career in it.";
</script>

<div class="main flex justify-center">
	<div class="content">
		<h1>{Title}</h1>
		<p>{Description}</p>
	</div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		.main {
				background-color: #235789;
				@apply p-10;
		}
		.content {
				background-color: #F3F4F5;
				@apply p-10 w-1/2;
        border: 10px outset #ea3f45;
		}
		h1 {
				font-family: 'Skranji', cursive;
				@apply text-5xl;
		}
		p {
				font-family: 'Hind Madurai', sans-serif;
				@apply text-2xl;
		}
</style>