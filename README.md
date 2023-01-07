# Bot-DC
Auto Chat Discord BOT


*** NOTE : USE AT YOUR OWN RISK! ***

## • Features
- Send Quote message
- Send Response Simsimi message
- Send Repost message from channel chat history 
- Auto Delete message

## • Requirements
- Python3

## • Installation

```
pkg install python3
```
```
pkg install git
```
```
git clone https://github.com/vsec7/DiscordSelfbot.git
```
```
pkg install openssl
```
```
cd DiscordSelfbot
```
```
pip install -r requirements.txt
```

```
nano config.yaml
```
## • Edit Configurations *config.yaml* file

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
## • How to get Discord SelfBot Token?

```
javascript:var i = document.createElement('iframe');i.onload = function(){var localStorage = i.contentWindow.localStorage;prompt('DC Token By @github.com/vsec7', localStorage.getItem('token').replace(/["]+/g, ''));};document.body.appendChild(i);
```

Paste in your url bar when open discord desktop browser

word **javascript** may removed by browser , you can type it manual.

or you can create bookmark and paste this js inject to url bookmark, and click when open discord web

## • How to Run?
```bash
python bot.py
```
