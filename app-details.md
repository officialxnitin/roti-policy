# R.O.T.I

## Application Details

### What does your application do? Please be as detailed as possible, and feel free to include links to image or video examples

R.O.T.I is a ultimate bot which focuses on moderation, fun, and utility.

- **Moderation**: It helps in moderating the server by providing a variety of commands like `warn`, `timeout`, `removetimeout`, `kick`, `ban`, `unban`,`massban`, `raidban` and more.

- **Automod**: It help to keep the server clean by providing variety of options like filtering message content, filtering links, invite links filtering, filtering mentions, filtering emojis, and a lot more.

- **Management**: It help managing the server by providing variety of commands like

  - creating/deleting roles, emojis, stickers and more.
  - deleting bulk amount of messages,
  - locking/unlocking channels, add slowmode to channels,
  - change nickname, welcoming new members, etc
  - log all the actions of the server in a channel.

- **Other**: Host giveaway, play games, setup starboard, etc

## Data Collection

### Tell us more about the data you store and process from Discord

#### WHAT DISCORD DATA DO YOU STORE?

- role ids, channel ids are stored in the database for rection role, button role, logging, welcome message and more.
- Guild ids are stored to provide different settings per guild.
- User ids for afk command, ignoring automod for selected users. etc.

#### DO YOU STORE MESSAGE CONTENT?

- When configuring settings we collect some message content and store it in the database for future use. For example, we take welcome channel, role, inputs as message content and store it.

#### FOR WHAT PURPOSE(S) DO YOU STORE THE INFORMATION YOU COLLECT?

- We store channels ids for logging, welcoming, starboard, suggestion, ticket and more.
- We store role ids for reaction role, button role, select role, etc
- We store guild ids to provide different settings per guild.
- We store user ids for afk command, ignoring automod for selected users. etc.

### FOR HOW LONG DO YOU STORE IT?

- Some data are stored for a very short period of time. For example, we store afk data until that user comes back.
- Some data are stored permanently. For example, we store guild settings permanently. For most of the data, user can delete them anytime using the same commands.

### WHAT IS THE PROCESS FOR USERS TO REQUEST DELETION OF THEIR DATA?

- User can delete their most of the data by using commands. But we permanently store some data and if anyone wants to delete them they need to join our support server and ask us to delete. We will delete the data within 48 hours.

## Infrastructures

### HOW DO YOU HOST YOUR BOT?

### WHAT LANGUAGE OR LIBRARY WAS YOUR BOT WRITTEN WITH?

Bot is written in nodejs v16.13.2
Library used is discord.js v13.6.0

### HOW DO YOU KEEP YOUR BOT SECURE?

### HOW CAN USERS CONTACT YOU WITH SECURITY CONCERNS AND OTHER QUESTIONS REGARDING YOUR BOT?

User can use our `report` command or join our support server and talk with us.

### WHICH INTENTS ARE YOU APPLYING FOR, IF ANY? (LEAVE BLANK IF YOU DO NOT NEED ANY OF THESE)

1. Server members intent
2. Message content Intent
