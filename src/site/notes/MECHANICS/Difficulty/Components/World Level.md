---
{"dg-publish":true,"permalink":"/mechanics/difficulty/components/world-level/","noteIcon":""}
---


---

<center>HOW VELMORYTH RESPONDS TO PLAYER ACTION</center> 

---

Difficulty in Chronicle is not a static toggle. It is a reflection of time, power, and consequence. The stronger the player becomes and the longer they survive, the more the world pushes back. There are no safe zones, no perfectly balanced encounters, only survival in a world that is always watching, and always changing.

---

## World Level

Difficulty isn’t about punishing the player, it’s about preserving danger. In many RPGs, power leads to safety. In Chronicle, power invites attention. The more capable you become, the more the world acknowledges you and resists. This is reflected through the World Level value.

This approach ensures that challenge persists organically, rather than through artificial gates or difficulty spikes.

It also complements Chronicle’s other pillars:

[[MECHANICS/The Core Pillars/Exploratory Survival\|Exploratory Survival]]: Stronger players must still prepare, as tougher enemies make every journey treacherous.

[[MECHANICS/The Core Pillars/Immersion\|Immersion]]: No damage numbers or enemy level tags break immersion—just the feeling that something out there is watching you, growing with you.

[[MECHANICS/The Core Pillars/Combat\|Combat]]: Stats lethal. An ever present challenge. A constant test of strength

<center>World Level = Time + Power</center>

World Level is how difficulty scales, calculated from two variables, ***Time*** and ***Character Level***.

### Time Passed

The longer you play, the more the world responds.

New enemies migrate, mutated variants appear, and familiar threats grow in number or aggression.

Easy Mode disables this mechanic entirely.

Normal Mode enables it by default.

Hardcore Mode enables it aggressively, including world events like spreading miasma, with no option to pause and introduces permanent character death.


### Character Level

This is a hidden measure, quietly tracking a player’s growth. There are no level indicators in Chronicle available to the player, It is totaled by adding [[MECHANICS/Difficulty/Components/Skill Level\|Skill Level]], [[MECHANICS/Difficulty/Components/Talent Level\|Talent Level]], and [[MECHANICS/Difficulty/Components/Item Level\|Item Level]] resulting in [[MECHANICS/Difficulty/Components/Character Level\|Character Level]]. 

This system subtly adjusts the world’s difficulty without breaking immersion or introducing artificial enemy scaling. 

## World Level & Time

After **Character Level** (CL) is totaled, the **time** variable is added to determine **World Level**. Because *time* itself can reach a maximum of **1000** points, the combined total of **CL + Time** caps at **2000**. 

#### How Time Accumulates

- **+2.5 points per in-game day**  
- **+25 points every 10 days**  
- **+250 points every 100 days**  

After roughly **one in-game year**, time hits its **1000-point** cap though this can be adjusted in the settings or set during character creation if you want a slower or faster progression.

#### World Level & Combat Scaling

For every **125 points** of **(CL + Time)**, enemies gain:
- **+10% Damage** and **+5% Health**  
- Meanwhile, *players* also gain **+7.5%** to both damage and health.  

This escalates **additively** at each threshold:
- At **maximum** World Level (2000 points), **enemy damage** is at **+190%** and **enemy health** at **+80%**.  
- Players enjoy **+120%** to damage and health.

> **Note**: The final **three tiers** (WL14-16) give enemies a significantly larger damage boost, keeping combat **quick and lethal** as you approach endgame conditions. These numbers may be fine-tuned based on testing to ensure the game’s hallmark **survival challenge** remains balanced.

The world always remains slightly ahead.

See the table below for more visual data;

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

## World Level & Loot

World Level gradually scales loot quality as well, This results in a sort of snowball effect, whereas better loot provides better bonuses to [[MECHANICS/The Player Character/Attributes/Attributes Overview\|attributes]], thereby increasing the rate of scaling. Please see the table below to better understand how this is combated and adjusted to smooth the curve. 

#### Table Values 

- **Loot Quality Mod**: Represents the percentage boost to the chances of higher-tier loot as the world level increases. This affects the drop chances for Rares, Epics, and eventually Legendaries.

