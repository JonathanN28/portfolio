<script>
	export let date = 1930;
	export let summary = 'daiwjdwoiwa';
</script>

<div>
{#if date == ''}
<p class='summary'>{summary}</p>
{:else}
<p class='date'>{date}</p>
<hr>
<p class='summary'>{summary}</p>
{/if}
</div>

<style>
		p {
				font-size: 20px;
		}
		div {
				background-color: rgb(255, 130, 130);
				width: 14%;
				padding: 10px;
				border-radius: 20px;
				border: rgb(255, 100, 100) 10px outset;
		}
		hr {
				border: none;
				border-radius: 1em;
				height: 0.25em;
				background-color: rgb(230, 100, 100);
				margin-top: 5px;
				margin-bottom: 5px;
		}
		.date {
				text-align: center;
		}
		.summary {
				text-align: center;
		}

</style>