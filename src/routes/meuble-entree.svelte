<script>
	import ArrowRightIcon from 'svelte-remixicon/lib/icons/ArrowRightFill.svelte';
	import ArrowLeftIcon from 'svelte-remixicon/lib/icons/ArrowLeftFill.svelte';

	import { seo } from '$lib/store.js';

	$seo = {
		title: 'Meuble Entree',
		description: 'Popi Creations Meuble unique Design Furniture Bleu Sapin Console'
	};
</script>

<div class="flex flex-col ">
	<div class="m-auto max-w-prose flex flex-col items-center p-3">
		<h1 class=" text-3xl uppercase text-center mb-3">Console entrée</h1>
		<div>Sapin - Peuplier 86 x 86 x 12</div>
		<p class="text-gray-500">vendu</p>
		<img class="" src="entree-face.webp" />
		<img src="entree-haut.webp" />
		<img class=" mt-16" style="" src="entree-cote.webp" />
		<img class="mt-16 mb-6" src="entree-diag.webp" />
		<div class="flex w-full justify-center items-center  ">
			<a class="/table-2" href="/banc">
				<ArrowLeftIcon size="30" />
			</a>
			<a class="ml-auto" href="/buffet">
				<ArrowRightIcon size="30" />
			</a>
		</div>
	</div>
</div>

<style>
	h1 {
		color: #f9b256;
	}
</style>
