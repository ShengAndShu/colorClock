# colorClock
colorClock是一个基于jQuery和canvas的插件，它能够在你的页面上插入一个动画时钟。
## 使用方法
###1.引入文件
    <script src="colorClock.js"></script> 
###2.HTML
    <canvas id="clock" style="right:0; bottom:0"></canvas>
你可以自定义style中的位置<br><br>
###3.javascript
        $(function(){
	    $('clock').colorClock();
	});
###4.配置
**clockColor**：字符串，设置时钟颜色，默认"rgb(200,200,200)"<br>
**canvasWidth**: 整数，设置画布宽度，默认Math.round(document.documentElement.clientWidth/4)<br>
**canvasHeight**: 整数，设置画布高度，默认Math.round(document.documentElement.clientHeight/4)<br>
**paddingLeft**: 整数，设置画布paddingLeft，默认Math.round(document.documentElement.clientWidth/80)<br>
**paddingTop**: 整数，设置画布paddingTop，默认Math.round(document.documentElement.clientHeight/80)<br>
**maxBalls**: 整数，设置运动小球的最大数量（调整插件占用的内存资源），默认300