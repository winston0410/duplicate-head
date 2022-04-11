<script lang="ts" context="module">
    import { mkSchema } from '$lib/jsonld'
</script>

<script lang="ts">
    let orgSchema = {
        "@context": "https://schema.org/",
		"@type": "Organization",
    }
</script>

<svelte:head>
    {@html mkSchema(orgSchema)}
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
