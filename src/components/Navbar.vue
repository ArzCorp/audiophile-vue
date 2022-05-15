<template>
	<nav>
		<ul
			:class="[
				openStyles,
				'fixed z-[80] lg:static transition-transform duration-[700ms] lg:transition-none top-0 left-0 bg-black min-w-[200px] min-h-screen lg:min-h-min px-3 lg:px-0 py-5 lg:py-0 flex-col lg:flex-row flex lg:items-center gap-8 text-sm',
			]"
		>
			<div class="lg:hidden">
				<i
					class="fas fa-angle-double-left absolute top-3 right-3"
					@click="handleClose"
				/>
			</div>
			<li>HOME</li>
			<li>HEADPHONES</li>
			<li>SPEAKERS</li>
			<li>EARPHONES</li>
		</ul>
	</nav>
</template>

<script>
export default {
	props: {
		handleClose: Function,
		isOpen: Boolean,
	},
	computed: {
		openStyles() {
			if (this.isOpen) return 'transform-x-[200] lg:transform-x-[0px]'
			return '-translate-x-[200px] lg:-translate-x-[0px]'
		},
	},
}
</script>
