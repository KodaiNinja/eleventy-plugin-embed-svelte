<script lang="ts">
	let count: number = 0; // <- TypeScript!
</script>

<style>
	div {
		padding: 1em;
		margin-bottom: 1em;
		border: 1px solid crimson;
		width: fit-content;
		box-shadow: 0 8px 6px -6px crimson;
		border-radius: 5px;
	}
</style>

<div>
	<h2>
		Here's the obligatory
		<strong>&ldquo;reactive&rdquo;</strong>
		counter:
		{count}
	</h2>

	<button on:click={() => ++count}>Up the count!</button>
</div>
