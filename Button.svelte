<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}
</script>

<style>
	button {
	  background: rgba(145, 92, 182);
	  color: white;
	  border: none;
	  padding: 12px 24px;
	  border-radius: 16px;
	  box-shadow: 0 0 15px rgba(145, 92, 182, 0.4);
	}
</style>

<button on:click={handleClick}>
  Clicked {count} {count === 1 ? 'time' : 'times'}
</button>