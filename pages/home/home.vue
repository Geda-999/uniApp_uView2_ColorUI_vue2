<template>
  <view>
    <!-- 测试-这是colorui库 -->
    <view class="cu-bar bg-white">
    	<view class="action">
    		<text class="cuIcon-locationfill text-gray"></text> 广州
    	</view>
    	<view class="content text-bold a">
    		MCAKE
    	</view>
    	<view class="action text-grey">
    		<text class="cuIcon-search"></text>
    		<text class="cuIcon-sort"></text>
    	</view>
    </view>
    
    <!-- 测试-这是uview2组件库 -->
    	<view style="padding: 20px;">
    		<u-button type="primary" text="确定"></u-button>
    		<u-button type="primary" :plain="true" text="镂空"></u-button>
    		<u-button type="primary" :plain="true" :hairline="true" text="细边"></u-button>
    		<u-button type="primary" :disabled="disabled" text="禁用"></u-button>
    		<u-button type="primary" loading loadingText="加载中"></u-button>
    		<u-button type="primary" icon="map" text="图标按钮"></u-button>
    		<u-button type="primary" shape="circle" text="按钮形状"></u-button>
    		<u-button text="渐变色按钮" color="linear-gradient(to right, rgb(66, 83, 216), rgb(213, 51, 186))"></u-button>
    		<u-button type="primary" size="small" text="大小尺寸"></u-button>
    	</view>
  </view>
</template>

<script>
  export default {
    data() {
      return {
        
      };
    }
  }
</script>

<style lang="scss">

</style>
