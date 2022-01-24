<template>
	<view class="content">
	    <image class="logo" src="../../pagesA/static/test.png" />
		<button @click="goToDetail">跳转到详情页面</button>
	</view>
</template>

<script lang="ts">
    import Vue from 'vue';
	export default Vue.extend({
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {
			goToDetail () {
				uni.navigateTo({
					url: '/pagesA/detail/index'
				})
			}
		}
	});
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height: 100vh;
	}
</style>
