# COD Warzone Stats Documentation

[![N|Solid](https://i.imgur.com/AQgDpj9.png)](https://www.python.org/downloads/)

[![Build Status](https://i.imgur.com/O6AFons.png)](https://github.com/fluxboy2/codwarzonebot)

COD Warzone Stats Documentation is a discord bot that replies back to your commands with a PNG that you can send to your friends or tage them with.

  - Compare you and your friend's stats!
  - Lookup single user stats
# TODO LIST:
  - Create a new template for the table in the image(templat.html)
  - Maybe add multiplayer support to lookup multiplayer stats

# New Features!
#### 0.0.1
  - Any output the bot gives, such as comparing two players or looking a single player up, will be in a .png format to be easily downloaded if wanted. Click on the photo generated by the bot. Then right click the image and then click on save image preview. Save wherever you like.
  - You can now compare you and your friend to see side by side who is better!
### Installation
- Use this link to add the bot to a server you are admin in. [Authorize Discord Bot](https://discord.com/api/oauth2/authorize?client_id=751455260454682714&permissions=67632192&scope=bot)
- Then use these commands below to use the bot
### Usage/Commands
Looks up two people and compares them
```sh
.compare <player_platform> <player_username> <player_platform> <player_username>
```
Single user lookup
```sh
.lookup <player_platform> <player_username>
```

##### <player_platform> can be one of 5 options:

- act = Activision
- psn = Playstation Network
- xbl = Xbox Live
- steam = Steam
- bnet = Battle Net
##### <player_username> can have spaces in it, but you need to use "double quotes".
Example: .compare bnet myuser#43567 act "activision user"



# Info
- If you do not specifiy the exact unique name of that user there is a possibility that the api will choose someone with that same name but a different identifier, for example: myuser#9000 as #9000 is the identifer.
- I think there is a way to set your profile to not show stats on the call of duty website. If a user does this the api cannot see their stats and will return in chat an error message.
