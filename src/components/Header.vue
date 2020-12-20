<template>
<header>

  <nav class="navbar padding fixed-top navbar-expand-lg navbar-light scrolling-navbar">
    <img src='../assets/logo.svg' alt="">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="/">About me<span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/">Relationships</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/">Requirements</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/">Users</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/">Sign Up</a>
        </li>
      </ul>
    </div>
  </nav>

</header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scopedSlots>
@import '@/style/variables.scss';
.navbar.padding{
    padding: 10px;
    padding-left: 30px;
}
.nav-item{
    padding-top: 2px;
    margin-right: 12.5px;
    float: right;
}
.navbar{
    background-color:$background-color;
}
</style>