<div align="center">

Vuepress Template

![GitHub package.json version](https://img.shields.io/github/package-json/v/openHacking/vuepress-template?style=flat-square)
[![GitHub license](https://img.shields.io/github/license/openHacking/vuepress-template?style=flat-square)](https://github.com/openHacking/vuepress-template)
</div>

## 介绍

基于[Vuepress Template](https://openhacking.github.io/vuepress-template/zh/) 项目，一个简单的VuePress案例模板，目的是让用户可以直接clone这个仓库，作为初始化一个VuePress网站启动项目，然后在这个项目的基础上新增自定义配置和功能。



### 主题

- [vuepress-theme-blogplus](https://github.com/Dushusir/vuepress-theme-blogplus) 一款简洁的博客主题

### 插件

- [vuepress-plugin-qrocde](https://github.com/openHacking/vuepress-plugin-qrcode) 展示当前网址二维码供移动设备扫描

## 用法

### 第一步

下载仓库代码
```sh
git clone https://github.com/MroZ11/vuepress-template.git
```

### 第二步

安装依赖
```sh
cd vuepress-template
npm i
# npm i --registry=https://registry.npm.taobao.org
```

### 第三步

启动项目，随后即可根据自己的需求修改配置、编写文档内容
```sh
npm run docs:dev
```

### 第四步

打包项目
```sh
npm run docs:build
```
结果会在`docs/.vuepress/`目录下生成一个`dist`文件夹，里面就是打包后的代码
