# YouTube Watch Later Redirection Script

[简体中文](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect#youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91%E8%84%9A%E6%9C%AC) | **English**

Grease monkey script: 

when you click on a video in the YouTube Watch Later list with the left or middle mouse button, automatically redirects the link to the original link of that video and opens it in a new tab.

### Table of Contents

[Background](#Background)

[Introduction](#Introduction)

[Installation](#Installation)

[Instructions](#Instructions)

[Version Updates](#Version_Updates)

[Update Plans](#Update_Plans)

[Contribution and Feedback](#Contribution_and_Feedback)

## Background

Sometimes you just want to open a video for later viewing, and when you're done: take a sip of tea, blow on the air conditioning, have a smile on your lips, and browse the comments section.

But YouTube's Watch Later mode is enabled by default, and there's no way to turn it off (I couldn't find it even after searching).

Maybe you can wait until you're almost done and pause it first, then run to browse the comments section. But that would be a huge disruption to the viewing experience.

**Is this tolerable? It's not tolerable!**

So this script was born, watch the original video directly in normal mode, it's that simple~.

PS: I basically didn't find a single script for YouTube Watch Later, so I wrote one for my own use. Even JavaScript zero basis directly written, this is my first script, thanks to the help of GPT. (Bad writing, please feel free to spray)

## Introduction

- Automatically redirects video links in the Watch Later list to the original link of the video. (Currently only for clicks from the [YouTube Watch Later page](https://www.youtube.com/playlist?list=WL))
- Support left and center mouse click operations.
- Show redirection tips on the page, and support customizing the tip box style.
- For YouTube Single Page Applications (SPA), accessing the Watch Later page from the left sidebar of YouTube will also be listened to. (i.e. clicking from the red box in the image below to watch later)
- ![jhz2veqj dnj](https://github.com/user-attachments/assets/de786f65-5254-4fe9-b3fc-c98de3165d61)


## Installation

1. Install the browser extension [Tampermonkey](https://www.tampermonkey.net/).
2. Install it at [GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91).
3. Or [→Click Here←](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/raw/main/YouTube-Watch-Later-Redirect.user.js) to install it now.(Update with GreasyFork source)
   

## Instructions

- The script automatically fetches the original link for each video in advance when the [YouTube Watch Later page](https://www.youtube.com/playlist?list=WL) opens, and returns the prompt by default, which disappears after 3 seconds by default (bottom right in the image below).
- ![qjf50ni5 2de](https://github.com/user-attachments/assets/39bbaa0e-e758-4d3a-8e90-cbadb5a540fe)
- When you click with the left or middle mouse button on the red part of the image below (except in the green box), the script will open the original link of the video in a new tab.
- When you click on the author of the video (in the green box below) with the left or middle mouse button, the script determines that you should not redirect at this point and opens the author's profile page instead.
- ![afytb1r1 0px](https://github.com/user-attachments/assets/b73b4982-e866-4833-aafd-8f617795fe91)
- You can customize whether or not to display the “Redirection Complete” alert box through the TamperMonkey Script Settings menu.
- ![m1tobvex nms](https://github.com/user-attachments/assets/317d350b-4c50-463f-9e93-c8e454a80a07)
- ![wc0r5hp3 von](https://github.com/user-attachments/assets/b701f0b6-30a3-4a3a-96bc-7c390f59bd84)

- The position, size, auto-hide time, and prompt word of the prompt box can be adjusted through the TamperMonkey script settings menu.
- ![nulk3d1k i5t](https://github.com/user-attachments/assets/962120d8-0b76-41fd-ba78-bcf8f590e9eb)
- ![akxa0wcj 1gp](https://github.com/user-attachments/assets/b9a88306-3673-4d48-b232-7c951bc5b0c3)

## Version_Updates

Please watch [CHANGELOG](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/blob/main/CHANGELOG.md)

## Update_Plans

- [ ] Refactor the code using Claude (the previous code written by GPT was too disorganized)
- [ ] Add new feature: Export the list of videos to watch later to a TXT file

## Contribution_and_Feedback

If you've found a problem, or have any suggestions for improvements, feel free to submit feedback via [GreasyFork](https://greasyfork.org/zh-CN/scripts/507417-youtube-%E7%A8%8D%E5%90%8E%E5%86%8D%E7%9C%8B%E9%87%8D%E5%AE%9A%E5%90%91/feedback) or on [GitHub Issue](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/issues) or [Pull Request](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/pulls). Your feedback and contributions are greatly appreciated!
