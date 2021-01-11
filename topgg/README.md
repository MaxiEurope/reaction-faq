<p align="center">
    <a href="https://github.com/MaxiEurope/reaction-faq">
        <img src="https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/reaction.png" width="128" height="128">
    </a>
</p>

<h1 align="center">Reaction bot🎉 - FAQ</h1>
<p align="center">Reaction bot is the best utility bot for OwO - stats, zoo calculator, reminders, quest system, and much more!
    <br>
    <br>
    <a href="https://discord.gg/KwfCk7r">Support server</a>
    ·
    <a href="https://discord.com/oauth2/authorize?client_id=519287796549156864&scope=bot&permissions=347200">Add the bot</a>
</p>
<br>
<br>

## ✨ Features

- 🏓 **Reaction bot** mentions you when you can hunt/battle again.
- 🎨 **Reaction bot** allows you to set custom reminders for owo patreon commands.
- 📜 **Reaction bot** has a quest system - managing quests is now way easier.
- 🔢 **Reaction bot** can calculate zoo stats and visualize huntbots.
- 🔊 **Reaction bot** allows you to use custom OwO prefixes.
- 📢 **Reaction bot** has a command for your own reminders.

## 🚦 Status

<p align="center">
    <a href="https://top.gg/bot/519287796549156864" target="_blank">
        <img src="https://top.gg/api/widget/status/519287796549156864.svg" alt="reaction bot 🎉" />
    </a>
    <a href="https://top.gg/bot/519287796549156864" target="_blank">
        <img src="https://top.gg/api/widget/servers/519287796549156864.svg" alt="reaction bot 🎉" />
    </a>
    <a href="https://top.gg/bot/519287796549156864" target="_blank">
        <img src="https://top.gg/api/widget/owner/519287796549156864.svg" alt="reaction bot 🎉" />
    </a>
</p>

## 📢 Updates & Support

