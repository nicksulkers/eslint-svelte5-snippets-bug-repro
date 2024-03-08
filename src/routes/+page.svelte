<script lang="ts">
	const mySnippetInDisguise = mySnippet;
</script>

{#snippet mySnippet()}
	<p>Hello World!</p>
{/snippet}

{@render mySnippetInDisguise()}
