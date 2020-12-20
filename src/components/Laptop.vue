<template>
  <div class="laptop">
      <h1 class="laptop__header">Let's get acquainted</h1>
      <div class="laptop__logo">
          <div class="laptop__img">
            <img src="../assets/man-laptop-v1.svg" class="img_logo" alt="">
          </div>
          <div class="laptop_text">
            <h2>I am cool frontend developer</h2>
            <span class="paragraf padding__paragraf">We will evaluate how clean your approach to writing CSS and Javascript code is. 
                  You can use any CSS and Javascript 3rd party libraries without any restriction.
            </span> 
            <span class="paragraf padding__paragraf__second">
                  If &nbsp;&nbsp;3rd&nbsp;&nbsp; party css/javascript libraries are added to the project via bower/npm/yarn you will get bonus points. 
                  If you use any task runner (gulp/webpack) you will get bonus points as well.
                  Slice service directory page PSD mockup into HTML5/CSS3. 
            </span>
              <a href="/" class="laptop__sign-now">Sing up now</a>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>
<style lang="scss" scopedSlots>
.laptop__sign-now{
    font-size: 16px;
    line-height: 60px;
    color: #ef5b4c !important;
    font-weight: 600;
}
.laptop__sign-now:hover{
    color:#d24335 !important;
}
@mixin padding($property) {
    margin-bottom: 22px;
    margin-top: $property;
    padding-right: 15px;;
}

.padding__paragraf{
    @include padding(19px);
}
.padding__paragraf__second{
    @include padding(24px);
}
.laptop_text{
    margin-top: 59px;
    margin-left: 4px;
}
.img_logo{
    width: 100%;
    height: 100%;
}
.laptop__img{
    width: 430px;
    height: 285px;
    margin-top: 63px;
    margin-left: 10px;
}
.laptop__header{
letter-spacing: -0.75px;
text-align: center;
}
.laptop{
    width: 100%;
    padding-top: 65px;
}
.laptop__logo{
    display:grid;
    grid-template-columns: 0.5fr 1fr;
}
</style>