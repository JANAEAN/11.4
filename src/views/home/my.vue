<template>
  <div class="box">
    <div class="head">
      <div class="left">
        <img
          src="https://ss0.bdstatic.com/94oJfD_bAAcT8t7mm9GUKT-xh_/timg?image&quality=100&size=b4000_4000&sec=1572852806&di=4d57b06eb7cea293980fa832dff5b6ab&src=http://b-ssl.duitang.com/uploads/item/201808/31/20180831212309_wwxex.jpg"
        >
      </div>
      <div class="right">
        <p>不愿意透露姓名的马佳宁</p>
        <p> <span>年龄: 18</span>
        <span>活跃度 100</span></p>
       
      </div>
    </div>
    <div class="content">
      <div class="active">* 个人信息</div>
      <div class="active">* 我的评论</div>
      <div class="active">* 个人收藏</div>
      <div class="active">* 修改密码</div>
      <div class="active">* 退出</div>
    </div>
  </div>
</template>

<style lang="scss">
.head {
  width: 100%;
  height: 100px;
  background: tomato;
  display: flex;
}
.active {
  width: 100%;
  height: 30px;
  margin-top: 5px;
  background: #eee;
  font-size: 16px;
}
.left {
  width: 100px;
  height: 90px;
  margin-left: 20px;
}
.right {
  width: 275px;
  height: 100px;
 margin-left:10px;
}
.right p {
  font-size: 16px;
  margin-top:15px;
}
.right span {
  font-size: 16px;
 
}
.left img {
  height: 90px;
  border-radius: 50%;
  margin-top: 5px;
}
</style>


<script>
export default {};
</script>
