## About
Cyclone is a customizable Discord server bot that anyone can run!


## Replit Bot
It is recommended for beginners to run the bot on [replit](https://replit.com/).

To do this, create an account on replit then create a new project. Name it whatever you want, then click `Import from GitHub`, type github.com/cxgmc/cyclone-bot. Now you can create it.

Once you have created the project, select node.js as the language (on the right), and the run button should be **`node index.js`**


## Setup
To use Cyclone, you need to first create a bot.

### Create an Application
To create an application, go to the <a href="https://discord.com/developers/applications" target="_blank">Discord Developer Portal</a> and click `New Application` in the top right.

Give your application a nice name *(This will not be your bot's name)*

If you want, you can add an About Me section for your bot in the Description section of this page.

#### Creating the Bot
Click on `Bot`, then click on `Add Bot`, then `Yes, do it!`

Give your bot a nice name and icon.

In the Token section, click on `Copy`

Go to the `.env` file and where it says `TOKEN`, put your bots token.

> Example: `TOKEN=9182907147858274712893989184861829`

##### Find Your Guild ID

To find your server's Guild ID, you need to enable Developer Mode in User Settings > Advanced > Developer Mode

Right click on your server's icon on the left side, and click `Copy ID`.

##### Find A Channel's ID

Similar to finding a Guild ID, you need to right click on the channel's name and click `Copy ID`

Congrats! Your bot is now set up.

## Config

To configure your bot, go to the `config.toml` file in the root directory of your bot.

This is where you can customize everything about the bot. Let's begin by configuring the Rich Prescence (Bot's Activity/Game).

### Change Status
Go the [presence] section of the config, and change `status` to `"online"` `"idle"`, `"dnd"`, or `"offline"`.

#### Change AFK Status
Go the [presence] section of the config, and change `afk` to `true or `false`.

### Change Activity
Go the [presence] section of the config, and change `activity` to whatever you like. *(Make sure it's wrapped in quotes!)*

#### Change Activity Type
Go the [presence] section of the config, and change `activitytype` to `"STREAMING"` `"WATCHING"`, `"PLAYING"`, or `"COMPETING"`.

Congrats, you just configured your first part! The rest of the config is self-explanatory, and everything has comments on it explaining what it does and how to change it!
