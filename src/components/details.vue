<template>
    <div class="details">
        <section>
			<div>
				<img src="../../static/images/details.jpg" alt="">
			</div>
			<div>
				<router-link class="div" to="details1">简介</router-link>
				<router-link class="div" to="details2">目录</router-link>
				<router-link class="div" to="details3">评价</router-link>
			</div>
			 <router-view></router-view>
		</section>
    </div>
</template>
<script>
    export default{
       name:'details',
       data(){
           return{

           }
       } 
    }
</script>
<style scoped lang="less">
	
    .details{
    section{
    	padding-top:40px;
    	padding-bottom: 50px;
    	display: flex;
    	flex-direction:column;
    	>div{
    		width: 100%;
            text-align: left;
    		align-self:flex-end;
            margin: 0px;
            border-top:0px;
			
    	}
    	>div:first-of-type{
			width: 100%;
    		>img{
				width:100%;
				display: block;
    		}
    	}
    	>div:nth-of-type(2){
    		width: 100%;
    		display:flex;
			padding: 5% 0;
    		>.div{
    			flex:1;
    			display: flex;
    			justify-content:center;
    			text-align: center;
    			font-size: 20px;
				color:#333;
    			>span{
    				display: block;
    				width: 60%;
    				padding: 8% 0;

    			}
    		}
    		>div:first-of-type{
    			color: #2cc17b;
    			span{
    				border-bottom: 3px solid #2cc17b;
    			}
    		}
    	}
    	
    }
}
</style>