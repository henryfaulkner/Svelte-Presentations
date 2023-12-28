<script lang="ts">
	import Slide from './slide.svelte';
</script>

<!-- Introduction Slide - says nothing - date -->
<!-- Now Logo animation -->
<Slide animate backgroundColor="aquamarine">
	<div class="absolute left-[-275px] top-[-280px]">
		<img src="now-logo.svg" class="rotate-image h-36 w-36" />
	</div>
	<div class="absolute right-[-275px] top-[-280px]">
		<img src="now-logo.svg" class="rotate-image h-36 w-36" />
	</div>
	<div class="r-fit-text relative left-0 top-[-60px] text-[#244538]">🔥NowAccount App Update🔥</div>
	<div class=" relative left-0 top-[-80px] pt-8 text-[#244538]">🎊January 2nd, 2024🎉</div>
</Slide>

<!-- Quick Joke -->
<!-- meme -->

<!-- Summary -->

<Slide animate backgroundGradient="linear-gradient(to bottom, #c1d2c7, #ff8700)">
	<div data-id="launch-title" class="font-semibold text-[#244538]">
		We are launching <div class="inline underline decoration-[#ff8700] decoration-wavy">
			3 new features.
		</div>
	</div>
	<div class="mt-14 flex place-content-center gap-2">
		<div
			data-id="box-1"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-red-600 text-[48px]"
		>
			📧
		</div>
		<div
			data-id="box-2"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-green-600 text-[48px]"
		>
			📜
		</div>
		<div
			data-id="box-3"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-blue-600 text-[48px]"
		>
			👩‍💼
		</div>
	</div>
</Slide>

<Slide animate backgroundGradient="linear-gradient(to bottom, #c1d2c7, #ff8700)">
	<div data-id="launch-title" class="font-semibold text-[#244538]">
		We are launching <div class="inline underline decoration-[#ff8700] decoration-wavy">
			3 new features.
		</div>
	</div>
	<div class="mt-14 flex items-center justify-center gap-2">
		<div
			data-id="box-1"
			class="mx-12 flex h-[200px] w-[200px] items-center justify-center rounded-lg bg-red-600 px-2"
		>
			<div class="text-[96px]">
				📧
				<div class="text-[18px] text-[#ebebeb]">Confirmation Email<br /> Enhancement</div>
			</div>
		</div>
		<div
			data-id="box-2"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-green-600 text-6xl"
		>
			📜
		</div>
		<div
			data-id="box-3"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-blue-600 text-6xl"
		>
			👩‍💼
		</div>
	</div>
</Slide>

<Slide animate backgroundGradient="linear-gradient(to bottom, #c1d2c7, #ff8700)">
	<div data-id="launch-title" class="font-semibold text-[#244538]">
		We are launching <div class="inline underline decoration-[#ff8700] decoration-wavy">
			3 new features.
		</div>
	</div>
	<div class="mt-14 flex items-center justify-center gap-2">
		<div
			data-id="box-1"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-red-600 text-[48px]"
		>
			📧
		</div>
		<div
			data-id="box-2"
			class="mx-12 flex h-[200px] w-[200px] items-center justify-center rounded-lg bg-green-600 px-2"
		>
			<div class="text-[96px]">
				📜
				<div class="text-[18px]">Onboarding History<br /> Feature</div>
			</div>
		</div>
		<div
			data-id="box-3"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-blue-600 text-6xl"
		>
			👩‍💼
		</div>
	</div>
</Slide>

<Slide animate backgroundGradient="linear-gradient(to bottom, #c1d2c7, #ff8700)">
	<div data-id="launch-title" class="font-semibold text-[#244538]">
		We are launching <div class="inline underline decoration-[#ff8700] decoration-wavy">
			3 new features.
		</div>
	</div>
	<div class="mt-14 flex items-center justify-center gap-2">
		<div
			data-id="box-1"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-red-600 text-[48px]"
		>
			📧
		</div>
		<div
			data-id="box-2"
			class="mx-12 flex h-[125px] w-[125px] items-center justify-center rounded-lg bg-green-600 text-6xl"
		>
			📜
		</div>
		<div
			data-id="box-3"
			class="mx-12 flex h-[200px] w-[200px] items-center justify-center rounded-lg bg-blue-600 px-2"
		>
			<div class="text-[96px]">
				👩‍💼
				<div class="text-[18px]">Client Dashboard<br /> Feature</div>
			</div>
		</div>
	</div>
</Slide>

<!-- 3 Feature summary bulletpoints -->
<!-- separate into 4 slides; highlighting bullet points as they are being talked about -->
<Slide>
	<Slide animate backgroundColor="#ffcd56">
		<div data-id="feature-title" class="r-fit-text text-start text-[#9a56ff]">
			Auto-Confirmation Email<br /> Enhancement
		</div>
		<div data-id="feature-content" class="text-start text-[#9a56ff]">
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🧑</div>
				<div>This is for: Account Managers and Clients.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>New email templates for automatic confirmation emails.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Invoice files are now attached to the confirmation emails.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Email Correspondence Module.</div>
			</div>
		</div>
	</Slide>
	<Slide animate backgroundColor="#ff6161">
		<div data-id="feature-title" class="r-fit-text text-start text-[#61ff61]">
			Onboarding History<br /> Feature
		</div>
		<div data-id="feature-content" class="text-start text-[#61ff61]">
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🧑</div>
				<div>This is for: Sales and Underwriting.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Consolidated Client Journey Visualization.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Displays every answer given by a client during onboarding.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Easy search functionality.</div>
			</div>
		</div>
	</Slide>
	<Slide animate backgroundColor="#36a2eb">
		<div data-id="feature-title" class="r-fit-text text-start text-[#5a36eb]">
			Client Dashboard<br /> Feature
		</div>
		<div data-id="feature-content" class="text-start text-[#5a36eb]">
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🧑</div>
				<div>This is for: Clients.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>New ways to navigate NowAccount.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>NowAccount Observability.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Customizable Settings + Drag-and-Drop.</div>
			</div>
			<div class="flex">
				<div class="pr-[12px] pt-[12px] text-[24px]">🔥</div>
				<div>Intuitive Statistics.</div>
			</div>
		</div>
	</Slide>
</Slide>

<!-- Internal Dashboard Feature teaser -->
<Slide backgroundGradient="linear-gradient(to bottom, #c1d2c7, #ff8700)">
	<div class="relative top-[-60px] text-[64px] text-[#244538]">
		Account Manager Dashboard<br /> Feature coming soon...
	</div>
	<div class="relative top-[-30px] text-[64px]">👩‍💼 + 📊 = 📈</div>
</Slide>

<!-- Conclusion -->
<!-- meme -->
<Slide animate backgroundColor="#d18ffb">
	<div class="">
		<div class="relative left-[38%]">
			<iframe
				height="215"
				width="215"
				src="https://giphy.com/embed/CxhWJeIicfOEynsEn6"
				frameBorder="0"
				class="giphy-embed"
				allowFullScreen
			></iframe>
		</div>

		<div class="pt-12 text-[#fbe58f]">Thank you for your time.</div>
	</div>
</Slide>

<style>
	@keyframes rotate {
		from {
			transform: rotate(0deg);
		}
		to {
			transform: rotate(360deg);
		}
	}

	/* Apply the rotation animation to the image */
	.rotate-image {
		/* Apply the rotation animation */
		animation: rotate infinite linear 5s; /* You can adjust the duration and timing function */
	}

	div {
		font-family: 'Manrope', sans-serif;
	}
</style>
