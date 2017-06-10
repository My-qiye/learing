<template>
    <main class="details2">
       <div>拖延症</div>
       <ol>
           <li v-for="val1 in texts">{{val1}}</li>
       </ol>
    </main>
</template>
<script>
    export default{
       name:'details2',
       data(){
           return{
               texts:[
                   '1. 拖延症的类型',
                   '2. 拖延症从何而来？',
                   '3. 第三节拖延症的危害',
                   '4. 战拖，从抗击懒惰开始',
                   '5. 再见吧，拖拉斯基',
                   '6. 让完美主义见鬼去吧',
                   '7. 没有任何借口',
                   '8. 打造强大的执行力',
                   '9. 有目标的人才不拖延',
                   '10. 时间管理，终结拖延恶习',
                   '11. 来吧！给自己来点正能量'
               ]
           }
       } 
    }
</script>
<style src="../assets/css/details2.less" lang="less" scoped>
    /*@import '../assets/css/normalize.css';*/
    /*@import '../assets/css/detail.less';*/
</style>