<script>
	import ArrowRightIcon from 'svelte-remixicon/lib/icons/ArrowRightFill.svelte';
	import ArrowLeftIcon from 'svelte-remixicon/lib/icons/ArrowLeftFill.svelte';

	import { seo } from '$lib/store.js';

	$seo = {
		title: 'Table Bleu',
		description:
			'Popi Creations Meuble unique Design Furniture Table Moderne Hetre Plexi Couleur Bleu Salon'
	};
</script>

<div class="flex flex-col ">
	<div class="m-auto max-w-prose flex flex-col items-center p-3">
		<h1 class="text-3xl uppercase text-center ">Table Bleu</h1>
		<div>Hêtre - Multiplex - Alupanel - Verre armé</div>
		<div>40 x 100 x 35,5</div>
		<p class="text-gray-500">vendu</p>
		<img class="mt-32 mb-28" style="" src="tableuface.png" />
		<img class="mb-12" src="tableu.png" />
		<img class="" src="table-bleu-angle.png" />
		<div class="flex w-full justify-center items-center">
			<a class="/table-2" href="/commode">
				<ArrowLeftIcon size="30" />
			</a>
			<a class="ml-auto" href="/banc">
				<ArrowRightIcon size="30" />
			</a>
		</div>
	</div>
</div>

<style>
	h1 {
		color: gold;
	}
</style>
