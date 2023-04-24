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
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		p {
				font-family: 'Hind Madurai', sans-serif;
				font-size: 1.5rem;
				color: #0c1115;
		}
		div {
				background-color: #F3F4F5;
				width: 300px;
				padding: 20px;
				/*border-radius: 20px;*/
				/*border: 10px outset rgb(150, 150, 180);*/

		}
		hr {
				border: none;
				border-radius: 1em;
				height: 0.25em;
				background-color: #ea3f45;
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