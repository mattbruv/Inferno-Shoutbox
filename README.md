Inferno-Shoutbox
================

The classic Inferno Shoutbox is now available for free MyBB forums.

Description
This is the long awaited Inferno Shoutbox Lite for MyBB! This shoutbox was inspired by "Inferno vBShout for vBulletin"*. Many people who have used that shoutbox in the past know that it was easily the best shoutbox available for vBulletin. Unfortunately, nothing like it existed for MyBB, until now! The lite version is and will always be free. The download link is included below.

Additional Information

Auto-Idle
Auto-Idle is a feature that is included to help optimize the shoutbox and save server resources. If a user has the shoutbox loaded but isn't actively participating in it, they will be marked as "Idle" after a certain amount of time (definable in the ACP). This prevents unnecessary requests for data if the user isn't even there to read it.

Advanced Network Updating System
The Shoutbox ANUS is a feature that (when turned on) will drastically reduce the amount of bandwith/server resources used by the shoutbox. Basically, instead of constantly refreshing the shouts every X seconds, it will check to see if there is any new data worth updating for, and if there is, it will update.

Private Message System
If enabled, the PMS (Private Messaging System) will allow users to communicate with each other quickly and effectively in secondary shoutbox "tabs". All conversations via private messaging can only be seen by the sender and reciever, and the user can have unlimited amounts of private conversations. To start a private conversation, click on a user's name in the shoutbox, or alternatively use the command below. 

Commands

Note: As of 1.1, All commands and their output is now editable via the plugin language file.

Regular User Commands

/me [message]
Shows a /me message
/pm [user or userid]; [message]
Command way of sending a user a private message

Moderator Commands
Admins inherit all of these

/notice [your message here]
Sets the Shoutbox Notice that appears above the shouts.
/removenotice
Removes the shoutbox notice
/ban [user or userid]
bans a user from viewing/participating in the shoutbox and archive
/unban [user or userid]
unbans a user
/silence [user or userid]
silences a user from viewing/participating in the shoutbox and archive
/unsilence [user or userid]
unsilences a user
/prune
Deletes all messages in the shoutbox
/prune [user or userid]
Deletes all messages by a certain user in the shoutbox

Administrator Commands

/say [user or userid]; [message]
Fakes a shout as the specified user; looks as if they made the shout. 
