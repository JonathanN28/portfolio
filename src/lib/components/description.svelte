<script>
	export let date = 1930;
	export let summary = 'daiwjdwoiwa';
</script>

<div>
{#if date == ''}
<p class='summary'>&bullet; {summary}</p>
{:else}
<p class='date'>{date}</p>
<hr>
<p class='summary'>&bullet; {summary}</p>
{/if}
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Cabin&family=Raleway:wght@500&display=swap');
		p {
				font-family: 'Raleway', sans-serif;
				font-size: 1.5rem;
				color: rgb(62, 75, 88);
		}
		div {
				background-color: rgb(247, 247, 255);
				width: 300px;
				padding: 20px;
				/*border-radius: 20px;*/
				/*border: 10px outset rgb(150, 150, 180);*/

		}
		hr {
				border: none;
				border-radius: 1em;
				height: 0.25em;
				background-color: rgb(180, 180, 200);
				margin-top: 5px;
				margin-bottom: 5px;
		}
		.date {
				text-align: center;
		}
		.summary {
				text-align: left;
		}

</style>