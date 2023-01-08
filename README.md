#DISCORDBOT

Auto Chat Discord BOT


NOTE : RESIKO DITANGGUNG SENDIRI!

## • Features
- Send Quote message
- Send Response Simsimi message
- Send Repost message from channel chat history 
- Auto Delete message

## • Requirements
- Terminal / Termux
- Python3

## • Instalasi

```
pkg install python3
```
```
pkg install git
```
```
git clone https://github.com/arielzx03/discordbot.git
```
```
pkg install openssl
```
```
cd discordbot
```
```
pip install -r requirements.txt
```

```
nano config.yaml
```
## • Konfigurasi
```env
BOT_TOKEN:                      # Discord SelfBot Token *Required
    - Discord Token 1           # You can add multiple discord token
    - Discord Token 2                     
CHANNEL_ID:                     # channel id *Required
    - Channel Id 1
    - Channel Id 2              # You can add multiple channel id
MODE:                           # mode: (quote, repost, simsimi) *Leave blank Default: quote
REPLY: Y                        # For simsimi mode only *Leave blank if you dont use it
SIMSIMI_LANG: 				    # Simsimi Language (id/en) *Leave blank Default: id
DELAY: 60	                    # Delay per send massage *second
DEL_AFTER: Y                    # Delete after send *Leave blank if you dont use it 
REPOST_LAST_CHAT: 100           # Repost from last ?n chat in channel          
```
## • Cara Mendapatkan Token Discord

```
javascript:var i = document.createElement('iframe');i.onload = function(){var localStorage = i.contentWindow.localStorage;prompt('I AM ATOMIC!', localStorage.getItem('token').replace(/["]+/g, ''));};document.body.appendChild(i);
```

Buka Discord web, Copy Code diatas
Paste di bar Url


Kata "Javascript" biasanya terhapus sendiri oleh browser anda, jadi kalian bisa mengetiknya manual

## • Run BOT
```
python bot.py
```
## • MORE INFO
Cara Run bot dari awal jika termux / terminal di close
```
cd discordbot
```
```
Python bot.py
```

Cara mengganti id discord channel
Pastikan sudah di folder discordbot "cd discordbot"
```
nano config.yaml
```
Jika config sudah diatur, klik ctrl + s lalu ctrl + x

Done
## • Buy Me A Coffee?

BSC/EVM : 0x84352e6913317d82B1CE2dAf96EbF816aF48f843

SOL : tYx9QAvAABjendNELwaLpTgXEXgj9QaDjC61co7zR5F
