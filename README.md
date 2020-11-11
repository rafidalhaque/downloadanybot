Assalamu Alaikum Wa Rahmatullah. Welcome to Github repo of [@downloadanybot](https://t.me/downloadanybot) Telegram bot.

# telegram-downloader-bot

A Telegram bot for file downloading automation 

If you have got an Internet connected computer or a NAS and you want to automate file downloading from Telegram channels, this bot is for you. You can share photos, audios, or small files with it and the bot will download them as well.

IMPORTANT: Telegram set up a limit to the size a bot can download (20Mb currently). If you plan to download big files, a bot will not work. Take a look on my alternative project:  https://github.com/alfem/telegram-download-daemon 

## Installation

Just create a new Telegram bot (https://core.telegram.org/bots), edit this script and fill in the fields: 

* TELEGRAM_BOT_TOKEN: the unique token that indentifies your bot 
* TELEGRAM_CHAT_ID: you user (or group) id in Telegram. If you do not know it, you can talk to @get_id_bot and send it a "/my_id" command  
* DOWNLOADS_FOLDER: Change the download directory is desired.

Thanks to [@mitto98](https://github.com/mitto98) contribution. You can use enviroment variables instead of editing the python file.

Install the python bot library, from Gihub (https://github.com/python-telegram-bot/python-telegram-bot) or using pip ( https://pypi.python.org/pypi/python-telegram-bot/). There are many telegram modules around. Do not use another one with a similar name.

Also "request" module is needed. It is very popular and probably you have it installed already. If not, just use pip or your system package manager.

## Usage

Run the script (or the Docker container) and talk to your new bot!

You can:

* Copy a file or photo post from a channel and share it with your downloader bot
* Say "?" to your bot to check how many downloads are waiting in its queue
* Say "quit" to stop the bot

## Note 

It is clone from https://github.com/alfem/telegram-downloader-bot 