# HTML5
canvas、json、input、本地化存储、form表单等

-关于白色粒子特效：
# CanvasStar
-白色点点背景特效，可升级七彩五星哦 o(≧v≦)o~~


    @var star_r:star半径系数，值越大，半径越大；
    @var star_alpha:star透明度，值越大，越透明；
    @var initStarNum:初始化star个数；
    @var move_distance:位移距离，即star向上跑的距离，数值越大，相同时间内，速度越快。
    @var dot_r:dot半径系数，值越大，半径越大；
    @var dot_alpha:dot透明度；
    @var dot_speed:dot运动速度；
    @var dot_vanish:dot消失条件，透明度小于vanish时消失；
    @var dot_mindis:dot最小距离；
    @var dot_maxdis:dot最大距离；


-用法：

```
<canvas id="canvas"></canvas>

<script src="js/canvasStar.js"></script>

<script>

	new CanvasStar().init();
	
</script>
```

- html5语义化标签
- 存在不同浏览器兼容性展示效果问题
- form表单有以下几种：

1. text
1.  checkbox
1. radio
1.  textarea
##### html5存在许多表单新类型
1. date
2. email
3. password
4. url
5. number(存在max,min等许多属性值)
6. submit
7. range(进度条)
8. color（选色器
9. autocomplete，input的属性之一，文本框出现之前输入过的内容，但根据具体调整
---
- datalist(有自动过滤效果)
- 音频视频video,audio(添加音乐外链)

---
###### canvas
- 模糊时可以通过css进行缩放
- height,weigth一定要写在标签内部

---
##### 
