# Viewerjs jQuery图片查看器
## 更新
### Viewer.js 有以下特点：
- 支持移动设备触摸事件
- 支持响应式
- 支持放大/缩小
- 支持旋转（类似微博的图片旋转）
- 支持水平/垂直翻转
- 支持图片移动
- 支持键盘
- 支持全屏幻灯片模式（可做屏保）
- 支持缩略图
- 支持标题显示
- 支持多种自定义事件

## 使用方法
### 载入 CSS 文件
```html
<link rel="stylesheet" type="text/css" href="css/reset.css"/>
<link rel="stylesheet" type="text/css" href="css/viewer.min.css">
<link rel="stylesheet" type="text/css" href="css/mobie.css"/>
```

### DOM底部载入 JavaScript 文件
```html
<script type="text/javascript" src="js/common.js"></script>
<script type="text/javascript" src="js/jquery-1.12.3.js"></script>
<script type="text/javascript" src="js/viewer-jquery.min.js"></script>
<script type="text/javascript" >
        $('#dowebok').viewer({
            url: 'data-original'
        });
</script>
```

### DOM 结构
```html
<ul class="images clearfix" id="dowebok">
    <li class="item"><img data-original="img/tibet-1.jpg" src="img/tibet-1.jpg" alt="Cuo Na湖"></li>
    <li class="item"><img data-original="img/tibet-2.jpg" src="img/tibet-2.jpg" alt="青藏高原"></li>
    <li class="item"><img data-original="img/tibet-3.jpg" src="img/tibet-3.jpg" alt="大昭寺"></li>
    <li class="item"><img data-original="img/tibet-4.jpg" src="img/tibet-4.jpg" alt="布达拉宫1"></li>
    <li class="item"><img data-original="img/tibet-5.jpg" src="img/tibet-5.jpg" alt="布达拉宫2"></li>
    <li class="item"><img data-original="img/tibet-6.jpg" src="img/tibet-6.jpg" alt="布达拉宫3"></li>
    <li class="item"><img data-original="img/tibet-7.jpg" src="img/tibet-7.jpg" alt="拉萨河"></li>
    <li class="item"><img data-original="img/tibet-8.jpg" src="img/tibet-8.jpg" alt="Namtso 1"></li>
    <li class="item"><img data-original="img/tibet-9.jpg" src="img/tibet-9.jpg" alt="Namtso 2"></li>
</ul>
```


## 移动端效果如下图所示：
<p align="left">
  <img src="img/sketch_01.jpg" alt="效果图">
  <span>&nbsp;&nbsp;&nbsp;&nbsp;</span> 
  <img src="img/sketch_02.jpg" alt="效果图">
</p>
## pc端效果如下图所示：
<p align="center">
  <img src="img/sketch_03.jpg" alt="效果图">
</p>
<p align="center">
  <img src="img/sketch_04.jpg" alt="效果图">
</p>
**[⬆ 回到顶部](#Viewerjs jQuery图片查看器)**
