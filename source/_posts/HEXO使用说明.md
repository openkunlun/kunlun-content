---
title: HEXO使用说明
date: 2017-09-12
---

#### 环境搭建

安装`nodejs`，请参考 [nodejs.org](https://nodejs.org/)
安装`hexo`，请参考 [hexo.io/](https://hexo.io/)
克隆项目[`http://git.kunlun/kunlun/kunlun-content`](http://git.kunlun/kunlun/kunlun-content)


#### 依赖插件
``` shell
npm install 插件名
```

> hexo-renderer-jade
> hexo-deployer-git

#### 运行

``` shell
hexo server
```

#### 使用

``` shell
hexo new `hello`
```

使用任意编辑器，以 `markdown` 编辑文档后保存


#### 编译生成
``` shell
hexo generate
```

#### 发布
``` shell
hexo deploy
```

#### 其它

项目本身使用 `git` 进行管理，修改完成请提交所有变更
编译后会生成一个纯静态文件分支`pages`



