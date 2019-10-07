<template>
	<view class="i_container">
		<view class="index_header">
			<view class="w_navtab">
				<image src="/static/icon/餐饮美食/餐饮列表/餐饮切片/back2.png" mode=""></image>
				<text>巴黎婚纱摄影（公明总店）</text>
				<image src="/static/icon/餐饮美食/餐饮列表/餐饮切片/more1.png" mode=""></image>
			</view>
		</view>
		<view class="i_nav">
			<view class="shop_logo">
				<image src="../../static/icon/餐饮美食/餐饮美食/商家环境01.png" mode=""></image>
			</view>
			<view class="introduce_con df">
				<view class="introduce_tit">
					YISHION 以纯专卖店
				</view>
			</view>
			<view class="foods_intro">
				<text>YISHION 以纯专卖店YISHION 以纯专卖店YISHION 以纯专卖店YISHION 以纯专卖店</text>
				<text class="introduce_youhui">
					消费赠15%折扣积分
				</text>
			</view>
			<view class="shop_bottom foods_img">
				<image src="../../static/icon/餐饮美食/餐饮美食/商家环境01.png" mode=""></image>
				<image src="../../static/icon/餐饮美食/餐饮美食/龙井虾仁.png" mode=""></image>
				<image src="../../static/icon/餐饮美食/餐饮美食/商家环境03.png" mode=""></image>
			</view>
			<!-- <view class="line"></view> -->
			<view class="spa_time_con">
				<view class="spa_time">
					<image src="../../static/icon/餐饮美食/商铺.png" mode=""></image>
					<text>9:00至下午18:00营业</text>
				</view>
				<view class="spa_serve df">
					<view class="food_mark">有包厢</view>
					<view class="food_mark">无烟区</view>
					<view class="food_mark">有停车位</view>
					<view class="food_mark">有包厢</view>
				</view>
			</view>
			<view class="line"></view>
			<view class="daohang df">
				<image class="daohang_img" src="../../static/address.png" mode=""></image>
				<text class="w_address">雁塔区丈八沟街道科技四路团结南路中国邮政银行对面</text>
				<view class="w_address_car df">
					<view class="didi">
						打车
					</view>
					<image src="../../static/icon/婚纱摄影/婚纱摄影/打车.png" mode=""></image>
					<text>|</text>
					<image src="../../static/icon/婚纱摄影/婚纱摄影/电话.png" mode=""></image>
				</view>
			</view>
			<!-- <view class="line"></view> -->

			<view class="i_shop">
				<view class="shop_top">
					<view class="shop_top_con">
						<view class="shop_name">
							<view class="shop_name_th">
								推荐菜
							</view>
							<view class="huodong">
								&gt;
							</view>
						</view>
					</view>
					<view class="pro_address shop_top_address">
						<view class="shop_top_address_name">商家招牌菜(5)</view>
					</view>
				</view>
				<view class="shop_bottom">
					<view class="shop_bottom_con">
						<image src="../../static/icon/首页/首页/商家02-1.png" mode="aspectFit"></image>
						<text>招牌三合一</text>
					</view>
					<view class="shop_bottom_con">
						<image src="../../static/icon/首页/首页/商家02-2.png" mode=""></image>
						<text>招牌三合一</text>
					</view>
					<view class="shop_bottom_con">
						<image src="../../static/icon/首页/首页/商家02-3.png" mode=""></image>
						<text>招牌三合一</text>
					</view>
				</view>
			</view>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {

		}
	}
</script>

