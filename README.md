# travel
vue2.5开发去哪网app
# travel
项目下载地址：https://git.imooc.com/yousi2016
#### 项目介绍
vue2.5开发去哪网app

#### 软件架构
软件架构说明


#### 安装教程

1.到官网下载安装node
2.注册码云创建一个私有仓库存贮项目代码
3.到官网下载安装git（gitbash是linnus的）小型环境
本地只有一个本地库，远程可以有多个，github一个，gitee一个哦
操作git的问题：
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


4.安装vue-cli脚手架工具：npm install --global vue-cli
5.创建一个基于webpack模板的新项目:vue init webpack travel
6.如果出现以下信息，说明安装依赖成功：
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

Documentation can be found at https://vuejs-templates.github.io/webpack

7.$ git status
fatal: not a git repository (or any of the parent directories): .git

Administrator@TIZJMN9PAGN50M8 MINGW64 /d/imooc/vue/travel
$ git init
Initialized empty Git repository in D:/imooc/vue/travel/.git/
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
 create mode 100644 static/.gitkeep

9.将本地库和远程库关联：$ git remote add origin git@github.com:yousi2016/travel.git

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
fatal: refusing to merge unrelated histories


11.可以看到，本地库已经关联了origin的远程库，并且，该远程库指向GitHub。
$ git remote -v
origin  git@github.com:yousi2016/travel.git (fetch)
origin  git@github.com:yousi2016/travel.git (push)

12.我们可以删除已有的GitHub远程库：
    git remote rm origin
13.给远程库另起名字：
	git remote add github git@github.com:michaelliao/learngit.git

14. 出现：输入wq即可

15.如果从gitee上clone下的仓库，传不到github上，那只需要做两个步骤：

	1.git fetch github master
	
	2.git merge github/master
	
16.查看远程仓库和本地仓库异同：
git diff master github/master

一.项目预热：<br/>
	1.单文件组件与Vue中的路由<br/>
		1.删掉components文件夹，创建pages->home->Home.vue<br/>
		2.创建pages->list->List.vue(注意不要用tab缩进，用空格可以)<br/>
		
	2.单页应用VS多页应用
		单页应用原理：根据路径不同，前端通过js路由感知到URL的变化，通过js动态的将当前页面内容清除掉，然后将另一个页面的内容挂在到页面上
		这样只会向服务器发一次请求哦
		http://localhost:8080/页面保存后会自动刷新
	3.项目代码初始化
		1.删除assets里面logo.png
		2.在assets下面新建styles->reset.css(重置样式)
		 	在main.js里面引入：import './assets/styles/reset.css'
		3.在assets下面新建styles->border.css(解决1px在不同屏幕下显示不一样的问题)
			在main.js里面引入：import './assets/styles/border.css'
		4.停一下服务：clear
		5.安装fastclick(解决移动端click点击延迟300ms的问题)
			1.先安装cnpm：npm install -g cnpm --registry=https://registry.npm.taobao.org
			2.cnpm install fastclick --save(--save不管是开发环境还是线上版本代码都需要使用fastclick)
			3.import fastClick from 'fastclick'
		6.移动端流行的开发技术：iconfont
			1.打开网站：http://www.iconfont.cn
			2.点击图标管理->我的项目->新建项目
		7.删掉router下index.js里面的
			import List from '@/pages/list/List'
			, {
		      path: '/list',
		      name: 'List',
		      component: List
		    }
		  删掉pages->list
		 删掉home->Home.vue里面的：
		 	<div class='home'>home</div>
    		<router-link to='/list' class='home'>列表页</router-link>
    		.home {
			   font-size: 50px;
			}
		8.将travel上传到github和gitee上
			1.clear
			2.在GitHub上新建一个travel项目
			3.git clone https://github.com/yousi2016/travel.git
			4.git add .
			5.git commit -m 'project init'
			6.git remote -v
				origin  https://github.com/yousi2016/travel.git (fetch)
				origin  https://github.com/yousi2016/travel.git (push)
			7.git remote rm origin
			8.git remote add github git@github.com:yousi2016/travel.git
			9.git remote add gitee git@gitee.com:frontEndArchitect/travel.git
			10.git remote -v
				gitee   git@gitee.com:frontEndArchitect/travel.git (fetch)
				gitee   git@gitee.com:frontEndArchitect/travel.git (push)
				github  git@github.com:yousi2016/travel.git (fetch)
				github  git@github.com:yousi2016/travel.git (push)
			11. git push github master
			12.从github将travel项目导入到gitee中
			13.git push gitee master
二.项目实战 - 旅游网站首页开发<br/>
	##Vue项目首页 - header区域开发<br/>
		1.安装css的预处理框架stylus（相当于less）：cnpm install stylus --save<br/>
			如果显示如下就说明已经成功安装：<br/>
			√ Installed 1 packages<br/>
			√ Linked 19 latest versions<br/>
			√ Run 0 scripts<br/>
			√ All packages installed (20 packages installed from npm registry, used 2s(network 2s), speed 262.26kB/s, json 20(224.64kB), tarball 277.58kB)<br/>
	
		2.安装stylus-loader:
			cnpm install stylus-loader --save
		3.npm run dev
			如果报错：（删除index.js里面多余的空格）
			✘  http://eslint.org/docs/rules/no-multiple-empty-lines  More than 1 blank line not allowed
			src\router\index.js:4:1
		4.缩进规则一定要是两个space空格键
		
		5.在src>pages>home>components新建一个Header.vue
			
  				

			
			


	

















