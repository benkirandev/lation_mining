<h1>
    <br>
        BN Scripts
    <br>
</h1>

<h4 align="center">The best mining script available on FiveM.</h4>

<p align="center">
    <img src="https://img.shields.io/github/stars/iamlation/lation_mining?logo=github">
    <img src="https://img.shields.io/github/downloads/iamlation/lation_mining/total?logo=github&style=social">
</p>

<p align="center">
    <a href="#key-features">Key Features</a> •
    <a href="#dependencies">Dependencies</a> •
    <a href="#installation">Installation</a> •
    <a href="#support">Support</a> •
    <a href="#more-scripts">More Scripts</a>
</p>

[![lation 247robbery youtube preview](https://img.lationscripts.com/other/lation-mining-thumbnail.jpg)](https://youtu.be/yy2uLH5mtcs)

## 🔑 Key Features

* Supports all major FiveM frameworks
  - [ESX](https://github.com/esx-framework)
  - [QBCore](https://github.com/qbcore-framework)
  - [QBox](https://github.com/Qbox-project)
  - [Ox](https://github.com/overextended)
* Built-in log support
  - [Fivemanage](https://fivemanage.com/?utm_source=github&utm_medium=lation)
  - [Fivemerr](https://fivemerr.com/?utm_source=github&utm_medium=lation)
  - Discord (not recommended)
* Supports many notification systems
  - [ox_lib](https://github.com/overextended/ox_lib)
  - ESX
  - QBCore
  - [okok](https://okok.tebex.io/package/4724993/?utm_source=github&utm_medium=lation)
  - [Wasabi](https://wasabiscripts.com/product/6215100/?utm_source=github&utm_medium=lation)
  - [Samuel](https://github.com/Samuels-Development/sd-notify)
  - & more
* Locales support by [ox_lib](https://github.com/overextended/ox_lib)
  - en, es, cs, etc
  - (looking for contributors - [learn more](https://github.com/IamLation/translations))
* Built-in XP system
  - Create as many levels as you wish
  - Set the required XP to reach each level
  - Customize how much XP is rewarded for actions
  - Change what level is required for all actions
  - Includes tiered pickaxes with durability system
* Player statistics & leaderboard
  - Players can view their lifetime statistics (total mined ore, etc)
  - Customize what stats to display or not (or turn them all off)
  - Includes a leaderboard displaying top 10 players by XP
  - Leaderboard can also be disabled if desired
* Pickaxe durability system
  - Includes 4 tiers of pickaxes
  - Customize how fast (or slow) each pickaxe type degrades
  - Set the level required to use (and purchase) each pickaxe
* Create unique mining zones
  - Assign specific prop(s) to each zone
  - Customize what level is required to mine
  - Change how long it takes to mine
  - Reward one or more items with optional chance variable
  - Customize how long until the ore respawns
  - .. all these options can be customized per zone
* Powerful ingot smelting
  - Smelt your mined ores into ingots
  - Ability to require multiple ores to create 1 ingot
  - Customize each ingot smelting process and requirements
  - Change required level, duration, XP & item(s) rewarded on completion
* Included "The Mines" shop
  - Customizable shop to sell pickaxes & more
  - Ability to add any items for sale
  - Change hours available, account used for purchases & more
  - Option to include metadata on items sold
  - Ability to require a certain mining level to purchase specific items
  - Assign a blip, ped model, scenario & more
  - Or disable this shop altogether & use your own
* Included Pawn Shop
  - Allow players the ability to earn money for mined ores, ingots, etc
  - Assign prices received for each item
  - Or disable this shop altogether & use your own
  - If you use ox_inventory, we recommend using our dedicated [pawn shop](https://github.com/IamLation/lation_pawnshop) script

## ⚠️ Dependencies
The following resources are **required** in order to setup this resource:
* [oxmysql](https://github.com/overextended/oxmysql/releases)
* [ox_lib](https://github.com/overextended/ox_lib/releases)
* [ox_target](https://github.com/overextended/ox_target/releases), [qb-target](https://github.com/qbcore-framework/qb-target) or [interact](https://github.com/darktrovx/interact)

## 🖥️ Installation

* **Step 1**
  - Install (*or ensure you have the latest of*) each dependency listed above
* **Step 2**
  - Download the latest release of ```lation_mining```
* **Step 3**
  - Extract the zipped folder into your servers main ```resources``` directory
* **Step 4**
  - Add ```ensure lation_mining``` in your ```server.cfg``` file *after* all dependencies
* **Step 5**
  - Add items & images from ```install``` folder into your inventory resource
  - There is no need to execute the ```.sql``` file - *the script will auto-insert*
  - **Do not delete** the install folder or the ```.sql``` file - *or you will get errors*
* **Step 6**
  - Restart your server & enjoy!
