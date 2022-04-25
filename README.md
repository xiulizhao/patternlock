# patternlock
模拟Android模式手势解锁元素,用于需要使用不同类型的图案锁定<br>
<img src="http://www.wware.org/img/jsuo.png?_bed" width="400px"><br>
普通属性<br>
data-patternlockid	设置元素的唯一id值	ddd<br>
data-matrix	设置定义模式矩阵	[3,3]<br>
data-margin	设置定义模式圈的边距	20<br>
data-radius	设置定义图案圆的半径	25<br>
data-patternvisible	设置是否在绘图时使图案可见	true/false<br>
data-lineonmove	设置连线时是否显示连线	true/false<br>
data-enablesetpattern	是否设置动态显示模式	true/false<br>
data-allowrepeat	是否设置重复画点	true/false<br>
控制属性<br>
data--reset	重置绘制图案	true/false<br>
输出属性<br>
data-x-patternlock	输出出来的密码数字<br>
修改图案样式<br>
```css
<style>
        .patt-holder{
            background:#ffe600
        }
        .patt-dots{
            background:#F00;
        }
        .patt-circ.hovered{
            border:1px solid #000;
        }
        .patt-lines{
            background:#f0f;
            opacity: 0.7;
        }

    </style>
```
