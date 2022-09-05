# Bot Pixiv Proxy

基于 [Heroku](https://dashboard.heroku.com/apps) 搭建的 `Pixiv` 反向代理。
将请求重定向到 `i.pximg.net`。
未来若 `heroku` 不再支持，将会作废或迁移。

![](images/heroku.png)

## 目前支持

1. 根据图片 `pid` 获取图片：
    
    例子：https://okabebot-pixiv.herokuapp.com/101021356
2. 根据参数 `t` 选择图片质量：

   支持

   + original 
   + regular 
   + small 
   + thumb 
   + mini
    
    例子：https://okabebot-pixiv.herokuapp.com/101021356?t=thumb

<div>			<!--块级封装-->
    <div style="text-align: center;">	<!--将图片和文字居中-->
    <img src="https://okabebot-pixiv.herokuapp.com/101021356"
         alt=""
         style="zoom:100"/>
    <br>
    pid: 101021356
    </div>
</div>
