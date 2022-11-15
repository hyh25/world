<html lang="zh-CN">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>时间</title>
    <style>  
      body {
        margin: 0;
      }
    </style>
  </head>
  <body>
    <body><center>
    <h1 style="background-color:brown ">世界是我们的
    </h1>
    <img src="C:\Users\HUAWEI\Pictures\Camera Roll\wallhaven-qzdqvr.jpg" width="auto" height="auto"
     ait="服了" width='400px' heiht="400px">
    <div>
   <div style="background-color:#F5F5DC;height:800px">
   </div>
   <div style="background-color:#00FFFF;height:100px"></div>
</body>
div class="videocontainer">
    <video class="fullscreenvideo" poster="__ROOT__/Themes/tdt/Asset/images/loginbg.jpg" id="bgvid" playsinline="" autoplay="" muted="" loop="">
        <source src="C:\Users\HUAWEI\Videos\星际穿越版 新增三种.mp4" type="video/mp4">
    </video>
</div>
.fullscreenvideo {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -100;
    -webkit-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%);
    -webkit-transition: 1s opacity;
    transition: 1s opacity;
}


.videocontainer{
    position: fixed;
    width: 100%;
    height: 100%;
    overflow: hidden;
    z-index: -100; 
}


.videocontainer:before{
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    display: block;
    z-index: -1;
    top: 0;
    left: 0;
    background: rgba(25,29,34,.65);
}
<script>
    var video= document.getElementById('v1');
    video.playbackRate = 0.5;
</script>
</html>

