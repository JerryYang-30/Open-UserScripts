# YouTube Watch Later Redirection Script

[简体中文](https://github.com/JerryYang-30/Open-UserScripts#youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91%E8%84%9A%E6%9C%AC) | **English**

Grease monkey script: 

when you click on a video in the YouTube Watch Later list with the left or middle mouse button, automatically redirects the link to the original link of that video and opens it in a new tab.

### Table of Contents

[Background](#background)

[Introduction](#introduction)

[Installation](#installation)

[Version Updates](#version-updates)

[Update Plans](#update-plans)

[Contribution and Feedback](#contribution-and-feedback)

## Background

Sometimes you just want to open a video for later viewing, and when you're done: take a sip of tea, blow on the air conditioning, have a smile on your lips, and browse the comments section.

But YouTube's Watch Later mode is enabled by default, and there's no way to turn it off (I couldn't find it even after searching).

Maybe you can wait until you're almost done and pause it first, then run to browse the comments section. But that would be a huge disruption to the viewing experience.

**Is this tolerable? It's not tolerable!**

So this script was born, watch the original video directly in normal mode, it's that simple~.

PS: I basically didn't find a single script for YouTube Watch Later, so I wrote one for my own use. Even JavaScript zero basis directly written, this is my first script, thanks to the help of GPT. (Bad writing, please feel free to spray)

## Introduction

- Automatically redirects video links in the Watch Later list to the original link of the video.
- Support left and center mouse click operations.
- Show *redirection done* tips on the page, and support customizing the tip box style.
- Support for exporting *Watch Later* video list.
- When you click on the author of the video (in the green box below) with the left or middle mouse button, the script determines that you should not redirect at this point and opens the author's profile page instead.
- ![afytb1r1 0px](https://github.com/user-attachments/assets/b73b4982-e866-4833-aafd-8f617795fe91)


## Installation

1. Install the browser extension [Tampermonkey](https://www.tampermonkey.net/).
2. Install it at [GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91).
3. Or [→Click Here←](https://github.com/JerryYang-30/Open-UserScripts/raw/main/YouTube-Watch-Later-Redirect.user.js) to install it now.(Update with GreasyFork source)
   



## Version Updates

Please watch [CHANGELOG](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/blob/main/CHANGELOG.md)

## Update Plans

- [ ] Refactor the code using Claude (the previous code written by GPT was too disorganized)
- [x] Add new feature: Export the list of videos to watch later to a TXT file

## Contribution and Feedback

If you've found a problem, or have any suggestions for improvements, feel free to submit feedback via [GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91/feedback) or on [GitHub Issue](https://github.com/JerryYang-30/Open-UserScripts/issues) or [Pull Request](https://github.com/JerryYang-30/Open-UserScripts/pulls). Your feedback and contributions are greatly appreciated!
