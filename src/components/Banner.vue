<template>
  <div class="jumbotron padding bg">
    <h1 class="jumbotron__header">TEST ASSIGNMENT FOR FRONTEND DEVELOPER POSITION</h1>
    <p class="jumbotron__text">We kindly remind you that your test assignment should be submitted as a link to github/bitbucket repository. Please be patient, we consider and respond to every application that meets minimum requirements. We look forward to your submission. Good luck! The photo has to scale in the banner area on the different screens</p>
    <button type="button" class="btn btn-danger btn-lg jumbotron__button">Sing up now</button>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '@/style/variables.scss';

.jumbotron{
    height: 715px;
    width: 100%;

    background-image: url("../assets/banner-photo.jpg");
    border-radius:0 !important;
    background-repeat: no-repeat;
    background-size: 100%;
    background-position: center;
}
.jumbotron.padding{
    padding-left: 30px;
}
.jumbotron__header{
    width: 530px;
    padding-top: 103px;
    font-size: 50px ;
    color: $background-color;
    letter-spacing: -0.6px;
    word-wrap: break-word;
}
.jumbotron__text{
    width: 532px;
    height: 122px;
    font-size: 16px;
    padding-top: 17px;
    line-height: 24px;
    color: $background-color;
}
.jumbotron__button{
    width: 210px;
    height: 38px;
    margin-top: 33px;
    font-size: 16px !important;
    padding:6px 4px 6px 6px !important;
    color: $background-color2;
    font-weight: 600;
    text-align: center;
}
</style>