# 开发基本步骤
## 1	安装node.js
+ 安装node.js之前，先进行nvm的安装
	>https://github.com/coreybutler/nvm-windows/releases 
+ 最好选择稳定版本
**具体安装步骤：**
+ 选择第二种安装方式是自动安装，不需要多余的各种配置；直接下一步就可以完成安装；
+ 安装完nvm之后
+ 列出nvm的基本操作指令
+ nvm install ## 安装指定版本，可模糊安装，如：安装v6.2.0，既可nvm install v6.2.0，又可nvm install 6.2
+ nvm uninstall ## 删除已安装的指定版本，语法与install类似
+ nvm use ## 切换使用指定的版本node
+ nvm ls ## 列出所有安装的版本
+ nvm ls-remote ## 列出所以远程服务器的版本（官方node version list）
+ nvm current ## 显示当前的版本
+ nvm alias ## 给不同的版本号添加别名
+ nvm unalias ## 删除已定义的别名
+ nvm reinstall-packages ## 在当前版本node环境下，重新全局安装指定版本号的npm包
+ 安装需要的node版本，此时需要注意的是安装的下载地址，国内服务器可能会比较慢，甚至可能直接下载安装失败；
+ 推荐设置淘宝镜像：
	>https://npm.taobao.org/
	>npm install -g cnpm --registry=https://registry.npm.taobao.org
+ Node-v也可以查看当前node版本
## 2	webpack的安装
**使用npm安装webpack：**
+ 全局安装：
	>npm install webpack -g
+ 当前项目安装：
	>npm install webpack --save-dev
+ 速度慢：
	>npm config set registry https://registry.npm.taobao.org
+ 后缀添加last为当前最新稳定版本，或者@+版本号到指定版本
+ 在新项目本地运行的时候
	>首先：npm isntall 
	>然后：npm init 初始化
## 3	Vue安装以及项目初始化
**推荐直接安装vue脚手架**
+ 安装：
	>npm install -g vue-cli
+ 使用vue创建一个新的项目：
	>vue init webpack my-work
+ my-work是自己的项目名称（自定义命名）
+ 完成之后使用npm run dev将项目跑起来，之后可以在浏览器中打开localhost:8080(默认端口为8080)


**声明：本文内容仅是本人学习的记录，不保证在项目中可用，若引用此代码导致了严重后果，本人不承担任何法律责任。**
