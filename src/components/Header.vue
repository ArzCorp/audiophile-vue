<script setup>
import Logo from './Logo.vue'
import Navbar from './Navbar.vue'
import Cart from './Cart.vue'
</script>

<template>
	<header
		class="bg-black text-white w-full mx-auto py-9 border-b border-[#979797]"
	>
		<div class="w-full max-w-[80%] mx-auto flex items-center justify-between">
			<Logo />
			<Navbar />
			<Cart />
		</div>
	</header>
</template>
