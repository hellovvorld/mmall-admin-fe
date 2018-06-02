项目初始化步骤

1.安装nodejs环境,推荐使用v4.4.7
    下载地址 : https://nodejs.org/download/release/v4.4.7/

2.全局安装webpack v2.x
    命令: (sudo) npm install -g webpack

3.全局安装webpack-dev-server
    命令: (sudo) npm install -g webpack-dev-server

4.在慕课网上下载源码，解压缩

5.在项目根目录执行npm初始化
    命令: npm install (--registry=https://registry.npm.taobao.org)

6.启动项目
    开发模式: npm run dev (windows系统上为npm run dev_win)
    生产模式: npm run dist (windows系统上为npm run dist_win)

7.开发模式下预览项目
    访问：http://localhost:8086/dist/view/index.html


注意：
1.后台管理系统使用了sass, 需要安装ruby和sass

2.后端接口也要使用代理，http://localhost:8086/manage/* --> http://admin.happymmall.com/manage/

3.后台管理系统的预览账号：admin  happymmalladmin
## 环境搭建(全局安装不需要添加版本号、局部安装需要添加版本号)
```
1、npm install webpack -g 全局安装 (npm uninstall webpack -g)
2、npm init
3、npm install webpack@4.2.0 --save-dev
4、npm install babel-core --save-dev
5、npm install babel-loader --save-dev
6、npm install babel-preset-es2015 --save-dev
7、npm install babel-preset-react --save-dev
8、npm install css-loader style-loader --save-dev
9、npm install extract-text-webpack-plugin file-loader html-loader html-webpack-plugin --save-dev
10、npm install jsx-loader node-sass sass-loader url-loader webpack-dev-server --save-dev
11、npm install bootstrap@3.3.7 --save
12、npm install font-awesome@4.7.0 --save
13、npm install rc-pagination --save
14、npm install react --save
15、npm install react-dom react-fileupload react-router --save
16、npm install sb-admin-2 simditor --save
```