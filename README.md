# 🤖 WhoToBan?

A powerful Discord moderation and utility bot with advanced security features and comprehensive server management tools.

# ✨ Features

# 🛡️ Security & Moderation
- **User Risk Assessment** - Analyzes account age and flags suspicious users
- **Auto Member Monitoring** - Alerts when new members join with risk levels
- **Moderation Tools** - Kick, ban, and message clearing capabilities
- **Permission Checks** - Ensures only authorized users can use mod commands

# 📊 Server Information
- **Server Statistics** - Member count, creation date, boost level
- **User Profiles** - Detailed user information and avatars
- **Real-time Data** - Live server and member statistics

# 🌐 Internet Search
- **Multi-Platform Search** - Searches across 15+ major platforms
- **Comprehensive Results** - Google, Reddit, YouTube, GitHub, and more
- **Instant Links** - Direct access to search results

# ⚡ Utility Commands
- **Ping/Latency** - Check bot response time
- **Help System** - Complete command documentation
- **Slash Commands** - Modern Discord slash command interface

# 🚀 Commands

| Command | Description | Permissions |
|---------|-------------|-------------|
| `/check <user>` | Check user risk level | Everyone |
| `/info <user>` | Get detailed user information | Everyone |
| `/ping` | Check bot latency | Everyone |
| `/members` | Show server member statistics | Everyone |
| `/serverinfo` | Display comprehensive server info | Everyone |
| `/datamine <query>` | Search across multiple platforms | Everyone |
| `/avatar <user>` | Display user's avatar | Everyone |
| `/kick <user> <reason>` | Kick a member | Kick Members |
| `/ban <user> <reason>` | Ban a member | Ban Members |
| `/clear <amount>` | Delete messages (max 100) | Manage Messages |
| `/help` | Show all available commands | Everyone |

# Prerequisites
- Python 3.8+
- discord.py library
- Discord Bot Token

# Invite Link Generation
Use Discord's OAuth2 URL Generator with these scopes:
- `bot`
- `applications.commands`

Required permissions:
- Send Messages
- Use Slash Commands
- Embed Links
- Read Message History
- Manage Messages
- Kick Members
- Ban Members

# 📋 Risk Assessment System

WhoToBan? automatically evaluates new members based on account age:

- 🚨 **ULTRA SUSPICIOUS** - Account created today
- 🚨 **SUSPICIOUS** - Account less than 7 days old
- ⚠️ **CAUTION** - Account less than 30 days old
- ✅ **SAFE** - Account 30+ days old

# 🔒 Security Features

- **Permission Validation** - Commands check user permissions before execution
- **Error Handling** - Comprehensive error management and user feedback
- **Rate Limiting** - Built-in Discord API rate limit compliance
- **Secure Token Handling** - Token should be stored as environment variable in production

# Privacy Policy
WhoToBan? collects minimal data necessary for functionality:
- Discord user IDs and usernames
- Server information and member lists
- Command usage for debugging
- No personal messages or private data stored

# 📞 Support

- **Discord**: hrishitkhare
- **Email**: hrishitkhare4@gmail.com

# 📄 License

ALL RIGHTS ARE RESERVED FOR THE BOT AND THE SOURCE CODE OF THE BOT

## ⚠️ Disclaimer

This bot is provided "as is" without warranties. Users are responsible for compliance with Discord's Terms of Service and all applicable laws. The bot owner is not liable for any misuse or damages.

**Made with ❤️ for Discord communities by Hrishit Khare / F(ox)Safety**
