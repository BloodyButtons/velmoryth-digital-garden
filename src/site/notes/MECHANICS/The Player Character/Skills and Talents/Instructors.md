---
{"dg-publish":true,"permalink":"/mechanics/the-player-character/skills-and-talents/instructors/","noteIcon":""}
---


Chronicle discards the classic “open a panel and click +” paradigm.  

Every new ability is a social, geographic, or experiential milestone tied to **Instructors** and, at the pinnacle, **Grandmasters**.  

This document lays out the system in full: the ethos, architecture, locations, progression logic, and how it differs from mainstream RPG models.

---

## Design Ethos

| Pillar | Implementation | Classical Contrast |
|--------|----------------|--------------------|
| **Diegetic Progression** | Power comes only from people you meet and challenges you master—not UI trees. | *Elder Scrolls V* exposes every perk in a menu; Chronicle keeps catalogues in-world. |
| **Exploration as Curriculum** | Skills are regional; the map itself is your course schedule. | *Diablo IV* lets you respect in town; Chronicle makes the journey matter. |
| **Earned Mastery** | Early fizzle/ miss rates, mentor quests, and bespoke trials make each upgrade feel fought-for. | *Modern MMORPGs* auto-unlock at level-up. |
| **Scarcity, not Infobloat** | ~20 unique mentors world-wide, each thematic and memorable. | *Path of Exile* features 1 300+ nodes; players rely on third-party planners. |

---

## Instructor Framework

### 2.1  Tier-Progressive Mentors

* A settlement hosts **one** mentor per attribute cluster.  

* Through a short, story-aligned quest (bounty, ritual, lesson) you promote that mentor:
  
  * **Apprentice → Journeyman → Master**

* Promotion unlocks higher-rank skills and raises Writ cost tier.

### 2.2  Currency

* **Tin Writ** – common, Rank 1 skills  

* **Iron Writ** – uncommon, Rank 2-3 skills  

* **Last Writ** – rare, Rank 4 capstone skills / modifier runes  

*(Full drop-rates in Economy chapter.)*

### 2.3  One-Time Attribute Gift

* Completing a mentor’s first promotion quest grants a **single +2** to that mentor’s governing attribute.  

* No repeatable or weekly boosts exist—stat identity remains meaningful.

### 2.4  Discovery & Feedback

* **Clues**: lorebooks, regional NPC rumours, mentor dialogue.  

* **Feedback**: every key event fires a 2-second toast:  
 
  * “Skill Learned – Frost Spike”  
  
  * “New Mentor Rank – Journeyman”  
  
  * “Talent Available – Bulwark”  

  * “The World Grows Stronger (+1)”

### 2.5  Why Instructors Matter

1. **Narrative glue** – each mentor embodies Chronicle’s cultures: forge-monks, plague clerics, swamp cut-throats.  

2. **Difficulty pacing** – since [[MECHANICS/Difficulty/Components/World Level\|World Level]] recalculates only on rest (once per 24 h), mentor hunts naturally throttle power spikes.  
3. **Replayability** – different build goals send players to different corners of the map every run.

---

## Geographic Network

| Site                  | Mentor Coverage & Rank Cap                                  | Lore Rationale                                   |
| --------------------- | ----------------------------------------------------------- | ------------------------------------------------ |
| **Lasthearth**        | All attributes – up to Journeyman                           | Largest frontier keep; mercenary melting pot.    |
| **The Crucible**      | **STR • VIT • FTH** – up to Master                          | Volcanic forge-city; paladin legions train here. |
| **Grimholt**          | **FTH • MIN** – Journeyman→Master                           | Silent monastery; scholars of fate and decay.    |
| **Gloamsrest**        | **DEX • STR** – Apprentice→Master                           | Fog swamp; haven for spear raiders & smugglers.  |
| **The Den** (roaming) | All attributes – up to Journeyman                           | Black-market haven; good early fallback.         |
| **Eldermere**         | **INT • MIN** – Apprentice→Master                           | Ruined elven academy; arcanists linger.          |
| **Chapel of Decay**   | **FTH • MIN • DEX** – Journeyman→Master                     | Living city; hex-clerics and assassins.          |
| **Forsaken Ascent**   | **STR • VIT • REF** – **Grandmaster** (Defensive/Evasion)   | Battlehome; tests raw endurance.                 |
| **The Black Hollow**  | **INT • REF • DEX** – **Grandmaster** ([[MECHANICS/The Player Character/Skills and Talents/Magic/Magical Skills/Destruction/Destruction\|Destruction]]/[[MECHANICS/The Player Character/Skills and Talents/Physical Skills/Finesse/Finesse\|Finesse]]) | Arcane abyss; only agile minds survive.          |

