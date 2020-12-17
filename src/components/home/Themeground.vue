<template>
  <div id="themeground">
    <!-- 小鹿 -->
    <div id="deer" class="background_img">
      <img id="deer_img" class="img " src="../../assets/home/deer.png" />
      <div id="deer_text" class="text " style="display:none; visibility: hidden">
        <p></p>
      </div>
    </div>

    <!-- 黑框 -->
    <div id="blank" class="background_img">
      <div id="blank_div" class=""></div>
      <div id="blank_text" class="text " style="display:none; visibility: hidden">
        <p></p>
      </div>
    </div>

    <div id="words" class="default" data-left="530" data-top="144" data-width="890" data-height="281">

      <div id="oursudoku" class="default _一级标题">
        <div id="oursudoku_div" class=""></div>
        <div id="oursudoku_text" class="text ">
          <p><span>OurSudoku</span></p>
        </div>
      </div>

      <div id="subheading" class="default _一级标题">
        <div id="subheading_div" class=""></div>
        <div id="subheading_text" class="text ">
          <p><span>-集对战、分享、交流一体的在线数独平台</span></p>
        </div>
      </div>

      <div id="describe" class="default _文本段落">
        <div id="describe_div" class=""></div>
        <div id="describe_text" class="text ">
          <p><span>数独是源自18世纪瑞士的一种数学游戏。是一种运用纸、笔进行演算的逻辑游戏。玩家需要根据9×9盘面上的已知数字，推理出所有剩余空格的数字，并满足每一行、每一列、每一个粗线宫（3*3）内的数字均含1-9，不重复。数独盘面是个九宫，每一宫又分为九个小格。在这八十一格中给出一定的已知数字和解题条件，利用逻辑和推理，在其他的空格上填入1-9的数字。使1-9每个数字在每一行、每一列和每一宫中都只出现一次，又称“九宫格”。</span></p>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'themeground'
  }
</script>

<style>
  @import url("../all.css");
  @import url("home.css");
</style>
