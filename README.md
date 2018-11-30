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
npm install webpack -g 全局安装 (npm uninstall webpack -g)
npm init
npm install webpack@4.2.0 --save-dev
npm install node-sass@4.10.0 --unsafe-perm --save
npm install bootstrap@3.3.7 font-awesome@4.6.3 rc-pagination@1.7.1 react@15.4.2 react-dom@15.4.2 react-fileupload@2.4.0 react-router@3.0.2 sb-admin-2@3.3.8 simditor@2.3.6 --save-dev
npm install babel-core@6.9.1 babel-loader@6.2.4 babel-preset-es2015@6.9.0 babel-preset-react@6.5.0 css-loader@0.23.1 extract-text-webpack-plugin@2.1.0 file-loader@0.8.5 html-loader@0.4.3 html-webpack-plugin@2.26.0 jsx-loader@0.13.2 sass-loader@5.0.1 style-loader@0.13.0 url-loader@0.5.7 webpack-dev-server@1.16.2 --save
```
