# Raytaylorism V1.0a

这是我制作的一款扁平化风格的[Hexo]主题，基于[Furatto]和[Font Awesome]。

**注意：本主题是在hexo 1.2.4版本下开发，对于2.0以上的hexo有一些显示上的问题。

[主题预览]

## 安装

```
git clone https://github.com/raytaylorlin/hexo-theme-raytaylorism.git
```

修改 `_config.yml` 中的`theme`一项的值为 `Raytaylorism`即可启用主题。

## 使用的插件

代码语法高亮 [Google-code-prettify]

流量分析 [Google Analytics]

第三方社会化评论 [多说]

响应式侧滑菜单 [jQuery.jPanelMenu.js]

## 更新日志

* 1.0.1(2013-8-26) 使页面主内容在高度不够的时候可以自适应屏幕，让页脚沉底
* 1.0.2(2013-8-31) 添加了About页面并使用自定义模板
* 1.0.3(2013-9-1) 新增响应式设计的侧滑菜单
* 1.0.4(2013-9-2) 针对手机进行响应式设计，重新定义所有版面的字体大小
* 1.0.5(2013-9-5) 调整基础布局，新增首页加载更多按钮
* 1.0.6(2013-9-15) 新增新功能导航效果
* 1.0.7(2013-9-18) 修复“加载更多”动画效果滚动不到位的问题
* 1.0.8(2013-9-19) 修复“你当前所在的位置”为空的bug
* 1.0.9(2013-9-19) 修复IE新功能导航阴影的显示问题
* 1.1.0(2013-9-20) 把新功能导航的特征值分离到博客的配置中
* 1.1.1(2013-9-20) 修复Google Analytics无效的bug
* 1.1.2(2013-10-3) 修复google_analytics.ejs中没有引用博客配置的错误
* 1.1.3(2013-10-6) 修改新功能导航的DOM识别方式为查询字符串，给navbar的各项添加id
* 1.1.4(2013-10-7) 新增about.ejs模板
* 1.1.5(2013-10-8) 修复在其他页面点击header的博客名没有回到首页的bug
* 1.1.6(2013-10-18) 将Furatto升级到V2.0版本
* 1.1.7(2013-10-21) 修复Furatto升级版本后网格布局的显示错误
* 1.1.8(2013-10-24) 修复Furatto升级版本后各种样式的问题
* 1.1.9(2013-11-1) 新增读书栏目
* 1.2.0(2013-12-12) 修复当在hexo配置中new_feature_guide字段不存在时，生成会报错的问题
* 1.2.1(2013-12-16) 修复升级hexo版本到2.3.0后，正文中代码排版的问题
* 1.2.2(2014-1-3) 重新调整全局的字体大小
* 1.2.3(2014-1-4) 修复“加载更多”无法滚动的问题
* 1.2.4(2014-1-7) 修复Furatto升级版本后侧滑栏样式的问题
* 1.2.5(2014-1-8) 修复升级hexo版本到2.3.0后，归档的标题没有显示的问题
* 1.2.6(2014-1-10) 添加分类目录菜单

[Hexo]: http://zespia.tw/hexo/
[主题预览]: http://raytaylorlin.com/
[Google-code-prettify]: https://code.google.com/p/google-code-prettify/
[Google Analytics]: http://www.google.com/analytics/
[Furatto]: http://icalialabs.github.io/furatto/
[Font Awesome]: http://fortawesome.github.io/Font-Awesome/
[多说]: http://duoshuo.com/
[jQuery.jPanelMenu.js]: http://jpanelmenu.com/