<style>
	page {
		background: #FFFFFF;
	}

	image {
		display: block;
	}

	.line {
		width: 100%;
		border: 2upx solid #EEEEEE;
		margin: 20upx 0;
	}

	.df {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
	}

	.con {
		width: 700upx;
		background: #FFFFFF;
	}

	.i_container {
		/* margin-top: 47upx; */
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;

		position: relative;
	}

	.index_header {
		width: 100%;
		height: 408upx;
		background: url('~@/static/icon/背景图.png') no-repeat center;
	}

	.i_nav {
		width: 704upx;
		background: #FFFFFF;
		justify-content: center;
		flex-wrap: wrap;
		position: absolute;
		top: 189upx;
	}

	.i_shop {
		width: 700upx;
		display: flex;
		flex-direction: column;
		margin-top: 20upx;
		background: #FFFFFF;
		padding: 25upx 15upx;
	}

	.shop_top {
		display: flex;
		flex-direction: column;
	}


	.shop_name {
		width: 100%;
		display: flex;
		justify-content: space-between;
		margin-bottom: 20upx;
	}

	.shop_top_address {
		display: flex;
		justify-content: space-between;
	}

	.shop_top_address image {
		width: 20upx;
		height: 22upx;
	}

	.shop_top_address text {
		margin-right: 10upx;
	}

	.shop_top_address_name {
		margin-left: 20upx;
	}

	.shop_name_th {
		font-size: 32upx;
		font-weight: 900;
	}

	.shop_bottom {
		display: flex;
		justify-content: space-between;
	}

	.shop_bottom_con {
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.shop_bottom image {
		display: block;
		width: 220upx;
		height: 180upx;
	}

	.shop_bottom_con text {
		font-size: 26upx;
		text-align: center;
		padding-top: 10upx;
	}

	.w_navtab {
		width: 100%;
		height: 75upx;
		background: transparent;
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0 22upx;
		font-weight: 900;
		color: #514318;
	}

	.w_navtab image {
		width: 42upx;
		height: 42upx;
	}

	.introduce_con {
		width: 700upx;
		height: 88upx;
		align-items: center;
		justify-content: space-between;
		padding-left: 20upx;
	}

	.introduce_tit {
		font-size: 38upx;
	}

	.introduce_youhui {
		display: inline-block;
		padding: 5upx;
		border-radius: 16upx;
		font-size: 24upx;
		color: #FFFFFF;
		background: #f48a3c;
		margin: 10upx 0;
		text-align: center;
		position: absolute;
		right: 10upx;
	}

	.spa_time_con {
		width: 700upx;
		height: 130upx;
	}

	.spa_time {
		display: flex;
		align-items: center;
		padding: 20upx;
		font-size: 28upx;
		color: #5f5f5f;
		font-weight: 900;
	}

	.spa_time image {
		width: 25upx;
		height: 25upx;
		margin-right: 6upx;
	}

	.spa_serve {
		justify-content: flex-start;
		padding: 0 20upx;
	}

	.spa_serve image {
		width: 28upx;
		height: 28upx;
	}

	.spa_serve text {
		padding: 0 20upx 0 10upx;
	}

	.daohang {
		padding: 0 0 20upx;
		border-bottom: 8upx solid #f8f8f8;
		justify-content: space-between;
	}

	.daohang image {
		width: 26upx;
		height: 30upx;
		/* margin-left: 20upx; */
	}

	.daohang_img {
		margin: -25upx 10upx 0 0;
	}

	.w_address {
		width: 375upx;
		margin-right: 10upx;
	}

	.w_address_car {
		justify-content: flex-end;
		flex: 1;
		height: 52upx;
		/* border-left: 4upx solid #DDDDDD; */
		position: relative;
	}

	.didi {
		width: 48upx;
		height: 27upx;
		background: #fc9214;
		color: #FFFFFF;
		font-size: 16upx;
		text-align: center;
		position: absolute;
		border-top-right-radius: 14upx;
		border-top-left-radius: 14upx;
		border-bottom-right-radius: 14upx;
		top: -6upx;
		right: 80upx;
	}

	.w_address_car image {
		width: 40upx;
		height: 37upx;
		/* margin-left: 68upx; */
	}
	.w_address_car text{
		margin: 0 34upx;
		color: #f8f8f8;
	}

	.foods_img {
		padding: 0 10upx;
		margin-top: 32upx;
	}

	.foods_intro {
		padding-left: 20upx;
		color: #b3b3b3;
		font-size: 20upx;
		position: relative;
		margin-bottom: 20upx;
	}

	.shop_logo {
		position: absolute;
		top: -88upx;
		right: 22upx;
		border: 4upx solid #FFFFFF;
	}

	.shop_logo image {
		width: 143upx;
		height: 132upx;
	}

	.food_mark {
		padding: 10upx 15upx;
		border-radius: 20upx;
		background: #8c9246;
		color: #FFFFFF;
		font-size: 20upx;
		text-align: center;
		margin-right: 20upx;
	}
	.huodong{
		font-size: 30upx;
		color: #c6c6c6;
	}
</style>
