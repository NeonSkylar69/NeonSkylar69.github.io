---
layout: post
title:  "Develop Diary "
date:   2021-08-11 20:15
category: Know
---
##  对自己最近几天开发blog的过程做个~~总结~~吐槽:clap:

&emsp;&emsp;原本是Hexo+GitHub Pages 来搭建自己博客的，结果Hexo实在给我整不会了，索性**脱坑**,换成了Jekyll 。[Jekyll](https://jekyllrb.com/docs/)和[Github Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)全是参考了官方的**doc**，不得不说Jekyll的官方doc做的是真比Hexo的好。  

>  官方doc是首选新手攻略:+1:

但Jekyll版本实在甩了GitHubPages依赖版本两大**ver.**以至于``bundle exec jekyll serve``时疯狂报错:sweat:，后来楞半天其实就缺个gem-webrick，大无语。但总的来说**建站部分**Jekyll还是很友好的:+1:。



&emsp;&emsp;主题的选择上，我fork了GH上的的一个主题——[louie](https://github.com/lilykonings/louie)，这个主题原本就是简易复古稍带点文艺的feel，但是要动刀的地方太多了（qs）于是我耗了两天在修改Layouts（布局）和ResponsiveDesign（响应式设计）（~~响应式真EZ~~）上，仅仅是只花了不到1h在设计自己的css上（呵呵），而且协调css和响应式也相当耗时，早知如此，我就自己从头到尾设计主题算了:sweat:。louie并不自带pagination和archives需要自己动手开发，然而自己只整出了前者，后者当个Flag立了。开发过程收获最多的可能就是对盒子模型的进一步理解和收藏了一堆宝藏博主及网页(e.g. [Google Fonts](https://fonts.google.com/)  对于字体选择和导入过于友好)。IMO,前端设计的成就感比较容易获得，但要说学到什么知识点，倒也没什么新鲜的，可能更多的是经验我觉得。先立几个flag吧！    

- [x] Pagination
- [x] Archive
- [ ] PicGallery
- [ ] MusicPlay
- [ ] DomainNamee

吐槽一下自己的画技，~~网页的icon画的跟个煮熟的牛排一样LOL!（其实我是想画成mc里的书的:sweat:)。~~刚刚保存了下，看到自己的post乱糟糟的，中文字体和英文字体有点不搭，无奈改日在设计吧。说实话，自己真的花了很多心思在blog的css设计上，现在的版面比之前文艺了个几倍，而且对首页的图片排版我真的想了很久也改了很久，原本是图片应该``opacity:40%``置于文字之下的，但是由于post list居中起来太麻烦，索性直接拎出来做成图片廊（图片来源于某个画藏网站:yum:)。说到这里我来气了，真的想喷响应式设计的代码逻辑，真的没搞懂@media和原来.class的优先级顺序，给我整5心态了。域名的话，等学校邮箱账号申请审核完就能白嫖GH的学生计划了:yum:。



&emsp;&emsp;按道理这篇应该是个总结的，但发现没啥好总结的，就单纯吐槽。改日再写篇《为何想建博客》好了，建好了的话这里就能补上个链接了（呵呵）。累了，困了，拉闸，睡觉:zzz:

> &emsp;久倦市尘嚣，  
>
> &emsp;归来听夏蝉。  
>
> &emsp;——梅疏影《归故山》

---

### 附加更新记录

- 2021.8.12 更新了网页icon![icon](/assets/icon.png) &emsp;这回画的像书了
- 2021.8.12 补上post [《为何想建博客》](/life/2021/08/12/PurposOfBlogging.html)
- 2021.8.14 更新Arichive功能-[record](/categorylist.html)
- 2021.8.17 优化post的布局（原来自己一直在110%下布局:sweat:）
- 2021.8.17 添加友链
