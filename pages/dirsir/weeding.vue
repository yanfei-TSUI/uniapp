<template>
	<view class="w_container">
		<view class="w_navtab">
			<image src="/static/icon/餐饮美食/餐饮列表/餐饮切片/back2.png" mode=""></image>
			<text>巴黎婚纱摄影（公明总店）</text>
			<image src="/static/icon/餐饮美食/餐饮列表/餐饮切片/more1.png" mode=""></image>
		</view>
		<view class="banner">
			<image src="../../static/icon/婚纱摄影/婚纱摄影/店铺环境.png" mode=""></image>
		</view>
		<view class="introduce_con df">
			<view class="introduce_tit">
				巴黎婚纱摄影（公明总店）
			</view>
			<view class="introduce_youhui">
				消费1000元获得100积分
			</view>
		</view>
		<view class="introduce_info">
			巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱.
		</view>
		<view class="line"></view>
		<view class="daohang df">
			<image class="daohang_img" src="../../static/address.png" mode=""></image>
			<text class="w_address">西安市雁塔区丈八沟街道科技四路团结南路中国邮政银行对面</text>
			<view class="w_address_car df">
				<view class="didi">
					打车
				</view>
				<image src="../../static/icon/婚纱摄影/婚纱摄影/打车.png" mode=""></image>
				<image src="../../static/icon/婚纱摄影/婚纱摄影/电话.png" mode=""></image>
			</view>
		</view>
		<view class="show_con">
			作品展示
		</view>
		<view class="show_img df">
			<view class="img_left_con">
				<image src="../../static/icon/婚纱摄影/婚纱摄影/作品一.png" mode=""></image>
				<text class="active">包邮套餐+送全新婚纱+...</text>
				<view class="count">
					<text>服装：5套</text>
					<text>精修：98张</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/婚纱摄影/婚纱摄影/作品一.png" mode=""></image>
				<text class="active">包邮套餐+送全新婚纱+...</text>
				<view class="count">
					<text>服装：5套</text>
					<text>精修：98张</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/婚纱摄影/婚纱摄影/作品一.png" mode=""></image>
				<text class="active">包邮套餐+送全新婚纱+...</text>
				<view class="count">
					<text>服装：5套</text>
					<text>精修：98张</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/婚纱摄影/婚纱摄影/作品一.png" mode=""></image>
				<text class="active">包邮套餐+送全新婚纱+...</text>
				<view class="count">
					<text>服装：5套</text>
					<text>精修：98张</text>
				</view>
			</view>
		</view>

	</view>
</template>

<script>
</script>

<style>
	image {
		display: block;
	}

	.df {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
	}

	.w_container {
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.w_navtab {
		width: 100%;
		height: 75upx;
		background: #FFFFFF;
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0 22upx;
		font-weight: 900;
	}

	.w_navtab image {
		width: 42upx;
		height: 42upx;
	}

	.banner {
		margin: 22upx 0 0 0;
	}

	.banner image {
		width: 700upx;
		height: 470upx;
	}

	.introduce_con {
		height: 88upx;
		align-items: center;
	}

	.introduce_tit {
		font-size: 38upx;
	}

	.introduce_youhui {
		width: 180upx;
		height: 32upx;
		line-height: 32upx;
		border-radius: 16upx;
		font-size: 16upx;
		color: #FFFFFF;
		background: #f48a3c;
		margin-left: 70upx;
		text-align: center;
	}

	.introduce_info {
		padding: 0 33upx;
		line-height: 46upx;
		color: #929292;
	}

	.line {
		width: 700upx;
		height: 4upx;
		background: #FFFFFF;
		margin: 0 auto;
		margin: 20upx 0;
	}

	.daohang image {
		width: 26upx;
		height: 30upx;
		margin-left: 20upx;
	}

	.w_address {
		width: 512upx;
		margin-right: 10upx;
	}

	.w_address_car {
		justify-content: flex-start;
		flex: 1;
		height: 52upx;
		border-left: 4upx solid #DDDDDD;
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
		top: -10upx;
		left: 40upx;
		z-index: 2;
	}

	.w_address_car image {
		width: 50upx;
		height: 50upx;
		margin: 0 20upx;
	}

	.show_con {
		width: 710upx;
		height: 60upx;
		line-height: 60upx;
		background: #f59407;
		font-size: 30upx;
		color: #FFFFFF;
		border-radius: 5upx;
		padding: 0 20upx;
		margin: 60upx 0 10upx 0;
	}
	.show_img {
		flex-wrap: wrap;
	}
	.show_img image{
		width: 345upx;
		height: 230upx;
		margin:10upx;
	}
	.active{
		font-size: 28upx;
		font-weight: 900;
		padding-left:10upx;
	}
	.count text{
		font-size: 20upx;
		color: #aeaeae;
		padding-left:10upx;
	}
	.daohang_img{
		margin: -25upx 10upx 0 0;
	}
	.img_left_con, .img_right_con{
		border: 4upx solid #fafafa;
	}
</style>
