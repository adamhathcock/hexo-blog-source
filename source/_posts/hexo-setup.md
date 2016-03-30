---
title: Setting up a blog
date: 2016-03-30 10:46:35
tags:
  - hexo
---
## Hexo Setup
This was both easier and harder than I'd thought.

The [setup docs](https://hexo.io/docs/) for Hexo is actually very straight forward.  The hard part came when picking a stupid theme.

The first thing was picking a [theme](https://hexo.io/themes/) at all.  Most are kind of flashy.  I guess people want to show off Javascript frontend tricks.

I wanted something simple and finally settled on the default [Light theme](https://github.com/hexojs/hexo-theme-light) mainly because it worked out of the box.  The one extra I wanted was a twitter widget.  Maybe next time.

Deploy to github is so easy.  `hexo deploy` and bam it uploads to the repo.  Can't ask for more.

For the curious, my blog source is [here](https://github.com/adamhathcock/hexo-blog-source)  The more interesting bits are the [config for the overall blog](https://github.com/adamhathcock/hexo-blog-source/blob/master/_config.yml) and the [config for the theme](https://github.com/adamhathcock/hexo-blog-source/blob/master/themes/light/_config.yml).