---
layout: default
title:  "在GitHub Pages上，使用任意主题（模板）"
date:   2019-06-12 17:50:00
categories: main
---
##### 使用任意主题
***
就在一年多前，为GitHub Pages提供支持的开源项目Jekyll引入了共享主题。从那时起，您已经能够使用大约十几个主题来改变GitHub Pages网站的外观。

从今天开始，您可以在GitHub.com上使用[数百个社区策划的主题中的任何一个](https://github.com/topics/jekyll-theme)。
要使用任何公共的GitHub托管主题构建您的网站，请将以下内容添加到您网站的_config.yml文件中：
```Html
remote_theme: owner/name
```
替换`owner`和`name`为仓库的所有者和主题名称。

如果您有兴趣将其Jekyll主题提供给其他用户，只需按照创建基于Gem的主题的说明操作，并确保存储库是公开的。


