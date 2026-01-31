---
{"dg-publish":true,"permalink":"/mechanics/chronicle-gdd-deprecated/","noteIcon":""}
---

 
***==OVERVIEW*==** 

**A ~ indicates a truncated piece of information to be expanded upon in a later section.**    

**A * indicates something that may be subject to change.**

*CHRONICLE* is a hardcore survival RPG that harkens back to things like WoW Classic and DnD. It is meant to be a revival of the "old school" of RPGs injected with "New School" ideology. In short, *CHRONICLE* is the RPG I've always wanted to play.

***==CORE TENETS==***

- <font color="#f79646">Open World Sandbox - An expansive open world to facilitate exploration and freedom of choice. Everything is unleveled, meaning players can traverse freely and accomplish goals in any order they wish. ~</font>**There is no fast travel, save for between major cities via caravan.** 

- <font color="#9bbb59">Classless Leveling - Players may at any time invest in any attribute, skill or talent. There are no restrictions. This allows players to mix and match their characters however they'd like and opens up a wide variety of builds. ~</font>

- <font color="#8064a2">Survival Mechanics - Players need to eat, drink, and sleep to maintain their state as well as manage temperature.</font> *Player race can have an effect on temperature.* ~

- <font color="#ffc000">Immersion - As little menus as possible in game.</font> <font color="#ffc000">Books and maps are read physically in the world.Vendors will have their items physically placed.</font>  *Inventory, skill, and speech screens will still have menus you can access.* 

# ***GAMEPLAY STRUCTURES***

*Chronicle* is meant to be played slowly and methodically, akin to games like *The Long Dark* and similar titles. 

## ***DIFFICULTY***

In *Chronicle,* **difficulty is fully dynamic.** This is handled in a couple different ways via ***World Level***. ~

1.  Difficulty increases slowly over *time*. On Easy Difficulty this is disabled. Normal mode enabled this from the very start.  **Hardcore mode is an optional difficulty.** 

2. Difficulty also scales off of *Character Level.* In most RPGs this is a visible measure of players' progress, but **in Chronicle this is a hidden statistic.** It is totaled by adding **Skill Level**, **Talent Level** and **Item Level**. 

**World Level** is totaled by adding the sum of these two values.

#### CHARACTER LEVEL 

*Character Level* is the totaled sum of **Skill, Talent, and Item Levels.** This total is added to the *time variable* which calculates **World Level.** ***Character Level is a bit of a misleading term. Think of it as more "Character Points". Players can have a maximum character level of 1000. 250 SL, 250 TL, and 500 IL.*** 
##### SKILL LEVEL

*Skill level is the value assigned to the character by totaling the **skill value** of all skills across the different **skill classes**, to a **maximum of 250 skill value.**

**Every skill is worth 20 points. Having the maximum available skills enabled will also add +10 points and spike the difficulty considerably. Players are free to enable the maximum allowed skills at their own discretion, but it is a good idea to "pick and choose".**

***Higher tiers of base skills still retain their value of 20, so this can be a good alley to gain an edge on enemies. Skills can also be disabled or interchanged at Rest Locations and Instructors.*** 

##### TALENT LEVEL

*Talent Level* is the value assigned to the character by totaling *all active talents.* **Talents are generally more powerful than skills and are worth 40, to a maximum of 240 + 10 (with maximum talents enabled.)** 

***Like Skills, Talents can also be interchanged or disabled freely at Rest Areas or Instructors.*** 

**Talents are only available to players who take a prerequisite number of skills in a ***skill class***. **Depending on the chosen Talent, this number can vary.**  

#####  ITEM LEVEL

*Item Level* is the accrued value applied to the character based on their current equipment. *It is a hidden stat.* **Item Level is also how the game determines what loot it should be generating.** 

There are **thirteen slots** for equipment. 
This includes;

1. Head
2. Shoulders
3. Chest & Arms
4. Waist
5. Gloves
6. Legs
7. Boots
8. Ring
9. Amulet
10. Quiver
11. Cape
12. Left Hand
13. Right Hand

==These thirteen slots will have each of their values assigned on a per item basis, which will be summed up the total Item Level.==

**Items can be of varying values. For example, each item in each slot could have a value of 1, resulting in item level 13. This is rounded to the nearest multiple of 10, so the *actual item level would be 10.* 

