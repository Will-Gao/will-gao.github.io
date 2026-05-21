---

# 我的第一篇博客：如何搭建个人网站

date: 2026-05-21 

categories: [Blog]

tags: [开始, Will Gao]
------------------

1  创建个人仓库：打开https://github.com/cotes2020/chirpy-starter  ，点击fork，命名为个人网站入口https://github.com/Will-Gao/will-gao.github.io

2  创建github启动流程：settings-pages-source-github actions

3  加载入口：index.html文件夹里的url位置加上个人主页地址：https://will-gao.github.io

4  启动网站：打开个人网站入口，主页显示--- layout: home # Index page ---

5  解决核心问题：找到文件pages-deploy.yml，位置：31行 uses: actions/checkout@v6，改成4 即可

6 静待1-3min，即可看到网站已正常访问，后续修改个人介绍即可
