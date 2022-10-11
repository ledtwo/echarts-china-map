
## echarts4 中国地图下钻至市、县、乡镇级

#### 1、使用方法

启动本地服务，再打开index.html
> 注意不可浏览器直接打开源文件，需要初始化加载地图，所以需要启动本地服务

示例demo：https://m.glinteah.com/map

> 中国 > 河南 > 许昌市 > 各县乡镇

![效果](static/preview.jpg)

>全国地图、世界地图、各省份地图数据JSON可查看map文件夹
>tip: 当前仅注册了河南省地图，如果需要其他省市，则在下面的在线地址里找到对应的省份，引入即可



````
例如：注册河南省份地图
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/echarts@4.9.0/map/js/province/henan.js"></script>

> echarts@4.9.0各个省份注册在线地址
https://cdn.jsdelivr.net/npm/echarts@4.9.0/map/js/province/
````
