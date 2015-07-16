# telegram-bot-node-sample

This is a very basic, functional example for a Telegram bot (https://telegram.org/blog/bot-revolution) backend written in Node.js.

What it does is simply sending a true-or-false question to the user which she is able to answer. It accepts command ``/get`` to get a new, random question from database (which actually is only a simple, hard-coded array in this example), ``/true`` to say that the answer to the question is true and ``/false`` to answer the question false.

What you need to do to get this example running is:

1. Replace the **BOT_TOKEN** variable in app.js with your bot's token, which you got from *@BotFather*

2. Run ``npm install`` from console in the project's root directory (of course you need to have node.js and npm installed on your computer or server)

3. Run ``node app.js`` to start it.

Afterwards you can go into Telegram and try writing a message with ``/get`` to *@YourBotName*...

This sample code is related to my article in [How to make Telegram Bots](http://ferdinand-muetsch.de/how-to-make-telegram-bots/).

If you have any further questions or suggestions contact me. You can find my mail address and Telegram nickname on [my website](http://ferdinand-muetsch.de).
