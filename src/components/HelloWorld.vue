<template>
  <div>
    <b-container fluid class="top-header bg-primary text-white">
      <b-row>
        <b-col>
          <i class="fa fa-phone fa-flip-horizontal fa-fw v-mid mg-left-5"></i>
          <span>
            +9821 4465 1267
          </span>

          <i class="fa fa-map-marker fa-fw v-mid mg-left-5"></i>
          <span>
            تهران، شهرک اکباتان مجتمع تجاری گلها، پلاک 144
          </span>
        </b-col>

        <b-col>
          <i class="fa fa-user fa-fw v-mid"></i>
          <i class="fa fa-shopping-cart fa-fw v-mid"></i>
          <i class="fa fa-search fa-fw v-mid"></i>
        </b-col>
      </b-row>
    </b-container>

    <b-navbar toggleable="lg" type="light" variant="light">
      <b-navbar-brand href="#">
        <b-img src="https://mannakala.com/Uploads/site-1/LogoImage/1.png">

        </b-img>
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">
            صفحه اصلی
          </b-nav-item>

          <b-nav-item href="#">
            مجله کودک
          </b-nav-item>

          <b-nav-item href="#">
            پاسخ به سوالات شما
          </b-nav-item>

          <b-nav-item href="#">
            درباره ما
          </b-nav-item>

          <b-nav-item href="#">
            تماس با ما
          </b-nav-item>

          <b-nav-item href="#">
            شرایط بازگشت کالا
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <div>
      <b-carousel
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="480"
        @sliding-start="onSlideStart"
        @sliding-end="onSlideEnd"
      >
        <b-carousel-slide>
          <template #img>
            <img
              class="d-block img-fluid w-100"
              width="1024"
              height="480"
              src="https://mannakala.com/Uploads/site-1/HeaderImage/10.jpg"
              alt="image slot"
            >
            <img
              class="d-block img-fluid w-100 position-absolute bottom-0"
              width="1024"
              height="480"
              src="https://mannakala.com/Themes/Public/manna-kala/Styles/Images/header-btm.png"
              alt="image slot"
            >

            <div class="carousel-passage">
              <h2>
                خرید اینترنتی انواع اسباب بازی با مناسب ترین قیمت در فروشگاه اسباب بازی ماناکالا
              </h2>

              <p>
                انواع اسباب بازی ها را در فروشگاه اسباب بازی ماناکالا در دسته بندی های مختلف به همراه توضیحات و تصاویر هر کالا مشاهده نمایید و خرید خود را به صورت اینترنتی انجام دهید. تمامی کالا ها در ماناکالا با بهترین کیفیت و مناسب ترین قیمت ارائه می شود. 
              </p>
            </div>
          </template>
        </b-carousel-slide>
      </b-carousel>
    </div>

    <b-container fluid class="doll-cat">
      <b-row>
        <h2 class="header-logo">
          <span>
            دسته بندی اسباب بازی ها
          </span>
        </h2>

        <b-col>
          <div>
            <b-img class="w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/54_500_500_70_CropFromCenter.jpg">

            </b-img>
          </div>
        </b-col>

        <b-col>
          <div>
            <b-img class="w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/65_500_500_70_CropFromCenter.jpg">

            </b-img>
          </div>
        </b-col>

        <b-col>
          <div>
            <b-img class="w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/64_500_500_70_CropFromCenter.jpg">

            </b-img>
          </div>
        </b-col>

        <b-col>
          <div>
            <b-img class="w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/63_500_500_70_CropFromCenter.jpg">

            </b-img>
          </div>
        </b-col>

        <b-col>
          <div>
            <b-img class="w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/62_500_500_70_CropFromCenter.jpg">

            </b-img>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.carousel-passage {
  position: absolute;
  top: 27%;
  right: 7%;
  max-width: 30%;
  background: rgba(255,255,255,.75);
  padding: 50px;
  border-radius: 40px;
}
.doll-cat {
  background-image: url('https://mannakala.com/Themes/Public/manna-kala/styles/Images/m2-bg.jpg');
}

.header-lego span:after {
    top: 4px;
    right: unset!important;
    left: -60px;
}
.header-lego span:before, .header-lego span:after {
    content: '';
    position: absolute;
    top: 4px;
    right: -60px;
    width: 25px;
    height: 32px;
    background: url('https://mannakala.com/Themes/Public/manna-kala/styles/Images/header-lego.png') no-repeat;
    background-size: 25px;
}
</style>