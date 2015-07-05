title: HEXO初探
date: 2015-07-05 19:22:05
tags:
---

2015年07月05日
=============

	├── node_modules  # HEXO的基本信息,我还没有仔细去看
	│   ├── hexo
	│   ├── hexo-deployer-git
	│   ├── hexo-generator-archive
	│   ├── hexo-generator-category
	│   ├── hexo-generator-index
	│   ├── hexo-generator-tag
	│   ├── hexo-renderer-ejs #主题是ejs格式的,这里应该是要用到
	│   ├── hexo-renderer-marked #markdown的工具在这里,应该是用来转换markdown到html的
	│   ├── hexo-renderer-stylus
	│   └── hexo-server #这个工具应该是用来hexo server时候启动的那个服务器
	├── public # 这个目录就是相当于apache的www目录,index.htm是在这里的
	│   ├── 2015
	│   ├── archives
	│   ├── css
	│   ├── fancybox
	│   └── js
	├── scaffolds
	├── source # 写的文章都在这里,里面是md格式的文件.
	│   └── _posts
	└── themes # 在这里的主题需要在_config中配置,重新hexo generate就可以更新
	    ├── ios7 # 当前我使用的主题,以后要修改就在这里修改
	    └── landscape


themes
======
1. 对于ios7部分,我这里修改了原有的几个配置的地方,主要是删除了原有的About/Subscribe,去掉了weibo相关的配置.

	todo: 对于About部分应该是要加回来的,其他的都还可以.

