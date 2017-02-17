# 基于vue2.0+vuex+localStorage开发的本地记事本

> 本文采用vue2.0+vuex+localStorage+sass+webpack，实现一个本地存储的记事本。兼容PC端和移动端。

## 功能说明

- 支持回车添加事件
- 支持事件状态切换
	- 添加事件 -> 进入未完成列表
	- 未完成 -> 已完成(勾选checkbox)
	- 未完成 -> 已取消(点击取消按钮)
	- 已完成 -> 未完成(取消勾选checkbox)
	- 已取消 -> 未完成(点击恢复按钮)
- 支持控制台打印所有事件数据
- 支持筛选事件
- 支持编辑事件
- 支持删除事件
- 支持清空所有事件
- 支持本地化存储
- 支持折叠面板

## 项目笔记 ##
本项目是使用vue-cli脚手架生成的项目，项目代码可以到我的github上clone下来。clone下来之后可进入文件目录

	// 执行
	npm install
	// 安装依赖完成之后再执行
	npm run dev
	// 即可在本地开启 http://localhost:8080 访问该项目

	// 如果 node-sass 安装失败，可使用 cnpm 安装
	npm install cnpm -g --registry=https://registry.npm.taobao.org
	cnpm -v 			// 查看cnpm版本号确认安装成功
	cnpm install node-sass -D
	
	//安装成功后再看看是否可以正确运行了

