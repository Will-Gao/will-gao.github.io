---

title: 我的第一篇博客
date: 2026-05-21 
categories: [Blog]
tags: [开始, Will Gao]
------------------

# 👋 Hello World

这是我用 Chirpy 搭建的第一篇博客！

如果你能看到这篇文章，说明：

* GitHub Pages 已经成功 ✅
* Chirpy 主题正常 ✅
* 博客系统上线 🎉

接下来我会持续更新内容 🚀

记录复制后如何快速使用
步骤可以问deepseek or kimi均可
https://github.com/Will-Gao/will-gao.github.io 我fork了一个项目https://github.com/cotes2020/jekyll-theme-chirpy
url改成了我的网址:index.html文件夹里的url位置加上个人主页地址：https://will-gao.github.io
出现了一个核心问题：主页显示--- layout: home # Index page ---，怎么解决，怎么问AI都解决不了，最终还是gpt搞定了
核心问题：找到 地址：pages-deploy.yml，位置：31行 uses: actions/checkout@v6，改成4 即可
