bot
    .on(bot.triggers.command, 'say', ['word'])
    .do(function(bot, conf, args) {
        this.reply(args.commandArgs.word);
    });
 
//-> !say hello 
//<- hello var Bot = require('discord-bot');

var bot = new Bot({
    email: <email>,
    password: <pass>
});
 
bot
    .on(bot.triggers.command, 'bot
    .on(bot.triggers.command, 'say', ['word'])
    .do(function(bot, conf, args) {
        this.reply(args.commandArgs.word);
    });
 
//-> !say hello 
//<- hello ')
    .do(function(bot, conf, args) {
        this.reply('world');
    });
 
bot.connect();bot
    .on(bot.triggers.command, 'say', ['word'])
    .do(function(bot, conf, args) {
        this.reply(args.commandArgs.word);
    });
