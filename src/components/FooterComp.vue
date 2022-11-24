<template>
  <footer>
    <div class="conteiner">
      <div class="DcComics">
        <div>
          <ul>
            <li class="titolo">DC COMICS</li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>Tv</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <ul>
            <li class="titolo">SHOP</li>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <div>
          <ul>
            <li class="titolo">DC</li>
            <li>Tems of use</li>
            <li>Privacy</li>
            <li>Ad Choise</li>
            <li>Adversting</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div>
          <ul>
            <li class="titolo">SITES</li>
            <li>DC</li>
            <li>MAD</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>

      <div class="img-logo">
        
      </div>
    </div>
    <div class="footer-icon">
      <div class="conteiner flex">
        <div class="sign-up">
          <a>SIGN-UP NOW!</a>
        </div>
        <div class="icon">
          <span>FOLLOW US</span>
          <img src="../assets/img/footer-facebook.png" alt="" />
          <img src="../assets/img/footer-periscope.png" alt="" />
          <img src="../assets/img/footer-twitter.png" alt="" />
          <img src="../assets/img/footer-youtube.png" alt="" />
          <img src="../assets/img/footer-pinterest.png" alt="" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComp",
  components: {},
};
</script>



<style lang="scss" scoped>

footer {
  background-image: url(../assets/img/footer-bg.jpg);
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.conteiner {
  width: 80%;
  display: flex;
  color: grey;
}

.DcComics {
  display: flex;
  flex-basis: 40%;
  margin: 35px 0;
}

.img-logo {
  flex-basis: 60%;
  display: flex;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-position: center;

  img {
    width: 50%;
  }
}

ul {
  list-style-type: none;
  li {
    margin: 8px 0px;
    margin-right: 25px;

    font-size: 12px;
  }
}
.titolo {
  color: white;
  font-weight: 700;
  font-size: 16px;
  margin: 10px 0;
}

.footer-icon {
  background-color: rgba(48, 48, 48, 255);
  width: 100%;
  padding: 20px 0;
  display: flex;
  justify-content: center;

  .flex {
    display: flex;
    width: 80%;
    align-items: center;
  }
}

.sign-up {
  flex-basis: 20%;
  display: flex;
  justify-content: start;
}

.icon {
  flex-basis: 79%;
  display: flex;
  justify-content: end;
  align-items: center;
}

div {
  span {
    color: rgba(2, 130, 249, 255);
    margin-right: 10px;
    font-weight: 800;
    font-size: 20px;
  }
  img {
    margin: 0 8px;
  }
}

div {
  a {
    border: 2px solid rgba(2, 130, 249, 255);
    padding: 10px 10px;
    color: white;
  }
}
</style>