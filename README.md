# Roastify

The DiscordJS based roasting bot that could roast the shit out of people, now with slash commands! All roasts are community-created and approved, and racial slurs, gender-based-insults, or similiar things are not tolerated.

# How to use

To use the bot, follow the given steps:

1. ## Add the bot

Fistly, you would have to add the bot to your server. To do this, click [here](https://discord.com/api/oauth2/authorize?client_id=856054827276435466&permissions=2147765312&scope=bot) and authenticate with your discord account (needs escalated privilages in the server)

1. ## Check if the bot is reachable

Use the following command with this prefix to check if the bot is working:

```txt
r!ping
```

This would return a message `@mention, pong!`

1. ## That's It!

You've successfully added the bot, next up, using the bot

# Bot Commands

Use the following commands in this manner `r!<command> <arguments>`

Command | Description
roast <name> | Roast the shit out of people, selects a random roast from community-contributed roasts
ping | Check if the bot is online and reachable
meme <number of memes (5 max)> | Send a random meme from a random (safe) subreddit

# How to contribute

To add a roast of your choice, first fork this repo by clicking on the fork button at the top (two branches splitting upwards icon), then go to your fork, and [clone the repo in the usual way](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository)

Then add a roast (or multiple roasts) in a new line in the [`insults.txt`](https://github.com/SnazzyCoder/Roastify/blob/main/insults.txt) file. While changing, please ensure that:

- You do not change or modify pre-existing roasts, and if you want to, you would have to create a new pull request (see next section)
- You do not add a 