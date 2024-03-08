<template>
  <div class="bg-image">
    <div class="hero">
      <img src="../public/logo.svg" />
      <h1>สิ่งที่น่ากลัวที่สุดของการจากลา...คือมันไม่ได้บอกว่าจะมาเมื่อไหร่</h1>
    </div>
  </div>
  <div>
    <div class="shop-hero">
      <h1>SHOP NOW</h1>
      <div class="้hero-recommended-products">
        <div class="shop-hero-image">
          <img src="../public/พัดตาลปัตรไปไม่กลับ.png" alt="" />
          <img src="../public/พัดตาลปัตรหลับไม่ตื่น.png" alt="" />
          <img src="../public/พัดตาลปัตรฟื้นไม่มี.png" alt="" />
          <img src="../public/พัดตาลปัตรหนีไม่พ้น.png" alt="" />
        </div>
        <div class="paragraph">
          <h1>
            ชุดตาลปัตรส่งผู้วายชนม์ (ไปไม่กลับ หลับไม่ตื่น ฟื้นไม่มี หนีไม่พ้น)
          </h1>
          <h2>ราคา: 1,849 บาท</h2>
          <p>อุปกรณ์เตือนใจ เมื่อถึงวันนั้นมาถึง เราทุกคนจะไปไม่กลับ หลับไม่ตื่น ฟื้นไม่มี และหนีไม่พ้น</p>
          <button>ไปยังหน้าสินค้า</button>
        </div>
      </div>
    </div>
  </div>
  <div class="shop-hero-1">
      <div class="shop-hero-1-image">
        <img src="../public/เสื้อหน้า.png" alt="">
        <img src="../public/เสื้อหลัง.png" alt="">
      </div>
      <div class="paragraph">
        <h1>เสื้อเจ้าพนักงานส่งวิญญาณ</h1>
        <h2>ราคา 590 บาท</h2>
        <button>ไปยังหน้าสินค้า</button>
      </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.bg-image {
  position: relative;
  width: 100%;
  height: 100vh;
  background-image: url(../public/dFQROr7oWzulq5Fa5K8CXBdcc85k03NLFE88jIQaDEGuBe1ElNLnR1sYvadlGvpjcCO.webp);
  background-size: 100%;
  background-repeat: no-repeat;
}
.hero {
  position: absolute;
  height: 100vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.hero img {
  width: 20%;
}
.hero h1 {
  font-size: 3rem;
  font-family: "Charm", cursive;
  margin-bottom: 2rem;
  color: white;
}
.shop-hero {
  font-family: "Charm", cursive;
  font-weight: 400;
  font-style: normal;
}
.shop-hero-image {
  display: flex;
  justify-content: center;
}
.shop-hero-image img {
  width: 15%;
  margin: 0 20px;
}
.paragraph{
  display: flex;
  flex-direction: column;
  align-items:center;
  margin-top: 2rem;
}
.้hero-recommended-products{
  border: 10px solid black;
}
.shop-hero-1-image{
  display: flex;
  justify-content: center;
}
.shop-hero-1-image img{
  width: 8rem;
  justify-items: center;
}
.shop-hero-1{
  margin: 2rem 0;
  padding: 2rem ;
  width: 20vw;
  height: auto;
  background-image: url(../public/background.jpg);
  background-size: 100%;
  display: flex;
  flex-direction: column;
  border-radius: 50px;
}
</style>
