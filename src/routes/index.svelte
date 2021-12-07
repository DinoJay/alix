<script>
	import Creations from './creations.svelte';
</script>

<div class="md:flex">
	<a class="creationsk" href="/creations">
		<div class="flex items-center justify-center">
			<div class="creations-text absolute m-auto  text-white font-sans uppercase">Creation</div>
			<img style="" src="creations.png" />
		</div>
	</a>
	<a class="collab" href="/collaborations">
		<div class="flex items-center justify-center h-full">
			<div class="collab-text absolute m-auto font-sans uppercase">Collab</div>
			<img style="max-height:300px" src="slash.png" />
		</div>
	</a>
</div>

<style>
	.creationsk {
		min-width: 50%;
	}
	.collab {
		min-width: 50%;
	}

	.collab-text {
		font-size: 4rem;
	}
	.creations-text {
		font-size: 4rem;
	}
</style>
