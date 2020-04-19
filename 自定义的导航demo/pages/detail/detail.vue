<template>
	<view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onNavigationBarButtonTap(e) {
			console.log("success",e);
			if(e.id=='test1'){
				uni.showToast({
					title:"你点击了自定义按钮"
				})
			}else{
				uni.showToast({
					title:"你点击了飞机按钮"
				})
			}
			
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
