![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=𝗪𝗘𝗟𝗖𝗢𝗠+𝗧𝗢+𝐉𝐀𝐒𝐌𝐈𝐍𝐄+𝐁𝐎𝐓!;𝗖𝗥𝗘𝗔𝗧𝗘𝗗+𝗕𝗬+𝗧𝗘𝗔𝗠+𝗠𝗢𝗩𝗜𝗘𝗦𝗖𝗔𝗙𝗘!;𝗔+𝗦𝗜𝗠𝗣𝗟𝗘+𝗠𝗖+𝗔𝗨𝗧𝗢𝗙𝗜𝗟𝗧𝗘𝗥+𝗕𝗢𝗧!)</p>
<p align="center">
  <img src="https://telegra.ph/file/28e819958834a60d68fd3.jpg" alt="MKN BOTZ LOGO">
</p>
<h1 align="center">
  <b> 𝐉𝐀𝐒𝐌𝐈𝐍𝐄 𝐁𝐎𝐓 </b>
</h1>

[![Stars](https://img.shields.io/github/stars/thedexter45/Jasmine?style=flat-square&color=yellow)](https://github.com/thedexter45/Jasmine/stargazers)
[![Forks](https://img.shields.io/github/forks/thedexter45/Jasmine?style=flat-square&color=orange)](https://github.com/thedexter45/Jasmine/fork)
[![Size](https://img.shields.io/github/repo-size/thedexter45/Jasmine?style=flat-square&color=green)](https://github.com/thedexter45/Jasmine)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/thedexter45/Jasmine)   
[![Contributors](https://img.shields.io/github/contributors/thedexter45/Jasmine?style=flat-square&color=green)](https://github.com/thedexter45/Jasmine/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/thedexter45/Jasmine/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/thedexter45/Jasmine.svg)](https://stars.medv.io/thedexter45/Jasmine)



## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
- [x] Custom File Caption

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `Support Chat` : Username of a Support Group / ADMIN. ( Should be username without @ and not ID
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* `USE_CAPTION_FILTER` : Whether bot should use captions to improve search results. (True False)
* `CUSTOM_FILE_CAPTION` : A custom file caption for your files. formatable with , file_name, file_caption, file_size, Read Readme.md for better understanding
* `CACHE_TIME` : The maximum amount of time in seconds that the result of the inline query may be cached on the server
* `IMDB` : Imdb, the view of information when making True/False
* `SINGLE_BUTTON` : choose b/w single or double buttons 
* `P_TTI_SHOW_OFF` : Customize Result Buttons to Callback or Url by (True = url / False = callback)

## Deploy to Koyeb

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/thedexter45/Jasmine&env[BOT_TOKEN]&env[API_ID]&env[API_HASH]&env[CHANNELS]&env[ADMINS]&env[PICS]&env[LOG_CHANNEL]&env[AUTH_CHANNEL]&env[MAX_RIST_BTNS]=10&env[CUSTOM_FILE_CAPTION]&env[DATABASE_URI]&env[DATABASE_NAME]=MknBotz&env[COLLECTION_NAME]=Telegram_files&env[SUPPORT_CHAT]&env[IMDB]=True&env[IMDB_TEMPLATE]&env[IMDB_DELET_TIME]=900&env[SINGLE_BUTTON]=True&env[START_MESSAGE]&env[FORCE_SUB_TEXT]&env[AUTH_GROUPS]&env[WELCOM_PIC]&env[WELCOM_TEXT]&env[BUTTON_LOCK_TEXT]&env[PMFILTER]=True&env[G_FILTER]=True&env[BUTTON_LOCK]=True&env[RemoveBG_API]&env[P_TTI_SHOW_OFF]=True&run_command=python%20bot.py&branch=main&name=mr-rofessor)              

## Deploy to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/Drx3Ko)

## Deploy to Heroku 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/thedexter45/Jasmine)

## Commands
```
start - check bot alive
ping - pong
settings - get settings 
logs - to get the rescent errors
stats - to get status of files in db.
filter - add manual filters
filters - view filters
connect - connect to PM.
disconnect - disconnect from PM
del - delete a filter
delall - delete all filters
deleteall - delete all index(autofilter)
delete - delete a specific file from index.
info - get user info
id - get tg ids.
imdb - fetch info from imdb.
users - to get list of my users and ids.
chats - to get list of the my chats and ids 
index  - to add files from a channel
leave  - to leave from a chat.
disable  -  do disable a chat.
enable - re-enable chat.
ban_user  - to ban a user.
unban_user  - to unban a user.
channel - to get list of total connected channels
broadcast - to broadcast a message to all Eva Maria users
```

## TELAGRAM SUPPORT 

* [![MOVIESCAFE](https://img.shields.io/static/v1?label=MOVIES&message=CAFE&color=critical)](https://t.me/mc_moviescafe)

## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 2.0.](https://github.com/EvamariaTG/evamaria/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.

