# lerna-demo
lerna的基本用法

```shell
lerna init #初始化项目
lerna create zyzweb-one  #创建项目包
#在package.json中添加  "postinstall": "lerna bootstrap"  npm install 可以安装根目录和每个项目依赖
lerna bootstrap  #安装依赖(给每个项目,不包含根目录)

#发包 可以自动增加版本号
lerna publish  #发布包(多个包同时发)  需要有远程仓库  包名不能重复   添加license

lerna ls  #列出所有包
lerna run start  #在每个包运行npm run start
```


### 参考链接

[Lerna 入门级教程](https://juejin.cn/post/6980887310980087815)