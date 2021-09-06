<template>
	<view>
		<!-- <view>
			<text>信息x</text>
		</view>
		<view>
			<text selectable>信息xy</text>
		</view>
		<view>
			<text space="nbsp">信     息xyx</text>
		</view>
		<view>
			<text decode="true">&amp;</text>
		</view> -->
		
		<!--  hover-class按下添加样式类   hover-stop-propagation阻止冒泡  hover-start-time 按住后多少秒才添加样式类    hover-stay-time松开后多少秒去除样式类-->
		<view class="box2" hover-class="pink"  :hover-stay-time="2000">
			<view class="box1" hover-class="red" hover-stop-propagation :hover-start-time="2000">盒子1</view>
		</view>
		<button>anniu</button>
		<!-- 设置大小  颜色  镂空  禁用  图标-->
		<button size="mini">anniu</button>
		<button type="primary">anniu</button>
		<button type="primary" plain>anniu</button>
		<button type="primary" disabled>anniu</button>
		<button loading>anniu</button>
		
		<!--  image图片会默认宽高  -->
		<image src="http://destiny001.gitee.io/image/cxk.gif"></image>
		<image src="http://destiny001.gitee.io/image/cxk.gif" mode="aspectFit"></image>
		<image src="http://destiny001.gitee.io/image/cxk.gif" mode="aspectFill"></image>
		
		
		
		
	</view>
</template>

<script>
</script>

<style>
	.box1{
		width: 100px;
		height: 100px;
		background-color: #808080;
	}
	.red{
		background-color: red;
	}
	.box2{
		width: 200px;
		height: 200px;
		background-color: #007AFF;
	}
	.pink{
		background-color: pink;
	}
</style>
