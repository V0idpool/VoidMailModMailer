# 📬 Void Mail Bot - Discord Mod Mail System 📬

![VoidMailBot](https://img.shields.io/badge/version-1.0.0-brightgreen)
![Release](https://img.shields.io/badge/Release-10%2F13%2F2024-blue)
<div align="center">
    <img src="https://raw.githubusercontent.com/V0idpool/Void_bot_DiscordBot_GUI/refs/heads/main/Void%20Bot%20Discord%20Bot%20Base%20(Standard)/vbotimage.png" alt="Void Mail Bot Logo" width="600"/>
</div>
---

## ⚙️ **Version**: 1.0.0 (Public Release)  
## 👨‍💻 **Author**: VoidBot Development Team ([@VoidPool](https://github.com/V0idpool))  
## ➕ **Add Void Mail Bot**: [Invite Void Mail Bot](https://discord.com/oauth2/authorize?client_id=1293727784044331048)  
## 📅 **Release Date**: 10/13/2024  

---

## 📖 **Description**  
Void Mail is a highly customizable Discord bot designed to manage mod mail systems, where users can directly message server staff through DMs, and staff can respond in designated mod mail channels within the server. This release focuses on seamless communication and efficient mod mail management, with MongoDB integration for logging mod mail conversations and server settings management.

---

## ⚙️ **Current Features**

- 📩 **Mod Mail System**: Users can message staff through DMs or the /modmail command, and staff can respond via mod mail channels within the server.
- 🗂️ **Automatic Mod Mail Logging**: Conversations are logged in a dedicated mod mail channel.
- ⚙️ **Slash Command Setup**: Easy configuration and setup through slash commands (`/setup`).

---

## 🔮 **Future Features (Subject to Change)**

- 📝 **Customizable Embed Messages**: Tailor mod mail notifications for your server.
- 🔍 **Enhanced Moderation Tools**: Additional moderation and logging features.
- ⚙️ **Improved User Interaction**: Advanced slash command handling for better customization and automation.

---

## 📌 **Notes**  

- 💻 This public release offers a full mod mail system with background task handling and MongoDB integration.
- ⚠️ **Setup Instructions**:  
  You need to configure the following settings before use:

  - Your bot’s token.
  - Your server ID.
  - MongoDB connection client URL and the name of your MongoDB cluster.
  - MongoDB database Collection names (Set these up in your DB cluster)

  After setting these up, use the `/setup` command to configure the mod mail channel. This saves the settings to MongoDB.

  Check out the [Discord.Net Docs](https://docs.discordnet.dev/) or refer to the code examples to further customize mod mail notifications, and other settings.

- ⚙️ The settings file (`UserCFG.ini`) is saved in the same directory as the bot. Use it to manually edit your bot’s settings, or primarily you can save the settings via the bots GUI.

- ❤️ Contributions and suggestions from the community are welcome! Help shape future releases of Void Mail Bot.

---

## 💡 **Support and Donations**  
- **Donate or Subscribe**: [Buy Me a Coffee](https://buymeacoffee.com/voidbot)  
- **Join the VoidBot Discord Support Server**: [Join for support, coding help, and more](https://discord.gg/nsSpGJ5saD)

---

## 📂 **Check out the GitHub!**  
[Void Mail Bot Source Code](https://github.com/V0idpool/VoidMailModMailer)
