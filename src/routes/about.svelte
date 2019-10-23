<script>
	import Select from 'svelte-select';

	let items = ['one', 'two', 'three'];
	let selectedValue = undefined;
	
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<Select {items} bind:selectedValue></Select>