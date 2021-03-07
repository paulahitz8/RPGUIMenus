[Go back to Github](https://github.com/paulahitz8/RPGUIMenus)

# Introduction
Since the beginning of the gaming era, the UI of a game miau miau miau. 

## UI vs UX
The terms UI and UX are often used incorrectly due to the lack of understanding of their actual meaning. UI, or User Interface, in video games is the way in which the player interacts with the game through methods, like the controller or keyboard, and interfaces, like the menus or HUD. On the other hand, UX, or User Experience, refers to how enjoyable or intuitive these interactions actually are. It is also important to clarify that the HUD, or Head-Up-Display, is the method in which the game visually displays the information to the player, being part of the game’s UI.

## Why is it important to have a good UI?
The goal of a good UI is to provide information to the user in a clear and quick way, avoiding distractions or unnecessary information. After some research I found a good list of questions that can ensure a good use of the UI. These are the following:

1. Does this interface tell me what I need to know right now?
2. Is it easy to find the information I am looking for?
3. Can I use this interface intuitively?
4. Are the things I am able to do on this screen obvious?
5. Is there any unnecessary information on the screen?
6. Are there any repetitive tasks that I can shorten?
7. Am I being consistent?

It is important to frequently ask these questions when designing and developing a video game in order to avoid any complications or unpleasant experiences. Some other key factor to be aware of:

- Hierarchy
- Size
- Color
- Contrast
- Position and layout


## Flowcharts
When designing the UI of the video game, there is a very common technique called the flowchart. This technique consists of designing a diagram that represents the different actions that the player can take while navigating through the different menus. This can help to ensure a logical and efficient way to access different information provided by the videogame. 

This is an example of a flowchart:

![flowchart](https://i.pinimg.com/originals/30/2c/f1/302cf109c4f89c58feba09fdeeae7f8f.png)

This is another example of a flowchart:

![flowchart2](https://images.squarespace-cdn.com/content/v1/57fd1900414fb5796ec9ef0e/1478447627883-RQIA8I174WY1EEG51FNG/ke17ZwdGBToddI8pDm48kIbKmVpWXp0hT9DwFKJuHfxZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PIXSL_jJZ390Sxde8xirMC93N_YOQPnKKwVrryIHtGryc/menu_flowChart.png)

As you can see it displays the different menus and the arrows show how the player can navigate through this. The purpose of this is to make it as simple as possible, to avoid confusion and distraction. 

# Types of Menus and Examples
I wanted to do a disclaimer here: every game is different, it is impossible to find a structure that suits every game since all of them have different elements that make the game. Some games have very simple menus and others have very complex ones with a bunch of options that the player can use. I will be showing you the most common, some particular ones that I find interesting, and I organized them from my point of view. I also added a screenshot as an example for every type.

## Main Menu
The most basic menu that we can find in almost every game is the main menu. We often see it right when we open the game, giving us the option to play, go to our settings, quit the game etc. Some games have a lot more options, it depends on the developers.

Skyrim:
![mainmenuskyrim](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/mainmenu_skyrim.jpg?raw=true)

## Pause Menu
What elements can we most likely find in the Pause Menu? 
- Continue
- Settings
- Exit

Again, depends on the game, there are some which give access to all of the menus available for the player.

_Read Dead Redemption 2_:
![pauserdd2](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/pausemenu_rdd2.png?raw=true)

## Character Selection Menu
Where the player gets to decide which character she or he can play.

_Destiny 2_:
![charselectdestiny](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/charselect_destiny.png?raw=true)

## Character Creation Menu
Where the player gets to create his or her character.

_Skyrim_:
![charcreationskyrim](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/charcreation_skyrim.png?raw=true)

## Stats Menu
Where the different stats of the character are being displayed. They can vary depending on the game. Some elements found are:
- Health
- Stamina
- Armor
- Intelligence
- Weight

_Dark Souls III_:
![statsdarksouls](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/stats_darksouls.png?raw=true)

## Skills Menu
This menu displays the skills that are or can be obtained by the character. They can be displayed in different ways, like in a list. I believe the most common and efficient way to display it is in a tree.

_Skyrim_:
![skillskyrim](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/skills_skyrim.jpg?raw=true)

## Inventory Menu
This menu displays the inventory of the character, which is basically what they are carrying in the game. 

_Pokemon Diamond/Pearl_:
![inventorypokemon](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/inventory_pokemon.jpg?raw=true)

## Equipment Menu
This menu can be often confused with the previous one, but it refers to the gear the character wears, like armor or weapons. It is sometimes linked to the inventory, since they are normally able to equip and unequip certain items.

_Dark Souls III_:
![equipmentdarksouls](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/equipment_darksouls.png?raw=true)

## Settings Menu
This menu allows the player to change certain options of the game. The most common options are:
- General/Gameplay
  - Language
  - HUD settings
  - Text settings
  - Brightness
- Controls
  - Keybinds
  - Keyboard and mouse
  - Controller
  - Sensitivity
- Graphics
  - Display
  - Quality
- Audio
  - Master volume
  - Music volume
  - Fx volume

_Cyberpunk 2077_:
![settingscyberpunk](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/graphics_cyberpunk.jpg?raw=true)

## Social Menu
Social menus are more often found in multiplayer games, but some games that are singleplayer still can offer some of these options. These are some submenus we can find here:
- Lobby
- Clan
- Matchmaking
- Party
- Friends list

_Destiny II_:
![socialmenudestiny](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/lobby_destiny.png?raw=true)

## Quest Menu
Where the quests of the player are being displayed, often with some backstory and location. Normally, they are divided into main quests and optional or secondary quests. Main quests tend to follow the story of the game.

_Skyrim_:
![questsskyrim](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/quests_skyrim.jpg?raw=true)

## Map Menu
Whether there is only one map or there are many worlds with different maps (like in Destiny), the Map Menu is where the world is being displayed, helping the player navigate around the different locations in the game. Sometimes, quests are signalized on the map, to make it easier for the player to understand where she or he needs to go.

_Pokemon Ruby/Sapphire/Emerald_:
![mappokemon](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/map_pokemon.png?raw=true)

## Crafting Menu
Crafting menus are somewhat common in RPG games. Sometimes they are linked to the inventory menu since we often need ingredients or pieces in order to craft certain objects.

_Last of Us 2_:
![crafting](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/crafting_lastofus.jpg?raw=true)

## Achievements Menu
This menu is mostly used to show off to our friends what we achieved while playing. Also, it is very satisfying to complete everything, at least for some players. 

_World of Warcraft_:
![achievementswow](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/achievements_wow.png?raw=true)

## Collections Menu
This is similar to the menu before, but it is specifically objects you can collect in the game, like for example in World of Warcraft you can collect different mounts and pets.

_Destiny 2_:
![collectionsdestiny](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/collections_destiny.png?raw=true)

## Shop Menu
Whether it’s a store with real money or in-game money, this is used to make the player spend money. With real money we can buy things like skins, special objects in the game, exclusive content etc. With in-game money we can often buy power-ups, better gear etc. But actually, the options are limitless. 

_Undertale_:
![shopundertale](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/shop_undertale.png?raw=true)

## News or Patch Notes Menu
This menu is also self explanatory. Here the game gives information to the player like about new updates or events that might be coming up. These are normally very common in multiplayer RPGs since they are constantly tweaking the games and adding more events for people to participate in.

_Dark Souls III_:
![newsdarksouls](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/news_darksouls.png?raw=true)

## Saving Slots Menu
This is another menu that can be found in singleplayer games, where the player can save his or her progression during that game. 

_Legends of Zelda_:
![savezelda](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/saveslot_zelda.jpg?raw=true)

## Player(s) Name Input Menu
I believe this menu is very specific, but it can be found also in RPG games, especially the old school ones. This menu is dedicated for the player to introduce his or her name.

_Undertale_:
![nameundertale](https://github.com/paulahitz8/RPGUIMenus/blob/main/docs/images/playerinput_undertale.png?raw=true)

# HUD and Dialogue
One of the most common elements found in video games is the HUD, where relevant information is displayed on screen for the player to use while playing. There are many different types of HUDs depending on what the developers are going for.

## Dialogue
We all know RPGs is one of the greatest genres of games in the world, with its origin being on tabletop board games, like Dungeons & Dragons. Here is where playing a role actually started. It becomes some kind of social experience that can require a party of people, or not. When the player is roleplaying, he or she is personifying another character. The interaction with this fantasy world is very important and can be done through dialogue with other people or the game itself. 

Factors about the player’s character and the world, like the era, class, gender and race are going to determine the form of communication in the game. Representing properly the character and the environment is important and adds to the immersion of the player into the game. Creating a dialogue is important and takes time, but it helps a lot into making the game better. 

Some games offer dialogue options, meaning that the character can choose between different sentences to say. This gives the player a little more freedom since he or she can decide what to say. Some games do not take into account what option you chose, since the reaction or the story will stay the same, but other games take the player’s choice into consideration and shifts accordingly. 


_Skyrim_:
![skyrimdialogue](https://miro.medium.com/max/700/1*IAVvUpe77o0YdbzOvVbk0g.jpeg)

We all know that there has to be a balance on how much dialogue is presented in the game. Japanese RPGs are well known for having a lot of text and backstory since most players like to roam around and interact with every NPC in the game to learn more about the game and its story. Some other people prefer to spam B to skip all of the dialogue because they can sometimes get annoying. In my opinion, finding a good balance between a lot and too little is important, but this of course is a personal opinion and everyone has their own preferences. Also, when it comes to excessive dialogue, this tends to be because the NPC or the actual game is giving information to the player that is not important to the actual gameplay.¡

Examples of dialogue in RPGs:

_Skyrim_:
![skyrimdialogue](https://i.imgur.com/r2f9fBG.jpg)

_Pokemon_:
![pokemondialogue](https://i.pinimg.com/originals/58/2f/79/582f798483c4d1ffdc2f3d2fef1354ee.jpg)

_Undertale_:
![undertaledialogue](https://i.pinimg.com/originals/73/05/2a/73052abcfa463e1d62dd554c6603b5cf.png)

_World of Warcraft_:
![wowdialogue](https://i.ytimg.com/vi/aQ-4-kqAhVs/maxresdefault.jpg)


# Evolution
As the years have rolled on and gaming has progressed and matures, the way information delivered to the player by the UI has evolved too. The interface of a video game can make or break the whole experience. 

Older video games are more conceptual than anything, machines created to explore the concept of video entertainment, not as something to get into the top of a leaderboard, so a UI was not really necessary. However, with the success of arcade machines, UI was introduced in a simple way, like PONG, where it only has the score on the screen. Newer arcade games had the goal of reaching the highest score, therefore displaying several digits on screen that will determine your score. Also, some icons were introduced like health, if the game had lives. 

Games started developing a more complex UI to give information to the player and to make the game more aesthetically pleasing and enjoyable.

Years ago, players only had 3 slots to introduce a name that would identify them on the top of the leaderboard. To this day, player input screens are very common, especially in RPGs, but they obviously have evolved, giving the player more freedom when choosing his or her name.

As time progressed, the information we needed to know on screen increased, due to the innovations in video games.

## Health
When players imagine health, the majority imagine a green bar that gets shorter when the player’s life is decreasing. It is one of the most basic ways to represent health in a game. Once the bar depletes, you are dead. 

However, many games across the decades have decided to approach the visual representation of health in a different way. It could be a numerical value, like a percentage, or different numbers depending on your class or your stats. It could be a row of hearts like in Minecraft, or it could actually be nothing. Super Mario Bros for example represented your health with the size of Mario, or Sonic the Hedgehog by the amount of rings you had. 

Some games like Doom, started using the UI in a good way.

As you can see, different information is given to the player, like the ammo, the health, the inventory, armor, and stats. Concretely about health, this game offers two ways of representing it, by a numerical percentage, or by the face of your character, which gets bloodier with lower health. A good thing Doom did is give you all of the information you needed on screen, without having to switch between menus while playing. 

## Inventory
When PC games started to be more popular RPG games were the most played. Translated from the tabletop to the screen, dungeon crawling, slaying beasts and exploring lands of fantasy was very popular. However, before the incorporation of more modern RPGs with separate menus, skill trees and *usually* minimalistic UIs, most of the things you needed to know where right there on the screen.

This game featured the TAB to switch between your items, spells and armor. The concept of different menus or switching away from the main action wasn’t as present as nowadays. Currently, games offer navigation to different menus or displays to see different options like inventory or skills. 

## Weapons
In the old days, the usual way to show how many bullets you have left was by a depleting row of bullets that was shown on screen, and the player could only reload once all of the bullets were gone. 

As the first person shooters genre boomed, this more visual representation carried out somewhat. Games like Call of Duty 4 Modern Warfare also had this visual representation of the bullets, but it actually turns out to be harder to read than a simple numeric value which games started to incorporate in their UI. Some games like Apex Legends even have the bullets displayed on the actual gun, making it more immersive. 

## Design

As the media progressed, the user interface was given much more flare. The aesthetics of the game you were playing would match with the design of the UI. For example, when playing a horror game, most likely you will get a spooky dark UI that can be splattered with blood. Or playing a futuristic game, expect a lot of neon lights and digital elements. As time passed by, RPGs tended to go for the more minimalistic design. 

Minimalism in the UI space can make a game more cinematic.

## Menus and Controllers
Where do we always begin? In the main menu. Sometimes the main menu is nothing more than the option to Start, Options or Quit. Title screens can be all the way to very simple or have an actual cinematic.

As console gaming became more popular over the years, menus were built with controllers in mind. Simplified buttons with submenus available were created rather than just dumping all of the options on the screen, making navigation harder with a thumbstick. A mouse is always quicker and more accurate than a controller in multiple ways, therefore some companies decided to implement a cursor that can be moved with the thumbstick. 

Video games have come a long way, from not needing to tell you much about what you are doing to giving you an actual encyclopedia to read within the options menu. To this day, developers are experimenting with ways to convey information to the player in the prettiest, most effective or least distracting way as possible. The amount of information we need while playing has evolved over time too. First we only needed to know scores, now we need to know how much HP a particular enemy has left or its weak spots, and all of that within a time frame. 	

# UI Design Template
I made a UI design templatethat may be able to help the different groups. Click [here](https://github.com/paulahitz8/RPGUIMenus/blob/main/templates/ui_design.md).

# Bibliography
- Bradley, Alan. “6 Examples of UI Design That Every Game Developer Should Study.” Gamasutra, www.gamasutra.com/view/news/289637/6_examples_of_UI_design_that_every_game_developer_should_study.php.
- Dakinedi, Akhil. “Top 5 Best Video Game UIs.” Medium, SUPERJUMP, 26 Feb. 2020, medium.com/super-jump/top-5-best-video-game-uis-db941d6a9357.
- Kionay. “RPG Dialogue Systems.” Medium, Medium, 28 June 2019, kionay.medium.com/rpg-dialogue-systems-1de601383a94.
- Nathan Lovato Nathan is a game design expert at GameAnalytics. Currently founder and game design instructor at GDquest., et al. “How To Make Your Game UI Shine, Increase Conversions.” GameAnalytics, 5 Nov. 2020, gameanalytics.com/blog/how-to-make-your-game-ui-shine-and-increase-conversions/.
- Quintans, Desi. “Game UI by Example: A Crash Course in the Good and the Bad.” Game Development Envato Tuts+, Envato Tuts, 22 Jan. 2013, gamedevelopment.tutsplus.com/tutorials/game-ui-by-example-a-crash-course-in-the-good-and-the-bad--gamedev-3943.
- Schreier, Jason. “What Makes RPG Dialogue Great (And How It Can Go Wrong).” Kotaku, Kotaku, 19 June 2013, kotaku.com/what-makes-rpg-dialogue-great-and-how-it-can-go-wrong-5910866. 
