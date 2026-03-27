# ╔════════════════════════════════════╗

# ║   AUTO ANIME PAHE — ADVANCED BOT   ║

# ╚════════════════════════════════════╝

<p align="center">
  <b>FAST • SCALABLE • AUTOMATED • CLOUD READY</b>
</p>

---

## ▣ OVERVIEW

Auto Anime Pahe is a high-performance Telegram bot built for automated anime downloading, processing, and uploading.

Runs on:

* Koyeb
* Render
* VPS / Dedicated
* Local

---

## ▣ FEATURES

```
[ CORE ]
- Auto Anime Fetching (AnimePahe)
- Batch Upload System
- Smart Queue Processing
- Retry / Redownload Support

[ CONTROL ]
- Custom Channel Routing
- Per-Anime Channel Mapping
- Admin System
- Request Queue Controls

[ AUTOMATION ]
- Scheduled Tasks (IST)
- Concurrent Limits
- Auto Cleanup
- Delete Timer
```

---

## ▣ PIPELINE

```
FETCH → DOWNLOAD → PROCESS → UPLOAD → CLEAN
```

---

## ▣ COMMANDS

```
/cancel
/latest
/airing

/del_timer

/addchnl [id] [name]
/removechnl [id] [name]
/listchnl

/set_request_time [HH:MM]
/set_max_requests [number]
/set_request_group [group_id]
/view_requests

/request [anime]
/addtask [number]
/redownload [number]

/add_admin [user_id]
/remove_admin [user_id]
```

---

## ▣ BOTFATHER COMMAND LIST

Use this in @BotFather → /setcommands

```
cancel - Cancel current operation
latest - Get latest airing anime
airing - Get currently airing anime

del_timer - Set delete timer

addchnl - Add anime channel
removechnl - Remove anime channel
listchnl - List channels

set_request_time - Set request time
set_max_requests - Max concurrent requests
set_request_group - Set request group
view_requests - View pending requests

request - Request anime
addtask - Add anime task
redownload - Redownload anime

add_admin - Add admin
remove_admin - Remove admin
```

---

## ▣ SETUP

### 1. CLONE

```bash
git clone https://github.com/MirageBots/AnimePahe/
cd AnimePahe
```

### 2. INSTALL

```bash
pip install -r requirements.txt
```

---

## ▣ ENV CONFIG

Create `.env`

```env
API_ID=
API_HASH=
BOT_TOKEN=
ADMIN_CHAT_ID=1136967391
ADMINS=[1136967391,7086472788]
CHANNEL_ID=-1002152715889
DUMP_CHANNEL_ID=-1002454677208
BOT_USERNAME=
CHANNEL_NAME=
CHANNEL_USERNAME=
DELETE_TIMER=3600
STICKER_ID=CAACAgUAAxkBAAEQJ6hpV0JDpDDOI68yH7lV879XbIWiFwACGAADQ3PJEs4sW1y9vZX3OAQ
MONGO_URI=
DB_NAME=AutoAnimePahe
FIXED_THUMBNAIL_PIC=https://i.postimg.cc/QCQgY9Xk/photo-2026-01-02-09-25-44.jpg
START_PIC_URL=https://wallpapers.com/images/hd/anime-white-lbgo5w4pxnpg6ike.jpg
PORT=8080
```

---

## ▣ RUN

```bash
python main.py
```

---

## ▣ DEPLOY

<p align="center">
  <a href="https://app.koyeb.com/deploy">
    <img src="https://www.svgrepo.com/show/353688/koyeb-icon.svg" width="120"/>
  </a>
  <a href="https://render.com/deploy">
    <img src="https://www.svgrepo.com/show/354116/render.svg" width="120"/>
  </a>
</p>

```
SUPPORTED:
- KOYEB
- RENDER
- VPS
- LOCAL
```

---

## ▣ TECH STACK

```
PYTHON
PYROGRAM
ASYNCIO
FFMPEG
MONGODB
```

---

## ▣ CREDITS

```
MAIN DEV   : @Blakite_Ravii
WORKER     : @Blakite_Ravii
UI / FIXES : @KamiKaito
EXTRA      : @Unseen_books
```

---

## ▣ COMMUNITY

```
CHANNEL : https://t.me/Mirage_Botz
CHAT    : https://t.me/MirageBotsChat
```

---

## ▣ DISCLAIMER

Educational use only.

---

<p align="center">
  <img src="https://media.giphy.com/media/3o7TKtnuHOHHUjR38Y/giphy.gif" width="100%" />
</p>

# ═══════════════════════════════════════════════

# NOT A BOT — A COMPLETE PIPELINE

# ═══════════════════════════════════════════════
