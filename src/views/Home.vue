<template>
	<div class="home">
		<Header />
		<div class="contain">
			<LeftItem></LeftItem>
			<RightItem></RightItem>
			<Footer></Footer>
		</div>
	</div>
</template>

<script>
	// @ is an alias to /src
	import Header from "../components/Header.vue"
	import LeftItem from "../components/LeftItem.vue"
	import RightItem from "../components/RightItem.vue"
	import Footer from "../components/Footer.vue"

	export default {
		name: "Home",
		components: {
			Header,
			LeftItem,
			RightItem,
			Footer
		}
	};
</script>

<style scoped lang="less">
	.contain{
		width: 1920px;
		height: 894px;
		background: #F4F7FA;
		position: absolute;
		left: 0px;
		top: 326px;
	}
</style>
