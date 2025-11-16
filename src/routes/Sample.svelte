<script lang="ts">
	let { url, newUrl }: { url: string; newUrl: URL } = $props();
	let homepage: string = 'https://example.com';
</script>

<a href={url}>Visit Example</a>

<a href={newUrl.href}>Visit Example</a>

<a href="https://example.com">Visit Example</a>

<a href={homepage}>Visit Homepage</a>
