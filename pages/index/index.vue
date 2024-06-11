<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view class="text-area">
			<text class="title">{{title}}</text>
			<navigator url="/pages/message" open-type="redirect">在当前面中展示</navigator>
			<scroll-view scroll-y="true" >
				<view> dddaa</view>
			</scroll-view>
			
			<!-- <view-router></view-router> -->
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: ''
			}
		},
		onLoad() {

		},
		methods: {
				
			toregister()
				
			{
				this.$router.push('/register')
			}
		}
	}
</script>

<style scoped>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
	button	
	{
		display: block;
	}
</style>
