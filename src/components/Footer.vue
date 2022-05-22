<template>
	<footer class="bg-black text-white pt-[75px] pb-12 flex">
		<Container>
			<div class="w-7/12 mr-36">
				<h2 class="mb-9 font-extrabold text-2xl">audiophile</h2>
				<p class="mb-14 text-white text-sm text-opacity-50">
					Audiophile is an all in one stop to fulfill your audio needs. We're a
					small team of music lovers and sound specialists who are devoted to
					helping you get the most out of personal audio. Come and visit our
					demo facility - we’re open 7 days a week.
				</p>
				<p class="text-white text-sm text-opacity-50">
					Copyright 2021. All Rights Reserved
				</p>
			</div>
			<div class="w-5/12">
				<ul class="text-xs justify-end uppercase mb-[105px] flex gap-8">
					<li class="hover:text-[#D87D4A]">Home</li>
					<li class="hover:text-[#D87D4A]">HEADPHONES</li>
					<li class="hover:text-[#D87D4A]">SPEAKERS</li>
					<li class="hover:text-[#D87D4A]">EARPHONES</li>
				</ul>
				<ul class="text-2xl justify-end flex gap-4">
					<li><i class="hover:text-[#D87D4A] fab fa-facebook-square" /></li>
					<li><i class="hover:text-[#D87D4A] fab fa-twitter" /></li>
					<li><i class="hover:text-[#D87D4A] fab fa-instagram" /></li>
				</ul>
			</div>
		</Container>
	</footer>
</template>
<script>
import Container from './Container.vue'
export default {
	components: { Container },
}
</script>
