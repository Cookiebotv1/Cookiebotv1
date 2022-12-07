<div align="center">


# Cookie 

> Cookie is a multipurpose WhatsApp bot using wa-automate-nodejs library!
>
>

<h3 align="center">Made with cookie 
<p align="center">
 


<p align="center">
  <a href="https://github.com/SlavyanDesu"><img title="Author" src="https://img.shields.io/badge/Author-SlavyanDesu-purple.svg?style=for-the-badge&logo=github" /></a>
</p>

# Installation
## 📝 Cloning this repo
```cmd
> git clone https://github.com/SlavyanDesu/BocchiBot.git
> cd
```

## ✍️ Editing the file
Edit the required value in `config.json`.
```json
{
    "ownerBot": "62812xxxxxxxx@c.us", 
    "prefix": "$",
    "uaOverride": "WhatsApp/2.2037.6 Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.83 Safari/537.36",
    "nao": "api-key",
    "vhtear": "api-key",
    "melodic": "administrator",
    "tobz": "BotWeA",
    "lol": "api-key",
    "authorStick": "@🦋",
    "packStick": "cookie"
}
```

`
## 🔍 Installing the dependencies
```cmd
> npm install
```

## 🆗 Running the bot
Regular node:
```cmd
> npm start
```

PM2:
```cmd
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```cmd
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

After that scan the QR code using your WhatsApp in your phone!

# Known issue
## ESM error
To prevent this, please use `node-fetch` and `parse-ms` with v2.x version.
```cmd
> npm install node-fetch@2.6.5
> npm install parse-ms@2.1.0
```

# Features
If you want to unlock premium commands, please buy me a coffee at least 1 on Ko-fi platform.

|     Deploy       |  Availability  |
| :--------------: | :------------: |
| Heroku           |       ✔️       |
| Local            |       ✔️       |

|     Leveling     |  Availability  |
| :--------------: | :------------: |
| Leveling         |       ✔️       |

|     Sticker Maker     | Availability |
| :-------------------: | :----------: |
| Send/reply image      |      ✔️      |
| Send/reply GIF        |      ✔️      |
| Send/reply MP4        |      ✔️      |
| Text to sticker       |      ✔️      |
| Text to sticker GIF   |      ✔️      |
| Sticker to image      |      ✔️      |
| Sticker WM            |      ✔️      |
| Take sticker          |      ✔️      |

|      Downloader     | Availability |
| :-----------------: | :----------: |
| Facebook video      |      ✔️      |
| YouTube audio/video |      ✔️      |
| Joox musics         |      ✔️      |
| TikTok video        |      ✔️      |
| TikTok profile pic  |      ✔️      |
| Twitter video/image |      ✔️      |
| Instagram post      |      ✔️      |
| Instagram story     |      ✔️      |
| LK21                |      ✔️      |
| TikTok no WM        |      ✔️      |

|         Misc         | Availability |
| :------------------: | :----------: |
| OCR (Image to Text)  |      ✔️      |
| Say                  |      ✔️      |
| Search lyrics        |      ✔️      |
| Shortlink maker      |      ✔️      |
| Wikipedia (EN)       |      ✔️      |
| Wikipedia (ID)       |      ✔️      |
| KBBI scarper         |      ✔️      |
| Stalk IG account     |      ✔️      |
| GSMArena scraper     |      ✔️      |
| Search food receipts |      ✔️      |
| YouTube search       |      ✔️      |
| Text to speech       |      ✔️      |
| AFK                  |      ✔️      |
| Distance calculator  |      ✔️      |
| Sticker search       |      ✔️      |
| Calculator           |      ✔️      |
| Al-Qur'an surah      |      ✔️      |
| List surah           |      ✔️      |
| Random contact       |      ✔️      |
| YouTube play         |      ✔️      |
| Whois                |      ✔️      |
| SMS gateway          |      ✔️      |
| Al-Qur'an tafseer    |      ✔️      |
| Al-Kitab search      |      ✔️      |
| LK21 scraper         |      ✔️      |
| Reminder             |      ✔️      |
| Image uploader       |      ✔️      |
| Sholat schedule      |      ✔️      |
| Latest Line stickers |      ✔️      |
| Check postage        |      ✔️      |
| Sending email        |      ✔️      |
| Random quotes        |      ✔️      |
| Genshin chara info   |      ✔️      |
| Bass boost           |      ✔️      |

|          Fun          | Availability |
| :-------------------: | :----------: |
| Weton jodoh           |      ✔️      |
| Horoscope             |      ✔️      |
| Harta tahta maker     |      ✔️      |
| Writing text maker    |      ✔️      |
| Glitch text maker     |      ✔️      |
| SimSimi chatbot       |      ✔️      |
| Blackpink logo maker  |      ✔️      |
| Pornhub logo maker    |      ✔️      |
| Galaxy text maker     |      ✔️      |
| Truth or dare         |      ✔️      |
| Asupan TikTok         |      ✔️      |
| PH comment maker      |      ✔️      |
| Triggered maker       |      ✔️      |
| Kiss image maker      |      ✔️      |
| 3D text maker         |      ✔️      |
| Freefire logo maker   |      ✔️      |
| Freefire banner maker |      ✔️      |
| Sliding text maker    |      ✔️      |
| Hero ML maker         |      ✔️      |
| Fire text maker       |      ✔️      |
| Couple balloon maker  |      ✔️      |
| Wasted maker          |      ✔️      |
| Cakl Lontong quiz     |      ✔️      |
| Hilih-ify text        |      ✔️      |
| Tebak gambar quiz     |      ✔️      |
| Random doge stickers  |      ✔️      |
| Dice                  |      ✔️      |

|       Weeb Zone       | Availability |
| :-------------------: | :----------: |
| Random neko girl      |      ✔️      |
| Random wallpaper      |      ✔️      |
| Random kemonomimi     |      ✔️      |
| Kusonime scraper      |      ✔️      |
| Komiku scraper        |      ✔️      |
| Random Video Loli     |      ✔️      |
| Anime tracer          |      ✔️      |
| Source finder         |      ✔️      |
| Random waifu pics     |      ✔️      |
| Anitoki latest update |      ✔️      |
| Random anime stickers |      ✔️      |
| Neonime latest update |      ✔️      |
| Anoboy on-going list  |      ✔️      |
| Search character      |      ✔️      |
| Sticker keywords      |      ✔️      |

|        Bot       | Availability |
| :--------------: | :----------: |
| Server usage     |      ✔️      |
| Blocked list     |      ✔️      |
| Ping             |      ✔️      |
| Delete messages  |      ✔️      |
| Bug report       |      ✔️      |
| Join group       |      ✔️      |
| Check serials    |      ✔️      |

|        Owner       | Availability |
| :----------------: | :----------: |
| Broadcasting       |      ✔️      |
| Clear all messages |      ✔️      |
| Leave all groups   |      ✔️      |
| Get snapshot       |      ✔️      |
| Ban                |      ✔️      |
| Eval               |      ✔️      |
| Shutdown           |      ✔️      |
| Add premium user   |      ✔️      |
| Set bot's info     |      ✔️      |
| Mute bot           |      ✔️      |
| Block              |      ✔️      |
| Unblock            |      ✔️      |

|    Moderation    | Availability |
| :--------------: | :----------: |
| Add              |      ✔️      |
| Kick             |      ✔️      |
| Promote          |      ✔️      |
| Demote           |      ✔️      |
| Leave bot        |      ✔️      |
| Everyone         |      ✔️      |
| Toogle NSFW      |      ✔️      |
| Set group icon   |      ✔️      |
| Anti-group link  |      ✔️      |
| Toogle welcome   |      ✔️      |
| Auto-sticker     |      ✔️      |
| Mute group       |      ✔️      |
| Anti-NSFW link   |      ✔️      |
| Anti-porn        |    Premium   |

|        NSFW        | Availability |
| :----------------: | :----------: |
| Lewds              |      ✔️      |
| nHentai lookup     |      ✔️      |
| Fetish             |      ✔️      |
| Latest Nekopoi     |      ✔️      |
| Pornhub downloader |      ✔️      |
| Waifu 18+          |      ✔️      |
| Yuri               |      ✔️      |
| Femdom             |      ✔️      |
| Lewd avatars       |      ✔️      |
| nHentai search     |      ✔️      |
| nHentai downloader | Premium/Free |
| Multi-lewds        |    Premium   |
| Multi-fetish       |    Premium   |

# Thanks to
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* [`YogaSakti/imageToSticker`](https://github.com/YogaSakti/imageToSticker)
* [`uukina`](https://github.com/uukina)
* [`MrPawNO`](https://github.com/MrPawNO)
* [`Pahri123`](https://github.com/Pahri123)
* [`LeviathanH`](https://github.com/LeviathanH)
* [`ferlitopym`](https://github.com/ferlitopym)
* [`AlvioAdjiJanuar`](https://github.com/AlvioAdjiJanuar)
* [`VideFrelan`](https://github.com/VideFrelan)
* [`VirusLauncher`](https://github.com/VirusLauncher)
* [`Sansekai`](https://github.com/Sansekai)
* [`Baguettou`](https://github.com/Baguettou)
* [`HAFizh-15`](https://github.com/HAFizh-15)
* [`TheSploit`](https://github.com/TheSploit)
* [`rashidsiregar28`](https://github.com/rashidsiregar28)
* [`irham01`](https://github.com/irham01)
* [`hardiantojek93`](https://github.com/hardiantojek93)
* [`gamingrkp`](https://github.com/gamingrkp)

# License
**BocchiBot** © [SlavyanDesu](https://github.com/SlavyanDesu), released under the MIT License.
Authored and maintained by SlavyanDesu.

<p align="center">
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FSlavyanDesu%2FBocchiBot?ref=badge_large"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FSlavyanDesu%2FBocchiBot.svg?type=large" />
</p>