**Attribute Coverage**

| Attribute | Where to Study |
|-----------|----------------|
| STR | Crucible · Gloamsrest · Forsaken Ascent · Lasthearth · Den |
| DEX | Gloamsrest · Chapel of Decay · Black Hollow · Lasthearth · Den |
| INT | Eldermere · Black Hollow · Lasthearth · Den |
| FTH | Crucible · Grimholt · Chapel of Decay · Lasthearth · Den |
| VIT | Crucible · Forsaken Ascent · Lasthearth · Den |
| REF | Forsaken Ascent · Black Hollow · Lasthearth · Den |
| MIN | Grimholt · Eldermere · Chapel of Decay · Lasthearth · Den |

---

##  Grandmasters

* **Nine in total**—one per skill class—each in a bespoke micro-location reachable only through lore navigation.  

* Completely optional but bestow:
  
  * **Rank 4 skill** + unique **Modifier Rune**
 
  * **Signature Boon** – permanent, small, flavourful (never raw attribute)

Each Grandmaster corresponds to an attribute, and in this way, **the skill they reward is based off the highest level of** ***Skill Class*** **pertaining to that attribute. (Subject to change, a list of available skills pertaining to the attribute is better)** One character may learn a high level destruction tier after passing the Intelligence trial, while another may learn a powerful summon or enchantment.

### 4.1  Trial Themes

| Attribute        | Trial Type                       | Venue Example                      |
| ---------------- | -------------------------------- | ---------------------------------- |
| [[MECHANICS/The Player Character/Skills and Talents/Physical Skills/Martial/Martial\|Martial]]      | Honour duel                      | Cliff-top arena above roaring surf |
| Finesse          | Stealth keep → duel on detection | Dilapidated marsh-fort             |
| [[MECHANICS/The Player Character/Skills and Talents/Physical Skills/Versatility/Versatility\|Versatility]]  | Adaptive gauntlet of mixed waves | Ringed coliseum with weapon racks  |
| [[MECHANICS/The Player Character/Attributes/Intelligence\|Intelligence]] | Timed runic puzzle vault         | Floating crystal spire             |
| [[MECHANICS/The Player Character/Attributes/Mind\|Mind]]         | Mirror maze, illusionary doubles | Eldritch library beneath Grimholt  |
| [[MECHANICS/The Player Character/Attributes/Faith\|Faith]]        | Relic retrieval + moral choice   | Catacombs below Chapel of Decay    |
| [[MECHANICS/The Player Character/Attributes/Vitality\|Vitality]]     | Blizzard endurance waves         | Summit caves of Forsaken Ascent    |
| [[MECHANICS/The Player Character/Attributes/Reflexes\|Reflexes]]     | High-speed trap course           | Collapse tunnels in Black Hollow   |

*Rematch allowed; death or retreat simply restarts the trial.*

### 4.2  World Impact

* Defeating a Grandmaster triggers a world news rumour and raises loot quality in their region.  

* World Level still respects the 24 h rest gate—no sudden double spikes.

---

## Classical Comparison Snapshot

| Pillar | Chronicle | Gothic (2001) | Elden Ring | PoE |
|--------|-----------|---------------|------------|-----|
| Skill Access | Mentor quests + Writs | Trainers with gold | Buy Ashes & incantations | Menu tree |
| Stat Boosts | Single +2 per mentor | Pay LP each level | Level-up only | Gear, passives |
| Capstones | Optional Grandmasters | Dragon Slayer runes | Remembrance bosses | Ascendancies |
| Difficulty Sync | WL rest-gate + loot boost | Static zones | Static zones | Self-scaling maps |

---

### Player Journey at a Glance

1. **Early game** – Train at Lasthearth, The Den.  

2. **Mid game** – Specialise via Crucible, Gloamsrest, Grimholt, Eldermere, Chapel.  

3. **Late game** – Pilgrimage to Forsaken Ascent and Black Hollow for Grandmaster boons.  

4. Every rest recalibrates the world: enemies tougher, loot richer.

Chronicle thus anchors every progression beat—skill, stat, and capstone—to physical places, living mentors, and tangible stories, upholding its mandate that *mastery must be discovered, not toggled in a menu*.