- **Outlier Chance (±Tier)**: A 10% chance for an "outlier" drop, which can either yield a lower-tier item or an item above the typical World Level tier. This keeps the loot exciting and unpredictable, even at higher levels.

- **Base Legendary Chance**: A baseline probability (which grows with World Level) that ensures Legendary drops remain a rare but consistent possibility, regardless of current content difficulty.

- **Stat Bonus Range**: The range of attribute bonuses provided by loot at each World Level, growing slightly with

| **WL** | **Loot Quality Mod** |      **Typical Tier Range**      | **Stat Bonus Range** |    **Outlier Chance (±Tier)**    | **Base Legendary Chance** | **Notes**                                                                                                         |
| :----: | :------------------: | :------------------------------: | :------------------: | :------------------------------: | :-----------------------: | :---------------------------------------------------------------------------------------------------------------- |
| **0**  |   +0%   (Baseline)   |   Tier 1–2 (Common → Low Unc.)   |       +1 to +3       | 10% (5% sub-tier, 5% above-tier) |         **0.1%**          | Almost all gear is Common/Uncommon. A tiny sliver can pop up as Legendary, a once-in-a-blue-moon miracle.         |
| **1**  |         +5%          |   Tier 1–3 (Common → Uncommon)   |       +2 to +4       |               10%                |         **0.2%**          | Uncommon items appear more reliably. Still a minuscule chance for a Legendary spark.                              |
| **2**  |         +10%         |    Tier 1–3.5 (High Uncommon)    |       +2 to +5       |               10%                |         **0.3%**          | Increasing chance of better Uncommons. Rarely, a Legendary dream item emerges.                                    |
| **3**  |         +15%         |    Tier 2–4 (Uncommon → Rare)    |       +3 to +5       |               10%                |         **0.4%**          | Rares emerge in small numbers. Legendary is fractional but possible.                                              |
| **4**  |         +20%         |     Tier 2–4.5 (Rare Likely)     |       +3 to +6       |               10%                |         **0.5%**          | Solid Rare possibility. 1-in-200 drops might be Legendary.                                                        |
| **5**  |         +25%         |  Tier 2.5–5 (Comfortable Rare)   |       +4 to +7       |               10%                |         **0.7%**          | Rares become more common. Legendary chance inches up.                                                             |
| **6**  |         +30%         |     Tier 3–5.5 (Stable Rare)     |       +4 to +8       |               10%                |         **0.9%**          | High-end Rares appear often from bosses.                                                                          |
| **7**  |         +35%         |    Tier 3–6 (Rare → Low Epic)    |       +5 to +8       |               10%                |         **1.1%**          | Epics appear rarely. Legendary is still a long shot, but possible.                                                |
| **8**  |         +40%         |  Tier 3.5–6.5 (Solid Rare/Epic)  |       +5 to +9       |               10%                |         **1.3%**          | Epics more likely on strong foes. Legendary is still a long shot, but possible.                                   |
| **9**  |         +45%         |     Tier 4–7 (Epic Emerges)      |      +6 to +10       |               10%                |         **1.6%**          | Epics show reliably from major bosses; Legendary is around ~1.6%.                                                 |
| **10** |         +50%         |    Tier 4.5–7.5 (Epic Window)    |      +6 to +11       |               10%                |         **2.0%**          | Rares are nearly guaranteed on elites, Epics frequent for bosses, ~1 in 50 chance of Legendary.                   |
| **11** |         +55%         |    Tier 5–8 (Confident Epic)     |      +7 to +12       |               10%                |         **2.4%**          | Epics appear for top-tier enemies; Legendary is a bit higher.                                                     |
| **12** |         +60%         |     Tier 5.5–8.5 (Late Epic)     |      +7 to +13       |               10%                |         **2.8%**          | A near 3% Legendary chance from big encounters.                                                                   |
| **13** |         +65%         | Tier 6–9 (High Epic + Rare Leg.) |      +8 to +14       |               10%                |         **3.3%**          | Legendaries not unheard of at endgame content.                                                                    |
| **14** |         +70%         |  Tier 6.5–9.5 (Peak Epic Range)  |      +8 to +15       |               10%                |         **3.8%**          | Epics are the norm for final-tier elites. Legendary edges closer to ~4%.                                          |
| **15** |         +75%         |  Tier 7–9.5 (Very Strong Epics)  |      +9 to +16       |               10%                |         **4.3%**          | Late epics abound, Legendary grows to 1 in ~23.                                                                   |
| **16** |         +80%         |  Tier 7.5–10 (Epic → Legendary)  |      +9 to +17       |               10%                |         **5.0%**          | The toughest foes have a ~1 in 20 chance of dropping Legendary-tier gear, with outliers surpassing standard tier. |



