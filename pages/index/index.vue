<template>
	<view class="container">
	</view>
</template>

<script>
	export default {
		onPullDownRefresh() {
			console.log('刷新');
			setTimeout(function() {
				uni.stopPullDownRefresh();
			}, 2000);
		},
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		methods: {}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
