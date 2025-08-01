---
title: AI_Painting
published: 2025-08-01T18:38:01+08:00
summary: "自建一个云端无限制的SD WebUI 小白也能轻松上手"
cover:
  image: https://cdn.jsdelivr.net/gh/Tavre/test_github_imgwarehouse@main/images/20250611135557690.webp
tags: [AI绘画, 白嫖, 云算力,飞浆]
categories: '教程'
draft: false 
lang: ''

---

# 使用百度飞浆 部署你的在线AI绘画

<code>下午打完游戏 仔细想了想我的AI绘画 有近乎一半的时间都在报错 不如我发一篇个人部署的教程 还节省我的成本</code>

## 教程开始

打开[飞桨AI Studio星河社区-人工智能学习与实训社区](https://aistudio.baidu.com/index)

点击右上角“登录”按钮

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-48-27-image.png)

使用百度账户登录即可 然后我们点击下方链接

[Stable Diffusion WebUI 在线体验 - 飞桨AI Studio星河社区](https://aistudio.baidu.com/projectdetail/7640442?channel=0&channelType=0&sUid=16990041&shared=1&ts=1754043924938)

 紧接着点击右上角“运行一下”

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-47-15-image.png)

紧接着点击“创建”

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-49-22-image.png)

然后再次点击右上角“专业开发”

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-49-57-image.png)

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-50-16-image.png)

这里的配置 选择V100的16G或32G **不要使用CPU（即基础版）**！ 否则你可能会遇到各种奇奇怪怪的问题

> 点数怎么获取呢 完善个人资料 会赠送你一些点数 然后通过一些任务 也会赠送你一些点数
> 
> 或者直接金钱解决问题 (呜呜呜 我恨有钱人）

进入到页面之后 根据图片提示双击文件![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-56-19-image.png)

这里右边加载会等待5分钟左右 请耐心等待

接下来根据图片提示 按步骤操作

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-19-59-23-image.png)

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-20-00-28-image.png)

点击“激活端口” 然后复制命令 再点击中上区域的“+”

紧接着 选择“终端”

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-20-01-36-image.png)

将我们复制的命令粘贴进去 不一会 即可在终端中看到外部链接

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-20-03-41-image.png)

我们访问 即使sd webui画面 现在就可以开始你的创作了！

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-20-05-48-image.png)

## 自定义模型

回到我们启动webui的页面

![](https://cdn.jsdelivr.net/gh/TenKavr/test_gi@main/images/2025-08-01-20-07-32-image.png)

根据图片提示 点击对应的对话框

在下载链接内填入C站模型下载链接 点击“开始下载” 即可下载并使用模型

C站链接：[civitai—国外知名大模型平台](https://civitai.com/)

## 声明

本项目作者——[旭_1994](https://aistudio.baidu.com/personalcenter/thirdview/9044961)\
项目地址——[Stable Diffusion WebUI 在线体验](https://aistudio.baidu.com/projectdetail/7640442)

本教程仅供学习和研究使用 任何风险都由用户承担