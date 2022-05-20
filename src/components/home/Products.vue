<template>
	<section>
		<Container>
			<div class="gap-y-12 gap-x-8 grid grid-cols-2 pb-36">
				<div class="bg-[#D87D4A] col-span-2">
					<div
						class="max-w-[900px] block lg:flex text-white pt-[52px] lg:pt-24 h-full lg:h-[560px]"
					>
						<figure
							class="h-[237px] lg:h-full w-full xl:min-w-max mt-auto ml-0 lg:ml-8 xl:ml-28"
						>
							<img
								class="h-full mx-auto xl:mx-0"
								src="src/assets/img/home/desktop/image-speaker-zx9.png"
								alt="speaker-zx9"
							/>
						</figure>
						<div
							class="text-center lg:text-left ml-14 xl:ml-36 mr-8 xl:mr-24 pb-16 lg:pb-0"
						>
							<p class="mt-16 lg:mt-0 font-bold text-5xl mb-6">
								ZX9 <br />
								SPEAKER
							</p>
							<p
								class="font-medium text-sm text-white text-opacity-75 mb-10 lg:mb-16"
							>
								Upgrade to premium speakers that are phenomenally built to
								deliver truly remarkable sound.
							</p>
							<Button black>See Product</Button>
						</div>
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
