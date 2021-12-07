<script>
	import '../styles/tailwind.css';
	import MenuIcon from 'svelte-remixicon/lib/icons/MenuLine.svelte';
	let open = false;
	const paths = ['popibleu.png', 'popijaune.png', 'popivert.png', 'popirouge.png'];
	$: i = new Date().getMilliseconds() % paths.length;
</script>

<nav class="flex items-center justify-between flex-wrap p-6">
	<div class="flex items-center flex-no-shrink  mr-6">
		<a href="/">
			<img style="height: 50px" src={paths[i]} height="20" />
		</a>
	</div>
	<div class="block ">
		<button on:click={() => (open = !open)} class="flex items-center px-3 py-2 text-teal-lighter ">
			<MenuIcon size="40px" />
		</button>
	</div>
	<div class="w-full block  {!open && 'hidden'} ">
		<div class="text-sm ">
			<a href="creations" class="block mt-4  text-teal-lighter mr-4"> Creations </a>
			<a href="collab" class="block mt-4  text-teal-lighter mr-4"> Collab </a>
			<a href="contact" class="block mt-4  text-teal-lighter "> Contact </a>
		</div>
	</div>
</nav>
<main>
	<slot />
</main>
