# live2d_bensz
 (～￣▽￣)～ 个人CDN看板娘小挂件(～￣▽￣)～ 

# 说明

所有代码均非原创，全部来自[参考](#参考)。

只为自己的小博客CDN看板娘所用。

# 使用

我用的是wordpress，只需要在`根目录/wp-content/themes/你的主题/footer.php`的</body>前面加上一句：

```html
<!--苯苯的看板娘-->
<script src="https://cdn.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/autoload.js"></script>
```

即可快速食用。

具体位置可以见我博客的源代码，地址在这：https://blognas.hwb0307.com

主要是使用了[参考](#参考)的大佬们所提供的前端和后端代码搭建的。

如果在本地博客搭建的话，可以实时预览，但是个人觉得没有必要吧，就托管在github上面就好了。

# 测试

> 个人专用，大佬们手下留情，不要点`https://purge*`类的网址。谢谢！

+ autoload.js
  + https://purge.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/autoload.js
  + https://cdn.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/autoload.js

+ waifu-tips.js
  + https://purge.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/waifu-tips.js
  + https://cdn.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/waifu-tips.js

+ waifu-tips.json
  + https://purge.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/waifu-tips.json
  + https://cdn.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/front/waifu-tips.json

+ model_list.json
  + https://purge.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/back/model_list.json
  + https://cdn.jsdelivr.net/gh/huangwb8/live2d_bensz@latest/back/model_list.json


# 其它

+ 有关jsdelivr的purge缓存工具的最新进展：https://www.jsdelivr.com/tools/purge

# 参考

+ [stevenjoezhang/live2d-widget](https://github.com/stevenjoezhang)
+ [fghrsh/live2d_api](https://github.com/fghrsh/live2d_api)
+ [fghrsh/live2d_demo](https://github.com/fghrsh/live2d_demo)
+ [summerscar / live2dDemo](https://github.com/summerscar/live2dDemo)