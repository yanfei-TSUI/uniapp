<template>
	<view class="h_container">
		<view class="w_navtab">
			<image src="../../static/back.png" mode=""></image>
			<text>INSTYLE造型 (KKmall商场店)</text>
		</view>
		<view class="banner">
			<image src="../../static/icon/详情页/详情页_02.png" mode=""></image>
		</view>
		<view class="hair_con">
			<view class="hair_title">
				INSTYLE造型
			</view>
			<view class="hair_style">
				通过人物风格学对人物的五大轮廓+质感+量感以及性格+职业+年龄，快速定位出你的风格
			</view>
			<view class="hair_prie">
				￥148.00
			</view>
			<view class="pro_info">
				产品详情
			</view>
			<view class="biao">
				<view class="tr">
					<text>【技术指导】</text>
					<text>单人剪发造型</text>
				</view>
				<view class="tr">
					<text>项目</text>
					<text>描述</text>
					<text>数量</text>
					<text>价格</text>
				</view>
				<view class="tr">
					<text>洗剪吹</text>
					<text>技术督导</text>
					<text>1次</text>
					<text>150元</text>
				</view>
			</view>
			<view class="hair_img">
				<image src="../../static/icon/详情页/详情页_06.png" mode=""></image>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
	.h_container {
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	view {
		width: 100%;
	}

	.w_navtab {
		width: 100%;
		height: 75upx;
		background: #FFFFFF;
		display: flex;
		justify-content: flex-start;
		align-items: center;
		padding: 0 22upx;
		font-weight: 900;
	}

	.w_navtab image {
		width: 42upx;
		height: 42upx;
	}

	.w_navtab text {
		flex: 1;
		text-align: center;
	}

	.banner {
		display: flex;
		justify-content: center;
		margin: 22upx 0 0 0;
	}

	.hair_con {
		width: 700upx;
		border: 2upx solid #DDDDDD;
	}

	.banner image {
		width: 700upx;
		height: 470upx;
	}

	.hair_title {
		height: 70upx;
		line-height: 70upx;
		font-size: 34upx;
		color: #3a3a3a;
		padding-left: 20upx;
	}

	.hair_style {
		font-size: 26upx;
		color: #454545;
		line-height: 40upx;
		font-weight: 900;
		padding: 0 10upx;
	}

	.hair_prie {
		font-size: 38upx;
		color: #e53f56;
		line-height: 100upx;
		font-weight: 900;
		padding-left: 20upx;
	}

	.pro_info {
		height: 46upx;
		font-size: 32upx;
		color: #efb34b;
		border-bottom: 2upx solid #c5c5c5;
		padding-left: 10upx;
	}
	.biao{
		border: 2upx solid #cfcfcf;
		border-bottom: none;
		margin-top: 25upx;
	}
	.tr{
		height: 50upx;
		border-bottom: 2upx solid #cfcfcf;
		display: flex;
		align-items: center;
	}
	.tr text{
		width: 175upx;
		text-align: center;
	}
	.hair_img image{
		width: 700upx;
		height: 555upx;
		margin-top: 10upx;
	}
</style>
