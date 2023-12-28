<script lang="ts">
	export let id: string | null = null;
	export let lines: string | boolean | null = null;
	export let noescape = false;
</script>

<pre data-id={id || null}>
  <code data-trim data-line-numbers={lines || null} data-noescape={noescape || null}>
    <!-- curly brackets around slot content are required to prevent Svelte from interpreting the code -->
    <slot />
  </code>
</pre>
