<!DOCTYPE html>
<html>
<head>
   <title>Operation Aborted Example</title>
    <style>
        body{
            margin: 0;
        }
        #video{
            position:fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            z-index: -1;
            -webkit-filter:grayscale(100%);
        }
    </style>
</head>
<body>

<div id="div">
    <video id="video" muted src="C:\Users\HUAWEI\Videos\星际穿越版 新增三种.mp4" autoplay loop>您的浏览器不支持\&lt; video&gt;元素</video>
</div>

<<script>
    var video= document.getElementById('video');
    video.playbackRate = 0.5;
</script>

</body>
</html>
