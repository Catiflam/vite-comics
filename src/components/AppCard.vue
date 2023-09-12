<script>
export default {
	props: {
		thumb: String,
		series: String,
	},
};
</script>
<template>
	<main>
		<div class="container">
			<div class="col character-card">
				<img :src="thumb" class="character-img" />
				<h2>{{ series }}</h2>
			</div>
		</div>
	</main>
</template>

<style lang="scss" scoped></style>
