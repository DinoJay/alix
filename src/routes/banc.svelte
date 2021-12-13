<script>
	import ArrowRightIcon from 'svelte-remixicon/lib/icons/ArrowRightFill.svelte';
	import ArrowLeftIcon from 'svelte-remixicon/lib/icons/ArrowLeftFill.svelte';
	import { seo } from '$lib/store.js';

	$seo = {
		title: 'Banc',
		description: 'Banc Sapin Bleu Meuble Popi design Atelier'
	};
</script>

<div class="flex flex-col ">
	<div class="m-auto max-w-prose flex flex-col items-center p-3">
		<h1 class="text-3xl uppercase text-center mb-3">Banc CHAUSSETTE DE SPORT</h1>
		<p>Sapin 32 x 78,5 x 16,5</p>
		<p class="text-gray-500">100€</p>
		<img class="mb-52 mt-28" style="" src="banc-face.png" />
		<img class="mb-52" src="banc-haut.png" />
		<img class="mb-40" width="400" src="banc-detail.png" />
		<img class="mb-32 mt-32 px-12" src="banc-situation.webp" />
		<img class="mb-12 px-12" src="banc-situation2.webp" />
		<div class="flex w-full justify-center items-center  ">
			<a class="/table-2" href="/table-bleu">
				<ArrowLeftIcon size="30" />
			</a>
			<a class="ml-auto" href="/meuble-entree">
				<ArrowRightIcon size="30" />
			</a>
		</div>
	</div>
</div>

<style>
	h1 {
		color: #5cac92;
	}
</style>
