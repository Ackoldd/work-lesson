<h1>Welcome to SvelteKit</h1>
<script>
	/** @type {import('./$types').PageData} */
	export let data;
</script>

<div>ID {data.product.id}</div>
<div>TITLE {data.product.idtitle}</div>
<img src={data.product.thumbnail} alt="thumbnailImage" />