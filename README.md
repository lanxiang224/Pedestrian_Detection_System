### 前后端代码参考项目地址：

前端参考项目地址：[youlaitech/vue3-element-admin: 🔥基于 vue3 + vite5 + typescript + element-plus 构建的后台管理前端模板（配套后端源码），vue-element-admin 的 vue3 版本。 (github.com)](https://github.com/youlaitech/vue3-element-admin)

后端参考项目地址：[haoxianrui/youlai-boot: 🌈 基于 Java 17 + Spring Boot 3 + Spring Security 6 + Vue 3 + Element-Plus 构建的前后端分离单体权限管理系统。 (github.com)](https://github.com/haoxianrui/youlai-boot)

### 前后端项目本地运行所需环境以及本地运行步骤：

vue3-element-admin目录下为前端相关代码

youlai-boot目录下为后端相关代码

#### 前端本地运行：

1. 若预先没有安装node.js，先下载安装node.js

2. 在vue3-element-admin目录下进入终端，运行以下命令：

   ```
   # 安装 pnpm
   npm install pnpm -g
   
   # 安装依赖
   pnpm install
   
   # 启动运行
   pnpm run dev
   ```

#### 后端本地运行：

1. 项目所需JDK版本为JDK17
2. 项目用到数据库为mysql和redis
3. 项目数据库表和初始数据由sql目录下的相关sql文件创建
4. 修改application-dev.yml文件中的mysql、redis相关配置代码
5. 运行后端时需先打开redis服务，即运行redis-server.exe，然后运行SystemApplication.java即可启动后端项目。

