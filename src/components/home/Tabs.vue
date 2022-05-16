<template>
	<ul class="flex justify-between">
		<li v-for="tab in tabs">
			<div :key="tab.id">
				<figure>
					<img :src="tab.img" :alt="tab.name" />
				</figure>
			</div>
		</li>
	</ul>
</template>

<script>
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
}
</script>
