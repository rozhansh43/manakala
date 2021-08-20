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
        <h2 class="main-title text-center">
          <span class="position-relative">
            دسته بندی اسباب بازی ها
          </span>
        </h2>

      <b-container>
        <b-row>
          <b-col>
            <a href="#" class="extended-item">
              <div class="position-relative">
                <b-img class="w-100 img-fluid img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/54_500_500_70_CropFromCenter.jpg">

                </b-img>
                <i class="plus-icons fa fa-plus"></i>
              </div>
            </a>
          </b-col>

          <b-col>
            <a href="#" class="extended-item">
              <div class="position-relative">
                <b-img class="w-100 img-fluid img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/54_500_500_70_CropFromCenter.jpg">

                </b-img>
                <i class="plus-icons fa fa-plus"></i>
              </div>
            </a>
          </b-col>

          <b-col>
            <a href="#" class="extended-item">
              <div class="position-relative">
                <b-img class="w-100 img-fluid img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/54_500_500_70_CropFromCenter.jpg">

                </b-img>
                <i class="plus-icons fa fa-plus"></i>
              </div>
            </a>
          </b-col>

          <b-col>
            <a href="#" class="extended-item">
              <div class="position-relative">
                <b-img class="w-100 img-fluid img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/54_500_500_70_CropFromCenter.jpg">

                </b-img>
                <i class="plus-icons fa fa-plus"></i>
              </div>
            </a>
          </b-col>

          <b-col>
            <a href="#" class="extended-item">
              <div class="position-relative">
                <b-img class="w-100 img-fluid img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/54_500_500_70_CropFromCenter.jpg">

                </b-img>
                <i class="plus-icons fa fa-plus"></i>
              </div>
            </a>
          </b-col>
        </b-row>
      </b-container>
    </b-container>

    <b-container>
      <b-row>
        <carousel :perPageCustom="[[0, 2], [768, 3], [1024,3]]">
          <slide class="product-slider">
            <a href="#" class="d-block text-decoration-none position-relative">
              <b-img class="img-fluid bg-2 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/1395_150_150_70_CropFromCenter.jpg">
              </b-img>

              <h4 class="my-5 text-center">
                <span class="text-dark">
                  فیگور بچه دایناسور تیرکس MOJO کد 387192
                </span>
              </h4>

              <p class="text-success position-absolute">
                135,000 تومان
              </p>

              <div class="d-flex justify-content-center">
                <b-button pill variant="primary mb-5">
                  مشاهده و خرید محصول
                </b-button>
              </div>
            </a>
          </slide>

          <slide class="product-slider mx-3 ">
            <a href="#" class="d-block text-decoration-none position-relative">
              <b-img class="img-fluid bg-2 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/1395_150_150_70_CropFromCenter.jpg">
              </b-img>

              <h4 class="my-5 text-center">
                <span class="text-dark">
                  فیگور بچه دایناسور تیرکس MOJO کد 387192
                </span>
              </h4>

              <p class="text-success position-absolute">
                135,000 تومان
              </p>

              <div class="d-flex justify-content-center">
                <b-button pill variant="primary mb-5">
                  مشاهده و خرید محصول
                </b-button>
              </div>
            </a>
          </slide>

          <slide class="product-slider">
            <a href="#" class="d-block text-decoration-none position-relative">
              <b-img class="img-fluid bg-2 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/1395_150_150_70_CropFromCenter.jpg">
              </b-img>

              <h4 class="my-5 text-center">
                <span class="text-dark">
                  فیگور بچه دایناسور تیرکس MOJO کد 387192
                </span>
              </h4>

              <p class="text-success position-absolute">
                135,000 تومان
              </p>

              <div class="d-flex justify-content-center">
                <b-button pill variant="primary mb-5">
                  مشاهده و خرید محصول
                </b-button>
              </div>
            </a>
          </slide>
        </carousel>
      </b-row>
    </b-container>

    <b-container class="bg-pattern" fluid>
      <b-row>
        <h2 class="main-title">
          <span class="position-relative">
           انواع اسباب بازی برای رده های سنی مختلف
          </span>
        </h2>

        <b-col sm="2">
          <div class="position-relative rotate-hover">
            <b-img class="img-fluid w-100 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/66_360_360_70_CropFromCenter.jpg">
            </b-img>

            <h4 class="position-absolute top-0 title">
              <span>
                بالای 12 سال
              </span>
            </h4>
          </div>

          <h4>
            بالای 12 سال
          </h4>
        </b-col>
        <b-col sm="2">
          <div class="position-relative rotate-hover">
            <b-img class="img-fluid w-100 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/71_360_360_70_CropFromCenter.jpg">
            </b-img>

            <h4 class="position-absolute top-0 title">
              <span>
                بالای 12 سال
              </span>
            </h4>
          </div>

          <h4>
            بالای 12 سال
          </h4>
        </b-col>
        <b-col sm="2">
          <div class="position-relative rotate-hover">
            <b-img class="img-fluid w-100 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/70_360_360_70_CropFromCenter.jpg">
            </b-img>

            <h4 class="position-absolute top-0 title">
              <span>
                بالای 12 سال
              </span>
            </h4>
          </div>

          <h4>
            بالای 12 سال
          </h4>
        </b-col>
        <b-col sm="2">
          <div class="position-relative rotate-hover">
            <b-img class="img-fluid w-100 img-circle" src="https://mannakala.com/Uploads/Thumbs/site-1/LinkImage/69_360_360_70_CropFromCenter.jpg">
            </b-img>

            <h4 class="position-absolute top-0 title">
              <span>
                بالای 12 سال
              </span>
            </h4>
          </div>

          <h4>
            بالای 12 سال
          </h4>
        </b-col>
      </b-row>
    </b-container>

    <b-container>
      <b-row>
        <h2>
          <span>

          </span>
        </h2>

        <div>
          <carousel :perPageCustom="[[0, 2], [768, 7], [1024,7]]">
            <slide>
              <a href="">
                <b-img src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/542_149_149_72_CropFromCenter.png">
                </b-img>
              </a>
            </slide>
            <slide>
              Slide 2 Content
            </slide>
          </carousel>
        </div>
      </b-row>
    </b-container>
    <b-container>
      <b-row>
        <h2 class="text-center">
          <a href="#">
            <span>
              مجله کودک
            </span>
          </a>
        </h2>
        
        <b-col md="4">
          <div class="position-relative">
            <b-img class="img-fluid w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/1404_480_400_70_CropFromCenter.jpg">
            </b-img>

            <div class="rotated-bg bg-info">
              <h2>
                تاثیر تنبیه و تشویق کودکان 
              </h2>
            </div>
          </div>

          <p class="bg-info position-relative text-justify dashed-border">
            تشویق و تنبیه چیست؟تشویق در لغت به معنای به شوق در آوردن و کار کسی را ستودن و او را دلگرم ساختن است. تشویق از تمایلات فطری هر انسانی است که تا پایان عمر در او باقی می ماند و تنبیه عبارت است از آگاه ساختن فرد نسبت به نتایج نامطلوبش. در تعلیم و تربیت وقتی از تشویق و تنبیه صحبت می شود منظور این است که
          </p>
        </b-col>
        
        <b-col md="4">
          <div class="position-relative">
            <b-img class="img-fluid w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/1404_480_400_70_CropFromCenter.jpg">
            </b-img>

            <div class="rotated-bg bg-info">
              <h2>
                تاثیر تنبیه و تشویق کودکان 
              </h2>
            </div>
          </div>

          <p class="bg-info position-relative text-justify">
            تشویق و تنبیه چیست؟تشویق در لغت به معنای به شوق در آوردن و کار کسی را ستودن و او را دلگرم ساختن است. تشویق از تمایلات فطری هر انسانی است که تا پایان عمر در او باقی می ماند و تنبیه عبارت است از آگاه ساختن فرد نسبت به نتایج نامطلوبش. در تعلیم و تربیت وقتی از تشویق و تنبیه صحبت می شود منظور این است که
          </p>
        </b-col>
        
        <b-col md="4">
          <div class="position-relative">
            <b-img class="img-fluid w-100" src="https://mannakala.com/Uploads/Thumbs/site-1/FeaturedImage/1404_480_400_70_CropFromCenter.jpg">
            </b-img>

            <div class="rotated-bg bg-info">
              <h2>
                تاثیر تنبیه و تشویق کودکان 
              </h2>
            </div>
          </div>

          <p class="bg-info position-relative text-justify dashed px-3 py-5">
            تشویق و تنبیه چیست؟تشویق در لغت به معنای به شوق در آوردن و کار کسی را ستودن و او را دلگرم ساختن است. تشویق از تمایلات فطری هر انسانی است که تا پایان عمر در او باقی می ماند و تنبیه عبارت است از آگاه ساختن فرد نسبت به نتایج نامطلوبش. در تعلیم و تربیت وقتی از تشویق و تنبیه صحبت می شود منظور این است که
          </p>
        </b-col>
      </b-row>
    </b-container>

    <b-img class="img-fluid w-100" src="https://mannakala.com/Themes/Public/manna-kala/Styles/Images/footer-top.png">
    </b-img>
    <footer class="bg-info text-white position-relative list-unstyled">
      <a class="bg-danger position-absolute back-to-top" href="">
        <i class="fa fa-arrow-up text-white"></i>
      </a>
      <b-container>
        <b-row>
          <b-col md="4">
            <h5>
              تماس با ما
            </h5>
          </b-col>

          <b-col md="4">
            <h5>
              شبکه های اجتماعی
            </h5>

            <div>
              <a href="#">
                <b-img src="https://mannakala.com/Themes/Public/manna-kala/styles/images/social/instagram.png">
                </b-img>
              </a>
            </div>
          </b-col>

          <b-col md="2">
            <h5>
              محصولات
            </h5>

            <ul class="text-secondary">
              <li>
                <a href="#">
                  پیشنهادات ویژه
                </a>
              </li>

              <li>
                <a href="#">
                  جدیدترین ها
                </a>
              </li>

              <li>
                <a href="#">
                  محبوب ترین ها
                </a>
              </li>

              <li>
                <a href="#">
                  پرفروش ترین ها
                </a>
              </li>
            </ul>
          </b-col>

          <b-col md="2">
            <h5>
              نمادها
            </h5>

            <b-row>
              <b-col md="4">
                <b-img class="img-fluid w-100" src="https://mannakala.com/Uploads/site-1/UserFiles/Admin/%D9%86%D9%85%D8%A7%D8%AF/logo-sep.png">
                </b-img>
              </b-col>

              <b-col md="4">
                <b-img class="img-fluid w-100" src="https://mannakala.com/Uploads/site-1/UserFiles/Admin/%D9%86%D9%85%D8%A7%D8%AF/logo-sep.png">
                </b-img>
              </b-col>

              <b-col md="4">
                <b-img class="img-fluid w-100" src="https://mannakala.com/Uploads/site-1/UserFiles/Admin/%D9%86%D9%85%D8%A7%D8%AF/logo-sep.png">
                </b-img>
              </b-col>
            </b-row>
          </b-col>
        </b-row>

      </b-container>

      <div class="bg-secondary">
        <b-container>
          <b-row>
            فروشگاه اسباب بازی مانا کالا
          </b-row>
        </b-container>
      </div>
    </footer>
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
  background-size: cover;
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
.rotated-bg {
  position: absolute;
  left: 0;
  bottom: -20px;
  width: 100%;
  height: 90px;
  clip-path: polygon(-4px 35px,101.35% 7.89%,101.35% 105.55%,-.81% 107.78%);
  transition: all .25s;
}

