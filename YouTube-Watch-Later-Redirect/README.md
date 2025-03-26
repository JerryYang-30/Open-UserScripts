# YouTube 稍后再看重定向脚本

油猴脚本：当你用鼠标左键或中键点击YouTube稍后观看列表中的视频时，自动将链接重定向到该视频的原始链接，并在新标签页中打开。

**简体中文** | [English](https://github.com/JerryYang-30/Open-UserScripts/blob/main/README_en.md)

### 目录

[诞生背景](#诞生背景)

[功能介绍](#功能介绍)

[安装方法](#安装方法)

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

- 自动将稍后观看列表中的视频链接重定向至视频的原始链接。
- 支持鼠标左键和中键点击操作。
- 在页面中显示 *重定向完成* 提示，并支持自定义提示框样式。
- 支持导出 *稍后观看* 视频列表
- 用鼠标左键或中键点击视频的发布作者（下图绿框部分）时，脚本会判断出此时不应该重定向，而是打开作者的个人主页。
- ![afytb1r1 0px](https://github.com/user-attachments/assets/b73b4982-e866-4833-aafd-8f617795fe91)



## 安装方法

1. 安装浏览器扩展 [Tampermonkey](https://www.tampermonkey.net/)。
2. 在[GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91)安装。
3. 或 [→点击此处←](https://github.com/JerryYang-30/Open-UserScripts/raw/main/YouTube-Watch-Later-Redirect.user.js) 立刻安装（利用GreasyFork源更新）。
   




## 版本更新历史

请看[CHANGELOG](https://github.com/JerryYang-30/Open-UserScripts/blob/main/CHANGELOG.md)

## 更新计划

- [ ] 用Claude重构代码（之前GPT写的太乱了）
- [x] 添加新功能：导出稍后观看的视频列表（至TXT文件）

## 贡献与反馈

如果你在使用过程中发现问题，或者有任何改进建议，欢迎通过 [GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91/feedback) 提交反馈 或在 [GitHub](https://github.com/JerryYang-30/Open-UserScripts) 提交 [Issue](https://github.com/JerryYang-30/Open-UserScripts/issues) 或 [Pull Request](https://github.com/JerryYang-30/Open-UserScripts/pulls)。非常感谢你的反馈和贡献！
