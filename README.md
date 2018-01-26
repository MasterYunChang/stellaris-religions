# Religion mod - Stellaris

This mod is about adding detailed representations of fictional religions to improve the social/event perspective of the game. This readme is a sort of roadmap as to where we need to go.

## Definitions

The mod introduces different religions which will affect pops and their attitude to certain events.


**Religion categories:**
- Monotheists
- Polytheists
- Atheists
- Animists 

**List of possible religions with general characteristics:**
- Technocracy (veneration of machines/technology)
- Animalist (veneration of big animal-looking beasts travelling in space / animal-looking aliens? -> create a Fallen Empire to that effect?)
- "Self-centerism" (veneration of a mythological being)
- Planets (belief that certain planets are sacred for colonization)
- Special Ruins (finding a special ruin(s) to confere special powers [Dead Space Style] > special events?)
- Only One Species (cannot tolerate other life forms / religions -> added dmg bonus but trading malus are applied)
- Constant "beatitude" (delighted with other species - praising them)? (pacifist government)

The mod will also introduce secondary quests (special buildings to build, sacred wars towards enemy religions, etc...)

Religions should have multiple ethics: one could be aggressive and dominative, another could advertise pacifism and open-mindedness.

## Todo

### Events
At the beginning of a game, a pop-up shows up prompting the player whether he wants to play with religions or not.

**Chain of events:**

#### Init (game started)

- User wants to play the mod ?
	- Yes:
		- Prompt which religion according to category list and **[TODO] Religion name**
		- Upon selection, assign religion characteristics to all pops + government
		- Continue playing the mod and game
	- No:
		- Does not proceed with loading the mod.
		
		
#### Per religion category chain of events
	
1. Monotheists
	- **[TODO]**
2. Polytheists
	- **[TODO]**
3. Atheists
	- **[TODO]**
4. Animists
	- **[TODO]**

### Social

##### Traits (depends on religion category) - Adds bonus

???? 

##### Government
A Religion and the Government type should be tied together. For example, a *Democracy* government will induce to the pops a more "free thinking" and less cohesive pops (a mix of atheists and something else), that could be defined through custom events, or a general percentage.

*Proposition*:
- Democracy: pops are "free" and do what they think. They should be able to choose their religion of choice, or not to believe in any. Minor religious presence within pops could make these concerned populations happier, with a steady decrease in happiness in case of no positive events.
- Oligarchy: pops are more-or-less obliged to follow one religion, although some minor religions are tolerated. If a minor religion wants to become the main religion, either some "holy wars" events could occur, a sequence of events (riots, uprisings, wild conversions or propaganda...) or a tragic consequence (lost war, a sacred planet destroyed/recaptured...)
- Dictatorship: pops are obliged to follow the official religion, minor religions will be prosecuted and exterminated upon the player's choice.
- Monarchy: similar to dictatorship
- Hive Mind: no religions.

##### Civics

??? 

#### Game modifications:
We should modify the content of the following folders, found in \SteamLibrary\steamapps\common\Stellaris\common

- Ethics
- Edicts
- Attitudes?
- On_actions (events)
