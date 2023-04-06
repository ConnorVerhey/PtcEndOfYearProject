<script>
	export let answer = false;
</script>

{#if answer}
	<p class="correct">This answer was correct!</p>
{:else}
	<p class="incorrect">this answer was incorect!</p>
{/if}

<style>
.correct {
	color: green;
	font-weight: bold;
	text-decoration: undeline; 
}

.incorrect {
	color: red;
	font-weight: bold; 
	text-decoration: underline;
	font-style: italic; 
}
</style>