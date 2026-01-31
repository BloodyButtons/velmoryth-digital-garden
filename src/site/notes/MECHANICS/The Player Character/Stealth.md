---
{"dg-publish":true,"permalink":"/mechanics/the-player-character/stealth/","noteIcon":""}
---


---

<center>A KNIFE IN THE DARK</center> 

---

*Chronicle* handles stealth through two primary channels, **vision** and **sound**, modulated by lighting, loadout, and the player’s **Sneak talent** (Ranks 1 - 5). Remove vision or noise and you remain unseen; fail either check and nearby AI can acquire you.

---
 
## Vision‑Cone Detection

Every foe projects two cones:

| Cone Type  | Base Width | Base Length | Notes                            |
|------------|-----------|-------------|----------------------------------|
| Front      | 120°      | 12 m        | Direct focus area                |
| Peripheral | 60°       | 6 m         | Flicker checks every 0.7 s       |

**Sneak Rank** narrows both cones:

<center>EffectiveWidth = BaseWidth × (1 ÷ Rank)</center>

| Sneak Rank | Front Width | Peripheral Width |
|------------|-------------|------------------|
| 0          | 120°        | 60°              |
| 1          | 108°        | 54°              |
| 3          | 96°         | 48°              |
| 5          | 72°         | 36°              |

**Light tiers** shorten or lengthen cone reach:

| Light Level | Length Multiplier |
|-------------|------------------|
| Bright      | × 1.0            |
| Dim         | × 0.7            |
| Dark        | × 0.4            |

_Player‑held flames override ambient and count as Bright._

---
## **Detection Formula**  

A player is spotted if **all** are true:

1. Player’s position intersects an AI cone (after width/length modifiers).  

2. Player’s *Stealth Value* is lower than the AI’s *Perception*.  

3. Player’s noise pulse overlaps the AI’s hearing radius (see noise model).

<center>StealthValue = (DEX + 5×SneakRank) - (ArmorPenalty + EncumbrancePenalty) + LightBonus </center>

<center>LightBonus = +10 in Dark, +0 in Dim, -10 in Bright</center>

---

### Noise Model

Every step emits a sound sphere whose **radius** is calculated:

<center>NoiseRadius = BaseStep × Surface × [[MECHANICS/The Player Character/Equipment/Armor/Armor\|Armor]] × [[MECHANICS/The Player Character/General Stats/Encumbrance\|Encumbrance]] × Crouch × Talent × DexFactor
</center>

| Factor          | Multiplier                                    |
| --------------- | --------------------------------------------- |
| **BaseStep**    | 2 m                                           |
| **Surface**     | Stone 1.2 / Wood 1.0 / Grass 0.7 / Water 1.4  |
| **[[MECHANICS/The Player Character/Equipment/Armor/Armor\|Armor]]**       | Light 1.0 / Medium 1.1 / Heavy 1.25           |
| **[[MECHANICS/The Player Character/General Stats/Encumbrance\|Encumbrance]]** | Unburdened 1.0 / Burdened 1.10 / Heavily 1.25 |
| **Crouch**      | 0.5 if crouch‑walking                         |
| **Talent**      | 0.9^SneakRank                                 |
| **DexFactor**   | 1 – 0.01 × (max(DEX – 12, 0))                 |

---

## *Examples*  

- An Unburdened rogue ([[MECHANICS/The Player Character/Equipment/Armor/Light Armor\|Light armor]], DEX 16, Sneak 4) on grass while crouched:

<center>Noise = 2 × 0.7 × 1.0 × 1.0 × 0.5 × (0.9^4=0.66) × (1‑0.04) ≈ 0.44 m</center>

- A Heavily‑burdened knight ([[MECHANICS/The Player Character/Equipment/Armor/Heavy Armor\|Heavy armor]], DEX 10, Sneak 0) on stone walking upright:

<center>Noise = 2 × 1.2 × 1.25 × 1.25 × 1 × 1 × 1 ≈ 3.75 m</center>

---
### **Action Noise**  

Opening a chest, drawing a bow, or quaffing a potion emits a one‑time pulse of 3 m (modified only by SneakRank when crouching.)

---

### Player Feedback (Low‑UI)

* A faint border vignette grows brighter as vision or noise thresholds near detection.  

* A soft “heart‑thump” audio cue plays when an AI’s cone is about to overlap.  

* Crosshair flashes pale blue when fully hidden (neither cone nor noise overlap).

---

### System Interactions

* **[[MECHANICS/The Player Character/General Stats/Stamina\|Stamina]]** - Crouch movement drains 0.5 SP per second; running drains normal SP but doubles footstep radius.  

* **Encumbrance** - Higher load increases both noise and [[MECHANICS/The Player Character/General Stats/Stamina\|stamina]] drain, forcing inventory trade‑offs for stealth runs.  

* **[[MECHANICS/Combat/Components/Posture\|Posture]] & [[MECHANICS/Combat/Components/Critical Windows\|Critical Windows]]** - Striking from a hidden state triggers an automatic Critical Window.  

* **Throwing Weapons** - Smoke bombs instantly set local Light to Dark for 4 s, shrinking cones; the glass shatter counts as a 2 m noise pulse.  

* **[[MECHANICS/The Player Character/Skills and Talents/Magic/Magical Skills/Illusionism/Illusion\|Illusion]] Magic** – Minor “Veil” spell applies LightBonus +10 for 10 s; advanced “Shadow Mantle” adds SneakRank +1 (temp).  

* **Racial Quirks**   
  
  * [[MECHANICS/The Player Character/Race/Machination\|Machination]] joints add a flat +0.2 m to BaseStep unless recently oiled (maintenance consumable).  

  * [[MECHANICS/The Player Character/Race/Undead\|Undead]] have no heartbeat or breathing: automatic 0.2 m noise reduction, but heavy armor still clanks.

---

### Balancing Levers

* Adjust cone multipliers, noise radii, or the LightBonus constants without rewriting the framework.  

* Elite enemies can gain “True Sight” (ignore one SneakRank) to ensure late‑game challenge.  

* Dungeon designs control stealth difficulty via lighting layout and flooring material.

---

### Design Goals Recap

* **Readable but Tense** - Cones + noise give discrete stealth math while keeping the ambience diegetic.  

* **Stat Relevance** - [[MECHANICS/The Player Character/Attributes/Dexterity\|Dexterity]], Sneak talent, armor class, and encumbrance all visibly matter.  

* **Sandbox Friendly** - Smoke bombs, light spells, load‑out tweaks let players invent solutions instead of following scripted paths.