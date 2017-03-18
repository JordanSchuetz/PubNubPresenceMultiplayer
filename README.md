# PubNub Presence Multiplayer Player Movement Example

Please use your own PubNub API keys before testing

This is a example of a real time game using Phaser's API's and PubNub Presence. All the code is in one document and can be ran easily.  Move the characters with the arrow keys. Have one window open in your standard browser, and have another open in incognito since UUID's are saved per browser window.  Packets are sent every time the player moves and exponential smoothing is used to make player movements look fluid. When a player leaves the game, the player is removed from all other devices.

Work in progress

![Screenshot of Players](http://i.imgur.com/inQNkx4.png)
Open One Incognito Window & One Normal Window
http://ninjapigstudios.com/PubNub/javascriptmulti.html
