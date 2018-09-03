<template>
  <div>
    <home-header></home-header>
    <home-swiper :list='swiperList'></home-swiper>
    <home-icons :list='iconList'></home-icons>
    <home-recommend :list='recommendList'></home-recommend>
    <home-weekend :list='weekendList'></home-weekend>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeIcons from './components/Icons'
import HomeRecommend from './components/Recommend'
import HomeWeekend from './components/Weekend'
import { mapState } from 'vuex'
//发送ajax请求
import axios from 'axios'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwiper,
    HomeIcons,
    HomeRecommend,
    HomeWeekend
  },
  data () {
  	return {
  		lastCity: '',
  		swiperList: [],
  		iconList: [],
  		recommendList: [],
  		weekendList: []
  	}
  },
  computed: {
  	...mapState(['city'])
  },
  methods: {
  	getHomeInfo () {
  		//获取数据
  		axios.get('/api/index.json?city=' + this.city).then(this.getHomeInfoSucc)
  	},
  	getHomeInfoSucc (res){
  		res = res.data;
  		if ( res.ret && res.data ) {
  			const data = res.data
  			this.swiperList = data.swiperList
  			this.iconList = data.iconList
  			this.recommendList = data.recommendList
  			this.weekendList = data.weekendList
  		}
  	}
  },
  //生命周期函数
  mounted () {
  	this.lastCity = this.city
  	this.getHomeInfo()
  },
  activated () {
  	if (this.lastCity !== this.city) {
  		this.lastCity = this.city
  		this.getHomeInfo()
  	}
  }
  
}
</script>

<style>

</style>
