<template>
  <nav>
    <div class="logo">
      <img src="../public/logo.svg" alt="">
    </div>
    <div class="menu">
      <ul>
        <li><a href="#">หน้าแรก</a></li>
        <li><a href="#">เกี่ยวกับ</a></li>
        <li><a href="#">สินค้า</a></li>
        <li><a href="#">ติดต่อ</a></li>
        <li class="search-box"><input type="text" placeholder="ค้นหา" /></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
*{
  font-family: "Charm", cursive;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
nav{
  padding: 0.5rem;
  display: flex;
  justify-content: space-between;
  background-color: #333;
}
.logo img{
  width: 3rem;
  background-color: aliceblue;
  margin: 0 2rem;
}
.menu ul{
  display: flex;
  list-style: none;
}
.menu li{
  margin: 0 1rem;
}
.menu li a{
  color: aliceblue;
  text-decoration: none;
}


</style>