The loot table is dynamically adjusted to distribute items at, slightly below, or slightly above this level. **There is a %chance for outlier items which will push the player to the next threshold.**~ 

**Item level has a maximum of *500 points.*** 

#### TIME & WORLD LEVEL

After Character Level is totaled, the *time* variable is added to calculate **World Level.** 

*Time* has a maximum value of 1000. At maximum, **CHARACTER LEVEL + TIME = 2000.** 

***Every day that passes in game will add 2.5 to the time variable. Therefore, every 10 days is 25 points, every 100 days is 250 points, so on and so forth. After approximately one in game year, the time value will reach its maximum. You can set time passed at start during character creation.*** 

**Theoretically, this could be increased in a settings page should the player desire.** 

As a standard, every 125 points adds 10% damage and 5% health to enemies, *but also buffs **player damage and health*** *by 7.5%.* **These percentages are additive. At maximum world level, Enemies would deal 190% increased damage and have 80% more health. *Players would have 120% more damage and health.**** These percentages may be changed upon testing for the best feel, but this way the game should feel very lethal. Combat should be quick and brutal. ***The last three tiers of world level add much more damage to enemies.*** 

Please see the table below to better understand how World Level scales.

**D = DAMAGE
H = HEALTH
A = ALL**

| CL + TIME =` | WORLD LEVEL | CHANGES (ENEMY) | CHANGES (PLAYERS) |
| :----------: | :---------: | :-------------: | :---------------: |
|   0 (BASE)   |      0      |       N/A       |        N/A        |
|     125      |      1      |  +10% D  +5% H  |      +7.5% A      |
|     250      |      2      |  +20% D +10% H  |      +15% A       |
|     375      |      3      |  +30% D +15% H  |     +22.5% A      |
|     500      |      4      |  +40% D +20% H  |      +30% A       |
|     625      |      5      |  +50% D +25% H  |     +37.5% A      |
|     750      |      6      |  +60% D +30% H  |      +45% A       |
|     875      |      7      |  +70% D +35% H  |     +52.5% A      |
|     1000     |      8      |  +80% D +40% H  |      +60% A       |
|     1125     |      9      |  +90% D +45% H  |     +67.5% A      |
|     1250     |     10      | +100% D +50% H  |      +75% A       |
|     1375     |     11      | +110% D +55% H  |     +82.5% A      |
|     1500     |     12      | +120% D +60% H  |      +90% A       |
|     1625     |     13      | +130% D +65% H  |     +97.5% A      |
|     1750     |     14      | +150% D +70% H  |      +105% A      |
|     1875     |     15      | +170% D +75% H  |     +112.5% A     |
|     2000     |     16      | +190% D +80% H  |      +120% A      |
 




## ***CLASSLESS LEVELING**

Players in *Chronicle* do not follow a classic class structure similar to other RPGs or TTRPGs. Skills are refined through use, and **only through use.** There is a wide variety of them and they all interact with each other in different ways. ***This section will detail Character Creation, Attributes, Skills, and Talents.*** 

*<font color="#00b050">A foreword about Skills and Talents.</font>*  ***Skills and Talents are displayed in the same window, which is typically separated into two sections. One for talents, and the other for the skill tree. Please see a mockup below to better understand how this works.*** 

[INSERT MOCKUP HERE]
### ***ATTRIBUTES***

Attributes govern the capability of the player. They dictate their proficiency in different fields and are increased by using **active skills** in their domain. For example, **magic users may only increase intelligence by actively casting magic or studying with a relevant instructor.** This is to facilitate the feel or real growth and freedom, but to also pay respect to the difficult nature of becoming "The Hero".  Attributes are also used in **Attribute Checks**, which are only passed if the player has a skill at a relevant threshold.

The Attributes are as follows.

- **STRENGTH (STR)** - Strength dictates the ability to wield martial weapons, make STR checks, and take on certain ***Talents or Active Skills.*** Martial weapons include one and two handed swords, maces, great hammers, and clubs. They *also* include things like tower shields. Leveled up through melee combat, or use of relevant items. Can also be leveled at a Skill Instructor. Strength contains the **Intimidation** which can make players more "persuasive" in certain dialogues.

- **DEXTERITY (DEX)** - Dexterity governs the effectiveness of *nimble weapons*. Nimble weapons include daggers, spears, quarterstaves, bows, and throwing weapons. *Bows and Spears particularly use **STRENGTH** as a subscaler.* Like Strength, it is also used in Skill and Talent requirements. *Dexterity also affects running, jumping, climbing, sneaking, swimming,* **and casting times for magic users.** Dexterity also includes a unique talent called **Dextrous Tongue**, which makes players more persuasive in certain dialogues. Leveled up through use of relevant items or performing relevant actions. Can be trained with Skill Instructors. 

- **INTELLIGENCE (INT)** - Intelligence governs the effectiveness of Arcane, non faith-based magics. *The Arcane Schools of Destruction, Transmutation, Illusion and Conjuration scale off of this.* Intelligence is also a requirement for certain magical instruments, like wizards' staves or arcane foci. It is a hard requirement for learning various spells. Highly intelligent characters can also at times know when they're being lied to in dialogue. Leveled up through practicing magic.

- **FAITH (FTH)** - Faith is used in various Holy Invocations (the spells of a Cleric or Paladin). Certain holy instruments require faith to be used **as well as Healing Magic.** Faith can also be channeled into Dark Invocations, like Hexes and Curses. Hard requirement for faith-based magic. Can be leveled through prayer or practicing holy invocations.

- **VITALITY (VIT)** - Vitality is what governs overall health, weight limit, innate Physical Resistances, and how long you can go without Eating/Drinking. It also governs stamina, which is required to Attack, Block, and Run. *Higher VIT is required to wear the heaviest suits of armor.*  Leveled up through the use of heavier armors or attempting relevant actions. **It is important to note that Vitality scales less when attempting relevant actions without heavier armor, but will still scale. Taking damage in combat will also slightly increase VIT.** 

- **REFLEXES (REF)** - Reflexes governs dodge chance and Critical %. **Crits are governed by REF + Your second highest stat.** Reflexes are checked **every time you dodge any form of damage.** They are leveled through relevant actions and allow access to certain talents. *Reflexes are also leveled through the use of nimble weapons, but marginally compared to dodging or making a critical attack.* ***Light and Medium armors provide a small bonus to %dodge, making it easier to level Reflexes for players who plan to use it.*** 

- **MIND (MIN)** - Mind governs innate Magical Resistances, the capacity to memorize various spells, and the Psionic set of spells. Characters with high Mind (or Intelligence) can also perceive when they're being lied to, although not assuredly. **The Mind attribute grants spell slots at various thresholds.** *Players with high mind can also resist certain debuffs, like Terror.* 

### ***SKILLS***

Skills are active abilities used in or outside of combat. They can be practiced on training dummies. **Practicing on training dummies provides no bonus to Skill XP, but using new skills in combat does**. Practicing can reduce miss/backfire chance. However, using new skills **in combat** comes with the **risk of a %chance to miss as a melee/ranged/spell attack**. *New Spell Skills in particular, like Fireball or Magic Missile, have a %chance to fail cast or backfire alongside the %chance to miss.* As a result **Magic is not easy to use at first**, but practice will make it a very powerful tool, as it is the strongest Skill Class in the game. **The Skill Classes are as follows; Martial (STR), Finesse (DEX), Versatility (STR & DEX),  Destruction (INT), Enchanting (INT),  and Invocations (FTH),** *Defensive (VIT), Evasion (REF), and Tactica (MIN) do not have any active skills, only passive Talents.* ~  Leveling a skill increases its effectiveness, and at higher tiers can add modifiers to transform skills into an upgraded version of themselves. Talents follow a similar design philosophy, separated into Talent Classes of the same name. Skill Level is a hidden stat incorporated into the World Level, defined by number of skills learned. Maximum skill level adds to 250. Each skill is 20 points, and having maximum activated skills gives +10. ( For 250 ) 

### ***SKILL CLASSES*** 

**Skill Classes** are the respective domain of an attribute's practical use in gameplay. 

##### ***MARTIAL*** 

*The Martial skill class covers combat skills related to the ***Strength*** *attribute.* A proficient Martial character is a force to be reckoned with in close quarters.

- One Handed Swords
- One Handed Axes
- One Handed Maces 
- Two Handed Swords
- Two Handed Axes
- Two Handed Maces 
- Tower Shields 
- Dual Wield Sword, Mace, Axe
- One Hand Two Hand

##### ***FINESSE*** 

*The Finesse skill class encompasses all types of offensive combat skills related to the* ***Dexterity*** *attribute.* Characters invested in Finesse are quick and deadly. Think quick flurries of strikes. 

- Daggers 
- Dual Wield Daggers
- Throwing Weapons
- Rapiers 
- Bucklers
- Shortsword
- Shortsword & Dagger

##### ***VERSATILITY***

*The Versatility class pertains to skills that scale with ***both Strength and Dexterity.***  Versatile fighters use unique weapons with a range of capabilities. 

- Spears
- Halberds
- Fist Weapons
- Quarterstaffs
- Flails
- Curved Swords
- Bows
- Crossbows

##### ***DESTRUCTION***

*Destruction deals with all things offensive, magically speaking. This Skill Class covers the various schools of offensive magic in Silmoren.* Characters with a vast knowledge of Destruction Magic are a maelstrom of magical energy and destruction, but can otherwise be quite fragile.

- The School of Nature
- The School of Mind
- The School of Force
- The School of Entropy
- The School of Conjuration 

##### ***ENCHANTING***

*Enchanting concerns everything ***Destruction*** *does not. It is primarily a skill class comprised of utilitarian and defensive magicks, with some exceptions.* Skilled Enchanters are masters of matter manipulation and diversion.

- The School of Space
- The School of Transmutation 
- The School of Illusion
- The School of Mirrors

##### ***INVOCATIONS**

*Invocations channel the pure faith of the user. They are powerful offensive and defensive tools, bathed in righteousness.* Skilled Invokers smite their enemies with holy fury from almost any range.

- Veryn's Armament 
- Dhorakkian Aegis 
- Faelid Wrath
- Vorra 
- Khaltic Hexbrand 
- Sylthan Architect 
- Eldritch Terror


### ***TALENTS***

**Talents are passive abilities that alter the intended effect of other Talents and Skills.** **Or, they can produce a new standalone passive buff.** *Very few, rare Talents are capable of both effects, providing a new passive buff as well as altering an existing Talent or Skill.* This interlaced *Talent Web* allows for combinations of various passive buffs, allowing Talents to synergize. You can equip a maximum of (12)* Talents at once. These are interchangeable at any Instructor or Rest. Talent Level is a hidden stat incorporated into the World Level, defined by number of talents activated. Maximum talent level adds to 250. Each talent is 20 points, and having maximum activated talents gives +10. ( For 250 ) **Talents are divided into Talent Classes of the same name as Skill Classes.**

##### ***MARTIAL***

*The Martial skill class covers combat skills related to the ***Strength*** *attribute.* A proficient Martial character is a force to be reckoned with in close quarters.

- One Handed Swords
- One Handed Axes
- One Handed Maces 
- Two Handed Swords
- Two Handed Axes
- Two Handed Maces 
- Tower Shields 
- Dual Wield Sword, Mace, Axe
- One Hand Two Hand

##### ***FINESSE*** 

*The Finesse skill class encompasses all types of offensive combat skills related to the* ***Dexterity*** *attribute.* Characters invested in Finesse are quick and deadly. Think quick flurries of strikes. 

- Daggers 
- Dual Wield Daggers
- Throwing Weapons
- Rapiers 
- Bucklers
- Shortsword
- Shortsword & Dagger

##### ***VERSATILITY***

*The Versatility class pertains to skills that scale with ***both Strength and Dexterity.***  Versatile fighters use unique weapons with a range of capabilities. 

- Spears
- Halberds
- Fist Weapons
- Quarterstaffs
- Flails
- Curved Swords
- Bows
- Crossbows

##### ***DESTRUCTION***

*Destruction deals with all things offensive, magically speaking. This Skill Class covers the various schools of offensive magic in Silmoren.* Characters with a vast knowledge of Destruction Magic are a maelstrom of magical energy and destruction, but can otherwise be quite fragile.

- The School of Nature
- The School of Mind
- The School of Force
- The School of Entropy
- The School of Conjuration 

##### ***ENCHANTING***

*Enchanting concerns everything ***Destruction*** *does not. It is primarily a skill class comprised of utilitarian and defensive magicks, with some exceptions.* Skilled Enchanters are masters of matter manipulation and diversion.

- The School of Space
- The School of Transmutation 
- The School of Illusion
- The School of Mirrors

##### ***INVOCATIONS**

*Invocations channel the pure faith of the user. They are powerful offensive and defensive tools, bathed in righteousness.* Skilled Invokers smite their enemies with holy fury from almost any range.

- Veryn's Armament 
- Dhorakkian Aegis 
- Faelid Wrath
- Vorra 
- Khaltic Hexbrand 
- Sylthan Architect 
- Eldritch Terror

##### ***DEFENSIVE***

*Defensive Talents augment the user's ability to wear armor and utilize shields.* 

- Light Armor 
- Medium Armor
- Heavy Armor
- Shields

##### ***TACTICA***

*Tactica talents deal with the exploitation of enemy weakness, as well as spellcraft and other magickal practices.*

- Parrying
- Battle Awareness
- Enemy Knowledge 
- Spellcraft
- Casting Arts 

# ***CHARACTER CREATION***

Characters are created on game start should the player not already have an existing save. **Players may pick from one of seven races, and from an assortment of starting gear. Players may choose one active skill to start with from their chosen Skill Class after a brief introduction.** 

## ***RACES*** 

**<u>The base attribute arrays of all the races are merely suggestions. All starting attributes can be redistributed at creation. </u>**

 [The Races of Silmoren]
 
 - Humans - Fathered by **Veryn**
 - Elves - Fathered by **Syltharien**
 - Dwarves - Fathered by **Dhorak**
 - Drakes - Mothered by **Vorrash**
 - Mycari - Mothered by **Faelith**
 - Undead - Created by **Morkhalt**
 - The Automatons - Created by **Syltharien**

### HUMANS 

Humans are widely known for their adaptability. After all, it was them who coined the phrase "Jack of all trades, master of none." *However, Humans have also shown to have a higher capacity to learn, meaning they gain skill experience slightly faster.* They eat, drink, and rest normally. They react to temperature normally. *Humans are also able to adopt the tradition of other cultures and learn certain talents specific to other Races,* however, **they can only learn one**. ***Humans may not replicate the talents of Drakes.*** This talent is permanent, and can be decided at any time through a specific ritual site. **Their base array is STR 4, DEX 4, INT 4, FTH 4, VIT 4, REF 4, MIN 4** 

### ELVES 

Elves hail from the far western continent, migrating to Kyndreth after the Elvish Liberation. They are masters of arcane knowledge due to their heritage. Elves start with an extra spell slot and an increased intelligence stat. They also have less of a chance to miss spells or ranged weapon strikes. They are also very nimble, making good hunters and rogues. Elves are also very fragile, their tall and slender physiques result in physical weakness. They take 15% more physical damage. Their ancestry also means that Elves take 10% less Faith-based damage. The Elves also have the unique ability to sense magic power, some apparently even able to draw the lifeforce out of others for use as fuel in their own spells. Humans can take the "Mana Lich" talent to replicate this. Elves eat and drink slightly less than humans, and rest slightly less as well. They are slightly more susceptible to temperature changes. Their base array is STR 4 , DEX 8, INT 10, FTH 4, VIT 5,  REF 6, MIN 5.

### DWARVES 

A sturdy and harsh people, the Dwarves lived atop the mountains on both continents for millennia until the Broken War. When that happened, the Mother Clans split. Some went under the peaks of their stony homes, while others opted to stay where they were. Many have died off as a result of a separation of the regular supply chain and the clans are now scattered. Seeing one roaming away from the clan is not common. Dwarves have always been stout believers in the importance of hearth and home, and that even extended to Dhorak. Long after his departure, they still hold him high on his pedestal. The Mountain King still reigns. **Dwarves start with extra points in Vitality and Strength.** *Dwarves also have a fondness for liquor, and they reap more positive benefits from regular consumption.* *When drunk, they have no Reflex debuff as other races would and gain +20% strength.* ***Humans can take the "Lush" talent to replicate this.*** *They eat, sleep, and drink slightly more than most races.* Dwarves are very resistant to cold, and react normally to heat. **Their base array is STR 9 , DEX 5, INT 4, FTH 7, VIT 8, REF 5, MIN 4.** in

### DRAKES 

Hailing from the far reaches of the west, the Drakes are a new race only alive for the last millennia or so. Dragons thrive on the presence of Magic, and when the Elves brought it east they followed it. Each type of dragon; Fire, Frost, Lightning, Acid, and the elusive Abyssal, retreated to their respective corners. The Fire Dragons flew to the Southern Desert, comforted by its warm sands. The Frost Dragons flew to the peaks of the Sister Mountains. Lightning Dragons took to the skies as they are a nomadic breed. Acid Dragons, the few of them left, scattered across the various swamps dotting Kyndreth and Valndir. The fabled Dark Wyverns, the Abyssal Dragons, almost fully disappeared. Across many different lands there were rumors of their existence, but it was only ever a lone dragon, and they were never validated. They breathed a cursed, dark mist. It spewed from their mouths in heavy jets of deadly fumes. Reports of the mist being accompanied by a black flame are few and far between, but nonetheless present. The Drakes were a result of the various Vorric Cults that spawned around the dragons' settlements. Exactly how they are conceived is unknown, but it is known that almost every member of each cult has utterly and entirely disappeared. Whether the Drakes are a result of some kind of sacrifice, or transformation ritual is unknown. They're humanoid hybrids of man and Dragon. Drakes usually have tall, athletic builds with scales matching the color of the dragon they represent, **as well as wield the matching breath weapon.** ***Breath weapons do not contribute to Character Level.*** Although the have unmistakable human faces, they also sport large wings and a tail, with longer ears similar to Elves. *They eat, drink, and sleep more than normal. They are averse to colder temperatures and must wear heavier clothing or drink ***Emberwine*** *to regulate themselves. They are not affected by heat. Drakes are also capable of limited flight (jumping higher/farther). Drakes also gain a bonus to their Intimidate ability.* **Their base array is STR 9, DEX 9, INT 8, FTH 3, VIT 3, REF 3, MIN 4** 

### MYCARI

The Mycari are a fading people. When the Mother Faelith died, nature began its slow decline into a sundered remnant of what it was. Forests began to die, oceans began to acidify, the dirt became unforgiving and hostile, killing crops in mere days and poisoning rivers and lakes. The Mycari exist in this place, an outcast in their own home. They are tall and yet stocky creatures, their heads crested by mushroom caps and smaller outcroppings of more fungus. They are quite literally *sentient fungal bodies.* Mycari reproduce asexually, and do not require sleep or food. **Instead, Mycari must enter a meditative state and undergo a form of photosynthesis. This state lasts for 12 hours and occurs every two days. Longer than two days, and Mycari begin to dwindle quite fast.**  ***Humans can take the "Asceticism" talent and replicate this.*** **Meditating leaves fungal spores, and allows all Mycari to respawn from this point.** *Mycari are also susceptible to cold temperatures, ***and*** *hot ones.* **Their base array is STR 5, DEX 5, INT 8, FTH 4, VIT 6, REF 4, MIN 8** 

### UNDEAD

The Undead were a consequence of Morkhalt's imprisonment. As his corruption seeped into the very earth, bodies began to rise from their graves. They exist only in the darkness of caves, and roam the wilds at night. They are not very common, but when they appear they are certainly not well received. Even less common are the ones that come back fully sentient, usually the product of some form of ritual. *Undead are vilified by the community and must stay under cover of night, due to which enemies may be more difficult. They must also stay in disguise when interacting with the general populace.* However, Undead can wear certain garb or use certain magic to hide their face and protect them from sun exposure. **Sun Exposure is a deadly side effect of undeath. Natural light directly from the sun will cause them to slowly burn to ash.** Undead do not eat, sleep, or drink. They do not react to temperature changes. They are also susceptible to Holy Invocations and take +30% Holy damage. Undead can breathe underwater, and are immune to Bleed and Poison effects. ***Humans can turn undead by undergoing a certain unholy ritual. This will take up their racial talent slot.*** **The Undead's base array is STR 4, DEX 4, INT 4, FTH 4, VIT 4, REF 4, MIN 4** 

### AUTOMATONS

The Automatons are not so much a people, but relics of the past. They were used in the Elvish Liberation by Syltharien against the elven people. They have the look of a suit of disembodied blazing silver armor, completely covered from head to toe in various forms of metal plating, but the faint whirring of mechanical gears cannot be mistaken. Operated by a device called a Soul Cage, they trap the stripped and purified consciousness of any sentient creature- mainly Elves.  When Syltharien departed from the realm, and many Elves fled the western continents, the Automatons went to sleep. They fell motionless for many centuries. However, centuries after the liberation, they have woken again. And not only that, but with their old selves intact. Many once elves woke to their home destroyed, the golden fields of the western world burnt to ash. Nothing was left. That was many centuries ago, and now they are here in the east. Some have gone feral, but many remain quite coherent. *They are generally disliked by the populace.* Automatons start with very high strength. **The also lack the capacity to cast magic or holy invocations, but can almost fully resist various forms of it.** *They also cannot wear regular armor, but only Automaton Plate. Automaton Plate is the some of the strongest, and each set will last you awhile. Automatons can also wield two-handed weapons in one hand.* ***Humans can take "Colossus" to replicate this.*** *They do not eat, sleep, or drink, but instead require continuous maintenance. They must also consume fuel regularly for the engine that powers the Soul Cage.*  This is done with the proper tools, and special resources like Automaton Oil or other specific Automaton parts. These parts are uncommon to find in the world, but can be bought from certain craftsmen reliably (albeit in small amounts). **Their base array is STR 16, DEX 2, INT 2, FTH 2, VIT 10, REF 2, MIN 8**

### ***STARTING SKILLS***
# ***THE WORLD***
*Chronicle* is set in the world of **SILMOREN** (Sil-MORE-en). The game actually takes place in the eastern hemisphere, which houses the sister continents **VALNDIR** (valn-DEER) and **KYNDRETH** (KIN-dreth). There are several biomes and regions to provide a variety of survival challenges. 

## KYNDRETH

*The Birthplace, "Majestic Kin"*

Kyndreth is a forested, grassy continent. It very much resembles places like Whiterun Hold, modern day Canada or Western Montana. Verdant fields and dense pine forests. Towering mountain ranges. To the south are some small marshlands. 

## VALNDIR

*The Wandering Land*

A vast desert-like continent. Most of the continent is deserted due to the high temperature and unforgiving landscape. To the northeast is a small savannah and some more forested islands. There are steppes to the southeast. Also contains **The Dead Marshes.**

## TIMELINE

The Complete Creation Myth of Silmoren


---

I. The Primordial Chaos

In the beginning, there was only Chaos.

A roiling maelstrom of unrelenting insanity—a sea of unfathomable colors and thoughts that devoured themselves the moment they formed. There was no time, no space, no meaning. Only the eternal cacophony of formless existence.

From this chaos, the Old Gods arose.

They were not architects or visionaries. They did not create with purpose. They simply did. They were creatures of raw id, divine embodiments of compulsion, hunger, and vanity. Their wills, untempered by wisdom or restraint, carved the void with careless fervor.

From their toils, the first landmass was birthed:
The Mother Continent, the foundation of what would become Silmoren.


---

II. The Eldritch Conflict and the Rise of the Assemblage

As the Old Gods toiled, they began to see themselves as separate. They noticed their differences. And with that realization came conflict.

The Old Gods fought not for territory, but for dominance, for the sheer sake of fighting. Their war tore the cosmos asunder, rending stars from the sky and drowning worlds in god-blood.

From the shadows of their eternal war arose the Lesser Deities, fragments of divine will coalesced into new forms—still flawed, yet with the potential to understand.

Veryn, whose indomitable will burned like an unquenchable flame.

Syltharien, the seeker, hungering for infinite knowledge.

Dhorak, the conqueror, craving dominion over land and soul alike.

Vorrash, a bottomless hunger, desiring always more.

Faelith, who sought only to savor the fragile beauty of creation.

Zephariel, the silent chronicler, who birthed Time to give meaning to existence.

Morkhalt, the watcher, the quiet one, who understood more than he ever spoke.


The Old Gods used these Lesser Deities as tools, pawns in their cosmic games. But gods, even lesser ones, cannot be bound forever.

They grew weary of being weapons. They yearned for freedom.

In secret, they forged a weapon capable of doing the impossible—killing a god.

Dhorak hammered the blade with Syltharien’s guidance.

Faelith watched with sorrow.

Morkhalt wove dark truths into its core.

And Veryn, the unbreakable, took up the blade.


Thus began the Eldritch Conflict—a rebellion against their creators. Worlds were torn apart, and the Old Pantheon fell, their deaths birthing storms of divine ash and rivers of god-blood.

When the dust settled, the Lesser Deities stood triumphant.
They were no longer lesser. They were gods.

They called themselves The Assemblage.


---

III. The Sundering of the Mother Continent

The Mother Continent, ravaged by war, was left broken. The Assemblage reshaped it, but its wounds never fully healed.

Kyndreth, to the north, became The Birthplace—a land of structure, forged with divine precision.

Valndir, to the south, became The Wanderer’s Land—wild, untamed, where the echoes of chaos still whispered.


But land alone was not enough. The Assemblage hungered to fill the world with life, beings who could reflect their glory—and perhaps, their mistakes.


---

IV. The First Mortals and the Elvish Liberation

The first to create was Syltharien, whose thirst for knowledge was endless. From starlight and song, he crafted the Elves—tall, ethereal beings, reflections of his own boundless curiosity. They were his scholars, his archivists, recording every fragment of wisdom he unearthed.

But in his arrogance, Syltharien gifted them something dangerous:
Free will.

At first, they served willingly, chronicling his infinite works. But as eons passed, they grew restless. They saw their lives not as sacred, but as shackles.

And in their rebellion, they heard Morkhalt’s whisper.

The silent god, ever watchful, gifted them with the first form of true power: Magic. Not divine power, but raw, unbound energy—a force shaped by will alone.

Thus began the Elvish Liberation.

Elves fled north to Kyndreth, seeking freedom. Syltharien, enraged by their defiance, hunted them. Those he recaptured were transformed into Soul Cages, their spirits imprisoned to fuel monstrous creations called Automatons—soulless suits of metal, bound forever to his will.

But the spark of rebellion could not be extinguished. The Elves, fractured but free, endured.


---

V. The Birth of the Other Races

In the wake of the Elvish Liberation, the other gods created their own mortal children:

Veryn shaped Mankind in his image—resilient, ambitious, ever striving to bend the world to their will.

Dhorak forged the Dwarves—stout, unyielding, carved from stone and steel, masters of craft and conquest.

Vorrash mothered the dragons, reflections of her tempestuous lust for power. 

Morkhalt, in his silent experiments, gave rise to the Undead—creatures neither alive nor dead, bound by dark truths mortals were never meant to know.

Faelith wove life from nature itself, creating the Mycari — living humanoid fungal growth, animated by the pure essence of the world. 


For a time, peace reigned. Mortals built kingdoms, forged alliances, waged petty wars. The gods watched, distant yet ever-present.

But divine hubris knows no end.


---

VI. The Broken War and the Fall of Faelith

Inevitably, the gods clashed once more. Old rivalries, buried beneath the sands of time, ignited like dry tinder.

The conflict swept across Silmoren—the Broken War—a cataclysm that shattered empires and scarred the world.

In the chaos, Faelith fell first. She died amidst her beloved forests, her essence woven into the very roots and rivers of the land she cherished. Her death left vast regions to wither, turning verdant realms into lifeless husks.

Dhorak survived the war, though scarred in ways no forge could mend. His hunger for dominion tempered, but never extinguished.

Meanwhile, Morkhalt moved in the shadows, sowing seeds of corruption. He whispered to mortals, turning them against their divine patrons. He watched as his siblings bled, indifferent to their suffering.

When his betrayal grew too great to ignore, the gods united one final time:
They imprisoned Morkhalt deep beneath the oceans, chaining him in the abyss where no light could reach.

The gods, weary and broken, vanished soon after, leaving mortals to inherit a world scarred by divine arrogance.


---

VII. The Present Day: A World Slowly Dying

Now, Silmoren is a world slowly dying.

Morkhalt’s seething corruption festers beneath the oceans, seeping into the land. Entire regions rot from within, their people twisted into monstrous reflections of themselves. The Undead rise in droves, their empty eyes bearing silent witness to the god who birthed them.

After Syltharien’s departure, the Automatons—once soulless constructs—have awakened, their bound elven souls stirring. They are now fully sentient, trapped within cold metal husks, burdened by memories of a life long lost.


Kingdoms rise and fall, their histories forgotten beneath layers of ash and ruin. Mortals live, love, fight, and die, unaware of the cosmic threads that shaped their fate.

But a new force stirs.

A hero rises—neither fully divine nor truly mortal. A being shaped by the echoes of the past and the weight of the present.

They are called the Mortal God.

It is they who will face the festering rot beneath the waves. It is they who will confront the legacies of gods long gone. And it is they who will decide the fate of Silmoren—
To rid the world of divinity forever…

…for better or worse.

I'm