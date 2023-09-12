<script>
import AppHeader from "./components/AppHeader.vue";
import AppCard from "./components/AppCard.vue";
import AppFooter from "./components/AppFooter.vue";
import listCard from "../vue-dc-comics-2/dc-comics.json";

export default {
	data() {
		return { listCard };
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
	<AppCard v-for="card in listCard" :key="card.index" :thumb="card.thumb" :series="card.series" />
	<AppFooter />
</template>

<style lang="scss">
@use "./assets/styles/general.scss" as *;
</style>
