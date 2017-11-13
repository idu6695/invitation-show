<template>
  <div id="nav-top">
    <div class="logo-container">
      <div class="text-center">
        <ul class="logo-group">
          <li class="logo-group-item logo-img"></li>
          <li class="logo-group-item logo-text">초대를 해보자</li>
        </ul>
      </div>
    </div>
    <div class="menu-container text-center row">
      <div class="col-md-4 col-xs-4 menu-group-item"><a href="#">1</a></div>
      <div class="col-md-4 col-xs-4 menu-group-item"><a href="#">2</a></div>
      <div class="col-md-4 col-xs-4 menu-group-item"><a href="#">3</a></div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
  /* Common */
  @import url(http://fonts.googleapis.com/earlyaccess/hanna.css);
  @import url(http://fonts.googleapis.com/earlyaccess/nanumbrushscript.css);

  ul, li {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  a {
    text-decoration: none;
    color: black;
  }

  #nav-top {
    height: 200px;
    background-color: #F7F7F7;
    border-top: 2px solid #34A855;
    font-family: 'Hanna', serif;
    font-size: 18px;
  }

  .logo-container {
    height: 130px;
    border-bottom: 1px solid #DDDDDD;
  }
  .logo-text {
    padding: 45px;
    font-family: 'Nanum Brush Script', serif;
    font-size: 2em;
  }

  .menu-container {
    height: 70px;
  }
  .menu-group-item {
    padding: 22px;
  }
</style>
