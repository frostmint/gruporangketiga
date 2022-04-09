<script>
	import { Checkbox } from "fluent-svelte";
</script>

<div>
	<Checkbox>Checkbox</Checkbox>
	<Checkbox checked>Checkbox</Checkbox>
	<Checkbox checked indeterminate>Checkbox</Checkbox>
</div>
<div>
	<Checkbox disabled>Checkbox</Checkbox>
	<Checkbox checked disabled>Checkbox</Checkbox>
	<Checkbox checked disabled indeterminate>Checkbox</Checkbox>
</div>

<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	
	:global(body) {
		background-color: var(--fds-solid-background-base);
		color: var(--fds-text-primary);
	}
</style>
