---
layout: docs_cn
title: Tools Overview · Docs · KBEngine
tab: docs
docsitem: tools-overview
---

工具
========

### 安装助手([installer]):

	python kbengine/kbe/tools/server/install/installer.py install
	python kbengine/kbe/tools/server/install/installer.py uninstall



### Python版本的集群控制([cluster_controller]):

	python cluster_controller.py query: 
		查询服务端集群信息。

	python cluster_controller.py start: 
		启动服务端集群。

	python cluster_controller.py stop: 
		关闭服务端集群。

	python cluster_controller.py console: 
		在线调试，Python控制台等。



### 可视化控制台([GUIConsole]):

<img class="screenshots-img" src="{{ site.baseurl }}/assets/img/screenshots/guiconsole_debug.jpg">



[installer]: {{ site.baseurl }}/cn/docs/tools/installer
[cluster_controller]: {{ site.baseurl }}/cn/docs/tools/pycluster
[GUIConsole]: {{ site.baseurl }}/cn/docs/tools/guiconsole