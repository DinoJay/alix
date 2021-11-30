<script>
	import Creations from './creations.svelte';
</script>

<div class="md:flex">
	<a class="creationsk" href="/creations">
		<div class="flex items-center justify-center">
			<div class="creations-text absolute m-auto text-5xl">Creations</div>
			<img src="everest.jpeg" />
		</div>
	</a>
	<a class="collab" href="/collaborations">
		<div class="flex items-center justify-center h-full">
			<div class="collab-text absolute m-auto text-5xl text-yellow-300">Collab</div>
			<img src="slash.jpeg" />
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
		font-size: 5rem;
	}
	.creations-text {
		font-size: 5rem;
	}
</style>
