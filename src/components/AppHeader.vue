<script>
export default {
	data() {
		return {
			links: [
				{
					text: "Characters",
					url: "#",
					active: true,
				},
				{
					text: "Comics",
					url: "#",
					active: false,
				},
				{
					text: "Movies",
					url: "#",
					active: false,
				},
				{
					text: "Tv",
					url: "#",
					active: false,
				},
				{
					text: "Games",
					url: "#",
					active: false,
				},
				{
					text: "Collectibles",
					url: "#",
					active: false,
				},
				{
					text: "Videos",
					url: "#",
					active: false,
				},
				{
					text: "Fans",
					url: "#",
					active: false,
				},
				{
					text: "News",
					url: "#",
					active: false,
				},

				{
					text: "Shop",
					url: "#",
					active: false,
				},
			],
		};
	},
};
</script>

<template>
	<header>
		<div class="container">
			<div class="col">
				<img src="../../public/img/dc-logo.png" alt="" />
			</div>
			<ul>
				<li v-for="link in links" :key="link.text" :class="link.active ? 'active' : ''">
					<a :href="link.url">{{ link.text }} </a>
				</li>
			</ul>
		</div>
	</header>
	<main>
		<div class="jumbotron"></div>
	</main>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/mixins" as *;
header {
	@include center();
	flex-direction: column;
	padding-bottom: 2rem;
}
ul {
	margin-top: 2rem;
}
li {
	display: inline-block;
	padding: 1rem;
	font-weight: bold;
	cursor: pointer;

	&.active,
	&:hover {
		background-color: aqua;
	}
}
.active {
	background-color: aqua;
}
.jumbotron {
	width: 100%;
	height: 400px;
	background-image: url(../../public/img/jumbotron.jpg);
	background-attachment: fixed;
}
</style>