- [support server](https://discord.gg/KwfCk7r)

## 🤗 Support Development & Patreon

- [patreon page](https://www.patreon.com/reaction_bot)

## 🛠️ Commands

<p>
    <a href="https://github.com/MaxiEurope/reaction-faq">
        <img src="https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/help.png" width="800" />
    </a>
</p>

## 🤔 FAQ

### STEP ONE
- make sure reaction bot has permission to view the channel & send messages
<br>

### How do I set & update OwO prefix?

- type `owo prefix` in your channel

<a href="https://github.com/MaxiEurope/reaction-faq">
    <img src="https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/owoprefix.png" width="750">
</a>

### How do I enable OwO reminders?

- type `!r owoh on` and `!r owopray on`
- additionally, you can do `!r owo on` to get mentioned every 10 seconds

### How do I disable OwO reminders?

- type `!r owo off` / `!r owoh off` / `!r owopray off`

### I don't want ghostpings, what do I do?

- type `!r owo delete`, works for the `owoh`, `owopray` and `custom` command aswell

### How do I enable / disable the huntbot reminder?

⚠️ this reminder is enabled by default
- `!r owohb on` / `!r owohb off`

### How do I set / clear a huntbot channel?

- `!r owohb #channel` (mention a channel) / `!r owohb remove`

### My huntbot reminder doesn't work, help??

- [first step](https://github.com/MaxiEurope/reaction-faq#step-one)
- make sure you are the only person in the server with that name
- remove the __backtick__ ` from your name if you have one
- if you have closed DMs, then set a reminder channel using `!r owohb #channel`
- if you have **open DMs** and you **don't see** a "⏰" reaction on your huntbot message, then [join our support server](https://discord.gg/KwfCk7r) and we'll be happy to help you

### Reaction doesn't respond to my commands??

- [first step](https://github.com/MaxiEurope/reaction-faq#step-one)
- @mention it and use the correct prefix `!r`
- the bot might be offline / restarting, check later with `!r ping`
- your server is in a broken shard, kick and [re-add the bot](https://discord.com/oauth2/authorize?client_id=519287796549156864&scope=bot&permissions=347200)
- if you were spamming **5+ reaction bot commands in 5 seconds**, then you're **temp-blacklisted for 5 minutes** - wait
- if the bot is still not responding, then you're banned

### How do I get some in-depth help on a specific command?

- `!r help command`, replace `command` with an actual command name - `!r help owoh` for example

### How do I enable certain custom owo patreon commands?

- type `!r custom add command`, for example `!r custom add piku`
- you can find a list of valid __commands__ by doing `!r custom`
- disable/remove commands by doing `!r custom remove piku`

### How does the quest system work??

- if you're a **server owner**, then set a quest channel by doing `!r q channel #channel`
- you can remove the quest channel by doing `!r q channel remove` - removing the quest channel will disable the quest system
- you can add/remove quest managers by doing `!r q managers add @User` / `!r q managers remove @User`
- quest managers will be able to remove quests by ID, ban (blacklist users from using this system) and unban users

<br>

- if you're a **quest manager**, then you can remove quests by ID and ban & unban users from the quest system
- you can remove a quest by doing `!r q remove ID`, replace ID with the quest ID that can be found [here](https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/questid.png)
- you can ban/unban users from using the quest system by doing `!r q ban @User` / `!r q unban @User`

<br>

- everyone else including server owner & managers can add their own quest to the list by doing `!r q add type amount`
- available "types": [cookie](https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/questaddcookie) | [pray](https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/questaddpray) | [curse](https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/questaddcurse)
- you can add a max of 3 quests
- you can remove **your quest** by doing `!r q remove ID`, replace ID with the quest ID that can be found [here](https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/questid.png)

### I gave @User a cookie, but the quest didn't update??

- the bot will only update quests in the quest channel, that's what it is for

### I found an error / bug in the quest system, help?

- the quest system is fairly new, please report any bugs by doing `!r report` or by joining our [support server](https://discord.gg/KwfCk7r)

### Why is there a snail reaction on my message?

- this is an indicator that you're on a command cooldown, just wait and get familiar with the command cooldown by doing `!r help command`

### Why is XYZ command cooldown so high??

- this bot is being used by many users, decreasing the cooldown would ratelimit the bot and make it even more slower

### How does the hb command work?

- do `!r help hb`
- the `-radar` tag allows you to set a radar lvl, up to 1k
- the `-patreon` tag allows you to get patreon animals
- friendly reminder: this is just a visualizer and the shown animals will not get added to your zoo
- you can set a max of 5760 animals

### How does the owostats command work?

- enable the owohunt reminder for example (`!r owoh on`), and the number in the **grinding** field will increase every time you get mentioned by the bot

### How does the zoo command work?

- do `owo zoo` or `owo zoo display` (if you sold your animals recently) in a channel
- visit discord's [Where can I find my User/Server/Message ID?](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-) article and read
- after enabling the developer mode on your device/platfrom.. whatever, copy the message ID of your zoo (if your zoo has more than one message, then copy each message ID) and do `!r zoo MESSAGE_ID`

- example for **1 message zoo**

<a href="https://github.com/MaxiEurope/reaction-faq">
    <img src="https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/zoosingle.png" width="550">
</a>

- example for **multi message zoo**

<a href="https://github.com/MaxiEurope/reaction-faq">
    <img src="https://raw.githubusercontent.com/MaxiEurope/reaction-faq/main/assets/zoomultiple.png" width="800">
</a>

### How does the reminder command work?

- `!r help rm`
- create a reminder using `!r rm reminder in time`
- example 1.: `!r rm owo daily in 1day`, example 2.: `!r rm do homework and read a book in 1 week and 20 h`

- delete your reminder by doing `!r rm delete ID`, get your reminder ID by doing `!r rm list`
- you can set a timezone for the reminder list by looking up your timezone [here](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
- you can now set your timezone by doing `!r rm timezone Australia/Melbourne` for example


### Got an unanswered question? Ask in our [support server](https://discord.gg/KwfCk7r)