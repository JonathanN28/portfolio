<div class='base'>
	<h1 class='text-5xl text-center mb-10'>Pricing</h1>

	<div class='flex justify-center gap-x-6'>
		<div id='1' class='standard'>
			<h2 class=''> Standard</h2>
			<h3>3000 Valorant Points</h3>
			<h3>$27 / 3 months</h3>
			<hr>
			<ul>
				<li>Receive 1000vp every month</li>
				<li>Player banners and key-chain buddies</li>
				<li>Radianite</li>
				<li>Access to players' statistical data</li>
			</ul>
			<button>Select</button>
		</div>
		<div id='2' class='bg-cyan-300 p-10'>
			<p>Every Year</p>
		</div>
		<div id='3' class='bg-blue-800 p-10'>
			<p>Single Purchase</p>
		</div>
	</div>
</div>

<style>
		.base {
				background-color: #F3F4F5;
				@apply w-full h-full pt-10;
    }
		.standard {
				background-color: #0C1115;
				@apply max-w-2xl max-h-full p-5;
		}
		h2 {
        color: #F3F4F5;
				@apply text-4xl text-center;
		}
		hr {
				@apply mt-4 mb-4 border-0 bg-black h-1 w-3/4 mx-auto rounded-full;
		}
		h3 {
        color: #F3F4F5;
				@apply text-xl text-center mt-3;
		}
		ul {
				@apply list-inside text-center list-none;
		}
		ul li::before {
				content: "\2610";
				color: greenyellow;
				background-color: greenyellow;
				display: inline-block;
				width: 1em;
				@apply mr-5 rounded-2xl;
		}
		li {
        color: #F3F4F5;
				@apply m-3;
		}
		button {
        background-color: #EA3F45;
        color: #F3F4F5;
				@apply px-32 py-3 rounded-2xl mt-5 mx-auto;
		}
</style>