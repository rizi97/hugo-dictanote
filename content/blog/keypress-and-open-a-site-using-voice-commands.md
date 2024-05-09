---
layout: single
title: "Keypress and Open a Site using Voice Commands"
excerpt:
date: 2022-12-18
category: news
author: Anil Shanbhag
thumbnail: "https://rizi97.github.io/hugo-dictanote/assets/img/blog/featured.jpg"
---

Voice In v3.23 includes two new custom voice commands:

1. <open:*> to open a webpage. You can use this to open your favorite sites using voice commands. For example, you can create a new voice command 'open youtube' mapped to <open:https://youtube.com>. Then say open youtube anytime to open Youtube in a new tab.
2. <press:*> to simulate key presses on your keyboard. You can use it to press shift+enter to create a line break, or press ctrl+alt+s in Zendesk to mark a ticket as resolved. The voice command is completely customizable.
Here is an example list of voice commands you can implement using this.

![](https://rizi97.github.io/hugo-dictanote/assets/img/blog/Screenshot_2022-12-17_at_9.18.40_PM.width-800.png)

Implementing the key press emulation required us to get new permission: debugger. The debugger lets Voice In simulate key press similar to a real user.
Checkout the new voice commands and let us know what you think.

Happy Voice Typing!

> This article was written by Anil Shanbhag, [Voice In's](/voicein/) founder. Voice In lets you use your voice to type on [1000s on websites](https://dictanote.co/voicein/apps/), including Gmail, ChatGPT, Google Docs, Notion, etc.
> 
> ➤ [Start voice typing with Voice In](/voicein/)