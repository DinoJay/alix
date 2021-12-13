<script>
	import ArrowRightIcon from 'svelte-remixicon/lib/icons/ArrowRightFill.svelte';

	import { seo } from '$lib/store.js';

	$seo = {
		title: 'Table Grande Soeur',
		description: 'Popi Creations Meuble unique Design Furniture Table Moderne Hetre Plexi Couleur'
	};
</script>

<div class="flex flex-col ">
	<div class="sm:min-w-prose m-auto max-w-prose flex flex-col items-center p-3">
		<h1 class="mx-auto text-3xl uppercase text-center mb-3">Table grande soeur</h1>

		<p>Hêtre - Plexi fluo - Alupanel -Multiplex bouleau - Verre</p>
		<p>40 x 70,5 x 46,5</p>
		<p class="text-gray-500">420€</p>
		<img class="mt-20" src="grandesoeur-face.webp" />
		<img class="mb-40 mt-48" style="" src="grandesoeur-face.webp" />
		<img class="" src="grandesoeur-haut.webp" />
		<img class="mt-40 mb-12 " src="grandesoeur-situation.webp" />
		<div class="flex w-full justify-center items-center mb-3 ">
			<a class="ml-auto" href="/table-1">
				<ArrowRightIcon size="30" />
			</a>
		</div>
	</div>
</div>

<style>
	h1 {
		color: dodgerblue;
	}

	img {
		@apply px-1;
	}
</style>
