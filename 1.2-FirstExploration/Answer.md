# 关卡详解

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>javascript-lesson-1.2</title>
    <link rel="stylesheet" href="http://elf-mouse.github.io/cdn/js.lesson/1.2/layer.css">
</head>
<body>

    <!-- 开启页面加载效果 -->
    <script src="http://elf-mouse.github.io/cdn/js.lesson/1.2/layer.js"></script>
    <script>layer.open({ type: 2, shadeClose: false });</script>

    本页面用来测试 &lt;script&gt; 加载顺序~

    <!-- 引入 10MB 外部 JavaScript，比较耗时 -->
    <script src="http://elf-mouse.github.io/cdn/js.lesson/1.2/external.js"></script>

    <!-- 关闭页面加载效果 -->
    <script>setTimeout(function(){ layer.closeAll(); },500);</script>

</body>
</html>
```
