<script>
	export let name;

	let age = 1 + "岁";
	export let sex = "男";
</script>

<main>
	<h1>Hello {name}!</h1>
	<h2>age = {age}</h2>
	<h2>sex : {sex}</h2>
	<p>Visit the to learn how to build Svelte apps.</p>
	<div>
		<img src="../static/images/OIP.jpg" alt="" />
	</div>
	<p>
		<img src="/a1.jpg" alt="" />
	</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	img {
		max-width: 100%;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
