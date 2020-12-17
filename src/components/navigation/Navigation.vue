<template>
  <div class="navigation">

    <div id="rectangle" class="default box_1">
      <img id="rectangle_img" class="img " src="../../assets/navigationBar/rectangle.svg" />
    </div>

    <div id="logo" class="default placeholder" data-label="logo">
      <img id="logo_img" class="img" src="../../assets/navigationBar/logo.svg" />
      <div id="logo_text" class="text">
        <p><span>LOGO</span></p>
      </div>
    </div>

    <div id="inputbox" class="default text_field">
      <div id="inputbox_div" class=""></div>
      <input id="inputbox_input" type="text" v-model="name" placeholder="输入搜索题号" v-on:input="changetext" />
    </div>

    <div id="searchicon" class="default icon">
      <img id="searchicon_img" class="img " src="../../assets/navigationBar/searchicon.svg" />
      <div id="searchicon_text" class="text " style="display:none; visibility: hidden">
        <p></p>
      </div>
    </div>

    <div id="navchoice1" class="default label">
      <div id="choice1_div" class=""></div>
      <div id="choice1_text" class="text ">
        <p><span>比赛</span></p>
      </div>
    </div>

    <div id="navchoice2" class="default label">
      <div id="choice2_div" class=""></div>
      <div id="choice2_text" class="text ">
        <p><span>排名</span></p>
      </div>
    </div>

    <div id="navchoice3" class="default label">
      <div id="choice3_div" class=""></div>
      <div id="choice3_text" class="text ">
        <p><span>悬赏</span></p>
      </div>
    </div>

    <div id="navchoice4" class="default label">
      <div id="choice4_div" class=""></div>
      <div id="choice4_text" class="text ">
        <p><span>练习</span></p>
      </div>
    </div>

    <!-- 未登录 -->
   <div id="loading" class="default label">
      <div id="loading_div" class=""></div>
      <div id="loading_text" class="text ">
        <p><span>登录</span></p>
      </div>
    </div>

    <div id="register" class="default label">
      <div id="register_div" class=""></div>
      <div id="register_text" class="text ">
        <p><span>没有账号？注册</span></p>
      </div>
    </div>

    <!-- 已登录 -->
<!--    <div id="user" class="default icon">
      <img id="user_img" class="img " src="../../assets/navigationBar/user.svg"/>
      <div id="user_text" class="text " style="display:none; visibility: hidden">
        <p></p>
      </div>
    </div>

    <div id="mail" class="default icon">
      <img id="mail_img" class="img" src="../../assets/navigationBar/mail.svg"/>
      <div id="mail_text" class="text" style="display:none; visibility: hidden">
        <p></p>
      </div>
    </div> -->

<!--    菜单内容 (组合)
    <div id="u4777" class="default ax_default_hidden" data-label="菜单内容" style="display:none; visibility: hidden" data-left="1406" data-top="48" data-width="88" data-height="61">

      <div id="u4778" class="default box_2" data-label="弹出框">
        <div id="u4778_div" class=""></div>
        <div id="u4778_text" class="text " style="display:none; visibility: hidden">
          <p></p>
        </div>
      </div>

      <div id="u4779" class="default box_2">
        <div id="u4779_div" class=""></div>
        <div id="u4779_text" class="text ">
          <p><span>我的主页</span></p>
        </div>
      </div>

      <div id="u4780" class="ax_default box_2">
        <div id="u4780_div" class=""></div>
        <div id="u4780_text" class="text ">
          <p><span>修改密码</span></p>
        </div>
      </div>
    </div> -->

  </div>
</template>

<script>
  export default {
    name: 'navigation'
  }
</script>

<style>
  @import url("../all.css");
  @import url("navbar.css");
  @import url("../../resources/css/axure_rp_page.css");
</style>
