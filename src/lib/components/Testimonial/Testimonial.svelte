<!--Single testimonial card with company logo, product review, reviewer name-->
<script>
	export let quote =
		'Quote placeholder.';
	export let name = 'John Doe';
	export let role = 'CEO';
	export let company = 'Company Name';
	export let logo = 'https://via.placeholder.com/150';


</script>


<!--testimonial card styled with tailwind with shadow-->
<div class='w-full p-2'>
	<div class='robux p-4'>
		<div class='flex flex-col md:flex-row'>
			<div class='md:w-1/3'>
				<img alt='company logo'
						 class='rounded-full w-24 h-24 mx-auto md:mx-0 md:mr-6'
						 src={logo} />
			</div>
			<div class='md:w-2/3'>
				<p class='leading-tight text-justify text-2xl'>{quote}</p>
				<p class='text-right mt-2 text-2xl'>{name}</p>
				<p class='text-right text-2xl'>{role} at {company}</p>
			</div>
		</div>
	</div>
</div>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		.robux {
				background-color: #F3F4F5;
				border: 10px outset #ea3f45;
		}
		p {
				color: #0c1115;
				font-family: 'Hind Madurai', sans-serif;
		}
</style>