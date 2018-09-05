<template>
	<div>
		<div class="banner" @click="handleBannerClick">
			<img class='banner-img' src="//img1.qunarzz.com/sight/p0/1804/c8/c88bb5e69c9a9c5ea3.img.jpg_600x330_bda46e68.jpg"/>
			<div class="banner-info">
				<div class="banner-title">
					北京活的3D博物馆
				</div>
				<div class="bannner-number">
					<span class="iconfont banner-icon">&#xe692;</span>
					39
				</div>
			</div>
		</div>
		<common-gallary 
			:imgs='imgs' 
			v-show='showGallary'
			@close='handleGallaryClose'
		></common-gallary>
	</div>
	
</template>

<script>
	import CommonGallary from 'common/gallary/Gallary'
	export default {
		name: 'DetailBanner',
		data () {
			return {
				showGallary:false,
				imgs: [
				'http://img1.qunarzz.com/sight/p0/1501/ab/ab02fceb3fa0a60e.water.jpg_r_800x800_351dd5e6.jpg',
				'http://img1.qunarzz.com/sight/p0/1508/89/895a1b7add84f23faca053ce9e3153db.water.jpg_r_800x800_087730c7.jpg']
			}
		},
		methods: {
			handleBannerClick () {
				this.showGallary = true
			},
			handleGallaryClose () {
				this.showGallary = false
			}
		},
		components: {
			CommonGallary
		}
	}
</script>

<style lang="stylus" scoped>
	.banner
		position: relative
		overflow: hidden
		height: 0
		padding-bottom: 55%
		.banner-img
			width: 100%
		.banner-info
			display: flex
			position: absolute
			left: 0
			bottom: 0
			right: 0
			line-height: .6rem
			color: #fff
			background-image: linear-gradient(top, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.8))
			.banner-title
				flex: 1
				font-size: .32rem
				padding: 0 .2rem
			.bannner-number
				margin-top: .14rem
				padding: 0 .4rem
				height: .32rem
				line-height: .32rem
				border-radius: .2rem
				background: rgba(0, 0, 0, .8)
				font-size: .24rem
				.banner-icon
					font-size: .24rem
</style>