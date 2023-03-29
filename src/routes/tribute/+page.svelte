<script>
  // import Header from '$lib/components/header.svelte';
	// import Footer from '$lib/components/footer.svelte';
	import Description from '$lib/components/description.svelte';
	import src from '$lib/assets/marcel-marceau.jpg';
</script>

<!--<Header/>-->
<!--&lt;!&ndash; Your content goes here &ndash;&gt;-->
<!--<Footer/>-->

<h1 id='title'>Marcel Marceau</h1>
<figure id='img-div'>
	<img id='image' {src} alt="Marcel Marceau in a chair facing towards the reader" />
	<figcaption
		id='img-caption'>Marcel Marceau posing at us in a red cushy chair.
	Hands holding a hat that lay upon his lap.</figcaption>
</figure>
<div id='tribute-info' class='flex-container'>
	<Description date={''}
							 summary={'He'} />
	<Description date={1923}
							 summary={'He was born in Strasbourg, France.'} />
	<Description date={1939}
							 summary={'He participated in World War 2 in the French Resistance against the German-occupied France.'} />
	<Description date={'March 22nd, 2023'}
							 summary={'Google\'s Doodle celebrated him.'} />
</div>



<style>
		img {
				width: 500px;
		}
		.flex-container {
				display: flex;
				flex-direction: row;
				column-gap: 16px;
		}
</style>