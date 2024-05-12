# Introducing 🤖BubsBot🤖 for Your Discord Server

🤖BubsBot🤖 is a specialized Discord bot, meticulously crafted to enhance the management and moderation of your server. It is equipped with the capability to automatically delete messages that contain "@everyone" or "@here" from non-admin users, ensuring a spam-free environment for your community. 

In addition, it enforces discipline by timing out non-admin users who send such messages, for a duration of 24 hours. This feature acts as a deterrent, promoting a respectful and orderly communication within your server. 

With 🤖BubsBot🤖, experience a seamless, secure, and superior server management like never before.

## Adding 🤖BubsBot🤖 to Your Server

To add 🤖BubsBot🤖 to your Discord server, you'll need to follow these steps:

### 🤖Bot Token:🪙
- (a) The developer of 🤖BubsBot🤖 will `NOT` provide you with a bot token. This token allows the bot to authenticate with Discord's API and perform actions on your server.
- (b) You need to replace the `DISCORD_BOT_TOKEN` in the `bubsbot.py` file with your bot's token.

### 🔗Invite Link:🔗
- (a) The developer `will provide you with an invite link` for the bot. Use this link to invite the bot to your Discord server.

### Timeout Role:
- (a) Create a role on your Discord server for timing out users. This role should have no permissions. 
- (b) The role name should be called: `Timeout Role`
- (c) For The `Timeout Role` : **View Channel** , **Disable Send Messages** , **Enable Read Chat History**
- (d) Make Sure To add The `Timeout Role` to every channel in your discord server. Make sure to set the `Timeout Role` for each channel, **🚨you will have to do that!!🚨**

### 🤖Bot Configuration:⚙️
- (a) Once the bot is added to your server, it is set to run as intended. No modifications to the `bubsbot.py` file are allowed as they may affect its functionality.
- (b) The bot's command prefix and the name of the timeout role are pre-configured and should not be changed to ensure the bot works properly.
- (c) The `/test` command is specifically designed to work only for the server owner or users with the ADMIN role. No additional configuration is necessary for this command.

       copy & paste for role ->  SERVER OWNER/ADMIN   <- copy & paste for role

- (d) If you need to make any changes or adjustments, please contact the developer. Unauthorized modifications are not allowed and may lead to the bot malfunctioning.

### 🤖Bot Commands:🎮
- `/daily`: Use this command to claim your daily rewards in the form of coins.
- `/coins`: Use this command to check the total number of coins you have accumulated.
- `/change_status`: Use this command to change the bot's status for the server. This command is only available to the server owner or users with the ADMIN role.
- The bot also has built-in anti-spam features. Users who spam or misuse the `@everyone` or `@here` commands will be timed out for 24 hours. `This does not affect users with the SERVER OWNER/ADMIN role or the server owner.` After the timeout period, the bot will automatically remove the user from timeout.

Please note that these commands are case-sensitive and should be used exactly as shown.

### 🏃‍♂️Run the Bot:🤖
- (a) Once everything is set up, the developer will run the bot on your server and monitor its performance. If you encounter any issues or have further requests, communicate them to the developer for assistance.

### 🆘Contributing🆘
Contributions to 🤖BubsBot🤖 are always welcome! If you have ideas for improvements, bug fixes, or new features, feel free to contribute by forking the repository, making your changes, and submitting a pull request.

### License

This project is licensed under a proprietary license. All rights are reserved by the author. You are allowed to use and share the bot, but `Modifications are NOT` allowed. For any changes, please contact the developer. Unauthorized distribution of this project is prohibited.