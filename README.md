[![Build Status](https://www.travis-ci.com/MintoD/LuckyPlayer.svg?branch=main)](https://www.travis-ci.com/MintoD/LuckyPlayer)
![GitHub all releases](https://img.shields.io/github/downloads/MintoD/LuckyPlayer/total)
[![](https://poggit.pmmp.io/shield.state/LuckyPlayer)](https://poggit.pmmp.io/p/LuckyPlayer)
[![](https://poggit.pmmp.io/shield.dl.total/LuckyPlayer)](https://poggit.pmmp.io/p/LuckyPlayer)
[![Discord](https://img.shields.io/discord/832970039607033857.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/6sDGCk2JuD)
# LuckyPlayer v1.0.2
**Give money to players when they join the server at lucky time.**  
For example: You config ```luckyMoney: 100``` and ```luckyNumber: 1000```. If player is the 1000th player join the server, they will have 100$  
``NOTE!`` Make sure EconomyAPI is installed.
# Config
```yaml
luckyMoney: 100
# Players who join the 1000th server will receive $ 100
luckyNumber: 1000

message: "{PLAYER_NAME} is the {LUCKY_NUMBER}th player so he/she have {MONEY}$ for free!"
# {PLAYER_NAME} for the name of lucky player
# {MONEY} for the luckyMoney
# {LUCKY_NUMBER} fro the luckyNumber
```
# Installation
- Make sure that Sheep is installed
- Then use ```install LuckyPlayer``` to install plugin
# License
Released under the GPL-2.0 license.
