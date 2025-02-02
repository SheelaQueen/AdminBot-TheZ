# Admin Bot Commands

Total Commands: **64**

 

---
> Main Command | !panel

## 🛡️ Moderation Commands
- `!ban <user> [reason]`: Permanently ban a user  
- `!unban <user_id> [reason]`: Unban a user  
- `!kick <user> [reason]`: Kick a user from the server  
- `!mute <user> <duration> [reason]`: Temporarily mute a user  
- `!warn <user> [reason]`: Issue a warning to a user  
- `!clear <amount>`: Clear specified amount of messages  
- `!nuke [channel]`: Completely reset a channel  
- `!vcmute <user>`: Mute user in voice chat  
- `!vcunmute <user>`: Unmute user in voice chat  

---

## ⚙️ Management Commands
- `!lockdown [channel] [Min]`: Lock a channel | (optional) for a specified time  
- `!unlock [channel]`: Unlock a channel  
- `!slowmode <seconds>`: Set channel slowmode  

- `!announce <color (optional/HEX code!)> #channel <message with or no links>`: Send an announcement to a channel 

- `!addrole <user> <role>`: Add a role to a user  
- `!removerole <user> <role>`: Remove a role from a user  
- `!autorole <role>`: Automatically assign a role to new members - Toggle  
- `!autorole`: Show current autorole status  
- `!rolepanel`: Create a role panel for users to select roles 

- `!welcome`: Welcome panel (shows all settings)  

- `!automod <settings>`: Toggle automod features  

- `!automod spam_threshold <amount> <timeout/min>`: Set the spam threshold for automod | (optional) set timeout time 
- `!automod caps_threshold <amount>`: Set the caps threshold for automod
- `!automod add_whitelist <link>`: Whitelist a link
- `!automod add_banned_word`: Add a bad word to the automod
     
- `!setup`: Setup basic server settings  

- `!nickname <user_id> <nickname>`: Change the user's nickname  
- `!nickname <user_id>`: Remove the user's nickname  

- `!massrole <role>`: Add a role to all members 

- `!embed <title> <description>`: Create a custom embed message  
- `!say <channel> <message>`: Make the bot send a message  

- `!addchannel <channel> <user>`: Allows a user access to a channel  
- `!removechannel <channel> <user>`: Remove a user from a channel  

- `!invite <duration> <max uses>`: Create an invite link for a channel with customizable duration and max uses  
- `!invite_view`: Show all invite links and information about them  

---

## ℹ️ Information Commands
- `!serverinfo`: Display server statistics  
- `!userinfo [user]`: Show user information  
- `!roles`: List all server roles  
- `!stats`: Show bot statistics  
- `!activity <user>`: Check user activity status  
- `!servericon`: Show server icon in full size  
- `!poll <question> <option1> <option2>...`: Create a reaction poll  
- `!avatar [user]`: Show user's avatar in full size  
- `!ping`: Check bot's response time  

---

## 🎫 Ticket Commands | Got UI elements as well
- `!ticket [reason]`: Create a support ticket  
- `!close`: Close current ticket  
- `!add <user>`: Add user to ticket  
- `!remove <user>`: Remove user from ticket  
- `!ticketsetup <role>`: Setup what role sees tickets as admin  

---

## 💾 Backup Commands
- `!backup`: Creates basic structure backup (roles, channels, permissions)  
- `!backup true`: Creates full backup including messages (up to 100 messages per channel)  
- `!backup True 500`: Creates full backup with custom message limit (500 messages per channel in this example)  
- `!restore`: Restores a server from a backup file (attach the .json backup file with the command)  

---

## ⚙️ Configuration Commands
- `!exportconfig`: Export all server settings to a JSON file  
- `!importconfig`: Import server settings from a JSON file (attach the file)  

---

## 🎮 Fun Commands
- `!numbergame <number> <channel>`: Lets admins create a number game  
- `<number>`: Lets players guess the number in the chat it started  
- `!tictactoe`: Starts a tic-tac-toe game  
- `!joke`: Tells a random joke  

---

## 🔒 Owner Commands | More options UI based in discord channel.
- `!owner`: Opens a panel for owner-only commands  
- `!executecmd <guild_id> <channel_id> <command>`: Execute commands in other servers  
- `!leaveserver <guild_id>`: Make bot leave a specific server  
- `!botinfo`: View detailed bot statistics  

---


Small note: Script is intelligent meaning it got permissions to do all the commands. For example if u wnat to add someonne to a private channel u would need to have the manage_channels permission No user with a @everyone or a normal member role cant execute commands that need those permissions. But inforamtions commaands or the fun commands (excluded from starting a nubmer game that cna only do admins) backingn up the server cant be done by anyone. so its safe for u to add it and u can be sure that it cant be used against you. | By the way the small note got a bit bigger lol

[![Join My Discord](https://img.shields.io/badge/Join%20My%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](discord.gg/zsGTqgnsmK)


> #### |  If you are interested in that bot feel free to contact me
