# dyno-status
A Discord Bot which will show the real-time status of Dyno

## Installation and Startup

1) Clone the repository
2) Node 10 is required, so head to the [Node.js download page](https://nodejs.org/en/) and download/install the LTS version
3) Run `npm install` to install the dependencies (Eris and Axios)
4) Create a new bot application (see [Creating a bot account](#creating-a-bot-account))
5) Open `config.json` and set your desired channel ID for the status to go to
6) Start the bot

### Creating a bot account
1) Head to to [Discord Developer Portal](https://discordapp.com/developers/applications/)
2) Press New Application, call it whatever you want to name your bot
3) Head to the Bot tab, Add Bot
4) Copy the bot token - **__DO NOT SHARE THIS WITH ANYONE__**
5) Put the bot token in between the `''` on the first line of `index.js`, save
6) Head back to the Developer Portal, open the OAuth2 tab
7) Under `Scopes`, tick only the `bot` option
8) Give the bot `Send Messages` and `Embed Links` **IMPORTANT!**, the rest of the permissions are optional
9) Copy the URL, then invite the bot to your desired server

## Disclaimer

 - Although I am a Trusted member of Dyno, Dyno has no affiliation or relation with this project in any way. This was my own personal project, and I may remove this repository at the developer's request.
 - The bot was built on Node.js 10.16.0 LTS. I will support Node versions 10+, however if bugs occur on versions below Node 10, I will not fix them. However, if you wish to fix any bugs relating to this, feel free to make a PR.

## Release History

- 0.0.1 Initial Release