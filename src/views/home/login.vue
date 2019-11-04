<template>
  <div class="box">
    <p class="title">圈子登录</p>

    <input type="text" placeholder="用户名" class="ipt">
    <input type="text" placeholder="登录密码" class="ipt">
   <!-- 想跳路由在外面抱一个outer-link to="/home/my" -->
   <router-link to="/home/my"><button class="btn" >登录</button></router-link> 
  </div>
</template>

<style lang="scss">
.title {
  text-align: center;
  width: 100%;
  height: 50px;
  line-height: 50px;
  background: #eee;
  font-size: 20px;
}
.ipt {
  width: 90%;
  height: 40px;
  margin-left: 15px;
  background: #eee;
  border: none;
}
.btn {
  width: 90%;
  height: 50px;
  line-height: 50px;
  background: tomato;
  margin-top: 10px;
  margin-left: 15px;
  font-size: 16px;
  color: aliceblue;
  border: none;
}
</style>


<script>
export default {
  data(){
    return {

    }
  },
  methods: {
    // dianji(){
      
    // }
  },

};
</script>
