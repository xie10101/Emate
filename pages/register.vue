<template>
<view class="body">
	<!-- <view class="main">
		 <image src="../static/图标.png" mode="" class="icon-main"></image>
	</view> -->
	<ul>
		<li></li>
		<li></li>
		<li></li>
		<li></li>
		<li></li>
		<li></li>
	</ul>
</view>
</template>

<script>
</script>

<style scoped> 
	
.body{
	width:390upx;   
	height: 2000px;
	/* 高度由内容撑开 */
	background-color: #ff8315;
	display: inline-block;
}
	ul{
		width: 200upx;
		height: 1300upx;
		margin: 0 auto;
		display: flex;
		flex-direction: column;
	    margin-top: 146upx;
		justify-content: space-between;
	}	
	
li{
	list-style: none;
	width: 200upx;
	height: 100upx;
background-color: red;
}
ul li:nth-child(1)
{

}
	.icon-main{

	}
</style>