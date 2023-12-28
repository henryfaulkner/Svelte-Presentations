<script lang="ts">
	export let id: string | null = null;
	export let animate = false;
	export let restart = false;
	export let backgroundGradient: string | null = null;
	export let backgroundColor: string | null = null;
	export let backgroundImage: string | null = null;
</script>

<section
	data-auto-animate-id={id}
	data-auto-animate={animate || null}
	data-auto-animate-restart={restart || null}
	data-background-gradient={backgroundGradient}
	data-background-color={backgroundColor}
	data-background-image={backgroundImage}
>
	<slot />
</section>
