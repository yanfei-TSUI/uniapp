<template>
	<view class="w_container">
		<view class="meal_top">
			<img src="../../../static/icon/餐饮美食/餐饮列表/餐饮切片/back1.png" alt="">
			<img src="../../../static/icon/餐饮美食/餐饮列表/餐饮切片/search1.png" alt="">
			<img src="../../../static/icon/餐饮美食/餐饮列表/餐饮切片/more2.png" alt="">
		</view>
		<view class="meal_menu">
			<img src="../../../static/icon/餐饮美食/餐饮列表/餐饮切片/餐饮列表切片_02.gif" alt="">
		</view>
		<view class="meal_list">
			<view class="meal_list_menu">
				<view>筛选</view>
				<view>销量</view>
				<view>距离</view>
			</view>
			<view class="meal_list_ul">
				<li>
					<img class="meal_list_ul_img" src="../../../static/icon/餐饮美食/餐饮列表/miqi.jpg" alt="">
					<view class="meal_list_ul_info">
						<view class="meal_list_ul_info_title">米旗(枫叶新都市) <span>标签</span><span>标签</span></view>
						<view class="meal_list_ul_info_place">
							<img src="../../../static/icon/餐饮美食/定位.png" alt="">
							<text>快乐柠檬(西安大都荟店)</text>
							<text class="juli">681m</text>
							<text class="more_info">&gt;</text>
						</view>
						<view class="meal_list_ul_info_tag">
							<span>WIFI</span>
							<span>品种丰富</span>
							<span>好美味</span>
						</view>
						<view class="meal_list_ul_info_msg">
							今天到店消费59次
						</view>
					</view>
				</li>
				<li>
					<img class="meal_list_ul_img" src="../../../static/icon/餐饮美食/餐饮列表/miqi.jpg" alt="">
					<view class="meal_list_ul_info">
						<view class="meal_list_ul_info_title">米旗(枫叶新都市) <span>标签</span><span>标签</span></view>
						<view class="meal_list_ul_info_place">
							<img src="../../../static/icon/餐饮美食/定位.png" alt="">
							<text>快乐柠檬(西安大都荟店)</text>
							<text class="juli">681m</text>
							<text class="more_info">&gt;</text>
						</view>
						<view class="meal_list_ul_info_tag">
							<span>WIFI</span>
							<span>品种丰富</span>
							<span>好美味</span>
						</view>
						<view class="meal_list_ul_info_msg">
							今天到店消费59次
						</view>
					</view>
				</li>
				<li>
					<img class="meal_list_ul_img" src="../../../static/icon/餐饮美食/餐饮列表/miqi.jpg" alt="">
					<view class="meal_list_ul_info">
						<view class="meal_list_ul_info_title">米旗(枫叶新都市) <span>标签</span><span>标签</span></view>
						<view class="meal_list_ul_info_place">
							<img src="../../../static/icon/餐饮美食/定位.png" alt="">
							<text>快乐柠檬(西安大都荟店)</text>
							<text class="juli">681m</text>
							<text class="more_info">&gt;</text>
						</view>
						<view class="meal_list_ul_info_tag">
							<span>WIFI</span>
							<span>品种丰富</span>
							<span>好美味</span>
						</view>
						<view class="meal_list_ul_info_msg">
							今天到店消费59次
						</view>
					</view>
				</li>
			</view>
		</view>
		<view class="meal_shop">
			<h4>小雷户县软面(科技路店)</h4>
			<view class="meal_shop_title">
				<view class="meal_shop_title_left">
					月消费:500+
					<span>标签</span><span>标签</span>
				</view>
				<view class="meal_shop_title_right">600m</view>
			</view>
			<view class="meal_shop_list">
				<img src="../../../static/icon/餐饮美食/餐饮美食/龙井虾仁.png" alt="">
				<img src="../../../static/icon/餐饮美食/餐饮美食/外婆红烧肉.png" alt="">
				<img src="../../../static/icon/餐饮美食/餐饮美食/茶香鸡.png" alt="">
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
	image {
		display: block;
	}

	.w_container {
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		background-color: #FFFFFF;
	}

	.meal_top {
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		height: 110upx;
	}

	.meal_top img {
		height: 80%;
	}

	.meal_menu {
		height: 170upx;
	}

	.meal_menu img {
		width: 100%;
		height: 100%;
		;
	}

	.meal_list {
		margin-top: 20upx;
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: 0 20upx;
	}

	.meal_list_menu {
		width: 100%;
		display: flex;
		align-items: center;
	}

	.meal_list_menu view {
		padding: 4upx 30upx;
		margin-bottom: 30upx;
		color: #929292;
	}

	.meal_list_menu view:last-child {
		color: #161616;
	}

	.meal_list_ul {
		list-style: none;
		width: 100%;
	}

	.meal_list_ul li {
		padding: 20upx;
		border: 4upx solid #eeeeee;
		display: flex;
		align-items: center;
		margin: 10upx;
	}

	.meal_list_ul li .meal_list_ul_img {
		width: 190upx;
		height: 190upx;
		margin-right: 30upx;
	}

	.meal_list_ul_info {
		height: 190upx;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		/* align-items: center; */
		font-size: 26upx;
	}

	.meal_list_ul_info_title {
		font-weight: 800;
	}

	.meal_list_ul_info_title span {
		background-color: #0081FF;
		font-size: 12upx;
		color: #fff;
		padding: 4upx 10upx;
		margin: 0 10upx;
		font-weight: normal;
		border-radius: 5upx;
	}

	.meal_list_ul_info_place {
		display: flex;
		justify-content: space-between;
		align-items: center;
		color: #bebebe;
	}

	.meal_list_ul_info_place img {
		width: 20upx;
		height: 21upx;
		margin-right: 10upx;
	}

	.juli {
		color: #acacac;
		padding: 0 5upx 0 20upx;
	}

	.more_info {
		color: #585858;
	}

	.meal_list_ul_info_tag span {
		background-color: #D9D9D9;
		color: #333;
		padding: 4upx 8upx;
		margin: 0 10upx;
		font-weight: normal;
		border-radius: 10upx;
	}

	.meal_list_ul_info_msg {
		color: #FF4040;
		font-size: 12upx;
	}

	.meal_shop {
		width: calc(100% - 60upx);
		margin: 20upx;
		border: 2px solid #DDDDDD;
		padding: 20upx;
	}

	.meal_shop_title {
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin-top: 20upx;
	}

	.meal_shop_title_left {
		font-size: 24upx;
	}

	.meal_shop_title span {
		background-color: #0081FF;
		border-radius: 10upx;
		color: #FFFFFF;
		padding: 4upx 10upx;
		margin: 0 20upx;
	}

	.meal_shop_list {
		margin-top: 20upx;
		width: 100%;
		display: flex;
		align-items: center;
		justify-content: space-around;
	}

	.meal_shop_list img {
		width: 30%;
		height: 180upx;
		border-radius: 10upx;
	}
</style>
