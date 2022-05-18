<template>
	<button
		:class="[
			black,
			ghost,
			'min-w-[160px] tracking-[1px] py-4 px-2 text-xs font-bold text-center',
		]"
	>
		<slot></slot>
	</button>
</template>

<script>
export default {
	props: {
		black: Boolean,
		ghost: Boolean,
	},
	computed: {
		black() {
			if (this.black) {
				return 'bg-black text-white'
			} else {
				return 'bg-[#D87D4A] text-white'
			}
		},
		ghost() {
			if (this.ghost) {
				return 'bg-transparent text-black border border-black'
			} else {
				return ''
			}
		},
	},
}
</script>
