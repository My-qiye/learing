<template>
  <div id="app">
   <header style="z-index: 999;background:#fff;">
			<div @click="index()">云课堂</div>
			<div>
				<div>
					<i class="iconfonts">&#xe614;</i>
				</div>
				<div>
					<i class="iconfonts">&#xe680;</i>
					<i class="iconfonts">&#xe606;</i>
				</div>
			</div>
		</header>
    <router-view></router-view>

  </div>
</template>

<script>
export default {
  name: 'app',
	methods:{
		index:function(){
			this.$router.push('/');
		}
	}
}
</script>

<style lang="less">
  @import './assets/css/index.less';
</style>
