# hexo-theme-gallery

## Version 0.1.0

A Hexo theme for photography, gallery

## Intro

手里的几个网站切换为 Hexo 已经有一段时间了，个人感觉比 WordPress 好用，简洁轻量，主题、插件也很丰富。这是一个相册主题，图片使用腾讯云的对象存储保存，文章的 Title 与存储桶中的文件夹名称匹配时自动扫描所有图片，并以瀑布流的形式显示在文章页面中。

本主题当前为0.1.0版本，是我在春节休假期间用了几个小时时间做的，功能比较简单，还有很大的改进空间，欢迎有同样需求的朋友们一起开发。

### Demo Site

[35mm 纪实摄影](http://i.35mm.com.cn)

### Reference

https://me.idealli.com/post/73ad4183.html

https://www.ahonn.me/blog/create-a-hexo-theme-from-scratch

## Quick Start

1. 图片资源需预告上传到腾讯云对象存储空间，并配置权限、跨域访问 CORS 等；
2. 在主题中配置 COS 访问域名，0.1.0版本还比较简陋，请直接在 post.ejs 主设置，后续会修改为_config.yml 参数；
3. 下载主题文件到 themes/gallery/，在网站 _config.yml 中配置当前主题为 gallery；
4. 新建 post 并将 Title 设置为与 COS 中某个文件夹名称一致，提交发布即可查看效果；
5. 主题效果请参考 Demo Site：http://i.35mm.com.cn