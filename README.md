# ikanman-unlocker

这是一个Bookmarklet，用来帮助移动设备解锁ikanman.com/manhuagui.com的区域限制

用法非常简单，建立一个书签，在“地址”栏填入：

```JavaScript
javascript:document.cookie='country=US;domain=.manhuagui.com;path=/;max-age=2147483647';undefined
```

之后打开网站，点击书签，刷新页面即可

目前已测试通过设备：Chrome（Windows），Samsung Browser（Android），Safari（iOS 8）

PC用户建议使用用户脚本，简单快捷：<a href="https://greasyfork.org/zh-CN/scripts/30822-%E8%A7%A3%E9%99%A4ikanman-com%E4%B8%8A%E8%A2%AB%E5%B1%8F%E8%94%BD%E7%9A%84%E6%BC%AB%E7%94%BB" target="_blank">解除ikanman.com上被屏蔽的漫画</a>

**现在这种方法已经失效了，如果有需求，请使用不是中国和日本的IP访问即可，本项目留作纪念，不作删除**
