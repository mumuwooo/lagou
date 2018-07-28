<template>
    <div class="users">
        <span>10秒钟定制职位</span>
        <a href="javascript:">去登录</a>
    </div>
</template>

<script>
    export default {
        name:"Users",
    }
</script>

<style scoped>
   .users{
    border-bottom: 1px solid #e8e8e8;height: 43px;
    line-height: 43px;padding: 0 15px;
    color: #555;font-size: 1.4rem;
    position: relative;
    background: #fff;
   }
   .users>span{
    overflow: hidden; text-overflow: ellipsis;
    white-space: nowrap; display: block;
    margin-right: 100px; height: 100%;
    position: relative;
   }
   .users>a{
    position: absolute;
    right: 15px;top: 0;display: block;
    float: right;background-color: #f5f5f5;
    padding: 0 20px; height: 30px;line-height: 30px;
    margin-top: 6px;color: #00b38a;border-radius: 15px;
   }
</style>