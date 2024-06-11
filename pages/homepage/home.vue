<template>
	<view class="body">
		<view class="header">
			<view class="head-left" >
				
			</view>
			<view class="head-right">
				<h3 id="userid">小蔡不吃香菜</h3>
				<text style="color: #8d8d8d;">账号名：E00000001</text>
				<ul class="status_user">
					<li>关注 300</li>
					<li>粉丝 5</li>
					<li>好友 6</li>
				</ul>
			</view>
		</view>
		<view class="huiyuan">
			<view class="huiyuantop">
				<h2 style="color: #fdf0e5;">会员中心</h2>
				<button >去查看</button>
			</view>
			
			<ul >
				<Li>EMATE值 700</Li>
				<Li> 诚信度 100</Li>
			</ul>
		</view>
		<view class="navigations">
	
			<ul>
				<li>
					<text>我发布的</text><uni-icons type="forward" size="28" color="#000"></uni-icons>
				</li>
				<li>
					<text>快递</text><uni-icons type="forward" size="28" color="#000"></uni-icons>
				</li>
				<li>
					<text>我的交换</text><uni-icons type="forward" size="28" color="#000"></uni-icons>
				</li>
				<li>
					<text>地址管理</text><uni-icons type="forward" size="28" color="#000"></uni-icons>
				</li>
			</ul>
		</view>
		<button size="">退出登录</button>
	</view>
</template>

<script>
export default	
{	
	data()
	{
		return {
			
		}
	}
}
</script>

<style scoped>
			
		li{
			list-style: none;
		padding: 0 0;
		}
		
.body{
		width: 800upx;
		height: 1500upx;
        /* background-color: orange; */
	    display: inline-block;
		
	}
	
.header{
	display: flex;
	margin:56upx 75upx 21upx 23upx;
}
	.head-left{
width: 153upx;
height: 153upx;
background-color: #000;
	}
		
	.head-right{
	margin-left:40upx;
	
	}
	.head-right h3
	{
		margin-bottom:10upx ;
	}
	.head-right ul
	{
		color: #a7a7a7;
	display: flex;
	padding-left: 0upx;
	margin-top: 10upx;
	}
		
    .head-right ul li{
     padding-right:15upx;
margin-right: 15upx;
border-right: 1px solid #909090;
height: 35upx;
line-height: 35upx;
	}
		
	.huiyuan{
width: 680upx;
height: 160upx;
margin:45upx 36upx 40upx 40upx;
background-color: #f27c14;
		border-radius: 18upx 18upx 0 0;
	}
		
	.huiyuantop{
	width: 100%;
	background-color: #f27c14;
	border-radius: 18upx 18upx 0 0;
	position: relative;
	height: 100upx;
	overflow: hidden;
	}
		
	.huiyuantop button{
		width:150upx;
		height: 50upx;
		position: absolute;
   top: 22upx;
   right: 26upx;
   font-size: 30upx;
   line-height: 50upx;
   color: #f27c14;
   border-radius: 50upx;
	}
	.huiyuantop h2
	{
		font-weight: 400;
		font-size: 42upx;
margin-top: 18upx;
margin-left: 32upx;
	}
	.huiyuan ul	
{
	width: 100%;
	height:128upx;
	display: flex;
	background-color: #fff;
	border-radius: 18upx;
	border: #d5d5d5 1px solid;
	padding: 0;
}
.huiyuan ul	 li
{   text-align: center;
	color: #f27c14;
	height: 90%;
	width:350upx;
	margin-top: 8upx;
	padding-left: 10upx;
	line-height: 110upx;
	border-right: #d0d0d0 2px solid;
}
	.huiyuan ul	 li:nth-child(2)
	{
		border-right: 0;
	}
.navigations{
	width: 670upx;
	height: 539upx;
	/* background-color: ; */
    margin:110upx 40upx 0px  46upx ;
    border: 1upx solid #c2c2c2;
    border-radius: 30upx;
}
.navigations ul	
{
	padding: 0 0;
	display: flex;
   flex-direction: column;
   justify-content: space-between;
   align-content: space-between;
   padding: 22upx;
}
.navigations ul	 li
{   height: 125upx;
	width: 100%;
	font-size: 32upx;
	font-weight: 600;
	line-height: 126upx;
	border-bottom: 2px solid #c2c2c2;
position: relative;
}
.navigations ul	 li  .uni-icons
{   right: 2px;
	position: absolute;
}
.navigations ul	 li:nth-child(4)
{
	border-bottom: 0;
}
	
button{
width: 85%;
border-radius: 30upx;
margin-left:40upx;
margin-top: 130upx;
}
</style>