<script>
	export default {
		globalData: {
			ifLogin: false,
			base_url: 'http://127.0.0.1'
		},
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style lang="scss">
	/*每个页面公共css */
	page {
		background-color: #f7f7f7;
	}
</style>
