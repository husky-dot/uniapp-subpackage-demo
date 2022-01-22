<template>
	<view class="content">
		<button @click="goToDetail">跳转到活动详情页面</button>
		<button @click="goToSubDetail" style="margin-top:30rpx">跳转到子包活动详情页面</button>
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
			goToDetail() {
				uni.navigateTo({
					url: '/pages/activity/detail'
				})
			},
			goToSubDetail() {
				uni.navigateTo({
					url: '/pagesA/activity/detail'
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
