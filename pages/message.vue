<template>
	<view class="body">
		<view class="head">
			<h2>消息</h2>
			<button>清除未读</button>
		</view>
		<view class="search">
			<input type="text" placeholder="搜索聊天记录/联系人/服务号" />
		</view>
		<view class="main">
			<ul>
				<li>
					<image src="../static/通知.png" mode=""></image>
					<view class="notice">
						<h2>通知消息</h2><text>2月份个人年度财务</text>
					</view>
				</li>
				<li>
					<image src="../static/互动.png" mode=""></image>
					<view class="reaction">
						<h2>互动消息</h2><text>还没有新通知哦</text>
					</view>
				</li>
				<li>
					<image src="../static/精选.png" mode=""></image>
					<view class="special">
						<h2>EMATE精选</h2><text>帖子上新提醒</text>
					</view>
				</li>
				<li>
					已经没有更多了
				</li>
			</ul>
		</view>
	</view>
</template>

<script>
</script>

<style scoped>
	.body {
		width: 800upx;
		height: 1500upx;
		/* background-color: orange; */
		display: inline-block;
	}

	.head {
		width: 100%;
		height: 70upx;
		padding: 20upx 70upx 25upx 70upx;
		display: flex;
		align-items: baseline;
	}

	.head h2 {
		font-weight: 600;
		font-size: 46upx;
	}

	.head button {
		margin: 0;
		margin-left: 40upx;
		width: 160upx;
		font-size: 30upx;
		padding: 0;
		height: 40upx;
		line-height: 40upx;
		background-color: #d9d9d9;
		font-weight: 600;
		border-radius: 30upx;
	}

	.search {
		width: 670upx;
		border: 2upx solid #424242;
		height: 64upx;
		line-height: 64upx;
		border-radius: 20upx;
		margin-left: 35upx;

	}

	.search input {
		width: 90%;
		height: 100%;
		margin-left: 20upx;
	}

	.main {
		width: 680upx;
		margin: 80upx 44upx 0upx 40upx;
		background-color: #fff;
	}

	.main ul {
		width: 100%;
		display: flex;
		flex-direction: column;

	}

	.main ul li {
		display: flex;
		align-items: center;
		margin-bottom: 66upx;
	}

	.main ul li image {
		width: 72upx;
		height: 80upx;
	}

	.main ul li view {
		margin-left: 30upx;

	}

	.main ul li view h2 {
		font-size: 40upx;
	}

	.main ul li view text {
		color: #858585;
		font-size: 26upx;
	}

	.main ul li:nth-child(4) {
		width: 100%;
		margin-left: 220upx;
		color: #858585;
		font-weight: 500;
	}
</style>