.dashed-border::after {
  content: '';
  position: absolute;
  top: 15px;
  right: 50%;
  width: 90%;
  height: 0;
  background-color: transparent;
  border-bottom: 1px dashed #fff!important;
  margin-right: -45%;
}
.back-to-top {
  top: -90px;
  right: 50%;
  margin-right: -35px;
  border-radius: 50%;
  transition: all .25s;
  padding: 24px;
}

.fa-arrow-up:before {
   font-size: 24px;
}

.list-unstyled ul{
  list-style-type: none;
  padding: 0!important;
}
.img-circle {
  border-radius: 50%
}
.bg-pattern {
  background-image: url('https://mannakala.com/Themes/Public/manna-kala/styles/Images/pattern-bg.png');
  background-attachment: fixed;
}
.rotate-hover img {
    transition: all .25s;
}
.rotate-hover:hover img {
    filter: grayscale(100%) blur(3px);
    transform: rotate(
15deg
) scale(1.4);
}
.rotate-hover .title {
    background-color: rgba(73,193,234,.85);
}
.rotate-hover .title {
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    bottom: 0;
    border-radius: 50%;
    color: #fff;
    opacity: 0;
    transition: all .25s;
    margin: 0!important;

}
.rotate-hover .title span {
    position: absolute;
    top: 50%;
    right: 10px;
    left: 10px;
    margin-top: -13.6px;
}
.rotate-hover:hover .title {
    opacity: 1;
}
.rotate-hover {
      overflow: hidden;
    border-radius: 50%;
}
.main-title span:before, .main-title span:after {
    content: '';
    position: absolute;
    top: 4px;
    right: -60px;
    width: 25px;
    height: 32px;
    background: url('https://mannakala.com/Themes/Public/manna-kala/styles/Images/header-lego.png') no-repeat;
    background-size: 25px;
}
.main-title span:after {
    top: 4px;
    right: unset!important;
    left: -60px;
}
.plus-icons {
    position: absolute;
    bottom: 10px;
    right: 5px;
    font-size: 36px;
    opacity: 0;
    transition: all .25s;
}

