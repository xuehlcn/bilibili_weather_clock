# 网络天气时钟小电视
## 材料
| 材料         | 规格                       | 参考价格 |
| ------------ | -------------------------- | -------- |
| ESP01s       | 或者其他型号，尺寸合适即可 | 6-7元    |
| OLED         | 0.96寸，带3.3V稳压         | 9-11元   |
| 3.7V充电模块 |                            | 1-2元    |
| 3.7V锂电池   | 型号602525或者502525       | 5-7元    |
| 三脚开关     | 宽3.7长8.5                 | 0.1元    |
| 外壳         | 见3D文件                   |          |
| 线           | 若干                       |          |
| 亚克力       | 见图纸CAD                  | 5元      |
| 螺钉         | M2*10                      | 1元      |
| USB转TTL     | 有3.3V的                   | 3-5元    |



## 焊接/连线  
上传程序接线

![输入图片说明](https://images.gitee.com/uploads/images/2020/0612/131411_697c1bdf_5087908.png "上传程序接线.png")

主电路接线

（！！！！！！！！注意ESP01模块的VCC是接在OLED屏幕的3.3V稳压管的引脚上哦！！！！！！！！）

![输入图片说明](https://images.gitee.com/uploads/images/2020/0612/131420_d34f4364_5087908.png "电路接线.png")

## 3D打印外壳 
见3D文件夹，可自行修改

目前只针对0.96寸

1.3寸后期更新

## 程序  
需要修改的地方修改的地方我已在程序注释，请小伙伴认真阅读 


## 其他
网络时钟目前获取的是中科院以及阿里云的NTP

天气用的是和风天气API，可百度搜索并自行注册