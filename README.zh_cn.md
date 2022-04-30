# Hugo-Academia-Theme
![demo-en](static/images/demo-en.png)
Hugo 版本的个人(学术)主页

> 基于 [Jekyll/academicpages](https://github.com/academicpages/academicpages.github.io) 与 [Hexo/hexo-theme-academia](https://github.com/PhosphorW/hexo-theme-academia).

演示站 : https://zzsqwq.github.io/zs-academic-pages/

演示站源代码 : https://github.com/zzsqwq/zs-academic-pages


## Features
1. 多语言支持
2. 配置简单且迅速
3. 使用 yaml 文件进行配置

![demo-cn](static/images/demo-zh_cn.png)

## Quick Start
1. 点击[这里]((https://github.com/gohugoio/hugo/releases))下载 Hugo 并且使用下列命令创建一个新的站点。
```shell
$ hugo new site example_site
```
2. 在新建的站点中初始化 Git 仓库。
```shell
$ cd example_site
$ git init
```
3. 将此主题仓库添加为项目的子模组（当然直接当成一个目录也可以，不过这样更方便）。
```shell
$ git clone https://github.com/zzsqwq/hugo-academia-theme.git themes/hugo-academia
```

4. 配置你的 `config.yaml`. 你可以在[这里](https://github.com/zzsqwq/academic-pages-demo/blob/master/config.yaml)找到一个完整的配置文件。可以基于此进一步配置。

5. 使用 `hugo server` 来预览你的站点。就这么多，恭喜你建成了你的个人主页！


**Ps:** 你也可以 Fork 或者直接克隆演示站点源代码 [academic-pages-demo](https://github.com/zzsqwq/academic-pages-demo) 然后基于此配置。