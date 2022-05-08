<script setup>
import Logo from './Logo.vue'
import Navbar from './Navbar.vue'
import Cart from './Cart.vue'
import Container from './Container.vue'
</script>

<template>
	<header
		class="bg-black text-white w-full mx-auto py-9 border-b border-[#979797]"
	>
		<Container>
			<div class="flex items-center justify-between">
				<Logo />
				<Navbar />
				<Cart />
			</div>
		</Container>
	</header>
</template>
