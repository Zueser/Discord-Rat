# Discord-Rat
## Legal Disclaimer
This tool has been created for educational purposes only.

I am not responsible for its misuse.

## Features
- [x] clipboard
- [x] download
- [x] drives
- [x] help
- [x] ip
- [x] kill
- [x] msg
- [x] network
- [x] notify
- [x] ps
- [x] run
- [x] screenshot
- [x] tasklist
- [x] token
- [x] tree
- [x] type
- [x] user
- [x] webcam
- [x] keylogger

## Setup
The first step in getting this bot running is creating a Discord bot. This can be done by signing into Discord in your browser and then going to the [Discord Developers](https://discord.com/developers) webpage. After downloading the Python script, place the bot's token in the last line. You may also change the bot's prefix. To run the bot, you must have all of the required modules installed. This can be done by running ```pip install -r requirements.txt```. You may then run the script. After the word *Ready* flashes on the console window, the bot is up and running.

## Usage
For information about the command syntax, use ```$help``` followed by the name of the command to get a detailed description on what it does and how to use it. If you want to hide tne default console window, change the file extension to ```.pyw```.

## Security
This RAT has been written in Python, which is an interpreted language. This means that in order to run it, you either must have Python installed, or compile it with a tool such as Pyinstaller. However, be careful when doing this. If someone is to decompile it, they might be able to find your bot token, which would let them do absolutely anything with the bot account. This is why when inviting the bot to a server, it is best to only give it the permissions you need, such as reading and sending messages.
