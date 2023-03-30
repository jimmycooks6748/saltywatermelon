<script>
    export let answer = true;
</script>
{#if answer}
<p style="color: green;"> haha you thought
</p>
{:else}
<p> not quite... </p>
{/if}