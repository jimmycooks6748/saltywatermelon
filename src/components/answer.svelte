<script>
    export let answer = true;
</script>
{#if answer}
<p style="color: green;"> haha you thought
    
</p>
{:else}
<p style="color: red;"> not quite... </p>
{/if}
<style>
	.correct, .incorrect {
		font-weight: bold;
		text-decoration: underline;
	}
	.correct {
		color: green;
	}
	.incorrect {
		color: red;
	}
</style>