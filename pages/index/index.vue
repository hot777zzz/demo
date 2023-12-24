<template>
	<view>
	<view class="search_box">
		<view class="search_box_border">
			<u-input placeholder="搜索优质产品" placeholder-style="color: #969696" prefixIcon="search"
				prefixIconStyle="font-size: 22px;color: #909399;margin-left:30rpx" readonly>
			</u-input>
		</view>
	</view>
	<h1>测试</h1>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {

		},
		methods: {
		
		}
	}
</script>

<style lang="scss">
	// 搜索框样式
	.search_box {
		background: linear-gradient(135deg, #12CA64 0%, #1ACA67 100%);

		.search_box_border {
			width: 94.6%;
			height: 124rpx;
			background: linear-gradient(320deg, #36E182 0%, #26DD76 100%, #26DD76 100%);
			margin: 0 auto;
			box-shadow: 0 -1px 3px 0 #31B96D;
			border-radius: 38rpx 38rpx 0 0;

			.u-border {
				border: none;
				padding-top: 16px !important;

				.u-input__content {
					height: 64rpx;
					border-radius: 32rpx;
					background-color: #fff;

					.u-input__content__field-wrapper__field {
						font-size: 26rpx !important;
					}
				}
			}
		}
	}
</style>