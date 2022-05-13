<script setup>
import Logo from './Logo.vue'
import Navbar from './Navbar.vue'
import Cart from './Cart.vue'
import Container from './Container.vue'
</script>

<template>
	<header
		class="bg-black text-white w-full mx-auto py-5 lg:py-9 border-b border-[#979797]"
	>
		<Container>
			<div class="flex items-center justify-between">
				<div class="flex items-center">
					<div class="lg:hidden">
						<p class="fas fa-bars mr-10" @click="toogleMenu" />
					</div>
					<Logo />
				</div>
				<div v-if="isOpen">
					<Navbar :handleClose="toogleMenu" />
				</div>
				<Cart />
			</div>
		</Container>
	</header>
</template>

<script>
export default {
	data() {
		return {
			isOpen: false,
		}
	},
	methods: {
		toogleMenu() {
			this.isOpen = !this.isOpen
		},
	},
}
</script>
