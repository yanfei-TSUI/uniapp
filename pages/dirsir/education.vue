<template>
	<view class="w_container">
		<view class="w_navtab">
			<image src="../../static/back.png" mode=""></image>
			<text>美联英语（宏发中心）</text>
			<image src="../../static/More.png" mode=""></image>
		</view>
		<view class="introduce_con df">
			<view class="introduce_tit">
				美联英语（宏发中心）
			</view>
			<!-- 			<view class="introduce_youhui">
				消费1000元获得100积分
			</view> -->
		</view>
		<view class="show_img df threeImg">
			<image src="../../static/icon/教育培训/教育培训/教学环境01.png" mode=""></image>
			<image src="../../static/icon/教育培训/教育培训/教学环境02.png" mode=""></image>
			<image src="../../static/icon/教育培训/教育培训/教学环境03.png" mode=""></image>
		</view>
		<view class="introduce_info">
			巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱，超过200万新人有限推荐，巴黎婚纱.
		</view>
		<view class="shouqi">
			收起 ∧
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
		<view class="show_con">
			课程
		</view>
		<view class="show_img df">
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/学生英语.png" mode=""></image>
				<text class="active">包邮套餐</text>
				<view class="active">包邮套餐+送全新婚</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/教育培训/教育培训/零基础英语.png" mode=""></image>
				<text class="active">包邮套餐</text>
				<view class="active">包邮套餐+送全新婚纱</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/教育培训/教育培训/宝妈英语.png" mode=""></image>
				<text class="active">包邮套餐</text>
				<view class="active">包邮套餐+送全新婚纱</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
			<view class="img_right_con">
				<image src="../../static/icon/教育培训/教育培训/个人提升英语.png" mode=""></image>
				<text class="active">包邮套餐</text>
				<view class="active">包邮套餐+送全新婚纱</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
		</view>
		<view class="more_ke">
			<text>更多课程</text>
			<image src="../../static/icon/教育培训/教育培训/更多.png" mode=""></image>
		</view>
		<view class="mingshi">
			<view class="all_tea">
				名师风采
			</view>
			<view class="">
				全部七位老师&gt;
			</view>
		</view>

		<view class="show_img df mingshi">
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<view class="active">包邮套餐</view>
				<view class="active">包邮套餐</view>
				<view class="count"><text>￥9.9</text></view>
			</view>
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/教师02.png" mode=""></image>
				<view class="active">包邮套餐</view>
				<view class="active">包邮套餐</view>
				<view class="count"><text>￥9.9</text></view>
			</view>
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<view class="active">包邮套餐</view>
				<view class="active">包邮套餐</view>
				<view class="count"><text>￥9.9</text></view>
			</view>
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/教师02.png" mode=""></image>
				<view class="active">包邮套餐</view>
				<view class="active">包邮套餐</view>
				<view class="count"><text>￥9.9</text></view>
			</view>
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<view class="active">包邮套餐</view>
				<view class="active">包邮套餐</view>
				<view class="count"><text>￥9.9</text></view>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
	image {
		display: block;
		width: 50upx;
		height: 50upx;
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

	.introduce_con {
		height: 88upx;
		align-items: center;
		justify-content: flex-start;
		padding-left: 20upx;
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
.shouqi{
	height:90upx;
	display: flex;
	justify-content: center;
	align-items: center;
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
		left: 65upx;
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
		font-size: 32upx;
		font-weight: 900;
		border-radius: 5upx;
		padding: 0 20upx;
		margin: 60upx 0 10upx 0;
	}

	.show_img {
		flex-wrap: wrap;
	}

	.show_img image {
		width: 345upx;
		height: 230upx;
		margin: 10upx;
	}

	.threeImg image {
		width: 230upx;
		height: 170upx;
		margin: 6upx;
	}

	.active {
		font-size: 28upx;
		font-weight: 900;
		padding-left: 10upx;
	}

	.count text {
		font-size: 30upx;
		color: #ec9d37;
		padding-left: 10upx;
	}

	.more_ke {
		height: 99upx;
		display: flex;
		justify-content: center;
		align-items: center;
		color: #afafaf;
		font-size: 28upx;
	}

	.more_ke image {
		width: 25upx;
		height: 28upx;
	}

	.mingshi {
		width: 700upx;
		height: 85upx;
		display: flex;
		justify-content: space-between;
		align-items: center;
		border-top: 2upx solod #F9F9F9;
	}
	.mingshi image{
		width: 127upx;
		height: 146upx;
		margin: 0 5upx;
	}
</style>
