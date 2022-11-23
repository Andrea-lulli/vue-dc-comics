<template>
  <div>
    <div class="content"></div>
    <div class="conteiner">
<div class="shop">
      <div class="card">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span>DIGITAL COMICS</span>
      </div>

      <div class="card">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span>DIGITAL COMICS</span>
      </div>

      <div class="card">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span>DIGITAL COMICS</span>
      </div>

      <div class="card">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span>DIGITAL COMICS</span>
      </div>

      <div class="card">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span>DIGITAL COMICS</span>
      </div>
    </div>
  </div>
    </div>
    
</template>

<script>
export default {
  name: "MainComp",
};
</script>

<style lang="scss" scoped>
.content {
  background-color: black;
  width: 100%;
  height: 50px;
}
.conteiner{
    background-color: blue;
  width: 100%;
  display: flex;
  justify-content: center;
 
}
.shop {
  background-color: blue;
  width: 80%;
  display: flex;
  align-items: center;
}
.card {
  display: flex;
  align-items: center;
  padding: 20px 0;
  color: white;
  flex-basis: 24%;
  justify-content: space-around;
  img {
    width: 20%;
  }
}
</style>