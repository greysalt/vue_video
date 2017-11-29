<template>
  <div class="home-container">
    <div class="entry">
      <router-link to="/detail/16049">ENTRY</router-link>
    </div>   
  </div>
</template>

<script>
</script>
<style lang="scss">
.home-container{
  width:200px;
  height:200px;
  border:1px solid #fff;
  border-radius:200px;
  position:fixed;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  display:flex;
  justify-content:center;
  align-items:center;

  .entry {
    width: 100px;
    height: 100px;
    border-radius: 100px;
    border:1px solid #fff;
    text-align:center;
    &:hover{
      background:#666;
    }

    a {
      color:#fff;
      line-height:100px;
      font-size:20px;
    }
  }
} 


</style>
