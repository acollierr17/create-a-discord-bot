# Create A Discord Bot

[![Join the Discord](https://discordapp.com/api/guilds/480231440932667393/embed.png)](https://discord.gg/g7wr8xb)

Creating a Bot Application in Discord is easy! First, you need to go to the [Developer Dashboard](https://discord.com/developers/applications) and click "New Application."

![](https://i.imgur.com/BOxMrSJ.png)

Give a name for the application. This *does not* have to be the same name as your bot. However, you may give your client application and bot application the same name. Afterward, click create.

In this screenshot, there is the option to select a team for your application. Teams are optional for most cases. However, if you're looking to collaborate with other people, setting up a team and your application under that team is useful!

*Note: Make sure to read the [Discord API Terms of Service](https://discord.com/developers/docs/legal) to understand the usage of their API.*

![](https://i.imgur.com/ekM4z0w.png)

You are now at the "General Information" section of your application. You can name your application, provide a description as well as retrieve your application's ID and secret (used for OAuth2). You also can transfer your application to a Team and delete your application.

I suggest you find a suitable (and appropriate) icon that reflects your bot well. Along with that, provide a brief description of what your bot does.

On this page, you will also see a prompt labeled "Developer License." This purchasable license gives extra features for game developers on Discord. Read more about it [here](https://support-dev.discord.com/hc/en-us/articles/360027891611-Sell-Your-Game-on-Discord-How-to-do-it).

![](https://i.imgur.com/maJPClA.png)

After you finish the basics above, click on the "Bot" tab in the menu on the left. You're going to "Add Bot" and confirm the action by click "Yes, do it!" in the pop-up.

![](https://i.imgur.com/iV4jn2B.png)

![](https://i.imgur.com/CnShvPp.png)

You will now see the information regarding your newly created bot user. You can do a variety of things such as:  

* Change the bot's username and icon  
* Get your bot token or regenerate it  
* Change the visibility of your bot as well as its OAuth2 requirements  
* Privileged [Gateway Intents](https://discord.com/developers/docs/topics/gateway#gateway-intents)  
* Preview the integer for your bot's permissions  

On this page, you're going to grab your bot's by clicking the "Copy" button under "Token" or clicking "Click to Reveal Token" and copying that.

**IMPORTANT:** Do not **ever** share this bot token with unauthorized users or people you don't trust. **Ever**. Sharing your bot's token to a random person in your Discord server is the equivalent of giving someone the keys to your house and walking away. So keep your bot token safe at all times!

Someone who has your token has **full** control over your bot account's permissions and can do whatever they please with it. If you believe your token became compromised, I urge you to go back to your application in the [Developer Panel](https://discord.com/developer/applications) and click the "Regenerate" button. Follow the prompts to complete this process. Regenerating your token will automatically disconnect your bot from the Discord API.

![](https://i.imgur.com/25vM6GD.png)

Now you're going to want to invite your new bot to your server. The Discord Developer Dashboard has a built-in way to generate the link needed to invite your bot as well as set up the permissions you want.

When setting up your permissions, only choose the permissions your bot is going to need to be able to function fully. You don't need to go overkill, especially if it's a public bot. If it's a private bot or a development bot, then this isn't a big deal.

To generate the invite link, go to the "OAuth2" tab in the menu on the left; you can also look above the "Bot" tab. Under scopes, select "bot." You **must** choose this option to invite the bot to your server. You will see a URL show up at the bottom of the "Scopes" Dashboard.

![](https://i.imgur.com/07KWmx2.png)

Now under "Bot Permissions," select the permissions you wish to have preassigned to your bot upon inviting it. You can change these permissions at any time, so don't worry if you mess something up here. The permissions will automatically fill into the URL above.

After doing this, go back to the URL below the "Scopes" Dashboard. Simply click the "Copy" button to copy this to your clipboard.

![](https://i.imgur.com/ekvsEnh.png)

Open a new tab in your browser, paste this link in, and hit "Enter." You should see a page like the one below. Select your server from the dropdown menu under "Add Bot To" and click "Continue."

Also, confirm that you're signed in to the right Discord account by checking "Signed in as ...". Double-checking what account you're signed in as should solve any issues with not seeing your server in the dropdown menu and overall making sure you're doing things right.

![](https://i.imgur.com/J89N8wb.png)

On this page, if you pre-selected permissions in the Developer Dashboard, you can confirm them here. You can disable any permissions added here if need be, but you can't add new ones. You're going to need to do that in your Discord server (read more here).

If your permissions are correct, click "Authorize" to confirm the authorization process (your bot will join your server after completing the Captcha on the next page).

![](https://i.imgur.com/OReSg7d.png)

On this page, complete the Captcha. Afterward, you'll get a message that the authorization is complete. Your bot should now be on your server!

![](https://i.imgur.com/amQ6gtG.png)

![](https://i.imgur.com/Bc1Wgwv.png)

If you head over to your server, you invited the bot too, you'll see it in the member list!

My bot is online just for this guide. If you want more information on how to create a Discord bot and get it online, here are some communities you can get involved in:

* Nerd Cave Development: [YouTube](https://www.youtube.com/channel/UCI_HY3KnAH_VusYqFvL2U9g?view_as=subscriber) | [Discord](https://discord.gg/g7wr8xb) | [Website](https://thenerdcave.us)  
* MenuDocs: [YouTube](https://www.youtube.com/channel/UCpGGFqJP9vYvzFudqnQ-6IA) | [Discord](https://menudocs.link/discord) | [Website](https://menudocs.org)  

*Contact **anthony#8577** on Discord if you wish to be featured here*

![](https://i.imgur.com/5WVBqx0.png)