## World Anchors

Certain safe havens (e.g., Lasthearth) could resist world scaling, remaining steady to act as long-term settlements or hubs. These are known as Anchors. This is better detailed in the [[MECHANICS/Overworld/Settlements\|Settlements]] section.

## Player Feedback 

To help players understand growing difficulty without UI numbers, when World Level increase the player character will dream upon their next rest. These are randomly selected and their are a variety of scenarios detailed below. They are always foreboding, telling of imminent danger, or nightmarish. 

### Dream Sequences by World Level

WL 1

> You dream of a lonely bird soaring over the Silent Plains. A single black arrow cuts through the moonlit sky. It strikes true, and the bird tumbles, wounded. You sense your foes have grown bolder.


WL 2

> In your sleep, a thick fog creeps through a forgotten graveyard. From the gloom, a gaunt figure rises, eyes flickering with pale fire. You awaken certain that the land grows more dangerous.


WL 3

> You see a candlelit banquet hall filled with silent diners, their eyes hollow. At the head of the table, a robed shape lifts a chalice brimming with blood. You feel the weight of new threats.


WL 4

> A howling wind sweeps through an ancient forest, toppling trees. In the chaos, bestial silhouettes dart among the roots, eyes shining. You stir, knowing the wilds have grown more savage.


WL 5

> Rain lashes a barren field. You stand amid the mud, sinking deeper with each step. Figures around you rise from the mire, skeletal arms grasping. Dawn comes, but the dread remains.


WL 6

> You drift through a city of shadows, deserted streets echoing with distant screams. Something immense prowls behind the walls. You wake, heart pounding, feeling new terrors stirring.


WL 7

> Shimmering lights dance over a corrupted lake. Beneath the surface, twisted shapes glide closer. Their whispers trail you back into waking—where you know the danger has intensified.


WL 8

> Lightning fractures a black sky, and for an instant, you see legions of the dead marching on a distant horizon. Their footsteps reverberate in your mind. You sense a deeper malice unleashed.


WL 9

> A colossal door of rune-etched stone creaks open. From the darkness beyond, cold eyes watch you. You stumble awake, certain that even locked horrors now stir and walk in Velmoryth.


WL 10

> A single candle flickers in an abandoned temple. It gutters out, leaving you in pitch-black silence. Then you hear slow, scraping footsteps closing in. Dawn breaks, but the menace lingers.


WL 11

> You’re on a desolate road, hands stained with ash. Crimson clouds boil overhead, and a mournful horn blares in the distance. You rouse gasping, convinced that doom marches ever closer.


WL 12

> A silver mirror stands in the center of a ruined hall. You peer into it: your reflection wavers, consumed by a writhing shadow. When you bolt upright, your breath is ragged, dread unshakable.


WL 13

> Smoke rises from a fortress on a cliff’s edge. You hear screams behind the walls, but you cannot enter—gates of twisted iron refuse you. You wake, drenched in sweat, dread echoing.


WL 14

> A regal throne room stands in dust. Long-dead knights kneel before a silent monarch whose crown glimmers with red embers. When the monarch’s gaze meets yours, you are banished to waking.


WL 15

> Labyrinthine corridors stretch endlessly, each corridor lined with rotting tapestries. You run, but the halls shift and twist. Far away, you hear a chorus of tormented wails. You rise, shaken.


WL 16

> In endless night, a crimson moon hangs above a battlefield of broken swords. A towering figure gestures toward you, and the dead rise at its command. The final darkness beckons.


## World Reset Mechanics

Rare rituals or sacrifices can reduce World Level temporarily, but always at a cost. 

Offering a powerful weapon up to the powers that be, killing a corrupted NPC, or giving up a [[MECHANICS/The Player Character/Skills and Talents/Skills And Talents\|skill]] you've mastered are all ways of doing this. 


> “The world forgets you, for a time...”



