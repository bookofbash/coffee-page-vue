<template>
  <div class="container">
      <div class="title">#COFFEE</div>
      <div class="subtitle">Coffee perfection since 1927.</div>
      <div class="banner-grid">
          <div class="banner"><img :src="images.bannerImage"></div>

          <!-- <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/alisha-hieb-4-Pj2x7J22M-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/brigitte-tohm-lbdNTcejZQs-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/clem-onojeghuo-9AEh9i-WPhI-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/janko-ferlic-specialdaddy-h9Iq22JJlGk-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/lex-sirikiat-1tEkissU8dY-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/nathan-dumlao-ikU3J1nr52w-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/nathan-dumlao-r-KfktlyBL0-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/nathan-dumlao-tA90pRfL2gM-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/nolan-issac-It0DCaCBr40-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/pablo-merchan-montes-SCbq6uKCyMY-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/toa-heftiba-09SxeOdtlPE-unsplash.jpg"></div>
          <div class="banner-image animated fadeInRight wow"><img src="./../../static/banner-images/toa-heftiba-BgtVT7bVVcc-unsplash.jpg"></div> -->
      </div>
  </div>
</template>

<script>
export default {
      data() {
        return {
            images: {
                bannerImage: require('../../static/banner.png')
                
            }
        }
    }
}
</script>

<style scoped>
.container{
    margin-top: 140px;
    margin-left:0px;
    margin-right:0px;
    width: 100%;
}
.title{
    font-size: 2.5rem;
    font-family: Garamond,Baskerville,Baskerville Old Face,Hoefler Text,Times New Roman,serif; 
    font-weight: 900;
    margin-bottom: 10px;
}
.subtitle{
    font-size: 1rem;
    font-weight: 500;
}
/* .banner-grid{
    margin-top: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;

} */
.banner-image img {
    display: flex;
    height: 170px;
    width: 170px
    
}
.banner {
    margin-top: 40px;
    display: flex;
    justify-content: center;
    margin-bottom: 0px;
    background: black;
}
</style>