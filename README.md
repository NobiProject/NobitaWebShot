# Website-Screenshot-Bot
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/14e4b6f385a44aa9b35602e3ff52a668)](https://app.codacy.com/manual/alenpaul2001/Web-Screenshot-Bot?utm_source=github.com&utm_medium=referral&utm_content=alenpaul2001/Web-Screenshot-Bot&utm_campaign=Badge_Grade_Dashboard)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Try it on telegram](https://t.me/getwebshotrobot)](http://t.me/getwebshotrobot)

A Telegram _Web-Screenshot_ Bot Based on Pyrogram
# Introduction

Telegram Bot that creates screenshot _[PNG/JPEG]_ or PDF of a given link. Can be matched with various other settings like resolution, partial or full-page rendering. The bot can currently be found in @BetterWebShotBot.

### Available Resolutions are :

1. 640x480
2. 800x600
3. 1280x720
4. 2560x1440

Splitting of long pages are available for png and jpeg.

# Installing 

> Note: the bot requires chromium/chrome binary to render websites.
### <b>The Legacy Way</b>
Simply clone the repository and run the main file:

```sh
git clone https://github.com/nobitanobi/nobiwebshot.git
cd NobiWebshot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 __main__.py
```
#### an example config.py 👇
```py
class Config:
    BOT_TOKEN = "12345:49dc3eeb1aehia5cI2TesHNHc"
    API_ID = 259423
    API_HASH = "eb06d4abfb49dc3eeb1aebf581e"
    # Leave this None to automatically download chrome binary
    EXEC_PATH = None
    # Optional Fields
    LOG_GROUP = -123993202
    SUPPORT_GROUP_LINK = "https://t.me/botsupportgr"
```


# Thanks to

[Dan Tès](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)

[Mattwmaster58](https://github.com/NobitaNobi) for the port of [Pyppeteer Library](https://github.com/NobitaNobi/nobiwebshot)

### special thanks to :

[<\-W4RR10R-/>](https://github.com/KratosProject) and [@Kratos_71](https://t.me/Kratos_71) for helping me.

[Λиʞ⫯𝚝⅁øμϩᴧ⋎](https://github.com/KratosProject) and 
[//NobitaNobi//](https://github.com/NobitaNobi) for suggesting new features.

### Made with ❤️️ in India
### Copyright & License 

* Copyright (C) 2021 by [NobitaNobi](https://github.com/NobitaNobi)
* Licensed under the terms of the [GNU AGPL Version 3.0](https://github.com/NobitaNobi/NobiWebShot/blob/master/LICENSE)
