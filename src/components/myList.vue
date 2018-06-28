<template>
    <div class="list-wrapper">
        <div class="list-header">
            <div class="left-header">搜索热点</div>
            <div class="right-header">
                <span class="left-dir"><</span>
                <span>.</span>
                <span>.</span>
                <span>.</span>
                <span class="right-dir">></span>
            </div>
        </div>
        <div class="list-title">
         <div class="left-title">排名</div>
         <div class="right-title">搜索指数</div>
        </div>
        <div class="list-content">

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>
<style>
  .list-wrapper {
      width: 300px;
      border: 1px solid lime;
  }
  .list-header, .list-title {
        display: flex;
        height: 30px;
        line-height: 30px;
   }

   .left-header , .left-title{
       flex: 1;
   }

   .left-dir, .right-dir {
      color: rgb(56, 139, 255)
   }
   
   .normal-dir {
       color: rgb(204,204,204);
   }


</style>