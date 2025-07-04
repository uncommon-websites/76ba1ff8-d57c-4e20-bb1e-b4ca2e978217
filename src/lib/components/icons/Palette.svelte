<script lang="ts">
	type Props = {
		class?: string;
	};
	
	const { class: className = "size-4" }: Props = $props();
</script>

<svg class={className} fill="none" stroke="currentColor" viewBox="0 0 24 24">
	<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zM7 3H5a2 2 0 00-2 2v12a4 4 0 004 4h2a4 4 0 004-4V5a2 2 0 00-2-2H7z" />
	<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 3h2a2 2 0 012 2v6M16 3v10a4 4 0 004 4v0a4 4 0 004-4V5a2 2 0 00-2-2h-2M16 3a2 2 0 012 2v6" />
</svg>