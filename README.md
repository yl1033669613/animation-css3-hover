# animation-css3-hover
纯css3鼠标hover特效

## 兼容
使用了css3动画 需要iE10及以上

## 使用
确保父元素上有 `position:relative`<br>
确保父元素为块级元素<br>
确保父元素有宽高

```
<!-- 在你需要添加特效的元素内添加下面这段代码 并引用css -->
<a href="javascript:;" class="hover-mask" style="background-image: url(./images/blackbg.png);"> <!-- hover元素 可自定义背景图片-->
    <img src="./images/index_display_cross.png" class="hover-mask-content" alt=""> <!--可自定义hover元素的内容-->
    <span class="line-top"></span> <!-- 添加 from-center 类可使线框由边中点开始变化-->
    <span class="line-bottom"></span>
    <span class="line-left"></span>
    <span class="line-right"></span>
</a>
```