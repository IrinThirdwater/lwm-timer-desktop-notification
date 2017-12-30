# LWM Timer Desktop Notification

## What's this?
This is a script for a game called [Lords of War and Money](http://www.lordswm.com/?rid=4874384) (referral link), a browser-based tactical game based on the PC franchise [Heroes of Might and Magic](https://en.wikipedia.org/wiki/Heroes_of_Might_and_Magic). The [script, originally written by demin and xo4yxa](https://greasyfork.org/en/scripts/1217-hwm-time-restore), monitors in-game states and JavaScript [```alert```](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert) the player when some desirable activities become available to the player after being in cooldown. This repository is a fork of that script.

## What's new?
 * If the permission is granted, any notifications from the script will be made using desktop [```notification```](https://developer.mozilla.org/en-US/docs/Web/API/notification) instead of Javascript ```alert()```.
 * Can be toggled on and off in the setting page.
 
## Why?
These notifications can be repetitive and you may find that ```alert``` can sometimes be intrusive (forcing the broswer window's focus on the game tab until you respond) or not so intrusive (not being obvious when the window containing the game tab is not in focus).  
To solve this issue, I used ```notification```. It doesn't affect the current window/tab focus, and is intrusive enough that you still see it even when working in other windows.
