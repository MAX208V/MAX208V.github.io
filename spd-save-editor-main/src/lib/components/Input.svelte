<script lang="ts">
	export let value = "";
	export let readonly = false;
</script>

<input bind:value type="text" {readonly} class="w-full rounded-sm border bg-morning-blue px-1" />
