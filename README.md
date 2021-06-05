# discordbot sample made by STTARBUCKSU, Reserved by sttartbucksu.
const discord = require("discord.js");
const client = new discord.Client();

client.on("message", function(message){
    const msg = message.content;
    const Embed = new discord.MessageEmbed();

    if(msg=='embed_test'){
        Embed.setTitle('hello');
        message.channel.send(Embed);
    }
    
    if(msg=='send_test'){
        message.channel.send('hello');
});
client.login('discord token key');

# if you don't install node.js, please install node.js.
# go cmd (or powershell), enter cd and this js file Directory.
# Then nothing will pop up, That means it's a success.
# By the way, if you didn't invite a bot to the discode chat room, Google how to invite a discode bot.
# end)) comfile this file, goto discord bot chat room, and enter msg!
