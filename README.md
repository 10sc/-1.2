# experimentent made by aIt's just a freshman.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>The model of flex</title>
    <style>
      body {
        margin: 0px;
        height: 100vh;
        background-color: rgba(237, 231, 231, 0.127);
        opacity: 0.3;

        background-size: 100%;
      }

      .flex {
        display: flex;
        flex-wrap: wrap;
      }
      .Baise {
        background-color: rgba(255, 255, 255, 0.916);
      }
      .flex1 {
        flex: 1;
      }
      .column {
        flex-direction: column;
      }
      .mg8 {
        margin: 8px;
      }
      .mgr8 {
        margin-right: 8px;
      }
      .mgt8 {
        margin-top: 8px;
      }
      .Yinying {
        box-shadow: rgb(0 0 0 / 20%) 0px 2px 1px -1px,
          rgb(0 0 0 / 14%) 0px 1px 1px 0px, rgb(0 0 0 / 12%) 0px 1px 3px 0px;
      }
      p {
        font-size: larger;
      }
    </style>
  </head>

  <body
    background="https://ts1.cn.mm.bing.net/th/id/R-C.6592d6c38970f023f8e7d0cf5cd867d3?rik=EtgmTHxgS14vYg&riu=http%3a%2f%2fimg95.699pic.com%2fphoto%2f40139%2f0939.gif_wh860.gif&ehk=HYiLTNhKdtKpiZZ7V%2fr45uWESKAgIOGbFZvl%2fg2TPdc%3d&risl=1&pid=ImgRaw&r=0"
    class="flex"
  >
    <!-- 侧边栏 -->
    <div
      style="width: 200px; z-index: 1px"
      class="Baise flex column mg8 Yinying"
    >
      <!--头像栏-->
      <div
        style="height: 100px; justify-content: center"
        class="Baise Yinying flex"
      ></div>
      <!--导航栏-->
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
      <div style="height: 50px" class="Baise Yinying mgt8">
        <p style="color: #45211e; font-size: larger"><b>导航:</b></p>
      </div>
    </div>
    <!-- 主区域 -->
    <div class="flex1 flex column">
      <!--头部栏-->
      <div
        style="height: 100px;/* width: 100px;z-index: 1px;"
        class="Baise mgt8 Yinying flex"
      >
        <p></p>
      </div>
      <!--内容区-->
      <div class="flex1 flex">
        <!-- 左区 -->
        <div style="flex: 3" clsss=" flex column">
          <!--数据区-->
          <div class="flex mgt8 mgr8">
            <!--数据块-->
            <div
              style="height: 100px"
              class="flex flex1 Baise mgr8 Yinying"
            ></div>
            <!--数据块-->
            <div
              style="height: 100px"
              class="flex flex1 Baise mgr8 Yinying"
            ></div>
            <!--数据块-->
            <div
              style="height: 100px"
              class="flex flex1 Baise mgr8 Yinying"
            ></div>
            <!--数据块-->
            <div style="height: 100px" class="flex flex1 Baise Yinying"></div>
          </div>

          <!--列表区-->
          <div class="flex column mgt8 mgr8">
            <!--列表项-->
            <div style="height: 200px" class="Baise flex column Yinying"></div>
            <!--列表项-->
            <div
              style="height: 200px"
              class="Baise flex column mgt8 Yinying"
            ></div>
            <!--列表项-->
            <div
              style="height: 200px"
              class="Baise flex column mgt8 Yinying"
            ></div>
            <!--列表项-->
            <div
              style="height: 200px"
              class="Baise flex column mgt8 Yinying"
            ></div>
          </div>
        </div>
        <!-- 右区 -->
        <div style="flex: 1" class="flex column">
          <!--提示区-->
          <div style="height: 250px" class="Baise mgt8 Yinying"></div>
          <!--消息区-->
          <div style="height: 500px" class="Baise mgt8 Yinying"></div>
        </div>
      </div>
    </div>
  </body>
</html>
