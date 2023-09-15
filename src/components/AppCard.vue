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
		<div class="row">
			<div class="container">
				<div class="col-2 character-card">
					<img :src="thumb" class="character-img" />
					<h2>{{ series }}</h2>
				</div>
			</div>
		</div>
	</main>
</template>

<style lang="scss" scoped>
.row {
	background-color: black;
}
.character-card {
	font-size: 10px;
	text-align: center;
	color: white;
	.character-img {
		width: 100%;
	}
}
</style>
