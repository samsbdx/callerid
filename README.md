# CALLER ID

Caller id spoofing with PHP and asterisk
/*
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot
Our Channel: https://t.me/spamshopbot_bot

Notes:
This is a simple caller id spoofing script for asterisk.
It has been tested a bit - and was written more as a proof of concept then an actual production script (although it does work).

Steps:
1) make sure this script is in your asterisk-install:/var/lib/asterisk/agi-bin/ dir, copy the gsm sounds into your sounds dir
2) add this or something similar to your extensions.conf:
	exten => 1337,1,Answer
	exten => 1337,2,AGI(asterisk_callerspoof.php)
	exten => 1337,3,Hangup

3) reload asterisk or just the extensions
3.5) agi debug is helpful if there are problems
5) Try it out. Dial 1337 (or whatever extension you set up) and you should be prompted to enter the number you wish to spoof.
	then the number you wish to call. the call will be made immediately

As you can see - this is not a complicated script. in fact - it is really really simple. almost too simple.

*/
