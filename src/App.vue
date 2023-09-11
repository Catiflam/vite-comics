<script>
import AppHeader from "./components/AppHeader.vue";
import AppCard from "./components/AppCard.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
	data() {
		return {
			title: "hello vue",
		};
	},

	components: {
		AppHeader,
		AppCard,
		AppFooter,
	},
};
</script>

<template>
	<AppHeader />
	<AppCard />
	<AppFooter />
</template>

<style lang="scss">
@use "./assets/styles/general.scss" as *;
</style>
