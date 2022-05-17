<template>
	<Container>
		<ul class="flex gap-7 justify-center pt-24 pb-40">
			<li v-for="tab in tabs">
				<div
					:key="tab.id"
					class="bg-[#F1F1F1] flex justify-center pb-8 pt-28 relative min-h-[205px] w-[350px]"
				>
					<figure class="mx-auto w-[125px] h-[170px] absolute -top-[50px]">
						<img
							class="mx-auto w-full h-full object-contain"
							:src="tab.img"
							:alt="tab.name"
						/>
					</figure>
					<div>
						<h3 class="text-center font-bold text-lg mb-3">{{ tab.name }}</h3>
						<p class="text-center text-xs text-black text-opacity-50">
							Shop <i class="ml-1 fas fa-chevron-right text-[#D87D4A]" />
						</p>
					</div>
				</div>
			</li>
		</ul>
	</Container>
</template>

<script>
import Container from '../Container.vue'
export default {
	data() {
		return {
			tabs: [
				{
					id: 1,
					name: 'HEADPHONES',
					path: '/headphones',
					img: 'src/assets/img/shared/desktop/image-headphones.png',
				},
				{
					id: 2,
					name: 'SPEAKERS',
					path: '/speakers',
					img: 'src/assets/img/shared/desktop/image-speakers.png',
				},
				{
					id: 3,
					name: 'EARPHONES',
					path: '/earphones',
					img: 'src/assets/img/shared/desktop/image-earphones.png',
				},
			],
		}
	},
	components: { Container },
}
</script>
