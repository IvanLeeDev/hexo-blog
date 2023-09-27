#### 一、hexo-blog

Ivan's blog with hexo.

hexo 6.3.0

#### 二、添加 fluid theme

[Hexo Fluid 用户手册](https://hexo.fluid-dev.com/docs/start/)

> 1、Hexo5.0.0 版本以上，推荐用 npm 命令，在博客根目录执行以下命令：

```
npm install --save hexo-theme-fluid
```

> 执行完命令后，在博客根目录下穿件`_config.fluid.yml`文件，将主题的`_config.yml`内容复制一份进来。

> 2、指定主题：修改博客根目录的`_config.yml`文件。

```
theme: fluid  # 指定主题

language: zh-CN  # 指定语言，会影响主题显示的语言，按需修改
```

> 3、创建'关于'页面：首次使用主题，需要执行以下命令创建'关于'页面(类型)。

```
hexo new page about
```

> 执行以上命令后，会生成`/source/about/index.md`文件，打开文件，添加`layout`属性。注： `layout:about`必须存在，且不能是其他值，否则不能显示头像等样式。
