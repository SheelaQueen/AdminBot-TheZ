Fixed bugs:
 - Datetime errors
 - URL not found error Fixed
 - commands did not respond correctly
 - !setup Hirarchy errors


Added: 
 - view_historic command | lets u see who joined with what invite link
 - Script now handles server without icons
 - script now handles bots with no icons
 - script now handles user with no avatars
 - Snipe commands
   - !editsnipe
   - !snipe

 - added a better !setup 
   - Creates a full discord with channels, locked channels, roles with specific permissions andd hirachy

            "📜 Information": ["📌 rules", "📢 announcements"],
            "💬 General": ["💬 general-chat", "😂 memes"],
            "🔒 Admin Only": ["🔧 admin-chat", "📜 admin-logs"],
            "🤖 Bot Commands": ["⌨️ bot-commands", "📝 bot-logs"],
            "🎤 Voice Channels": ["🎤 General VC", "🎶 Music VC"],
            "🎮 Gaming": ["🎮 gaming-chat", "🕹️ game-logs"],
   - Roles
      - Owner, Bot (owner-level), member, admin, mod, bot (locked-down)
 

 Updated: 
  - Way more secure owner only access
  - enhanced security overall
  


Ignore:
 - webhook nonetype error 
   - You can just ignore it that will work just fine

 - cog was never awaited errors 
   - You can ignore that too


## NOTE

**!view_historic Command Limitations**

The !view_historic command tracks invite usage and member joins only after it has been enabled. It cannot retroactively track members who joined before the command was activated. This is because Discord does not store historical data about which invite was used when a member joined. As a result, the command can only provide data for future joins, not past ones.

**Key Points:**

1. No Historical Data:
  - Discord does not save information about which invite was used for members who joined before the bot started tracking.

2. Future Tracking Only:
  - The command will only track invite usage and member joins from the moment it is enabled onward.

3. Real-Time Tracking:
  - For accurate data, ensure the bot is active and tracking invites when new members join.