<script>
	export let answer = false;
</script>

{#if answer}
	<p style="color: green;">This answer was correct!</p>
{:else}
	<p style="color: red;">this answer was incorect!</p>
{/if}

