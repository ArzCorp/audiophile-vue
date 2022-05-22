<template>
	<section class="block lg:flex pb-52">
		<Container>
			<figure class="w-full block lg:hidden mb-16">
				<img
					class="w-full hidden md:block"
					src="src/assets/img/shared/tablet/image-best-gear.jpg"
					alt="banner"
				/>
				<img
					class="w-full md:hidden"
					src="src/assets/img/shared/mobile/image-best-gear.jpg"
					alt="banner"
				/>
			</figure>
			<div class="mr-32 w-full lg:w-6/12">
				<h2
					class="text-[28px] md:text-[40px] text-center lg:text-left font-bold uppercase mb-8"
				>
					Bringing you the <br class="hidden lg:block" />
					<span class="text-[#D87D4A]"
						>best <br class="hidden md:block lg:hidden" />
					</span>
					audio gear
				</h2>
				<p
					class="text-black text-opacity-50 text-center lg:text-left text-sm w-full 2xl:w-10/12"
				>
					Located at the heart of New York City, Audiophile is the premier store
					for high end headphones, earphones, speakers, and audio accessories.
					We have a large showroom and luxury demonstration rooms available for
					you to browse and experience a wide range of our products. Stop by our
					store to meet some of the fantastic people who make Audiophile the
					best place to buy your portable audio equipment.
				</p>
			</div>
			<figure class="w-6/12 hidden lg:block">
				<img
					class="w-full"
					src="src/assets/img/shared/desktop/image-best-gear.jpg"
					alt="banner"
				/>
			</figure>
		</Container>
	</section>
</template>
<script>
import Container from '../Container.vue'
export default { components: { Container } }
</script>
