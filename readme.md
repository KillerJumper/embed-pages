<div align="center">
    <h1>Buttons Pages Discord</h1>
    <p>
        <a href="https://www.youtube.com/channel/UCFJDHPs7eT60mR3WcqrzzAA"><img src="https://yt3.ggpht.com/yti/APfAmoF1398WBb_aPUS0t_aMCmGXmpgPDHVKAWD74rohrQ=s88-c-k-c0x00ffffff-no-rj-mo"/></a>
        <a href="https://g-ca.fr/profil/killerjumper"><img src="https://media.discordapp.net/attachments/859518903566860299/867168568940822528/final3000x3000.jpg?width=88&height=88"/></a>
    </p>
    <p>
        <a><img src="https://media.discordapp.net/attachments/859518903566860299/867168561764237382/tumblr_ou44uhyE4X1uuhxwpo5_400.gif?width=296&height=240"/></a>
    </p>
    <br> <br>
</div>
<br>

## 📂 | Installation
<br>

```sh
npm i discord-buttons-page-v13
```

## 📜 | Setup

<br>
<div>
    <h4>Setup code</h4>
</div>

```js
const Discord = require('discord.js'); // Define discord.js module with npm i discord.js@dev
const bot = new Discord.Client({ // Creating client of discord.js
    // Activate intents for discord.js V13
});
```

## ✍ | Examples

<br>
<div>
    <h4>In index.js</h4>
</div>

```js
const {createPages} = require('discord-buttons-page-v13');

bot.on('message', message => {
    if(message.author.bot) return;
    if(message.content != `!${commandName}`) return;

    let embed1 = new Discord.MessageEmbed()
    .setTitle('Exemple 1');

    let embed2 = new Discord.MessageEmbed()
    .setTitle('Exemple 2');

    const embeds = [embed1, embed2];
    const ButtonStyle = "PRIMARY"; // Or SECONDARY, SUCCESS, DANGER.
    const msg_delete = "!help for help command !"; // Défault : The embeds pages is closed !

    createPages(bot, message, embeds, ButtonStyle, true, false, msg_delete);
});
```

<div align="center">
    <img src="https://media.discordapp.net/attachments/823662921367158794/867574735625519104/unknown.png?width=300&height=121"/>
    <img src="https://media.discordapp.net/attachments/823662921367158794/867574747021180928/unknown.png?width=274&height=121"/>
</div>
<br>

## 👨🏻‍🤝‍👨🏻 | Help
<br>

[Documentation Discord.js V13](https://discord.js.org/#/docs/main/master/general/welcome)

[Documentation Discord-Buttons](https://discord-buttons.js.org/)

## 👥 | Contact
<br>

If you have any other problems or questions, you can join our [Support Server !](https://discord.gg/zQDb6Ekt7p)

<br>
<a href="https://discord.gg/zQDb6Ekt7p"><img src="https://discord.com/api/guilds/705512003313205380/widget.png?style=banner1"/></a>
