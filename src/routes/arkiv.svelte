<script>
	import Banner from "../components/banner.svelte";
</script>

<svelte:head>
	<title>Arkiv</title>
</svelte:head>

<Banner />
<main>
	<h1>Våre Tideligere Revyer:</h1>
	<ul>
		{#each ['2020', '2019', '2018', '2017'] as year}
			<li><a href="/{year}">{year}</a></li>
		{/each}
	</ul>
</main>
