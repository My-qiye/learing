<template>
    <div class="list">
        <nav>
            <router-link class="div" to="list1">免费排行</router-link>
            <router-link class="div" to="list2">畅销排行</router-link>
		</nav>
        <router-view></router-view>
    </div>
</template>
<script>
    export default{
        name:'list'
    }
</script>
<style lang="less">
    @import '../assets/css/normalize.css';
    @import '../assets/css/list.less';
</style>