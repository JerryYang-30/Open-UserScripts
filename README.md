# YouTube 稍后再看重定向脚本

油猴脚本：当你用鼠标左键或中键点击YouTube稍后观看列表中的视频时，自动将链接重定向到该视频的原始链接，并在新标签页中打开。

**简体中文** | [English](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/blob/main/README_en.md)

### 目录

[诞生背景](#诞生背景)

[功能介绍](#功能介绍)

[安装方法](#安装方法)

[使用说明](#使用说明)

[版本更新历史](#版本更新历史)

[更新计划](#更新计划)

[贡献与反馈](#贡献与反馈)

## 诞生背景
有时候，你只是想打开一个稍后观看视频，等看完之后：抿上一口茶，吹着大空调，嘴边挂着笑，浏览评论区。

但是！YouTube的稍后观看会默认开启连播模式，还没办法关掉这个连播（我找了半天也没找到）。

或许可以等到快看完了先暂停播放，然后跑去浏览评论区。可是这样就很影响观看体验。

**这能忍吗？这不能忍！**

所以这个脚本诞生了，直接用正常模式观看原视频，就是这么简单~

PS：关于YouTube稍后观看的脚本，我基本一个也没有搜到，为了自用所以写了一个。甚至是JavaScript零基础直接写的，这也是我的第一个脚本，感谢GPT的帮助。（写的烂，请轻喷）

## 功能介绍

- 自动将稍后观看列表中的视频链接重定向至视频的原始链接。（目前只针对从[YouTube稍后观看页面](https://www.youtube.com/playlist?list=WL) 点击的情况）
- 支持鼠标左键和中键点击操作。
- 在页面中显示重定向提示，并支持自定义提示框样式。
- 适用于YouTube单页应用（SPA），从YouTube左侧边栏进入稍后观看页面也会被监听到。（即从下图红框框部分点击进入稍后观看的情况）
- ![oupa45ku p3w](https://github.com/user-attachments/assets/08513620-ec39-4ccb-9f12-e4ce71c7de8b)


## 安装方法

1. 安装浏览器扩展 [Tampermonkey](https://www.tampermonkey.net/)。
2. 在[GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91)安装。
3. 或 [→点击此处←](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/raw/main/YouTube-Watch-Later-Redirect.user.js) 立刻安装（利用GreasyFork源更新）。
   

## 使用说明

- 脚本会自动在 [YouTube稍后观看页面](https://www.youtube.com/playlist?list=WL) 打开时，提前获取每个视频的原始链接，并默认返回提示，默认3秒后消失（如下图右下角）。
- ![3mzfjbdq er2](https://github.com/user-attachments/assets/3b8d8787-d24b-4d1a-8236-a2f655672a78)

- 用鼠标左键或中键点击下图红框部分（除了绿框里）时，脚本会在新标签页中打开视频的原始链接。
- 用鼠标左键或中键点击视频的发布作者（下图绿框部分）时，脚本会判断出此时不应该重定向，而是打开作者的个人主页。
- ![afytb1r1 0px](https://github.com/user-attachments/assets/b73b4982-e866-4833-aafd-8f617795fe91)

- 可以通过TamperMonkey脚本设置菜单自定义是否显示“重定向完成”的提示框。
- ![ikmz1z15 gc1](https://github.com/user-attachments/assets/1a825c8c-2b2f-403f-8730-79b26c0a21ac)
- ![3bbzl0q5 ucy](https://github.com/user-attachments/assets/f9ada660-bf7d-4b0a-bb4d-4505bda38cd1)


- 可通过TamperMonkey脚本设置菜单调整提示框的位置、大小、自动隐藏时间以及提示词。
- ![ijuj0khm y43](https://github.com/user-attachments/assets/fece4bda-4589-40c8-aa7a-5c4fb8d440d6)
- ![akxa0wcj 1gp](https://github.com/user-attachments/assets/b9a88306-3673-4d48-b232-7c951bc5b0c3)


## 版本更新历史

请看[CHANGELOG](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/blob/main/CHANGELOG.md)

## 更新计划

- [ ] 用Claude重构代码（之前GPT写的太乱了）
- [ ] 添加新功能：导出稍后观看的视频列表（至TXT文件）

## 贡献与反馈

如果你在使用过程中发现问题，或者有任何改进建议，欢迎通过 [GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91/feedback) 提交反馈 或在 [GitHub](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect) 提交 [Issue](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/issues) 或 [Pull Request](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/pulls)。非常感谢你的反馈和贡献！
