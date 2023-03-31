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
	<Description date={1923}
							 summary={'He was born in Strasbourg, France.'} />
	<Description date={1939}
							 summary={'He participated in World War 2 in the French Resistance against the German-occupied France.'} />
	<Description date={'March 22nd, 2023'}
							 summary={'Google\'s Doodle celebrated him.'} />
</div>

<blockquote cite='https://forbes.com/quote/6447'>
	<p>"Do not the most moving moments of our lives find us without words?"</p>
</blockquote>

<p>For more information, see <a id='tribute-link' rel='noreferrer'
									href='https://en.wikipedia.org/wiki/Marcel_Marceau'
	 target='_blank'>Marcel Marceau's biography on Wikipedia</a></p>


<style>
		h1 {
        background-color: rgb(180, 190, 190);
				font-size: 60px;
				text-align: center;
		}
		p, figcaption {
				font-size: 20px;
		}
		figure {
				background-color: rgb(210, 150, 140);
				width: 100%;
		}
		img {
				max-width: 100%;
				margin: auto;
		}
		figcaption {
				text-align: center;
		}
		.flex-container {
        background-color: rgb(220, 100, 100);
				display: flex;
				flex-direction: row;
				justify-content: center;
				column-gap: 16px;
		}
		blockquote {
				width: 25%;
				height: auto;
				margin: auto;
				padding: 10px;
		}
</style>