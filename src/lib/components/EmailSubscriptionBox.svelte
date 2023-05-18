<script>
	import subImg from '$lib/assets/kobby-mendez-UOl_IN96w0M-unsplash.jpg';
</script>

<section
	class='flex items-center justify-center h-full p-10 bg-zinc-700 ml-auto mr-auto'>
	<div class='bg-zinc-800 p-2 mx-6 emailBox borderoutset'>
		<div class='flex flex-col md:flex-row rounded-l-xl'>
			<img src={subImg} alt='boat on a lake'
					 class='object-fit object-cover rounded-t-xl h-80 md:h-64 md:rounded-l-xl md:rounded-r-none transform hover:scale-105 hover:rounded-xl duration-200' />
			<div class='py-4 px-2 md:p-4'>
				<h2
					class='font-serif text-xl font-medium text-center text-white md:text-left'>Receive 20 VP for free</h2>
				<p
					class='max-w-lg leading-5 tracking-wide text-center text-white md:text-left'> Each of our emails contain an image tracker and everytime you open each new email, you receive the free 20 VP.</p>
				<div
					class='flex flex-col mt-5 space-y-4 md:space-x-3 md:flex-row md:space-y-0'>
					<input type='text' placeholder='Enter your email address'
								 class='p-2 px-4 text-center text-black bg-neutral-200 border border-zinc-600 placeholder:text-xl placeholder:text-center md:text-left placeholder:md:text-left focus:outline-none transform focus:rounded-xl duration-200'/>
					<button
						class='px-5 py-3 text-xs rounded-b-xl md:rounded-r-xl md:rounded-l-none transform hover:scale-105 hover:rounded-xl hover:text-white duration-500'> Sign up</button>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		section {
				height: auto;
				background-color: #235789;
				/*position: fixed;
				top: 34rem;
				bottom: 0rem;
				left: 0rem;
				right: 0rem;*/
		}
		.emailBox {
				background-color: #F3F4F5;
		}
		h2, p {
				color: #0C1115;
		}
		h2 {
				font-family: 'Hind Madurai', sans-serif;
				@apply text-3xl;
		}
		p, input, button {
				font-family: 'Hind Madurai', sans-serif;
				@apply text-2xl;
		}
		button {
				background-color: #EA3F45;
				color: #F3F4F5;
				@apply text-xl;
		}
		button:hover {
				background-color: #C4393CFF;
		}
		input {
        transition: transform 0.5s cubic-bezier(0, 0.3, 0.5, 1);
		}
		input:focus {
				transform: scale(1.05);

		}
		.borderoutset {
        border: 10px outset #ea3f45;
		}

</style>