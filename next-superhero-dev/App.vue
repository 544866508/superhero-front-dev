<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			this.checkJWT()
			console.log('App Show')
		},
		onHide: function() {
			// if(uni.getStorageSync('AUTH_TOKEN')){
			// 	uni.removeStorageSync('AUTH_TOKEN')
			// }
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	.page {
		width: 100%;
		height: 100%;
		background-color: #f7f7f7;
		/* position: absolute; */
	}
	.page-block {
		background-color: #FFFFFF;
	}
	
	/* 分割线（实线） start */
	.line-wapper {
		padding: 0upx 20upx;
	}
	.line {
		height: 1px;
		background-color: #DBDBDA;
	}
	/* 分割线（实线） end */
</style>
