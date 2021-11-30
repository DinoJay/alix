<script>
	import '../styles/tailwind.css';
</script>

<div id="first" class="">
	<a href="/banc">
		<img class="md:max-w-prose" src="banc.png" />
	</a>
</div>
<div id="sec" class="">
	<a href="/buffet">
		<img class="md:max-w-prose" src="buffet.png" />
	</a>
</div>
<div id="third" class="">
	<a href="/commode">
		<img class="md:max-w-prose" src="commode.png" />
	</a>
</div>
<div id="fourth" class="">
	<a href="/meuble-entree">
		<img class="md:max-w-prose" src="meuble entree.png" />
	</a>
</div>

<style>
	#first {
		@apply flex;
		@apply justify-center;
		/* background-size: 100% auto; */
		/* background-repeat: no-repeat; */
		background-color: dodgerblue;
	}
	#sec {
		@apply bg-center;
		@apply flex;
		@apply justify-center;
		/* background-size: 100% auto; */
		background-repeat: no-repeat;
		background-color: tomato;
	}
	#third {
		@apply bg-center;
		@apply flex;
		@apply justify-center;
		/* background-size: 100% auto; */
		background-repeat: no-repeat;
		background-color: lightskyblue;
	}
	#fourth {
		@apply bg-center;
		@apply flex;
		@apply justify-center;
		background-size: 100% auto;
		background-repeat: no-repeat;
		background-color: yellow;
	}
</style>
