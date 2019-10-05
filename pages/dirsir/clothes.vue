<template>
	<view class="w_container">
		<!-- 		<view class="w_navtab">
			<image src="../../static/back.png" mode=""></image>
			<text>巴黎婚纱摄影（公明总店）</text>
			<image src="../../static/More.png" mode=""></image>
		</view> -->
		<view class="banner">
			<image class="bannerImg" src="../../static/icon/服装/001.png" mode=""></image>
		</view>
		<view class="introduce_con df">
			<view class="introduce_tit">
				YISHION 以纯专卖店
			</view>
			<view class="introduce_youhui">
				消费赠15%折扣积分
			</view>
		</view>
		<view class="line"></view>
		<view class="spa_time_con">
			<view class="spa_time">
				9:00至下午18:00营业
			</view>
			<view class="spa_serve df">
				<text>欢迎进店试选，以纯，打造你的不凡</text>
			</view>
		</view>
		<view class="line"></view>
		<view class="daohang df">
			<image src="../../static/address.png" mode=""></image>
			<text class="w_address">西安市雁塔区丈八沟街道科技四路团结南路中国邮政银行对面</text>
			<view class="w_address_car df">
				<view class="didi">
					打车
				</view>
				<image src="../../static/icon/婚纱摄影/婚纱摄影/打车.png" mode=""></image>
				<image src="../../static/icon/婚纱摄影/婚纱摄影/电话.png" mode=""></image>
			</view>
		</view>
		<view class="line"></view>
		<view class="in_shop">
			<view class="show_con">
				店内环境
			</view>
			<image src="../../static/icon/休闲娱乐/休闲娱乐_12.png" mode=""></image>
		</view>
		<view class="show_img df">
			<image src="../../static/icon/服装/007.png" mode=""></image>
			<image src="../../static/icon/服装/006.png" mode=""></image>
			<image src="../../static/icon/服装/005.png" mode=""></image>
		</view>
		<view class="line"></view>
		<view class="more_pro">
			<view class="more_tit">
				更多产品
			</view>
		</view>
		<view class="line"></view>
		<view class="show_img df">
			<view class="img_left_con">
				<image src="../../static/icon/服装/009.png" mode=""></image>
				<text class="active">工装，男装小...</text>
				<view class="count">
					<text>￥79.00</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/服装/010.png" mode=""></image>
				<text class="active">工装，男装小...</text>
				<view class="count">
					<text>￥79.00</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/服装/011.png" mode=""></image>
				<text class="active">工装，男装小...</text>
				<view class="count">
					<text>￥79.00</text>
				</view>
			</view>
		</view>
		<!-- 第二种样式 -->
		<view class="show_img df two">
			<view class="img_left_con">
				<image src="../../static/icon/服装/012.png" mode=""></image>
				<text class="active">工装，男装小...</text>
				<view class="active">
					工装，男装小...
				</view>
				<view class="count">
					<text>￥79.00</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/服装/013.png" mode=""></image>
				<text class="active">工装，男装小...</text>
				<view class="active">
					工装，男装小...
				</view>
				<view class="count">
					<text>￥79.00</text>
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

	.banner image {
		width: 750upx;
		height: 370upx;
	}

	.introduce_con {
		width: 700upx;
		height: 88upx;
		align-items: center;
		justify-content: space-between;
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

	.spa_time_con {
		width: 700upx;
		height: 130upx;
	}

	.spa_time {
		padding: 20upx 0;
		font-size: 28upx;
		color: #5f5f5f;
		font-weight: 900;
	}

	.spa_serve {
		justify-content: flex-start;
	}

	.spa_serve image {
		width: 28upx;
		height: 28upx;
	}

	.spa_serve text {
		padding: 0 20upx 0 10upx;
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
		left: 65upx;
	}

	.w_address_car image {
		width: 50upx;
		height: 50upx;
		margin: 0 20upx;
	}

	.in_shop {
		display: flex;
		width: 700upx;
		height: 90upx;
		align-items: center;
		/* background: #FFFFFF; */
		/* margin: 10upx 0; */
	}

	.in_shop image {
		width: 28upx;
		height: 30upx
	}

	.show_con {
		width: 100%;
		font-size: 32upx;
		font-weight: 900;
		height: 60upx;
		line-height: 60upx;
		font-size: 30upx;
		border-radius: 5upx;
	}

	.show_img {
		flex-wrap: wrap;
		width: 730upx;
	}

	.show_img image {
		width: 223upx;
		height: 226upx;
		margin: 10upx;
	}

	.active {
		font-size: 28upx;
		font-weight: 900;
		padding-left: 10upx;
	}

	.count text {
		font-size: 30upx;
		color: #ec5c8f;
		padding-left: 10upx;
	}

	.more_pro {
		width: 700upx;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.more_tit {
		width: 155upx;
		height: 45upx;
		line-height: 45upx;
		background: #e6610c;
		color: #FFFFFF;
		font-size: 28upx;
		border-radius: 22upx;
		text-align: center;
	}

	.more_phone {
		justify-content: flex-end;
	}

	.more_phone image {
		width: 26upx;
		height: 26upx;
		margin-right: 5upx;
	}

	.more_spa {
		display: flex;
		width: 700upx;
		height: 116upx;
		justify-content: space-between;
		align-items: center;
	}

	.more_spa_right {
		display: flex;
		align-items: center;
	}






	.two image {
		width: 345upx;
		height: 345upx;
		margin: 10upx;
	}
</style>
