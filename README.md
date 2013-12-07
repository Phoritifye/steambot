steambot
========

Steambot software made for interaction with steam trades. The software is mainly an example, but it does work successfully. The bot, once downloaded, will have a user handler for demonstration purposes, of course you can just run on the user handler if you want just a keybot that sells and buys. The power of the software is up to you, and what you do with it. You can code an entire new userhandler to sell multiple items, or you can just have it sell one item. The item and pricing can be changed rather simply. Look at backpack examiner codes to find what item you want. The pricing is measured by scraps.


This is based off of Jessecar96's steambot which his is no longer maintains, and is no longer operable. 

Donating
========
Like my bot? Consider donating!
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>


Downloading
===========

1. Download visual studios for running/editing of the program.
2. Use gitbash - The code must be CLONED to have all the right files.
3. Once all files are retrieved properly, goto Bin\Release\SteamBot.exe\SteamBot\Bin\Debug and find settings. Then insert your API key, fill in the account credentials. Then fill in what chat response you wish.

Running
=======

To run the bot, goto Bin\Release\SteamBot.exe\SteamBot and find the program saying Steambot, which is for visual studios.
Now just click start.
It should say to verify steamguard, type "auth 0=" then put your steam guard code after the equal sign.


Other helpful links
===================

https://github.com/Jessecar96/SteamBot/wiki/Usage-Guide
License - https://github.com/Jessecar96/SteamBot/blob/master/LICENSE
configuration guide - https://github.com/Jessecar96/SteamBot/wiki/Configuration-Guide (There is already a setting.json)

Contributing
============

1. Fork the repository
2. Branch it
3. Make and commit your changes.
4. Push your changes back to github
5. Start a pull request on the repository, make sure to explain what it does.

3. 
