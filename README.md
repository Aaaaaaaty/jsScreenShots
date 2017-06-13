# jsScreenShots
js screenShot plugin
### 依赖项
```
<script src="https://cdn.bootcss.com/jquery/3.2.1/jquery.min.js"></script>
<script src="https://cdn.bootcss.com/jcanvas/16.7.3/jcanvas.min.js"></script>
<script src="https://cdn.bootcss.com/html2canvas/0.5.0-beta4/html2canvas.min.js"></script>
```
### 快捷键可配置
```
/**
* @param {Array} quickStartKey 开始截图快捷键keyCode
* @param {Number} EndKey 结束截图快捷键keyCode
*/
function screenShot(quickStartKey, EndKey){
  ...
}
```
开始快捷键可以设置任意数目；结束快捷键为单一按键
#### 调用
```
screenShot([16, 65], 27) // 开始快捷键设置为shift+a；退出键为ESC
```
### 效果图
![](http://chuantu.biz/t5/106/1497323193x3550323713.gif)
