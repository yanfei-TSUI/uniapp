<template>
	<view class="w_container">
		<view class="w_navtab">
			<image src="../../static/back.png" mode=""></image>
			<text>美联英语（宏发中心）</text>
			<image src="../../static/More1.png" mode=""></image>
		</view>
		<view class="introduce_con df">
			<view class="introduce_tit">
				美联英语（宏发中心）
			</view>
			<!-- 			<view class="introduce_youhui">
				消费1000元获得100积分
			</view> -->
		</view>
		<view class="one_words">
			<text>美联英语美联英语美联英语英语美联英语美联英语英语美英语（宏发中心）</text>
		</view>
		<view class="show_img df threeImg">
			<image class="show_pic" src="../../static/icon/教育培训/教育培训/教学环境01.png" mode=""></image>
			<image class="show_pic" src="../../static/icon/教育培训/教育培训/教学环境02.png" mode=""></image>
			<image class="show_pic" src="../../static/icon/教育培训/教育培训/教学环境03.png" mode=""></image>
		</view>
		<view class="introduce_info">
			美联国际英语成立于2006年，巴黎婚纱2007年平拍战略升级。美联国际英语成立于2006年，巴黎婚纱2007年平拍战略升级。美联国际英语成立于2006年，巴黎婚纱2007年平拍战略升级。美联国际英语成立于2006年，巴黎婚纱2007年平拍战略升级。美联国际英语成立于2006年，巴黎婚纱2007年平拍战略升级。
		</view>
		<view class="shouqi">
			收起 ∧
		</view>
		<view class="line"></view>
		<view class="daohang df">
			<image class="daohangIcon" src="../../static/address.png" mode=""></image>
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
		<view class="show_con">
			课程
		</view>
		<view class="show_imgs df">
			<view class="img_left_con">
				<image class="left_pic" src="../../static/icon/教育培训/教育培训/学生英语.png" mode=""></image>
				<text class="active">零基础英语</text>
				<view class="active2">xx 10人一下</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
			<view class="img_left_con">
				<image class="left_pic" src="../../static/icon/教育培训/教育培训/学生英语.png" mode=""></image>
				<text class="active">零基础英语</text>
				<view class="active2">xx 10人一下</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/学生英语.png" mode=""></image>
				<text class="active">零基础英语</text>
				<view class="active2">xx 10人一下</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
			<view class="img_left_con">
				<image src="../../static/icon/教育培训/教育培训/学生英语.png" mode=""></image>
				<text class="active">零基础英语</text>
				<view class="active2">xx 10人一下</view>
				<view class="count">
					<text>￥9.9</text>
				</view>
			</view>
		</view>
		<view class="more_ke">
			<text>更多课程</text>
			<image src="../../static/icon/教育培训/教育培训/更多.png" mode=""></image>
		</view>
		<view class="line"></view>
		<view class="mingshi">
			<view class="all_tea">
				名师风采
			</view>
			<view class="other_tea">
				全部七位老师&gt;
			</view>
		</view>

		<view class="show_img2 df mingshi">
			<view class="block_box">
				<image class="person_pic" src="/static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<text class="name">风清扬</text>
				<text class="dsc">3年教授</text>
				<text class="kecheng">通用英语</text>
			</view>
			<view class="block_box">
				<image class="person_pic" src="/static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<text class="name">风清扬</text>
				<text class="dsc">3年教授</text>
				<text class="kecheng">通用英语</text>
			</view>
			<view class="block_box">
				<image class="person_pic" src="/static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<text class="name">风清扬</text>
				<text class="dsc">3年教授</text>
				<text class="kecheng">通用英语</text>
			</view>
			<view class="block_box">
				<image class="person_pic" src="/static/icon/教育培训/教育培训/教师01.png" mode=""></image>
				<text class="name">风清扬</text>
				<text class="dsc">3年教授</text>
				<text class="kecheng">通用英语</text>
			</view>
		</view>
	<view class="line" style="margin-top:100upx;"></view>
	</view>
</template>

<script>
</script>

<style>
	page{
		background: #FFFFFF;
	}
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
		padding: 0 24upx;
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
		padding-left: 24upx;
	}

	.introduce_tit {
		color: #2a2a2a;
		font-weight: 900;
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
	.img_left_con{
		display: flex;
		flex-direction: column;
		width: 350upx;
		margin: 10upx;
		border: 1px solid #dfdfdf;
		.left_pic{
			display: block;
			 margin: 0!important;
		}
	}
	.person_pic{
		width: 150upx;
		height: 130upx;
	}
	.name{
		color: #616260;
		font-size: 28upx;
	}
	.dsc{
		font-size: 28upx;
		color: #df9109;
	}
	.kecheng{
		font-size: 28upx;
		color: #a8a8a8;
	}
	.show_img2{
		margin-top: 100upx;
	}
	.show_img2 .block_box{
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	.all_tea{
		font-weight: 900;
	}
	.other_tea{
		color: #c6c6c6;
	}
.shouqi{
	height:90upx;
	display: flex;
	justify-content: center;
	align-items: center;
	}
	.introduce_info {
		padding: 0 30upx;
		line-height: 44upx;
		color: #717171;
		font-weight: bold;
	}

	.line {
		width: 750upx;
		height: 6upx;
		background: #f3f3f3;
		margin: 0 auto;
		margin: 20upx 0;
	}

	.daohang image {
		width: 26upx;
		height: 30upx;
		margin-left: 20upx;
	}
	.daohang .daohangIcon{
		margin-right: 10upx;
		margin-top: -30upx;
	}
	.w_address {
		color:#515151;
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
		padding:0 8upx;
		/* width: 48upx; */
		/* height: 27upx; */
		background: #fc9214;
		color: #FFFFFF;
		font-size: 16upx;
		text-align: center;
		position: absolute;
		border-top-right-radius: 14upx;
		border-top-left-radius: 14upx;
		border-bottom-right-radius: 14upx;
		top: -20upx;
		left: 44upx;
		z-index: 10;
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

	.show_img,.show_imgs {
		flex-wrap: wrap;
	}
	.show_pic{
		width: 370upx;
		height: 260upx;
		margin: 10upx;
	}
	.show_imgs image {
		width: 350upx;
		height: 175upx;
	}

	.threeImg image {
		width: 230upx;
		height: 175upx;
		margin: 6upx;
	}

	.active {
		font-size: 28upx;
		font-weight: 900;
		padding-left: 22upx;
	}
	.active2{
		font-size: 22upx;
		padding-left: 22upx;
		color: #959395;
	}
	.count text {
		font-size: 30upx;
		color: red;
		font-weight: 900;
		padding-left: 20upx;
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
	.one_words{
		width: 100%;
		padding-left: 24upx;
		font-size: 20upx;
		color: #b9b9b9;
	}
</style>
