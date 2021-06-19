---

## Video Compressor Bot

## HOW TO DEPLOY YOUTUBE TUTORIAL

<a href="https://youtu.be/YEwAN3iTGyE"><img src="https://img.shields.io/badge/How%20To-Deploy-red.svg?logo=Youtube"></a>

#### The Easy Way

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/fkokeralam123/VidComBot)

#### The Hard Way

```sh
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
# <Create config.py with variables as given below>
python bot.py
```

An example `config.py` file could be:

**Not All of the variables are mandatory**

```python3
from sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  TG_BOT_TOKEN = ""
  AUTH_USERS = [
    7351948
  ]
```

### [@BotFather](https://telegram.dog/BotFather) Commands

```
start - Checking bot live.
compress - To compress the video.
cancel - Stop the process.
log - Get log
help - To know about bot
```
## CREDITS

[FKO KERALAM](https://github.com/fkokeralam123/fkokeralam123)

#### LICENSE
- GPLv3
