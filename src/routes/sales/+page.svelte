<script>
	import HeroSideImageButton from
			'$lib/components/hero/HeroSideImageButton.svelte';
	import EmailSubscriptionBox from '$lib/components/EmailSubscriptionBox.svelte';
	import PriceTable from '$lib/components/PriceTable.svelte';
	import TestimonialGrid from '$lib/components/Testimonial/TestimonialGrid.svelte';
	import Testimonial from '$lib/components/Testimonial/Testimonial.svelte';
	import About from '$lib/components/About.svelte';
</script>


<HeroSideImageButton title='The only place you need to purchase'
										 subtitle='Valorant Points' buttonText1='Pricing'
										 imageUrl='https://images3.alphacoders.com/114/1149399.png'/>

<section class='md:px-96 px-10'>
	<h2>Valorant</h2>
	<p>Since the release of Valorant in 2020, the in-game store has been
		 providing animated and static bundles for the community. Each
		 individual skin inside are priced expensively which
		 incentivizes players to purchase the bargained price of the bundle.
		 Over the few last years, the prices of these steadily grew. There are 5
	tiers that determine the price of a bundle. The premium tier has seen
		 minimum prices of 70 dollars and recently, the Radiant
		 Entertainment
		 System bundle of the ultra tier hit the highest yet price of 11900 VP.
		 That is taking about 120 dollars out of your wallet. Lets not forget
		 that these animated bundles come with Radianite upgrades required to
		 unlock the full potential. You would need around 120 Radianite which is
		 90 dollars. In total you've spent 210 dollars.
	</p>
	<h2>Why choose us?</h2>
	<p>A single-purchase of Valorant Points is expensive and comes with no
		 extra benefits. Our pricing involves a different way to receive
		 Valorant Points and extra benefits. Using a subscription-based payment,
	you earn VP at a cheaper price, but in exchange you trade a month of your
		 time for this. Though this isn't a single-purchase since it comes with
		 extra benefits. Titles, key-chain buddies, and banners are included free
		 of charge as well as 50 Radianite points (They do not stack). The basic
		 package also includes access to your own personal gameplay statistics.
		 Each package is tailored to a specific audience.
		 </p>



</section>
<div>
<Testimonial
	quote='I am surpised that no corporate greed exists here. They are basically giving you free money.'
						 name='Bill Gates' role='CEO'
						 company='Microsoft'
						 logo='https://picsum.photos/200/300'/>
</div>
<PriceTable/>
<section class='md:-mt-44 md:px-96 px-10'>
	<p>The basic and standard
		 are geared towards casual players, and it gives access to reverting skin
		 upgrades and public gameplay statistics. The premium is
		 geared towards collectors and competitive players which gives Night Market's dates and
		 discounted bundles.
	</p>
</section>
<TestimonialGrid />



<About />
<EmailSubscriptionBox/>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Hind+Madurai:wght@500&family=Skranji:wght@700&display=swap');
		@media (min-width: 768px)
    {
				div {
            padding-left: 40rem;
            padding-right: 40rem;
				}
		}
		div {
				background-color: #235789;
				@apply py-10 w-full;
		}
		section {
				background-color: #F3F4F5;

				@apply w-full py-10;
		}
		h2 {
				color: #0C1115;
				font-family: "Hind Madurai", sans-serif;
				@apply text-center text-3xl mt-10 mb-4;
		}
		p {
				color: #0C1115;
        font-family: "Hind Madurai", sans-serif;
				@apply text-center text-2xl mb-6;
		}
</style>