.extended-item:hover img {
    border-bottom-right-radius: 3px;
    box-shadow: 0 0 15px rgb(0 126 255 / 30%);
}
.extended-item img {
    background-color: #fff;
    box-shadow: 0 0 15px rgb(0 126 255 / 15%);
    transition: all .25s;
}
.extended-item:hover .plus-icons {
    opacity: 1;
}
.carousel-control-prev-icon {
    right: 0;
    background: url('https://mannakala.com/Themes/Public/manna-kala/styles/images/slider/header-controls.png') no-repeat 0 0!important;
}
.carousel-control-next {
    width: 70px!important;
    height: 140px!important;
    top: 39%!important;
}
.carousel-control-next-icon {
  right: 0;
    background: url('https://mannakala.com/Themes/Public/manna-kala/styles/images/slider/header-controls.png') no-repeat 0 0!important;
}
.product-slider a {
  background-color: #ebecee;
  border-radius: 40px;
  border-bottom-right-radius: 3px;
  margin-top: 70px;
  transition: all .25s;
}
.product-slider a:hover {
    background-color: #ff286c;
}
.product-slider img {
  margin-top: -75px;
  background: #fff;
  margin-right: -20px;
  box-shadow: 0 0 15px rgb(255 40 108 / 15%);
  transition: all .25s;
}
.product-slider p {
    top: 32px;
    left: 32px;
    transition: all .25s;
}
</style>
