# YouTube Watch Later Redirection Script

Grease monkey script: 

when you click on a video in the YouTube Watch Later list with the left or middle mouse button, automatically redirects the link to the original link of that video and opens it in a new tab.

### Table of Contents

[Birth Background](## Birth Background)

[Introduction](#Introduction)

[Installation](#Installation)

[Instructions](#Instructions)

[Version Update](#Version Update)

[Update Program](#Update Program)

[Contribution and Feedback](#Contribution and Feedback)

## Background

Sometimes you just want to open a video for later viewing, and when you're done: take a sip of tea, blow on the air conditioning, have a smile on your lips, and browse the comments section.

But YouTube's Watch Later mode is enabled by default, and there's no way to turn it off (I couldn't find it even after searching).

Maybe you can wait until you're almost done and pause it first, then run to browse the comments section. But that would be a huge disruption to the viewing experience.

**Is this tolerable? It's not tolerable! **

So this script was born, watch the original video directly in normal mode, it's that simple~.

PS: I basically didn't find a single script for YouTube Watch Later, so I wrote one for my own use. Even JavaScript zero basis directly written, this is my first script, thanks to the help of GPT. (Bad writing, please feel free to spray)

## Features

- Automatically redirects video links in the Watch Later list to the original link of the video. (Currently only for clicks from the [YouTube Watch Later page](there should be a link here))
- Support left and center mouse click operations.
- Show redirection tips on the page, and support customizing the tip box style.
- Apply to YouTube Single Page Application (SPA). Access to Watch Later page from YouTube sidebar will also be listened to. (There should be a picture here.)

## Installation

1. Install the browser extension [Tampermonkey](https://www.tampermonkey.net/).
2. Click [Github Source](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect/raw/main/YouTube-Watch-Later-Redirect.user.js) to install it now.
   Or install it at [GreasyFork](here is the link).

## Instructions for use (there should be a picture description here)

- The script will automatically fetch the original link of the video in advance when the [YouTube Watch Later Page](should have a link here) opens.
- When you click on a video in the Watch Later list with the left or middle mouse button, the script will automatically jump to the original link of the video and open it in a new tab.
- When you click on the author of a video with the left or middle mouse button, the script determines that it should not redirect at that time and opens the author's home page instead.
- You can customize whether or not to display the “redirect complete” alert box from the script settings menu.
- You can adjust the position, size, auto-hide time and message of the alert box.
- If you want to change the style of the prompt box, please open the Tampermonkey menu to set it when the script is running.

## Version Updates

### Version 1.0.0

- Support redirection of video links in [YouTube Watch Later Page] (there should be a link here).
- Added redirection alert box and its customized settings.
- Solve the problem of unresponsive script in YouTube Single Page Application (SPA).
- Add URL change listening feature (catch browser forward and backward).

## Add URL change listening function (catching browser forward and backward).

- Not yet available

## Contributions and feedback

If you've found a problem, or have any suggestions for improvements, feel free to submit feedback via [GreasyFork](here's the link) or on [GitHub](https://github.com/JerryYang-30/YouTube-Watch-Later-Redirect) [ Issue](link here) or [Pull Request](link here). Your feedback and contributions are greatly appreciated!