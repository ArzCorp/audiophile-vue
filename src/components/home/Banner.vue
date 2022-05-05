<script setup>
import Button from '../Button.vue'
</script>

<template>
	<div class="flex items-center justify-between bg-[#181818] text-white">
		<div class="w-full max-w-[80%] mx-auto flex items-center justify-between">
			<div>
				<p>NEW PRODUCT</p>
				<h2>XX99 Mark II HeadphoneS</h2>
				<p>
					Experience natural, lifelike audio and exceptional build quality made
					for the passionate music enthusiast.
				</p>
				<Button />
			</div>
			<figure class="h-full w-full pb-10">
				<img
					class="mx-auto w-[60%]"
					src="src/assets/img/home/desktop/image-hero.jpg"
					alt="hero"
				/>
			</figure>
		</div>
	</div>
</template>
