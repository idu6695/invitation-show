<template>
  <div id="nav-bottom">
    <div class="row">
      <ul class="logo-group col-md-4 text-right">
        <li class="logo-group-item logo-img"></li>
        <li class="logo-group-item logo-text">초대를 해보자</li>
      </ul>
      <div class="col-md-8 footer-group">
        <div class="row">
          <ul class="text-center first-child">
            <li class="col-md-4 footer-group-item"><i></i><span>1</span></li>
            <li class="col-md-4 footer-group-item"><i></i><span>2</span></li>
            <li class="col-md-4 footer-group-item"><i></i><span>3</span></li>
          </ul>
        </div>
        <div class="row">
          <ul class="second-child">
            <li class="col-md-1 footer-group-item">1</li>
            <li class="col-md-1 footer-group-item">2</li>
            <li class="col-md-1 footer-group-item">3</li>
            <li class="col-md-1 footer-group-item">4</li>
          </ul>
        </div>
        <div class="row">
          <ul class="last-child">
            <li class="col-md-2 footer-group-item">초대를 해보자</li>
            <li class="col-md-3 footer-group-item">부산광역시 부산진구 만리산로 11</li>
            <li class="col-md-2 footer-group-item">개인연습자</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  /* Common */
  @import url(http://fonts.googleapis.com/earlyaccess/nanumbrushscript.css);

  ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  #nav-bottom {
    height: 175px;
    color: white;
    width: 100%;
    background-color: #505050;
  }

  .logo-text {
    padding: 67px;
    font-family: 'Nanum Brush Script', serif;
    font-size: 2em;
  }

  .footer-group {
    padding: 30px;
  }
  .first-child .footer-group-item {
    width: 130px;
    border: 1px solid #8F8F8F;
    padding: 10px 20px;
    margin: 0 5px;
  }
  .first-child:first-child {
    margin-left: 10px;
  }
  .second-child, .last-child {
    padding: 10px 0;
  }
  .last-child {
    font-size: 11px;
  }
</style>
