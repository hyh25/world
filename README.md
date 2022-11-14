<head>
    <script src="js/jquery-1.11.3.min.js"></script>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>My World</title>
    <style>  
      body {
        margin: 0;
      }
    </style>
  </head>
  <body><center>
    <h1 style="background-color:brown ">世界是我们的
    </h1>
    <img src="C:\Users\HUAWEI\Pictures\Camera Roll\wallhaven-qzdqvr.jpg" width="auto" height="auto"
     ait="服了" width='400px' heiht="400px">
    <div>
   <div style="background-color:#F5F5DC;height:800px">
   </div>
   <div style="background-color:#00FFFF;height:100px"></div>
  <audio id="myAudio" autoplay="autoplay">
    <source src="music/陈奕迅-富士山下.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  <audio src="music/陈奕迅-富士山下.mp3" controls="controls" autoplay hidden="true" style="display:none;"/>
</div>
<center>
    
<script>
  $(document).ready(function() {  
    $(".xwcms").removeClass("animation");
    $(".xwcms").on("click", function() {
      $(".xwcms").addClass("animation");
      $(this).toggleClass("pause");
      var audio = $("#music audio")[0];
      if (audio.paused) {
        $(".xwcms").addClass("animation");
        audio.play();
      } else {
        $(".xwcms").removeClass("animation");
        audio.pause();
      }
      audio.addEventListener('ended', function () {  
        $(".xwcms").removeClass("animation");
      }, false);
    });
  });
</script>
