<script>
	import Testimonial from '$lib/components/testimonial/Testimonial.svelte';
</script>


<section class='bg-neutral-100 w-full flex place-content-center py-10'>
	<div class='grid md:grid-cols-3 gap-4 w-3/4'>
		<Testimonial
			company='Riot Games'
			logo='https://picsum.photos/200/300'
			name='David Apples'
			quote='By far the best place to receive affordable and official in-game currency for Valorant.'
			role='Intern'
		/>
		<Testimonial
			company='Roblox'
			logo='https://picsum.photos/200/300'
			name='David Baszucki'
			quote='We would always come back to this pricing model and become inspired by it so that our customers are appreciative.'
			role='CEO'
		/>
		<Testimonial
			company='Minecraft'
			logo='https://picsum.photos/200/300'
			name='Notch'
			quote='When I first hopped on Valorant, I kept on getting destroyed by enemy players. I wanted a skin, but the official Valorant store had inflated prices. This is the best offer I ever seen.'
			role='Former CEO'
		/>
		<Testimonial
			company='Hypixel'
			logo='https://picsum.photos/200/300'
			name='Bob Bob'
			quote='Ever since this dropped, I been getting aces every match with the basic package. I can see how well I am doing.'
			role='Patreon Supporter'
		/>
		<Testimonial
			company='Valve'
			logo='https://picsum.photos/200/300'
			name='Bob Apples'
			quote='What makes this so awesome is that it is official. As a bonus, you get Radianite that is half the original cost.'
			role='Beta Tester'
		/>
		<Testimonial
			company='Apple'
			logo='https://picsum.photos/200/300'
			name='John Adams'
			quote='The standard package is the best right now as it contains everything you really need as a player of Valorant.'
			role='Customer Support'
		/>
	</div>
</section>

<style>
	section {
		background-color: #235789;
	}
</style>
