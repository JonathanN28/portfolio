<script>
	import subImg from '$lib/assets/kobby-mendez-UOl_IN96w0M-unsplash.jpg';
</script>

<section
	class='flex items-center justify-center h-full p-10 bg-zinc-700 ml-auto mr-auto'>
	<div class='bg-zinc-800 p-2 mx-6 rounded-2xl emailBox borderoutset'>
		<div class='flex flex-col md:flex-row rounded-l-xl'>
			<img src={subImg} alt='boat on a lake'
					 class='object-fit object-cover rounded-t-xl h-80 md:h-64 md:rounded-l-xl md:rounded-r-none transform hover:scale-105 hover:rounded-xl duration-200' />
			<div class='p-6 md:p-12'>
				<h2
					class='font-serif text-xl font-medium text-center text-white md:text-left'> Receive 99% discounts on gold bars</h2>
				<p
					class='max-w-xs leading-5 tracking-wide text-center text-white md:text-left'> Obtain daily coupon codes from 0 to 100% discount for purchasing gold bars. Sign up with your email.</p>
				<div
					class='flex flex-col mt-5 space-y-4 md:space-x-3 md:flex-row md:space-y-0'>
					<input type='text' placeholder='Enter your email address'
								 class='p-2 px-4 text-center text-black bg-neutral-200 border border-zinc-600 placeholder:text-xs placeholder:text-center md:text-left placeholder:md:text-left focus:outline-none transform focus:rounded-xl duration-200'/>
					<button
						class='px-5 py-3 text-xs rounded-b-xl md:rounded-r-xl md:rounded-l-none text-zinc-800 bg-lime-500 transform hover:scale-105 hover:rounded-xl hover:bg-lime-700 hover:text-white duration-500'> Sign up</button>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		section {
				background-color: #235789;
		}
		.emailBox {
				background-color: #F3F4F5;
		}
		h2, p {
				color: #0C1115;
		}
		h2 {
				font-family: 'Hind Madurai', sans-serif;
		}
		p, input, button {
				font-family: 'Hind Madurai', sans-serif;
		}
		button {
				background-color: #EA3F45;
				color: #F3F4F5;
		}
		button:hover {
				background-color: #C4393CFF;
		}
		input {
        transition: transform 0.5s cubic-bezier(0, 0.3, 0.5, 1);
		}
		input:focus {
				transform: scale(1.1);

		}
		.borderoutset {
        border: 10px outset #ea3f45;
		}

</style>