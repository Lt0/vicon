[中文说明](https://github.com/Lt0/vicon/blob/master/README-zh.md)

# vicon
Vicon is an simple iconfont componenet for vue.

<br>

## iconfont
iconfont is a Vector Icon Management & Communication Platform made by Alimama MUX.
[iconfont](http://www.iconfont.cn)

<br>
<br>

# Usage
## 1. Prepare iconfonts
Get your iconfonts from [iconfont](http://www.iconfont.cn) and then save in your porject.

<br>

### 1.1 Download zip
Select "Symbol" in your project page and then select "Download Code"

<img src="https://raw.githubusercontent.com/Lt0/vicon/master/doc/img/doc-1.png" alt="dowload icons" title="download icons from iconfont" />

<br>

### 1.2 save iconfont.js
unpack downloading zip package and then copy file "iconfont.js" to your new project.
Files looks like below:
```
project/
├── iconfont.js
└── main.js
```

<br>
<br>

## 2. install vicon
```
npm install vicon --save
```

<br>

After installing vicon, the whole project files looks like below:

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

## 3. import
import and regist vicon/iconfonts in main.js.
```
import icon from 'vicon'
import './static/icon/iconfont'

Vue.component('icon', icon)
```

<br>
<br>

## 4. use icon
Using icon selected from iconfont in template.
```
<template>
  <icon>tools</icon>
</template>
```

<br>

Note: 
1. icon name could be found in demo_symbol.html which include in download.zip(file downloaded by step 1)
2. you can open demo_symbol.html directly with web browser.

<img src="https://raw.githubusercontent.com/Lt0/vicon/master/doc/img/doc-2.png" alt="icon name" title="find icon name from demo_symbol.html" />
