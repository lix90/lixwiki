# 前端开发

包括前端开发语言、框架和工具，前端有关的设计原则和工具等。

## 前端模板

通过 hexo 静态博客生成器了解到了前端页面的模板，还没有对前端三种“语言”全面的了解，提前了解了下模板技术。本来前端技术让初学者眼花缭乱，各种各样的模板技术又人不知所措了。

三种截然不同的模板方案：
- String-based 模板技术：基于字符串的 parse 和 compile 过程；
- Dom-based 模板技术：基于 Dom 的 link 或 compile 过程；
- 杂交的 Living templating 技术：基于字符串的 parse 和基于 dom 的 compile 过程。

**前端模板对照表**

Contrast/Solutions | String-based templating | Dom-based templating | Living templating
:-------- | :---------| :-----------| :-----------
例子 | Mustache, Dustjs | Angularjs, Vuejs | Regularjs, Ractivejs, htmlbars Usage
语法 | ### | ### | ### |
活动性：X | ### | ###
性能：初始 | ### | # | #
性能：更新 | # | ### | ###
安全性 | # | ## | #####
Dom 无关 | ##### | X | ##
SVG 支持性 | X | ## | ###

参考：[前端模板技术面面观](http://leeluolee.github.io/2014/10/10/template-engine/)
