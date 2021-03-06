# Vue-Chatkit ( Version: 1.0 )
本项目为一个实时聊天的应用程序，前端主要使用了 Vue + Vuex + VueRouter 的全家桶进行构建，后端则是使用了由 [Pusher](https://dash.pusher.com/) 提供的 `Chatkit` 服务(一个完整的聊天后端服务)，以使得我们只需关心如何构建前端用户界面。

![Image text](https://github.com/GRPdream/chatkit/blob/master/src/readme-img/preview.png)

## 使用步骤
1. 克隆代码仓库
2. 安装对应的依赖(`npm install`)
3. 在根目录创建 `.env.local` 文件并按照远程仓库的同名文件配置
4. 运行项目(`npm run serve`)
5. 用下面的用户名访问 <http://localhost:8080/>

|   用户名   |   用户名   |   用户名   |
| :-------: |  :-------: | :------:  |
|    chan   |    tony    |   john    |

## 注意点
由于 `Pusher` 是国外网站，所以需要本地使用科学上网才能实现实时聊天功能。

## 后续改进
1. 增加撤回消息功能

## Changelog
1.0 : 完成聊天室基本功能 