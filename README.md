# travel
vue2.5开发去哪网app
# travel
项目下载地址：https://git.imooc.com/yousi2016
#### 项目介绍
vue2.5开发去哪网app

#### 软件架构
软件架构说明


#### 安装教程

1.到官网下载安装node<br/>
2.注册码云创建一个私有仓库存贮项目代码<br/>
3.到官网下载安装git（gitbash是linnus的）小型环境<br/>
本地只有一个本地库，远程可以有多个，github一个，gitee一个哦
操作git的问题：<br/>
	1.Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git remote -v
		origin  https://github.com/yousi2016/travel.git (fetch)
		origin  https://github.com/yousi2016/travel.git (push)
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git remote add github git@github.com:yousi2016/travel.git
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git remote add gitee git@gitee.com:frontEndArchitect/travel.git
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git remote -v
		gitee   git@gitee.com:frontEndArchitect/travel.git (fetch)
		gitee   git@gitee.com:frontEndArchitect/travel.git (push)
		github  git@github.com:yousi2016/travel.git (fetch)
		github  git@github.com:yousi2016/travel.git (push)
		origin  https://github.com/yousi2016/travel.git (fetch)
		origin  https://github.com/yousi2016/travel.git (push)
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git remote rm origin
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git remote -v
		gitee   git@gitee.com:frontEndArchitect/travel.git (fetch)
		gitee   git@gitee.com:frontEndArchitect/travel.git (push)
		github  git@github.com:yousi2016/travel.git (fetch)
		github  git@github.com:yousi2016/travel.git (push)
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git push github master
		ssh: connect to host github.com port 22: Connection timed out
		fatal: Could not read from remote repository.
		
		Please make sure you have the correct access rights
		and the repository exists.
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git status
		On branch master
		nothing to commit, working tree clean
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git add .
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git commit -m '2018 18:51'
		On branch master
		nothing to commit, working tree clean
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git push github master
		Counting objects: 3, done.
		Delta compression using up to 4 threads.
		Compressing objects: 100% (3/3), done.
		Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
		Total 3 (delta 2), reused 0 (delta 0)
		remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
		To github.com:yousi2016/travel.git
		   9e44c2e..1e36071  master -> master
	2.Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git commit -a -m 'add br'
		[master 44b55f4] add br
		 1 file changed, 6 insertions(+), 6 deletions(-)
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git push github master
		Counting objects: 3, done.
		Delta compression using up to 4 threads.
		Compressing objects: 100% (3/3), done.
		Writing objects: 100% (3/3), 353 bytes | 353.00 KiB/s, done.
		Total 3 (delta 2), reused 0 (delta 0)
		remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
		To github.com:yousi2016/travel.git
		   2f0fb1b..44b55f4  master -> master
		
		Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
		$ git push gitee master
		Counting objects: 9, done.
		Delta compression using up to 4 threads.
		Compressing objects: 100% (9/9), done.
		Writing objects: 100% (9/9), 2.08 KiB | 711.00 KiB/s, done.
		Total 9 (delta 5), reused 0 (delta 0)
		remote: Powered by Gitee.com
		To gitee.com:frontEndArchitect/travel.git
		   9e44c2e..44b55f4  master -> master


4.安装vue-cli脚手架工具：npm install --global vue-cli<br/>
5.创建一个基于webpack模板的新项目:vue init webpack travel<br/>
6.如果出现以下信息，说明安装依赖成功：<br/>
 Project name (travel)
