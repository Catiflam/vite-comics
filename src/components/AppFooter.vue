<script>
export default {
	data() {
		return {};
	},
};
</script>

<template>
	<div class="jumbo">
		<section class="container">
			<div class="footer-col">
				<img src="./../../public/img/dc-logo-bg.png" alt="" />
			</div>

			<div class="footer-col">
				<h3>Dc comics</h3>
				<ul>
					<li>Characters</li>
					<li>Comics</li>
					<li>Tv</li>
					<li>Games</li>
					<li>Videos</li>
					<li>News</li>
				</ul>
			</div>
			<div class="footer-col">
				<h3>Dc</h3>
				<ul>
					<li>Characters</li>
					<li>Comics</li>
					<li>Tv</li>
					<li>Games</li>
					<li>Videos</li>
					<li>News</li>
				</ul>
			</div>
			<div class="footer-col">
				<h3>Sites</h3>
				<ul>
					<li>Characters</li>
					<li>Comics</li>
					<li>Tv</li>
					<li>Games</li>
					<li>Videos</li>
					<li>News</li>
				</ul>
			</div>
			<div class="footer-col">
				<h3>Shop</h3>
				<ul>
					<li>Characters</li>
					<li>Comics</li>
					<li>Tv</li>
					<li>Games</li>
					<li>Videos</li>
					<li>News</li>
				</ul>
			</div>
		</section>
	</div>
	<section class="footer-links">
		<div class="container d-flex justify-content-beetwen">
			<div>
				<button>SING-UP NOW!</button>
			</div>
			<div>
				<a href="">FOLLOW US</a>
				<i></i>
				<i></i>
				<i></i>
				<i></i>
				<i></i>
			</div>
		</div>
	</section>
</template>
<style lang="scss" scoped>
.jumbo {
	width: 100%;
	height: 400px;
	background-image: url(../../public/img/footer-bg.jpg);
	background-attachment: fixed;
}

.footer-col {
	position: relative;
	color: white;
	img {
		position: absolute;
		left: 700px;
		top: 0;
		bottom: 300px;
		width: 400px;
		transform: rotate();
	}
}

.footer-links {
	width: 100%;
	height: 150px;
	background-color: rgba(32, 31, 31, 0.858);
}
</style>
