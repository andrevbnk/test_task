<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
@import '@/style/variables.scss';

#app {
  font-family: $font-family;
  font-size: 14px;
  a {
    text-decoration: none;
    &.router-link-exact-active {
      color: $secondary-color;
    }
  }
  a:hover{
    color:$primary-color;
  }
  a:active {
    color: $secondary-color;
   } 

  h1{
    font-size: 50px;
    line-height: 54px;
    font-weight: 400;
  }
  h2{
    font-size: 24px;
    line-height: 30px;
    font-weight: 400;
  }
  .paragraf{
    display:block;
    width: 100%;
    font-size: 16px;
    line-height: 24px;
    font-weight: 400;
  }
}

</style>
