<script lang="ts">
	import Sample from './Sample.svelte';
	let url = 'https://example.com' as const;
	let newUrl: URL = new URL('https://newexample.com');
</script>

<Sample {url} {newUrl} />
