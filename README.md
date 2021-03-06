## [Inline-Files-Bot](https://github.com/CyberBoyAyush/Inline-Files-Bot)

[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.png)](https://telegram.me/cyberboyayush)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

* Index channel/group files for inline search.
* When you going to post file on telegram channel/group this bot will save that in database, So you can search that easily in inline mode.
* Supports document, video and audio file formats with caption.

### Installation

#### Easy Way
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

#### Hard Way

```sh
python3 -m venv env
. ./env/bin/activate
pip install -r requirements.txt
# <Edit info.py with variables as given below>
python bot.py
```
Check `sample_info.py` before editing `info.py` file

### Admin commands
```
channel - Get basic infomation about channels
total - Show total of saved files
delete - Delete file from database
logger - Get log file
```

#### Variables

##### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com).
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/dsuTn4qV2GA)

##### Optional Variables
* `COLLECTION_NAME`: Name of the collections. Defaults to Telegram_files. If you going to use same database, then use different collection name for each bot
* `MAX_RESULTS`: Maximum limit for inline search results
* `CACHE_TIME`: The maximum amount of time in seconds that the result of the inline query may be cached on the server

### Contributions
Contributions Are Welcome Msg [@CyberBoyAyush](https://t.me/cyberboyayush)

# Get Some Help (Btw Its Easy To Deploy)
* [CyberBoyAyush](https://telegram.me/CyberBoyAyush)
* [Contact Us Bot](https://telegram.me/cyberboyayushbot)
