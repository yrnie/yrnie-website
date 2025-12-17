<script lang="ts">
	import { page } from '$app/state';
	import SiteContainer from '$lib/components/Content/SiteContainer.svelte';
	import robot from '$lib/assets/error_robot.png';
</script>

<SiteContainer background_tags="bg-gray-900">
	<div class="items-center justify-center">
		<h1 class="m-auto">Something went wrong...</h1>
		<p class="m-auto">Error: {page.error?.message}</p>
		<a href="/" class="m-auto">Go to homepage</a>
		<img src={robot} alt="shrugging robot" class="m-auto lg:size-full" />
	</div>
</SiteContainer>
