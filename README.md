### 个人临时图床

通过[jsdelivr](https://www.jsdelivr.com/?docs=gh)+[github](http://github.com/)搭建免费的CDN，优化图片打开速度。

搭建之后，发布relase，即可通过url直接访问，访问方式：

>开始：jsdelibr指定地址（https://cdn.jsdelivr.net/gh） 
>
>加上： github用户用（/aizener）
>
>加上：仓库名（/my-imgs）
>
>加上：@ 
>
>加上：发布版本号（1.1）
>
>加上：图片地址（/demo.gif）

如果不发布relase，的话上面的版本号步骤改为**分支名**即可；

清楚缓存

- `https://cdn.jsdelivr.net/......`
- `https://purge.jsdelivr.net/......`

例如：

https://cdn.jsdelivr.net/gh/aizener/my-imgs@1.1/demo.gif