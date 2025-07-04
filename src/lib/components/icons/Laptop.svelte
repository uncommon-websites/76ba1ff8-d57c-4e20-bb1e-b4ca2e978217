<script lang="ts">
	type Props = {
		class?: string;
	};
	
	const { class: className = "size-4" }: Props = $props();
</script>

<svg class={className} fill="none" stroke="currentColor" viewBox="0 0 24 24">
	<rect x="4" y="4" width="16" height="12" rx="1" />
	<line x1="2" y1="20" x2="22" y2="20" />
</svg>