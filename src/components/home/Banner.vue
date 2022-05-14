<script setup>
import Button from '../Button.vue'
import Container from '../Container.vue'
</script>

<template>
	<div
		class="relative flex items-center justify-between bg-[#181818] text-white"
	>
		<Container>
			<div class="flex items-center justify-between">
				<div
					class="relative z-20 text-center lg:text-left pb-[158px] pt-[128px]"
				>
					<p
						class="text-sm leading-5 text-opacity-50 text-white mb-4 md:mb-6 tracking-[10px]"
					>
						NEW PRODUCT
					</p>
					<h2
						class="text-[36px] md:text-[56px] md:leading-[58px] leading-[40px] font-bold mb-6 uppercase"
					>
						XX99 Mark II <br />
						HeadphoneS
					</h2>
					<p
						class="text-sm text-white text-opacity-50 leading-6 font-medium mx-auto lg:mx-0 mb-10 w-full md:w-7/12 lg:w-9/12"
					>
						Experience natural, lifelike audio and exceptional build quality
						made for the passionate music enthusiast.
					</p>
					<Button>See Product </Button>
				</div>
				<figure
					class="z-0 absolute lg:static top-0 left-0 right-0 h-full w-full pb-10"
				>
					<img
						class="mx-auto h-full opacity-50 lg:opacity-100 object-cover md:object-contain"
						src="src/assets/img/home/desktop/image-hero.jpg"
						alt="hero"
					/>
				</figure>
			</div>
		</Container>
	</div>
</template>
