<template>
	<view class="p_container">
		<view class="w_navtab">
			<image src="../../static/cuo.png" mode=""></image>
			<text>支付成功</text>
			<image src="../../static/moreif.png" mode=""></image>
		</view>
		<view class="success-icon">
			<image src="../../static/icon/支付成功/支付成功.png" mode=""></image>
		</view>
		<view class="pay_success">
			恭喜你支付成功 !
		</view>
		<view class="pay_item">
			<view>支付金额 :<text>30元</text></view>
			<view>积分抵扣 :<text>20元</text></view>
			<view>获得积分 :<text>4.5</text></view>
		</view>
		<view class="more_serve">
			<image src="../../static/icon/支付成功/继续付款.png" mode=""></image>
			<image src="../../static/icon/支付成功/更多福利.png" mode=""></image>
			<image src="../../static/icon/支付成功/快的打车.png" mode=""></image>
			<image src="../../static/icon/支付成功/法务咨询.png" mode=""></image>
		</view>
		<view class="business_tit">
			<image src="../../static/icon/支付成功/商家.png" mode=""></image>
			<text>推荐商家</text>
		</view>
		<view class="con i_product">
			<view class="pro_left">
				<image src="../../static/icon/支付成功/商家01.png" mode=""></image>
			</view>
			<view class="pro_right">
				<view class="pro_name">
					西雅图欢乐餐厅（公明天虹店）
				</view>
				<view class="pro_address">
					现金消费达15% 折扣积分
				</view>
				<view class="i_price">
					有车位
				</view>
				<view class="huodong">
					主营产品：各类美食，香辣火锅
				</view>
			</view>
		</view>
		<view class="con i_product">
			<view class="pro_left">
				<image src="../../static/icon/支付成功/商家02.png" mode=""></image>
			</view>
			<view class="pro_right">
				<view class="pro_name">
					西雅图欢乐餐厅（公明天虹店）
				</view>
				<view class="pro_address">
					现金消费达15% 折扣积分
				</view>
				<view class="i_price">
					有车位
				</view>
				<view class="huodong">
					主营产品：各类美食，香辣火锅
				</view>
			</view>
		</view>
		<view class="con i_product">
			<view class="pro_left">
				<image src="../../static/icon/支付成功/商家03.png" mode=""></image>
			</view>
			<view class="pro_right">
				<view class="pro_name">
					西雅图欢乐餐厅（公明天虹店）
				</view>
				<view class="pro_address">
					现金消费达15% 折扣积分
				</view>
				<view class="i_price">
					有车位
				</view>
				<view class="huodong">
					主营产品：各类美食，香辣火锅
				</view>
			</view>
		</view>
		<view class="con i_product">
			<view class="pro_left">
				<image src="../../static/icon/支付成功/商家04.png" mode=""></image>
			</view>
			<view class="pro_right">
				<view class="pro_name">
					西雅图欢乐餐厅（公明天虹店）
				</view>
				<view class="pro_address">
					现金消费达15% 折扣积分
				</view>
				<view class="i_price">
					有车位
				</view>
				<view class="huodong">
					主营产品：各类美食，香辣火锅
				</view>
			</view>
		</view>
	</view>
</template>
<script>

</script>
<style>
	page {
		background: #FFFFFF;
	}

	.p_container {
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.w_navtab {
		width: 100%;
		height: 75upx;
		background: #222a2d;
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0 22upx;
		font-weight: 900;
	}

	.w_navtab text {
		color: #FFFFFF;
	}

	.w_navtab image {
		width: 42upx;
		height: 42upx;
	}

	.success-icon image {
		width: 104upx;
		height: 104upx;
		margin-top: 20upx;
	}

	.pay_success {
		font-size: 44upx;
		font-weight: 900;
		color: #161616;
		margin-top: 80upx;
	}

	.pay_item {
		color: #f47c38;
		font-size: 30upx;
		margin-top: 60upx;
	}

	.pay_item text {
		color: #ababab;
		padding-left: 30upx;
		line-height: 40upx;
	}

	.more_serve {
		display: flex;
		flex-wrap: wrap;
		width: 410upx;
		height: 150upx;
		margin-top: 110upx;
	}

	.more_serve image {
		width: 175upx;
		height: 55upx;
		margin: 15upx;
	}

	.business_tit {
		width: 100%;
		height: 90upx;
		display: flex;
		align-items: center;
		font-size: 32upx;
		font-weight: 900;
		background: #f9f9f9;
	}

	.business_tit image {
		width: 42upx;
		height: 42upx;
		margin: 0 8upx 0 20upx;
	}

	.con {
		width: 700upx;
		background: #FFFFFF;
	}

	.i_product {
		margin-top: 20upx;
		padding: 20upx;
		display: flex;
	}

	.pro_left {
		width: 200upx;
	}

	.pro_left image {
		width: 160upx;
		height: 160upx;
	}

	.pro_right {
		display: flex;
		flex: 1;
		flex-direction: column;
		color: #b8b8b8;
	}

	.pro_name {
		font-size: 30upx;
		color: #4b4b4b;
		font-weight: 900;
	}

	.pro_address {
		color: #e0b580;
	}

	.i_price,
	.pro_address {
		line-height: 46upx;
	}
</style>
