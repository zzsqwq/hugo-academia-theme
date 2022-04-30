# hugo-academia-theme
<p align="center">
<img src="https://img.shields.io/badge/hugo-academia-theme.svg" href="https://github.com/zzsqwq/hugo-academia-theme"> <img src="https://img.shields.io/badge/license-MIT-green.svg" href="https://github.com/zzsqwq/hugo-academia-theme/blob/master/LICENSE">
</p>


![demo-en](static/images/demo-en.png)
Hugo version academic pages

> based [Jekyll/academicpages](https://github.com/academicpages/academicpages.github.io) and [Hexo/hexo-theme-academia](https://github.com/PhosphorW/hexo-theme-academia).

Live demo is here : https://zzsqwq.github.io/zs-academic-pages/

Demo repo is here : https://github.com/zzsqwq/zs-academic-pages

中文文档在这里：[README.zh_cn.md](https://github.com/zzsqwq/hugo-academia-theme/blob/master/README.zh_cn.md)

## Features
1. Multilingual support
2. Easy to configure
3. Yaml to configure

![demo-cn](static/images/demo-zh_cn.png)

## Quick Start
1. Download hugo [here](https://github.com/gohugoio/hugo/releases) and create a new hugo site.
```shell
$ hugo new site example_site
```
2. Init your git in hugo project.
```shell
$ cd example_site
$ git init
```
3. Add this repository as a submodule in your project.
```shell
$ git clone https://github.com/zzsqwq/hugo-academia-theme.git themes/hugo-academia
```

4. Configure your `config.yaml`. A fully configure file is [here](https://github.com/zzsqwq/academic-pages-demo/blob/master/config.yaml). You can use it as a foundation.

5. Preview your site use `hugo server`. That's all, congratulations!

**Ps:** You can also pull down or fork [academic-pages-demo](https://github.com/zzsqwq/academic-pages-demo) and configure it.



## Index Homepage configure

When a Markdown file Front-matter `homepage` parameter is true, this file will be displayed on the homepage.

You can see an example file [here](https://github.com/zzsqwq/academic-pages-demo/blob/master/content/en/a.md).
```shell
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
homepage: true
---
```