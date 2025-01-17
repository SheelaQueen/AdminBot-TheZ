# AdminBot Features Documentation

AdminBot is a comprehensive and robust Discord bot designed to manage and enhance server experiences. Below is a detailed feature breakdown, comparing AdminBot to popular alternatives like MEE6, Dyno, and Carl-Bot.

## Feature Comparison

| Feature                                | AdminBot | MEE6 | Dyno | Carl-Bot |
|----------------------------------------|----------|------|------|----------|
| **Moderation Commands**                | ✅        | ✅    | ✅    | ✅        |
| - Ban/Kick/Warn                        | ✅        | ✅    | ✅    | ✅        |
| - Clear Messages                       | ✅        | ✅    | ✅    | ✅        |
| - Mute with Duration                   | ✅        | ❌    | ✅    | ✅        |
| **Advanced Logging**                   | ✅        | ❌    | ❌    | ✅        |
| - Action Logging (Bans, Mutes, etc.)   | ✅        | ❌    | ❌    | ✅        |
| - Ticket Transcript Logging            | ✅        | ❌    | ❌    | ✅        |
| **Ticket System**                      | ✅        | ❌    | ❌    | ✅        |
| - Button-based Claim and Close         | ✅        | ❌    | ❌    | ✅        |
| - Add/Remove Users in Tickets          | ✅        | ❌    | ❌    | ✅        |
| - Ticket Logs                          | ✅        | ❌    | ❌    | ✅        |
| **Server Management Tools**            | ✅        | ✅    | ✅    | ✅        |
| - Lockdown/Unlock Channels             | ✅        | ✅    | ✅    | ✅        |
| - Slowmode Configuration               | ✅        | ❌    | ✅    | ✅        |
| - Announcement Command                 | ✅        | ❌    | ✅    | ✅        |
| **Dynamic Status Updates**             | ✅        | ❌    | ❌    | ❌        |
| - Rotating Status Messages             | ✅        | ❌    | ❌    | ❌        |
| - Status Reflecting Server Stats       | ✅        | ❌    | ❌    | ❌        |
| **Custom Commands/ for People who know how to customize the code**                    | ❌/ ✅    | ❌    | ✅    | ✅        |
| **Embed Message Customization**        | ✅        | ❌    | ❌    | ✅        |
| - Customizable Colors and Fields       | ✅        | ❌    | ❌    | ✅        |
| **Role Management with Panels**        | ✅        | ❌    | ❌    | ✅        |
| - Reaction-based Role Assignment       | ✅        | ❌    | ❌    | ✅        |
| **Welcome System (Highly Configurable)**| ✅        | ❌    | ❌    | ✅        |
| - Placeholders for User/Server Details | ✅        | ❌    | ❌    | ✅        |
| - Configurable Welcome Message         | ✅        | ❌    | ❌    | ✅        |
| **Auto-Moderation**                    | ✅        | ❌    | ✅    | ✅        |
| - Caps/Spam/Banned Word Detection      | ✅        | ❌    | ✅    | ✅        |
| - Configurable Thresholds              | ✅        | ❌    | ✅    | ✅        |
| **Activity and Member Tracking**       | ✅        | ❌    | ❌    | ❌        |
| - Server/Member Stats                  | ✅        | ❌    | ❌    | ❌        |
| - User Information Commands            | ✅        | ❌    | ❌    | ❌        |
| **Free and Open Source**               | ✅        | ❌    | ❌    | ❌        |
| **Pricing**                            | Free     | Freemium | Freemium | Freemium |

---

## Detailed Feature Breakdown

### 1. Moderation Commands
AdminBot provides a full suite of moderation tools to keep your server safe:
- `!ban <user> [reason]`: Permanently ban a user.
- `!kick <user> [reason]`: Remove a user from the server.
- `!mute <user> <duration> [reason]`: Temporarily mute a user with a specified duration.
- `!warn <user> [reason]`: Issue warnings to members.
- `!clear <amount>`: Bulk delete messages in a channel.

### 2. Advanced Logging
Keep track of server activities with detailed logs:
- Moderation actions such as bans, kicks, mutes, and warnings are logged.
- Ticket logs, including transcripts, are automatically saved in a dedicated `#ticket-logs` channel.

### 3. Ticket System
AdminBot offers a robust ticketing system for user support:
- Button-based interaction for claiming and closing tickets.
- Add or remove users dynamically to collaborate on resolving issues.
- Automatic logging and transcription of ticket discussions.

### 4. Server Management Tools
Enhance server management with powerful tools:
- `!lockdown [channel]`: Restrict sending messages in a channel.
- `!unlock [channel]`: Reopen a previously locked channel.
- `!slowmode <seconds>`: Set a cooldown between messages.
- `!announce <color/hex code> <channel> <message>`: Create a server announcement if u put in links it will also create a seperate message wit ha overwief of the lniks u put inthe message.

### 5. Dynamic Status Updates
Keep your server engaged with rotating status updates:
- Customizable status messages reflecting server stats like member count and activity.

### 6. Role Management
Streamline role assignment with:
- Reaction-based role panels for self-assignment.
- Commands like `!addrole <user> <role>` and `!removerole <user> <role>` for admins.

### 7. Welcome System
Customize user onboarding:
- Placeholders like `{user}`, `{server}`, and `{count}` allow personalized welcome messages.
- Commands to configure the color, channel, and content of welcome messages.

### 8. Auto-Moderation
Ensure a safe environment with automated moderation:
- Detection of caps, spam, and banned words with configurable thresholds.
- Flexible settings to suit different server needs.

#### Automod Commands:
- `caps_threshold`: Configure the tolerance for caps in messages.
- `spam_threshold`: Set the number of repeated messages to trigger spam detection.
- `spam_interval`: Define the time window for spam detection.
- `banned_words`: Add or remove words for automated filtering.
- `link_whitelist`: Manage a list of allowed links.

### 9. Information and Analytics
Gain insights into server and user activity:
- `!serverinfo`: Display server stats like member count and creation date.
- `!userinfo [user]`: Retrieve detailed information about a user.
- `!roles`: List all server roles and their member counts.
- `!stats`: Show bot statistics including uptime and server count.

---

## Complete Command List

### Moderation Commands
- `!ban <user> [reason]`
- `!kick <user> [reason]`
- `!mute <user> <duration> [reason]`
- `!warn <user> [reason]`
- `!clear <amount>`
- `!nickname <user_id> <nickname>`

### Server Management Commands
- `!lockdown [channel]`
- `!unlock [channel]`
- `!slowmode <seconds>`
- `!announce <message>`
- `!addrole <user> <role>`
- `!removerole <user> <role>`
- `welcome` | **Lets you configure the welcome message/color/channel etc.**

### Ticket System Commands
- `!ticket [reason]`
- `!add <user>`
- `!remove <user>`
- `!close`

- `Also u got clickable elements to claim a ticket/closing`

### Information Commands
- `!serverinfo`
- `!userinfo [user]`
- `!roles`
- `!stats`

### Automod Configuration


- `caps_threshold`
- `spam_threshold`
- `spam_interval`
- `banned_words`
- `link_whitelist`


### usage:
- `!automod <configuration> <value>`
### Example: 
    - !automod caps_threshold 5
    - !automod spam_threshold 3

    - !automod banned_words FUCK
    - !automod link_whitelist https://www.google.com

---

We got a lot of features as u can see and you know whats crazy? we got over 1600+ banned words and u can add more if u want.

made by TheZ
