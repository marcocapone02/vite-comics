<script>
export default {
  name: 'footer'
}
</script>

<template>

  <div class="root">

    <div class="link ">
      <ul class="first">
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="" width="42" height="42"> Digital comics</li>
        <li><img src="../assets/img/buy-comics-merchandise.png" alt=""> Dc merchandise</li>
        <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""> Subscription</li>
        <li><img src="../assets/img/buy-comics-shop-locator.png" alt="">Comic shop locator</li>
        <li><img src="../assets/img/buy-dc-power-visa.svg" alt="">Dc power visa</li>
      </ul>
    </div>

    <div class="dc-logo">
      <div class="link-2 d-flex">
        <ul class="list">
          <li><strong>Dc Comics</strong></li>
          <li>Charaters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>

        <ul class="list">
          <li><strong>DC</strong></li>
          <li>Teams Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talents Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>

        <ul class="list">
          <li><strong>Sites</strong></li>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>

      </div>

      <div class="link-2 d-flex">
        <ul class="list">
          <li><strong>Shop</strong></li>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>

  </div>

  <div class="sing-up d-flex">
    <div class="sign">sing-up now!</div>

    <ul>
      <li><img src="../assets/img/footer-facebook.png" alt=""></li>
      <li><img src="../assets/img/footer-periscope.png" alt=""></li>
      <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
      <li><img src="../assets/img/footer-twitter.png" alt=""></li>
      <li><img src="../assets/img/footer-youtube.png" alt=""></li>
    </ul>
  </div>
  </div>

</template>

<style scoped>
  .root{
    display: flex;
    flex-direction: column;
    background-image: url(../assets/img/footer-bg.jpg);
  }
  .link{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #0282F9;
  }

img{
  height: 50px;
}
  ul.first{
    margin: 0px;
    display: flex;
}

ul.first li{
  color: white;
  list-style: none;
  margin: 42px;
}

ul.first li:hover{
  font-weight: bold;
  cursor: pointer;
}
ul.list{
  color: white;
}
ul.list li:first-child{
  margin: 10px 0px;
  color: white;
}
ul.list li{
  color: gray;
  list-style: none;
  font-size: 14px;
  cursor: pointer;
}

.link-2{
  padding: 20px 230px;
}
.dc-logo{
  height: 100%;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-position: right;
  margin-right: 280px;
}

.sing-up {
  padding: 20px 300px;
  background-color: #303030;
  color: #0282F9;
  height: 100px;
  justify-content: space-between;
  align-items: baseline;
}

.sign{
  border: 1px solid #0282F9;
  padding: 10px;
  color: white;
  text-transform: uppercase;
}

.sing-up ul{
  display: flex;
  list-style: none;
}
.sing-up ul li img{
  height: 35px;
  margin: 10px;
}

</style>