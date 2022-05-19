<template>
	<section>
		<Container>
			<div class="gap-y-12 gap-x-8 grid grid-cols-2 pb-36">
				<div class="col-span-2 flex bg-[#D87D4A] text-white pt-24 h-[560px]">
					<figure class="h-full min-w-max mt-auto ml-28">
						<img
							class="h-full"
							src="src/assets/img/home/desktop/image-speaker-zx9.png"
							alt="speaker-zx9"
						/>
					</figure>
					<div class="ml-36 mr-24">
						<p class="font-bold text-5xl mb-6">
							ZX9 <br />
							SPEAKER
						</p>
						<p class="font-medium text-sm text-white text-opacity-75 mb-16">
							Upgrade to premium speakers that are phenomenally built to deliver
							truly remarkable sound.
						</p>
						<Button black>See Product</Button>
					</div>
				</div>
				<div class="relative col-span-2">
					<div class="absolute top-20 left-24">
						<p class="mb-8 font-bold text-[28px]">ZX7 SPEAKER</p>
						<Button ghost>See Product</Button>
					</div>
					<figure class="w-full">
						<img
							class="w-full"
							src="src/assets/img/home/desktop/image-speaker-zx7.jpg"
							alt="speaker-zx7"
						/>
					</figure>
				</div>
				<figure class="w-full">
					<img
						class="w-full"
						src="src/assets/img/home/desktop/image-earphones-yx1.jpg"
						alt="image-earphones-yx1"
					/>
				</figure>
				<div class="flex items-center justify-start pl-24 bg-[#F1F1F1]">
					<div>
						<p class="font-bold text-[28px] mb-8">YX1 EARPHONES</p>
						<Button ghost>See Product</Button>
					</div>
				</div>
			</div>
		</Container>
	</section>
</template>

<script>
import Button from '../Button.vue'
import Container from '../Container.vue'

export default { components: { Button, Container } }
</script>
