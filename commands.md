Commands:
=========

X specifies a number  
Arguments between ( ) are optional


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!clearchat | |clears the chat |
|!cycle | | toggle DJ cycle |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |


Bouncer
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | add user to the waitlist |
|!afkremoval | | toggles the afk check |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) |
|!deletechat | @user | delete all the chats by a certain user |
|!lock | | lock the waitlist |
|!lockdown | | lock down the room: only staff can chat |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
|!remove | @user | remove user from the waitlist |
|!roulette | | Starts roulette |
|!unlock | | unlock the waitlist |
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!afkreset | @user | resets the afk time of user |
|!afktime | @user | shows how long user has been afk |
|!autodisable | | toggle the autodisable |
|!ban | @user | bans user for 1 day |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
|!commanddeletion | | toggles if bot commands gets deleted |
|!cycleguard | | toggles the cycleguard |
|!dclookup / !dc | (@user) | do dclookup for user |
|!english | @user | ask user to speak english |
|!eta | (@user) | shows when user will reach the booth |
|!forceskip | | forceskips the current song |
|!historyskip | | toggles the history skip |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!lockskip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) |
|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!status | | display the bot's status and some settings |
|!timeguard | | toggle the timeguard |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unban | @user | unban user |
|!unmute | | unmute user |
|!voteratio | @user | display the vote statistic for a user |
|!whois | @user | returns plug related information about user |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!link | | give a link to the current song



User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!autowoot | | links to RCS, the advised script/plugin to use for autowooting |
|!commands | | gives a link to the commands |
|!cookie | (@user) | give a cookie to user |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!ghostbuster | @user | checks if user is ghosting |
|!gif | (message) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!help | | links to an image to help get people started on plug |
|!join | | join the roulette if it's up |
|!leave | | leave the roulette if you joined |
|!link | | when the user is the DJ, give a link to the current song |
|!op | | links to the OverPlayed list |
|!rules | | links to the rules |
|!thor | | users get moved to position 1 in the waitlist if they're worthy of Thor's hammer. |
|!website | | links to the website |


Skip Rasons
-----------

|Reason | Description |
|:-----:|:-----------:|
|theme | This song does not fit the room theme. |
|OP | This song is on the OP list. |
|History | This song is in the history. |
|Sound | The song you played had bad sound quality or no sound. "],
|NSFW | The song you contained was NSFW (image or sound). |
|Unavailable | The song you played was not available for some users. |