? Project name travel
? Project description (A Vue.js project)
? Project description A Vue.js project
? Author (yousi2016 <dingyousi888@gmail.com>)
? Author yousi2016 <dingyousi888@gmail.com>
? Vue build runtime
? Install vue-router? (Y/n) y
? Install vue-router? Yes
? Use ESLint to lint your code? (Y/n) y
? Use ESLint to lint your code? Yes
? Pick an ESLint preset (Use arrow keys)
? Pick an ESLint preset Standard
? Set up unit tests (Y/n) n
? Set up unit tests No
? Setup e2e tests with Nightwatch? (Y/n) n
? Setup e2e tests with Nightwatch? No
? Should we run `npm install` for you after the project has been created? (recom
? Should we run `npm install` for you after the project has been created? (recom
mended) npm

   vue-cli · Generated "travel".


# Installing project dependencies ...
# ========================

npm WARN deprecated bfj-node4@5.3.1: Switch to the `bfj` package for fixes and new features!

> uglifyjs-webpack-plugin@0.4.6 postinstall D:\imooc\vue\travel\node_modules\webpack\node_modules\uglifyjs-webpack-plugin
> node lib/post_install.js

npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

added 1246 packages in 435.529s


Running eslint --fix to comply with chosen preset rules...
# ========================


> travel@1.0.0 lint D:\imooc\vue\travel
> eslint --ext .js,.vue src "--fix"


# Project initialization finished!
# ========================

To get started:

  cd travel
  npm run dev

Documentation can be found at https://vuejs-templates.github.io/webpack<br/>

7.$ git status
fatal: not a git repository (or any of the parent directories): .git

Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel
$ git init
Initialized empty Git repository in D:/imooc/vue/travel/.git/<br/>
8.add和commit到本地仓库
nothing added to commit but untracked files present (use "git add" to track)

Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
$ git add .
warning: LF will be replaced by CRLF in .babelrc.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .editorconfig.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .eslintignore.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .eslintrc.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .postcssrc.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/build.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/check-versions.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/utils.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/vue-loader.conf.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/webpack.base.conf.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/webpack.dev.conf.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in build/webpack.prod.conf.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/dev.env.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/index.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in config/prod.env.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in package-lock.json.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in src/App.vue.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in src/components/HelloWorld.vue.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in src/main.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in src/router/index.js.
The file will have its original line endings in your working directory.

Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel (master)
$ git commit -m 'add travel'
[master (root-commit) cc136ed] add travel
 28 files changed, 12985 insertions(+)
 create mode 100644 .babelrc
 create mode 100644 .editorconfig
 create mode 100644 .eslintignore
 create mode 100644 .eslintrc.js
 create mode 100644 .gitignore
 create mode 100644 .postcssrc.js
 create mode 100644 README.md
 create mode 100644 build/build.js
 create mode 100644 build/check-versions.js
 create mode 100644 build/logo.png
 create mode 100644 build/utils.js
 create mode 100644 build/vue-loader.conf.js
 create mode 100644 build/webpack.base.conf.js
 create mode 100644 build/webpack.dev.conf.js
 create mode 100644 build/webpack.prod.conf.js
 create mode 100644 config/dev.env.js
 create mode 100644 config/index.js
 create mode 100644 config/prod.env.js
 create mode 100644 index.html
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 readme.txt
 create mode 100644 src/App.vue
 create mode 100644 src/assets/logo.png
 create mode 100644 src/components/HelloWorld.vue
 create mode 100644 src/main.js
 create mode 100644 src/router/index.js
 create mode 100644 static/.gitkeep<br/>

9.将本地库和远程库关联：$ git remote add origin git@github.com:yousi2016/travel.git<br/>

10.第一次push到远程库出问题：
$ git push -u origin master
To github.com:yousi2016/travel.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'git@github.com:yousi2016/travel.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

解决办法：
$ git pull origin master
warning: no common commits
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From github.com:yousi2016/travel
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
fatal: refusing to merge unrelated histories<br/>


11.可以看到，本地库已经关联了origin的远程库，并且，该远程库指向GitHub。
$ git remote -v
origin  git@github.com:yousi2016/travel.git (fetch)
origin  git@github.com:yousi2016/travel.git (push)<br/>

12.我们可以删除已有的GitHub远程库：<br/>
    git remote rm origin<br/>
13.给远程库另起名字：
	git remote add github git@github.com:michaelliao/learngit.git<br/>

14. 出现：输入wq即可<br/>

15.如果从gitee上clone下的仓库，传不到github上，那只需要做两个步骤：<br/>

	1.git fetch github master
	
	2.git merge github/master
	
16.查看远程仓库和本地仓库异同：<br/>
git diff master github/master

1.项目预热：<br/>
	1.单文件组件与Vue中的路由<br/>
		1.删掉components文件夹，创建pages->home->Home.vue<br/>
		2.创建pages->list->List.vue(注意不要用tab缩进，用空格可以)<br/>
		
	2.单页应用VS多页应用<br/>
		单页应用原理：根据路径不同，前端通过js路由感知到URL的变化，通过js动态的将当前页面内容清除掉，然后将另一个页面的内容挂在到页面上
		这样只会向服务器发一次请求哦<br/>
		http://localhost:8080/页面保存后会自动刷新<br/>
	3.项目代码初始化<br/><br/>
		1.删除assets里面logo.png<br/><br/>
		2.在assets下面新建styles->reset.css(重置样式)<br/>
		 	在main.js里面引入：import './assets/styles/reset.css'<br/>
		3.在assets下面新建styles->border.css(解决1px在不同屏幕下显示不一样的问题)<br/>
			在main.js里面引入：import './assets/styles/border.css'<br/>
		4.停一下服务：clear<br/>
		5.安装fastclick(解决移动端click点击延迟300ms的问题)<br/>
			1.先安装cnpm：npm install -g cnpm --registry=https://registry.npm.taobao.org<br/>
			2.cnpm install fastclick --save(--save不管是开发环境还是线上版本代码都需要使用fastclick)<br/>
			3.import fastClick from 'fastclick'<br/>
		6.移动端流行的开发技术：iconfont<br/>
			1.打开网站：http://www.iconfont.cn<br/>
			2.点击图标管理->我的项目->新建项目<br/>
		7.删掉router下index.js里面的<br/>
			import List from '@/pages/list/List'<br/>
			, {<br/>
		      path: '/list',<br/>
		      name: 'List',<br/>
		      component: List<br/>
		    }<br/>
		  删掉pages->list<br/>
		 删掉home->Home.vue里面的：<br/>
		 	<div class='home'>home</div><br/>
    		<router-link to='/list' class='home'>列表页</router-link><br/>
    		.home {<br/>
			   font-size: 50px;<br/>
			}
		8.将travel上传到github和gitee上<br/>
			1.clear<br/>
			2.在GitHub上新建一个travel项目<br/>
			3.git clone https://github.com/yousi2016/travel.git<br/>
			4.git add .<br/>
			5.git commit -m 'project init'<br/>
			6.git remote -v<br/>
				origin  https://github.com/yousi2016/travel.git (fetch)<br/>
				origin  https://github.com/yousi2016/travel.git (push)<br/>
			7.git remote rm origin<br/>
			8.git remote add github git@github.com:yousi2016/travel.git<br/>
			9.git remote add gitee git@gitee.com:frontEndArchitect/travel.git<br/>
			10.git remote -v<br/>
				gitee   git@gitee.com:frontEndArchitect/travel.git (fetch)<br/>
				gitee   git@gitee.com:frontEndArchitect/travel.git (push)<br/>
				github  git@github.com:yousi2016/travel.git (fetch)<br/>
				github  git@github.com:yousi2016/travel.git (push)<br/>
			11. git push github master<br/>
			
			12.从github将travel项目导入到gitee中<br/>
			
			13.git push gitee master<br/>
			
			
# HBuilder X - Release Notes
======================================
## 0.1.45.20180728-alpha
* 【重要】新增uni-app，使用vue技术，开发一次，iOS、Android、微信小程序三端同时生成。[详见](http://uniapp.dcloud.io/)
* 【重要】调整uniapp策略，之前的原生渲染uniapp改为nml项目[详见](http://ask.dcloud.net.cn/article/13507)
* uni-app：新增条件编译，采用类似 //#ifdef APP-PLUS 的写法做平台条件编译，代码块名为ifdef，还可双击ifdef选中整体代码段落。[详见](http://uniapp.dcloud.io/platform)
* uni-app：新增u开头的各种组件和api的代码块，如urequest即可快速生成联网代码
* 【重要】语法校验
	+ 新增html,vue,css,sass,less等语法验证插件【安装插件后默认是保存时校验，也可在工具菜单手动激活】
	+ 优化语法校验，在代码中通过波浪线直接标识，支持F4跳转到下一个语法错误
	+ json文件保存时，自动删除多余错误逗号
* 【重要】新增光标在api代码处，按F1打开对应的帮助文档。目前支持uni-app、plus、vue的api
* 优化新建菜单，增加文件模板及自定义模板
* 新增切换最近文件列表。Win:Ctrl+Tab；Mac:Alt+Tab。短按是在最近2个标签卡切换，长按可在列表中持续移动（逻辑同OS的切屏）
* 新增文件收藏功能，方便快速访问常用文件【Alt+Shift+f】
* 新增快捷键冲突时弹出选择菜单的功能
* 代码提示
	+ 优化js中json语法的提示
	+ 修复翻页可能错乱的bug
	+ 补充vue指令的信息帮助及vuex框架语法库
	+ 修复某些情况下框架语法库失效的问题
* Emmet：修复在css、php等文件中失效的bug
* 优化代码块教程，新增clogvar快捷打印变量的js代码块
* 优化vue转到定义
* 智能回车
	+ json的键值对和数组后回车，自动补充行尾逗号
	+ 优化js中/**回车处理
	+ 修复回车时光标可能在屏幕外的问题
* 智能双击
	+ 新增双击逗号左侧或右侧，选中数组或参数的前一个或后一个。大幅提升json的节点增删效率
	+ 新增双击条件编译区的ifdef或endif关键字选中条件编译段落
	+ 新增双击行尾行注释，选中注释段
	+ 新增Alt+双击括号引号，把两侧的括号引号也选中
* 优化重复插入，不选内容时是重复插入当前行，选内容时是重复插入选区。Win:Ctrl+Insert；Mac:Command+Shift+r
* 优化缩进，支持空格、tab转换和长度调整，使用方式：菜单【编辑】-【缩进】
* 外部命令新增terminal类型，使用该类型的外部命令运行环境设定为内置终端
* 优化内置终端插件的使用体验
* 优化运行
	+ 支持多设备运行到不同的控制台
	+ 修复项目名含有+号等特殊字符时，无法在内置web服务器运行和预览的问题
	+ 修复Mac无法自动识别已安装的浏览器的问题
	+ 修复预览时web服务器启动慢导致无法使用web服务器预览的bug
* markdown
	+ 粘贴外部图片到md文件时，自动整理到附件文件夹下，方便整体发行及预览
	+ 修复非项目下的md文件预览时不能显示图片的bug
* 修复某些情况下，ctrl+f搜索会导致程序崩溃的问题
* 修复大量删除项目内文件可能会导致崩溃或项目列表清空的问题
* 【App插件】支持Mac真机运行同步文件
* 【App插件】新增manifest.json中（plus->arguments）配置应用默认启动参数功能
* 【App插件】新增toast的图标支持设置宽高（iconWidth/iconHeight）
* 【App插件】Android平台云端打包支持在manifest中指定targetSdkVersion版本（解决Google提交应用要求支持Android8.0+的问题）
* 【App插件】Android平台修复应用资源可能被清理工具删除的问题
* 【App插件】Android平台修复未配置震动权限时扫码成功引起应用崩溃的问题
* 【App插件】Android平台修复特定情况下状态栏高度计算不正确的问题
* 【App插件】Android平台修复二维码通过图片扫码识别（plus.barcode.scan）不触发回调的问题
* 【App插件】iOS平台修复自定义基座concole.log日志无法输出的问题
* 【App插件】iOS平台修复获取支付通道状态未及时更新的问题

## 0.1.43.20180625-alpha
* 修复内置浏览器、内置终端插件配置错误的问题
* 解决某些情况下编辑器右键"在项目管理器中定位"不生效的问题

## 0.1.42.20180623-alpha
* 【重要】新增内置终端【win: Alt+c；mac: Ctrl+c】
	+ 支持多终端
	+ 菜单运行支持解析package.json的命令直接运行到内置终端
* 优化代码块的自定义和显示
* 优化Vue2.x语法提示
* 插件外部命令支持保存自动执行，在插件配置中将"onDidSaveExecution": true, 重启生效。可用于保存时自动编译、压缩、提交svn等
* 优化格式化
* 修复粘贴时有时代码没有智能缩进的问题
* 解决外部命令运行有时会提示node异常的问题
* 调整代码助手数字选择默认策略为Alt+数字插入
* 【App插件】【重要】新增原生视频播放组件（支持flv、rtmp/hls/rtsp协议），新增直播推流组件（rtmp协议），规范参考 [http://www.html5plus.org/doc/zh_cn/video.html](http://www.html5plus.org/doc/zh_cn/video.html)
* 【App插件】【重要】直播开发指南，参见[http://ask.dcloud.net.cn/article/13416](http://ask.dcloud.net.cn/article/13416)
* 【App插件】解决wap2app打包原生时没有编译的问题
* 【App插件】Android平台修复高德定位使用缓存数据导致定位不准确的问题
* 【App插件】Android平台修复默认不支持媒体输入的问题
* 【App插件】Android平台修复Webview设置bottom属性横竖屏切换后可能不生效的问题
* 【App插件】iOS平台修复NView不能显示部分网络gif文件的问题
* 【App插件】iOS平台修复应用内支付（IAP）无法获取购买凭证的问题
* 【App插件】iOS平台修复无法直达支付宝的芝麻认证页面的问题
* 【云服务】云端打包校验应用属主权限，减少appid乱用，详见[http://ask.dcloud.net.cn/article/13413](http://ask.dcloud.net.cn/article/13413)

## 0.1.41.20180612-alpha
* 代码助手新增右侧详细信息
* 代码助手新增单击Alt切换数字插入状态的功能
* 新增中文输入免干扰功能，在特定语法区输入全角的分号逗号括号会自动替换为半角符号，减少错误，编写更顺畅。可在设置中配置开关
* 修复设置分栏为4宫格并关闭HBuilder X后，无法再次启动HBuilder X的问题
* 修复HTML文件不提示vue指令的问题
* 完善自定义代码块的帮助说明

##0.1.40.20180607-alpha
* 修复内置浏览器无法加载页面资源的问题
* 修复win10下浏览器运行-Edge提示找不到Edge浏览器的问题

##0.1.39.20180606-alpha
* 修复wxml的注释和智能选中的一些问题
* 修复某些情况下，格式化后滚动条位置不正确的问题

##0.1.38.20180605-alpha
* 紧急修复mac上部分文件格式化、外部命令菜单显示的若干bug

##0.1.37.20180605-alpha
* 新增内置浏览器预览，即老版的边改边看 【win: Alt+p；mac: Ctrl+p】
* 强化微信小程序支持，更好的小程序开发工具 [详见](http://ask.dcloud.net.cn/article/13373)
	+ 支持新建微信小程序项目、文件
	+ 支持小程序语法提示
	+ 支持直接运行到微信开发工具的模拟器看效果和调试【菜单运行】
* 新增自定义代码块功能【菜单工具-自定义代码块】
* 补充mui代码块
* 默认支持格式化vue文件，并修复格式化后光标位置不正确的问题
* 修复某些情况下中文输入法卡的问题
* 修复vue中url跳转失效的问题
* 修复有时代码块失效或变卡的问题
* 修复Mac版代码提示经常失效的问题
* 修复真机运行有时崩溃的问题
* 修复es6编译无效果的问题
* 修复js压缩插件不支持es6的问题
* 修复文件内搜索时输入中文有时候会崩溃的问题
* 修复Mac下运行项目下的npm命令失效的问题
* 修复选中内容按左边括号，无法在2端加括号包围的问题。只支持大中小括号，不包含尖括号
* 修复输入左边引号括号智能补齐匹配引号括号不支持多光标的问题

##0.1.36.20180521-alpha
* 修复 UniApp真机运行失败的问题
* 强化折叠，见菜单跳转
	+ 折叠单行【Alt+-】
	+ 展开单行【Alt+=】
	+ 折叠子行【Alt+Shift+-】
	+ 展开子行【Alt+Shift+=】
	+ 折叠所有行【Alt+Ctrl+Shift+-】
	+ 展开所有行【Alt+Ctrl+Shift+=】
	+ 折叠其他区域【Alt+Shift+o】
* 新增 选中当前行(不含首尾空白字符) 【鼠标双击行尾】【Ctrl+Shift+l】
* 智能双击强化 双击-、_、.这3个连字符，选中相连的词。例如class="mui-table-view mui-table-view-chevron"

## 0.1.35.20180519-alpha
* 紧急修复运行浏览器和真机的一些问题

## 0.1.34.20180519-alpha
* 【重要】新增App换量联盟，免费获得翻倍用户，[详见](http://ask.dcloud.net.cn/article/13300)
* 【重要】大幅强化vue，可能是最好的vue开发工具
* 优化less、scss语法提示
* 解析项目下package.json中npm命令，在运行和外部命令菜单提供快捷执行入口
* 优化浏览器运行的若干体验问题
* 配置语言类型关联，指定某后缀名文件使用某种语言编辑器打开（设置里files.associations节点）
* win版在根目录新增reset.bat，执行bat可清除HBuilderX所有数据配置
* 优化框架语法提示库的加载
* 优化插件部分体验问题
* 修复mac下外部命令shell模式无法打开终端的问题
* 优化文件保存无权限时的逻辑
* 智能双击新增选中折叠。鼠标双击折叠行前字符左侧可选中该折叠区域
* 优化扩大选区【Ctrl+=】
* markdown：新增markdown的浏览器运行预览【Ctrl+r】
* 【App插件】修复创建5+app项目后没有从服务器自动获取appid的问题
* 【App插件】优化manifest校验提示

## 0.1.33.20180505-alpha
* 新增插件管理
* 新增保存自动刷新浏览器功能（仅通过内置服务器打开的页面生效）
* 新增粘贴智能缩进，光标在行首缩进位置(不是顶格)时粘贴自动处理缩进
* 新增光标历史前进后退【Alt+←、Alt+→】及清空光标历史
* 支持拖拽标签卡到外部直接生成新窗体
* 分栏增加垂直分栏和四宫格模式
* 内置服务器首次启动策略修改为浏览器运行后启动，弹出权限询问框时请务必点允许
* 修改某些情况下格式化后光标错位的问题
* 修复新建窗体后项目管理器单击展开变双击的问题
* 新建项目时补充hello wap2app模板
* 优化酷黑主题的一些问题
* 修复文档结构图/大纲的中文兼容问题
* 修复临时文件标题不随着第一行内容变更的问题
* 优化HBuilderX文件目录结构，减少文件数量

## 0.1.32.20180424-alpha
* 新增Ctrl+鼠标右键移除点击位置的多光标/选区
* 新增js、css等分号结尾的语言中，双击分号选择该段内容的功能
* 修复酷黑主题搜索输入框字体颜色看不清的问题
* 修复某些情况下代码块不提示的问题
* 【App插件】修改某些情况下真机运行Uni-App/快应用时，修改单文件同步结果不正确的问题

## 0.1.31.20180420-alpha
* 新增文档结构图/大纲功能【Alt+w】（mac是Ctrl+w）
* 智能双击：HTML中新增双击=选中Tag属性、Css中新增双击类名左侧选中整个类、优化js中function等关键字双击末尾则选中该词
* 优化酷黑主题体验，修复nss,njs等文件酷黑主题下没有高亮的问题
* 新增Ctrl+鼠标滚轮缩放字体的开关配置项:editor.mouseWheelZoom
* 修复二进制文件预览的一些错误
* 修复某些情况下升级过慢的问题

## 0.1.30.20180418-alpha
* 新增黑色主题
* 新增编辑器分栏功能【Alt+Shift+1、Alt+Shift+2、Alt+Shift+3】
* 转到定义支持在另一分栏打开，方便并排查看【Ctrl+Alt+鼠标点击或Alt+Shift+D或windows下Shift+F12】
* 支持Alt+N将焦点移到编辑器的功能。至此完成：Alt+Q是左侧项目管理器，Alt+O是顶部工具栏，Alt+C是底部控制台，Alt+N是中间编辑器（mac下Alt改为Ctrl）
* 补充了mac下的文件复制移动删除等操作
* 增加历史剪切板【Ctrl+Alt+v】
* 优化搜索功能，搜不到的文字会变红，查找下一个循环到开头时会悬浮图标指示
* 在空白文档粘贴内容时，会自动检测待粘贴内容是否HTML或json，并自动切换语言类型和自动格式化
* 取消js文件保存时自动校验语法的默认设置，需要的开发者请手动在设置中调整jshint.onsave选项
* 修复某些情况tab缩进变成8的问题
* 修复某些情况重命名文件引发崩溃的问题
* 修复某些情况引号智能补全错乱的问题
* 修复某些情况JS跨文件转到定义不正确的问题
* 修复某些情况项目管理器目录层级错乱的问题
* 修复忘记密码后没有提示已发送邮件的问题
* 【App插件】Uni-App支持web组件引用本地html、js、css文件
* 【App插件】快应用/Uni-App真机运行基座升级到1.0.16

## 0.1.29.20180409-alpha
* 紧急更新某些情况下内置web服务器打开html显示404的问题
* 【App插件】小程序to快应用/Uni-App转换器增加最小版本描述，解决提交到快应用平台失败的问题

## 0.1.28.20180406-alpha
* 增加web服务器插件,仅支持HTML文件在浏览器运行时使用
* 文件夹内搜索添加全部替换的功能
* 修复未搜索到结果时，状态栏信息立即消失的问题
* 修复设置和搜索结果编辑器替换所有有时候未替换的问题
* 修复有时异常退出导致项目列表清空的问题
* 修复大文档在某些情况下折叠造成卡顿的问题
* 修复某些情况下大文档着色引发异常的问题
* 【mac版】解决finder里打开方式不能选择HbuilderX的问题
* 【mac版】修复部分快捷键失效的问题
* 【App插件】解决某些情况下，调试debug卡死的问题
* 【App插件】小程序to快应用/Uni-App转换器支持 url跳转参数传递,优化部分样式,组件转换
* 【App插件】快应用真机运行基座升级到1.0.15

##0.1.27.20180403-alpha
* 解决某些情况下App插件升级或安装失败的问题
* 解决某些情况下Mac版tab键失效的问题
* 【App插件】解决快应用/Uni-App真机运行时，修改部分文件提示编译失败的问题
* 【App插件】小程序to快应用/Uni-App转换器优化部分组件及样式转换，增加template的样式转换

## 0.1.26.20180401-alpha
*  搜索结果在状态栏增加提示
*  修复文件夹、项目无法重命名的问题
*  修复重命名文件时，如果该文件已打开，会打开两个标签卡的问题
*  修复某些情况下设置未成功保存的问题
*  修复某些语言文件在某些情况下的折叠异常问题
*  优化less、scss的着色，修复markdown某些字符导致的着色异常问题
*  Markdown：悬浮预览支持gif动画
* 【重要】【App插件】添加Uni-App/快应用打包Android apk的功能
* 【App插件】优化Uni-App/快应用调试流程，解决某些情况下调试器启动失败等问题
* 【App插件】小程序to快应用/Uni-App转换器优化import,template标签转换、修复部分样式转换问题
* 【App插件】快应用/Uni-App调试基座修复a标签点击不处理href、二维码扫描引起程序崩溃、video不居中显示等问题
* 【App插件】新建5+App时提供模板项目 

## 0.1.25.20180326-alpha
* 解决Mac无法浏览器运行的问题，并新增自动检测Chrome、Safari和FireFox
* 多光标模式支持上下移动行【Ctrl+Up/Down】、回车、反回车【Shift+Enter】等操作
* 添加Uni-App、快应用示例模板，新建项目时可选择
* 转义里新增了首字母大写，调整了大小写转换的快捷键【Alt+Shift+U/L/T】
* 修复搜索到折叠区域时，折叠不展开的bug
* 修复了代码助手在窗体右边缘时被遮挡、自闭合标签回车缩进错误等问题
* 修复了Mac版粘贴表格(numbers)内容到markdown文档时无法自动转换markdown表格的问题
* 【App插件】快应用真机运行基座升级到1.0.13
* 【App插件】更新小程序to快应用/Uni-App转换器
* 【重要】小程序to快应用/Uni-App转换器开源了！[GitHub地址](https://github.com/dcloudio/uni-migration)

## 0.1.24.20180323-alpha
* 控制台右键菜单增加复制
* 解决创建快应用项目目录结构不正确的问题
* 解决debug快应用或Uni-App后有时无法退出的问题
* 优化快应用调试
* 解决某些情况下真机运行无法启动的问题
* 解决真机运行/调试debug时，修改单个文件后，设备上显示白屏的问题
*【快应用开发插件】转换器修复部分样式不生效的问题

##0.1.23.20180320-alpha
* 【重要】新增快应用开发、运行、调试。[详见](http://quickapp.dcloud.io)
* 【重要】新增Uni-App开发、运行、调试。Uni-App是5+App的升级版，仍然支持5+webview，但界面主体由原生渲染引擎绘制。支持开发一次发布到更多平台。[详见](https://github.com/dcloudio/Uni-App)
* 【重要】新增微信小程序转换为快应用/Uni-App
* 【重要】新增mac版
* markdown：支持excel、wps、word、number中粘贴表格进来，自动转为markdown表格【特色】
* markdown：从内存中粘贴图片进md，自动创建md的附件文件夹（类似另存网页），将图片保存到文件夹并将链接展示到md中。保存md时，会自动清理无效图片【特色】
* markdown：鼠标移到图片语法区，悬浮显示本地图片。配套图片粘贴功能，进一步加强了对word、evernote的替代【特色】
* markdown：新增标题折叠【特色】
* markdown：修复了列复制无法按列粘贴的bug
* 补充了各种新语言的折叠
* 智能双击统一支持Ctrl添加新选区
* 智能双击新增双击选中HTML tag
* 新增HTML tag的包围和反包围【Ctrl+]】
* 新增HTML tag的起始、结束标签的套框指示
* 合并行支持多光标，支持去重空格【Ctrl+Shift+k】
* 优化了注释的体验，支持多光标注释
* 给选区首尾设置光标【Ctrl+\】。这样双击选中首尾tag或if块，按Ctrl+\，就可以把光标放到首尾，然后Ctrl+/就可以同时注释掉首行和尾行
* 根据语法选择相同词 【Ctrl+Shift+e】。传统的Ctrl+e选择相同词，在选择tag比如div时，会把子div也选中，而Ctrl+Shift+e则只会选中首尾的tag名称，方便一起改名
* 撤销最后一个多光标或选区【Ctrl+Shift+z】。用于最后一个光标或选区选错时，丢弃掉这个光标或选区
* 粘贴为HTML【Ctrl+Shift+v】可以在网页或excel里选内容，直接粘贴为HTML源码
* 优化转到定义【Alt+单击】
* 优化启动后代码提示引擎加载的速度
* js语法校验选项默认开启ES6
* 优化若干代码助手细节
* 运行浏览器时windows下自动检测chrome、firefox的路径，如果没有配置webserver地址就用file协议打开
* 自动修正常见的设置界面json语法错误
* 在快捷键设置界面新增HBuilderX快捷键的理念说明

## 0.1.22.20180302-alpha
* 新增若干语言的行注释【Ctrl+/】和块注释【Ctrl+shift+/】
* 新增if、for等关键字语法块包围【Ctrl+]】与反包围【Ctrl+Shift+]】
* 强化智能双击：双击if、for等选中函数块、双击注释选中注释块、双击行首空白选择相同缩进行
* 新增扩大选区【ctrl+=】，可连续扩大选区
* 复制行、删除行、剪切行，补充了多光标操作，大幅提升效率
* 新增互换2个选区或2行内容【Ctrl+shift+x】
* 新增去除行尾空格
* 优化了粘贴时自动缩进
* markdown：补充* 号无序列表【ctrl+alt+8】、+号无序列表【ctrl+alt+=】设置行首列表符的快捷键
* markdown：优化粘贴，自动生成url、图片等标签，自动过滤重复列表符
* markdown：支持格式化对齐表格【Ctrl+K】（暂未兼容不同字体和缩放条件变化）
* 解决大的js文件语法校验时卡顿的问题
* 解决修改软件路径导致文件关联失效的问题
* 解决文件内容过少导致无法正确获取编码的问题
* 解决纯净模式没有隐藏控制台的问题
* 优化文件夹内搜索

## 0.1.21.20180225-alpha
* 解决css提示内容不全的问题
* 解决jshint语法验证时，没有错误却弹出控制台的问题
* 解决有时HBuilderX退出时会报错的问题

## 0.1.20.20180212-alpha
* 新增App打包
* 新增js和json的语法校验
* 新增搜索分类、目录内搜索(Ctrl+Alt+F)
* 新增转到定义(F12)
* 新增纯净模式(双击标签卡)和免打扰模式(F11)
* 优化搜索菜单
* 新增块注释功能(Ctrl+Shift+/)
* 新增ejs、jade等前端模板语法高亮
* 新增为选区每行行首添加光标(Ctrl+Shift+\，也可以理解为Ctrl+|)
* 新增行首列表符设置：无序列表(Ctrl+Alt+-)，有序列表(Ctrl+Alt+1)，任务列表(Ctrl+Alt+1[)，已完成任务列表(Ctrl+Alt+])，并支持多光标设置
* 新增双击列表符-、*、+、[ ]、[x]，选中列表整段区域
* 新增双击#选中markdown标题段落
* [菜单-帮助-markdown语法帮助]中更新了操作技巧
* 解决配置文件包含中文可能导致视图菜单下的自动换行设置失败的问题
* 解决启动后项目管理器没有自动选中当前编辑器打开的文件的问题
* 解决markdown文件中删除空格有时会误删有序/无序列表符号的问题
祝大家新春快乐

## 0.1.17.20180122-alpha
* 【重要】需求墙上线了，喜欢HBuilder X的朋友们请移步[http://dev.dcloud.net.cn/wish/](http://dev.dcloud.net.cn/wish/)投票，提出你的想法
* 添加项目手动排序功能（通过鼠标拖动项目管理器里的项目上下移动）
* 添加项目管理器内文件拖拽移动功能
* 添加拖拽外部文件复制到项目管理器功能
* 解决高分屏下保存框字太大的问题
### App相关
* 【真机运行插件】解决真机运行手机失去连接后，保存代码有可能会导致崩溃的问题
* 【真机运行插件】解决某些情况下检测不到手机的问题
* 【真机运行插件】更新快应用调试基座

## 0.1.16.20180117-alpha
* 解决同名文件标签卡无法区分的问题
* 新建无标题文档并粘贴一段json后，文档格式将自动调整为json，同时格式化该文档
* 项目管理器里的文件，打开后HBuilderX标题栏显示其磁盘全路径url。
* 赞助者登录后，用户名处显示赞助信息

## 0.1.15.20180115-alpha
* 修复html文档中，tab不触发emmet的问题

## 0.1.14.20180112-alpha
* HBuilderX内测开始，欢迎大家使用。

	

















