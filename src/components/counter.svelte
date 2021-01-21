<script>
	let count = 0;

	const increment = () => {
		count += 1;
	};
</script>

<button on:click={increment}>
	Clicks: {count}
</button>

<style>
	button {
		padding: 1em 2em;
		color: #ff3e00;
		background-color: rgba(255, 62, 0, 0.1);
		border-radius: 2em;
		width: 200px;
		font-variant-numeric: tabular-nums;
	}

	button:active {
		background-color: rgba(255, 62, 0, 0.2);
	}
</style>