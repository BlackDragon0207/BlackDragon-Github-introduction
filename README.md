### [ 흑룡 깃 허브 ]

대한민국에서 활동하고 있는 취미로 봇을 개발하는 중학생 입니다.

BlackDragon Community 의 대표로 활동 하고 있습니다. 

![Dragon](https://cdn.discordapp.com/attachments/772423311442837534/776502884274536488/25.png)

* [BlackDragon Community URL](httpsdiscord.ggXCpAAYY)

### [ 봇 코딩 언어 ]

* JavaScript(node.js)
* Python

현재 공부중임!

### [ 코딩 예시 ]

```js
const Discord = require('discord.js')
const moment = require('moment')
moment.locale('ko-KR')

exports.run = async (client, message, args) => {
    const create = Date.now()
    let command = client.emojis.get('비공개')
    let Developers = client.emojis.get('비공개')
    let java = client.emojis.get('비공개')
    let settings = client.emojis.get('비공개')
    let embed = new Discord.RichEmbed()
    .setColor(`#FFFFFF`)
    .setAuthor(`BlackDragon Community Bot 도움말`, client.user.displayAvatarURL)
    .setDescription(`**해당 봇은 흑룡 커뮤니티의 오피셜 봇입니다.**`)
    .addField(`${Developers} **Developers**`, `**ArdanKR & 흑룡**`)
    .addField(`${settings} **Coding Program**`, `**[discord.js](https://discord.js.org/#/)**`)
    .addField(`${java} **bot code support**`,`**ArdanKR**`)
    .addField(`⛔ **Copyright Holding**`, `**ArdanKR, 흑룡**`)
    .addField(`${command} **command help**`,`**D_commands**`)
    message.channel.send(embed)
}

exports.config = {
    name: "help",
    aliases: ['도움']
}
```
* 최근 흑룡 상태 : 뇌절
