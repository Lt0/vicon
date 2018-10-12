# vicon

Vicon 是一个为 vue 架构开发的极其简单的 iconfont 组件, 基于 vicon, 可以在 vue 项目中简单地使用 iconfont 的图标.

<br>
<br>

## iconfont
iconfont 是一个适量图标管理和交流平台, 由 Alimama MUX 创建. [iconfont](http://www.iconfont.cn)

<br>

# 使用
## 1. 准备图标
从 [iconfont](http://www.iconfont.cn) 网站准备好你需要用到的图标, 并保存到你的项目中.

<br>

### 1.1 下载图标压缩包
在 [iconfont](http://www.iconfont.cn) 网站上, 进入你的项目主页, 选择 Symbol, 然后点击 下载之本地.

示例如图:

<img src="https://raw.githubusercontent.com/Lt0/vicon/master/doc/img/doc-1.png" alt="dowload icons" title="download icons from iconfont" />

<br>

### 1.2 保存图标位 iconfont.js
上一步下载可以得到一个 zip 压缩包, 解压这个压缩包, 将里边的 iconfont.js 文件复制到你的项目中.

可能的文件列表如下:
```
project/
├── iconfont.js
└── main.js
```

<br>
<br>

## 2. 安装 vicon
```
npm install vicon --save
```

<br>

安装 vicon 之后, 整个项目的文件列表看起来可能长这样:
```
project/
├── iconfont.js
├── main.js
└── node_modules
    └── vicon
        └── ...
```


<br>
<br>

## 3. 导入 vicon
在项目的 main.js 中导入并注册 vicon/iconfonts.

```
import icon from 'vicon'
import './static/icon/iconfont'

Vue.component('icon', icon)
```

<br>
<br>

## 4. 使用图标

在 vue 项目的 template 中使用你在前面为项目准备的图标.
```
<template>
  <icon>tools</icon>
</template>
```

<br>

注意:

1. icon 名可以从解压出来的 zip 压缩包中的 demo_symbol.html 文件中找到.
2. 你可以直接用浏览器打开 demo_symbol.html 来查看图标及其名字.

<img src="https://raw.githubusercontent.com/Lt0/vicon/master/doc/img/doc-2.png" alt="icon name" title="find icon name from demo_symbol.html" />


