# vue+hbuilder 项目文件
> 本项目用于制作[vue](https://cn.vuejs.org/)+[hbuilder](https://www.dcloud.io/hbuilderx.html)手机app教程以及简单框架'

<img src="./mdImg/vue.png" style="zoom:30%"> <img src="./mdImg/hbuilder.png" style="zoom:80%">
> 同时vue UI采用[iview](http://v1.iviewui.com/) ui框架
![](./mdImg/iview.png)

## Build Setup
vue部分  在新项目文件夹下执行：
``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

> 打包
## 把vue项目打包
```
# 在vue目录下
npm run build 
```
打开hbuilderx
1. 新建项目

![p1](./mdImg/p1.png)

![](./mdImg/p2.png)

2. 删除项目的css img js index

![p3](./mdImg/p3.png)

3. 把刚才npm run build生成的dist文件里static和index拷贝近新创建的项目
   ![p4](./mdImg/p4.png)

4. 点击manifest.json文件然后发行

   ![p5](./mdImg/p5.png)
   进行如下配置![p6](./mdImg/p6.png)

5. 下载安装即可
   ![p7](./mdImg/p7.png)

6. 手机安装成图
   ![p8](./mdImg/p8.jpg)

# 作者

宁夏大学云计算与智能媒体信息处理实验室