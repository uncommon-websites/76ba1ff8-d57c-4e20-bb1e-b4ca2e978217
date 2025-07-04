<script lang="ts">
	type Props = {
		class?: string;
	};
	
	const { class: className = "size-4" }: Props = $props();
</script>

<svg class={className} fill="none" stroke="currentColor" viewBox="0 0 24 24">
	<circle cx="12" cy="12" r="10" />
	<polyline points="12,6 12,12 16,14" />
</svg>