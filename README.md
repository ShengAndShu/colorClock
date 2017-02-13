# colorClock
colorClock是一个基于jQuery和canvas的插件，它能够在你的页面上插入一个动画时钟。
# 使用方法
1.**引入文件**<br>
<pre><script src="colorClock.js"></script></pre><br><br>
2.**HTML**<br>
<pre><canvas id="clock" style="right:0; bottom:0"></canvas></pre><br>
你可以自定义style中的位置<br><br>
3.**javascript**<br>
<pre>$(function(){
    $('clock').colorClock();
});</pre><br><br>
4.**配置**<br>
        clockColor：字符串，默认"rgb(200,200,200)"<br>
        canvasWidth: 整数，默认Math.round(document.documentElement.clientWidth/4)<br>
        canvasHeight: 整数，默认Math.round(document.documentElement.clientHeight/4)<br>
        paddingLeft: 整数，默认Math.round(document.documentElement.clientWidth/80)<br>
        paddingTop: 整数，默认Math.round(document.documentElement.clientHeight/80)<br>
        maxBalls: 整数，默认300<br>

