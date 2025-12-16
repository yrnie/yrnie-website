<script lang="ts">
</script>

<div
	class="m-auto bg-linear-to-r from-blue-500 from-30% via-blue-400 to-blue-500 to-70% bg-fixed bg-center"
>
	<div class="sm:p-5 lg:p-10">
		<div
			class="mx-auto flex bg-neutral-800/60 sm:max-w-xl sm:rounded-2xl sm:backdrop-blur-sm md:max-w-2xl md:rounded-4xl md:p-4 lg:max-w-4xl lg:p-10 xl:max-w-6xl xl:p-12"
		>
			<div class="m-auto prose items-center justify-center font-mono font-thin prose-invert sm:p-5">
				<slot />
			</div>
		</div>
		<div
			class=" mx-auto flex bg-neutral-900 sm:mt-5 sm:max-w-xl sm:rounded-2xl sm:backdrop-blur-sm md:max-w-2xl md:rounded-4xl md:p-4 lg:max-w-4xl xl:max-w-6xl xl:p-10"
		>
			<div class="m-auto prose items-center justify-center p-3 font-mono font-thin prose-invert">
				<p>footer here</p>
			</div>
		</div>
	</div>
</div>
