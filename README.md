目前系统共收录 1.5w+ 张图片 API最后更新时间:2023-02-04

API基本调用格式：

```
https://your.domain/acg.php（随机动漫图）
https://your.domain/car.php（随机跑车图）
https://your.domain/heal.php(随机小清新图)
https://your.domain/model.php（随机模特图）
https://your.domain/scenery.php（随机风景图）
https://your.domain/game_wallpaper.php（随机游戏壁纸）
```

参数：

```
return=json/img
```

img调用格式

```
https://your.domain/acg.php?return=img（随机动漫图）
https://your.domain/car.php?return=img（随机跑车图）
https://your.domain/heal.php?return=img(随机小清新图)
https://your.domain/model.php?return=img（随机模特图）
https://your.domain/scenery.php?return=img（随机风景图）
https://your.domain/game_wallpaper.php?return=img（随机游戏壁纸）
```

JSON数据

```
{
    "code":"200" #图片状态码
    "acg":"https:\/\/ws1.sinaimg.cn\/large\/0072Vf1pgy1foxkfy08umj31kw0w0nng.jpg" #图片地址
    "width":"2048" #图片宽
    "height":"1152" #图片高
}
```