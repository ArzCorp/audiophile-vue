<script setup>
import Button from '../Button.vue'
import Container from '../Container.vue'
</script>

<template>
	<div class="flex items-center justify-between bg-[#181818] text-white">
		<Container>
			<div class="flex items-center justify-between">
				<div class="pb-[158px] pt-[128px]">
					<p
						class="text-sm leading-5 text-opacity-50 text-white mb-6 tracking-[10px]"
					>
						NEW PRODUCT
					</p>
					<h2 class="text-[56px] leading-[58px] font-bold mb-6 uppercase">
						XX99 Mark II HeadphoneS
					</h2>
					<p
						class="text-sm text-white text-opacity-50 leading-6 font-medium mb-10 w-9/12"
					>
						Experience natural, lifelike audio and exceptional build quality
						made for the passionate music enthusiast.
					</p>
					<Button>See Product </Button>
				</div>
				<figure class="h-full w-full pb-10">
					<img
						class="mx-auto h-full"
						src="src/assets/img/home/desktop/image-hero.jpg"
						alt="hero"
					/>
				</figure>
			</div>
		</Container>
	</div>
</template>
