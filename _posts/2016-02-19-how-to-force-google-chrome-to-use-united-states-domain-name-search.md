---
id: 219
title: 如何强制谷歌浏览器 使用 美国域名搜索
date: 2016-02-19T22:57:39+08:00
author: Kanaan Austen
layout: post
guid: https://blog.nieyujiang.info/?p=219
permalink: /2016/02/19/how-to-force-google-chrome-to-use-united-states-domain-name-search/
dsq_thread_id:
  - 4675112815
views:
  - 6
categories:
  - 黑科技
---
在使用谷歌浏览器的时候， 虽然已经设置为默认 https 加密搜索，英文，.com 的域名

https://www.google.com/search?hl=en-US&source=hp&q=%s&aq=f&aqi=&aql=&oq=&gs_rfai=

但是每次检索完之后，都是返回 .com.hk 的链接，**检索结果自动转跳**，而且还自带一套**安全过滤机制**。

在此也不对安全过滤机制吐槽啥了，对于一个重度的 谷歌粉来说， 不能获得全球最全面，最客观的信息结果，是无法忍受了，

于是特地花了些时间，研究如何默认 使用美国域名进行检索，得到最纯正，未经任何过滤篡改的结果。

下文当中提供了一种可行性方案

http://www.cnblogs.com/iftreasure/archive/2012/09/01/2666701.html

但是随着谷歌浏览器的升级， 似乎已经不再奏效了，在研究过程中发现通过以下几个步骤可以实现：

**1   登录谷歌账号**

**2  默认搜索语言为英文**

**3  默认搜索引擎为： https://www.google.com/search?hl=en-US&source=hp&q=%s&aq=f&aqi=&aql=&oq=&gs_rfai=**

**4  使用一次 https://www.google.com/ncr  搜索**

通过上诉步骤，谷歌浏览器就开始默认使用美国域名，理论上讲可能是谷歌记录了用户的行为，自动为用户调整选择了吧