<template>
  <div>
    <div class="content">
      <div class="jumbotron"></div>
      <div>
        <spam>CURRENT SERIES</spam>
      </div>
      <div class="box-card">
        <MainCardComp
          v-for="(elem, index) in Prodotti"
          :key="index"
          :Prodotti="elem"
        />
      </div>
      <button>LOAD MORE</button>
    </div>
    <div class="conteiner">
      <div class="shop">
        <div class="card">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <span>DIGITAL COMICS</span>
        </div>

        <div class="card">
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          <span>DIGITAL COMICS</span>
        </div>

        <div class="card">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <span>DIGITAL COMICS</span>
        </div>

        <div class="card">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <span>DIGITAL COMICS</span>
        </div>

        <div class="card">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <span>DIGITAL COMICS</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MainCardComp from "./MainCardComp.vue";

export default {
  name: "MainComp",

  components: {
    MainCardComp,
  },

  data() {
    return {
      Prodotti: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.jumbotron {
  background-image: url(../assets/img/jumbotron.jpg);
  background-repeat: no-repeat;
  width: 100%;
  height: 450px;
  background-size: cover;
}

.conteiner {
  background-color: rgba(2, 130, 249, 255);
  width: 100%;
  display: flex;
  justify-content: center;
}

.shop {
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
  font-size: 14px;
  img {
    width: 17%;
  }
}

.box-card {
  display: flex;
  width: 80%;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 0 auto;
  padding: 40px 0;
}

div {
  text-align: center;
  button {
    background-color: rgba(2, 130, 249, 255);
    color: white;
    padding: 10px 30px;
    border: 0;
    margin-bottom: 20px;
  }
}

div {
  position: relative;
  spam {
    text-align: start;
    background-color: rgba(2, 130, 249, 255);
    color: white;
    padding: 10px 30px;
    position: absolute;
    top: -20px;
    left: 125px;
  }
}
</style>