[![HM MUSIC BOT](https://telegra.ph/file/c24b0ad76a2c5d8ad1687.png)](https://telegram.me/hmrequestbot)

# HM MUSIC BOT

<h3>Requirements ๐</h3>

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.8+ or 3.7
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

๐งช Get STRING_SESSION from here:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/StringSession#main.py)

## Features ๐ฎ

- Thumbnail Support
- Playlist Support
- Showing track names when skipping
- Youtube, Local playback support
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play
- Keyboard selection support for youtube play
- Lyrics Scrapper
- Unlimited Queue

## Commands ๐ 

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/vsong <song name>` - download videos you want quickly
- `/lyric <song name>` - lyrics scrapper
- `/vk <song name>` - generate song without download

#### Admins Only ๐ทโโ๏ธ
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/musicplayer on` - to disable music player in your group
- `/musicplayer off` - to enable music player in your group
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status
- `/auth` - authorized people to access the admin commands
- `/deauth` - deauthorized people to access the admin commands
- `/control` - open the music player control panel
- `/silent` - mute the music player on voice chat
- `/unsilent` - unmute the music player on voice chat

### Sudo User ๐งโโ๏ธ
- `/stats` - see the bot statistic
- `/pmpermit on | off` turn on/off the assistant pmpermit
- `/userbotleaveall` - order the assistant to leave all groups
- `/gcast` - send a broadcast message from the assistant

### Owner Only ๐จ๐ปโโ๏ธ
- `/broadcast` - send a broadcast message from the bot
- `/block` - block people for using your bot
- `/unblock` - unblock people you blocked for using your bot
- `/blocklist` - show the list of all people who's blocked for using your bot

### pm-permit ๐ฌ
- `.yes` - approve user for sending message to assistant
- `.no` - disapprove user for sending message to assistant

## ๐ Support Inline Search

## Heroku Deployment ๐
The easy way to host this bot, deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Railway Deployment ๐
For deployment on railway you can see the full of [Necessary Variables Here](https://github.com/HM-DRIVE/HM-MUSIC-BOT/blob/main/example.env), make sure you fill all of it.

[![Deploy+on+Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=&envs=SESSION_NAME,BOT_TOKEN,BOT_USERNAME,BOT_NAME,GROUP_SUPPORT,ASSISTANT_NAME,OWNER_NAME,OWNER_ID,DATABASE_URL,LOG_CHANNEL,BG_IMAGE,UPDATES_CHANNEL,API_ID,API_HASH,PMPERMIT,SUDO_USERS,DURATION_LIMIT,THUMB_IMG)

