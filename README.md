# Rust Player Count Bot

This bot will connect to rcon and display your player count of your server as a status message.

Example output from the bot 
https://gyazo.com/3f77e646e19b545854a20f846036fa22

## How to setup

1. Have [Node.JS](https://nodejs.org) installed.
2. Clone the repository onto your computer.
3. Open a terminal in that folder, and install the packages with `npm install`.
4. Open the `config.json` and add your server information.
5. Once the config is correct run start.bat and console window will pop up with the status messages as it updates discord.

## Config Help
1. SetTimeOut - How often do you want to refresh the playercount.
2. WipedTodayEnabled - Set weather you want "Wiped Today" to show.
3. WipedTodayHours - How many hours you want to show "WIPED TODAY" for after a wipe.
4. IP - Server IP unless you have a rcon IP set. By default you wont.
5. RconPort - Port you use for rcon.
6. RconPassword - Password you use to connect to rcon.
7. DiscordToken - Any discord bot token to display the playercount as the status.

