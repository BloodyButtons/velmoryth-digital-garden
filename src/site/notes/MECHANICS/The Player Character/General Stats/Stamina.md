---
{"dg-publish":true,"permalink":"/mechanics/the-player-character/general-stats/stamina/","noteIcon":""}
---


---

<center>THE ENGINE</center>

---

If [[MECHANICS/The Player Character/General Stats/Health\|Health]] is the body’s structural integrity and [[MECHANICS/The Player Character/General Stats/Mana\|Mana]] the [[MECHANICS/The Player Character/Attributes/Mind\|mind]]’s arcane reservoir, **Stamina** is the kinetic engine that powers *everything* you physically do in *Chronicle*.  
From sprinting across the Silent Plains to chaining great‑sword combos or drawing a longbow, Stamina governs **how long** and **how hard** you can act before exhaustion sets in.

---

### Deriving Stamina

Stamina is primarily a function of **[[MECHANICS/The Player Character/Attributes/Vitality\|Vitality]]** (overall conditioning) with a minor contribution from **[[MECHANICS/The Player Character/Attributes/Dexterity\|Dexterity]]** (efficiency of movement):

<center>Base SP  =  80  + (Vitality × 4)  + (Dexterity × 1)</center>

| VIT | DEX | Base SP |
|-----|-----|---------|
| 8   | 8   | 112 SP  |
| 10  | 10  | 130 SP  |
| 12  | 12  | 148 SP  |
| 14  | 10  | 146 SP  |
| 16  | 6   | 144 SP  |

*Gear bonuses* ([[MECHANICS/The Player Character/Equipment/Armor/Light Armor\|Light Armor]] padding, enchanted [[MECHANICS/The Player Character/Equipment/Accessories/Rings\|rings]]) may add flat SP (+10) or percentage regen (+4 %/min).

---

###  What Consumes Stamina?

| Action                    | Cost (SP) | Notes |
|---------------------------|-----------|-------|
| Light weapon attack       | 6–10      | Scales with [[MECHANICS/Combat/Components/Weapon Tempo\|Weapon Tempo]] and size |
| Heavy weapon swing        | 15–25     | Greatswords, warhammers, greataxes |
| Bow shot / Crossbow reload| 8–16      | Strength lowers reload cost, DEX lowers draw cost |
| Dodge / dash              | 10–18     | Cost rises with Encumbrance tier |
| Sprint (per second)       | 4–6       | Cost rises with load and terrain slope |
| Shield block (on impact)  | 3–12      | Light < Heavy < Tower; flail impact +20 % |
| Spell channel (if applicable) | 1–3/sec | Certain physical invocations or channeled buffs |

> **[[MECHANICS/Combat/Components/Posture\|Posture]] Tie‑In:** [[MECHANICS/Combat/Components/Blocking\|Blocking]] or perfect parries convert a fraction of the incoming stamina cost into enemy posture damage; emptying your own SP increases posture damage taken.

---

### Regeneration & Exhaustion

#### Base Regen

* 5 % of Max SP per second **out of combat**.  

* 2 % of Max SP per second **in combat**.

#### Modifiers

* [[MECHANICS/Survival/Components/Fatigue\|Fatigue]] Stage 1 (no sleep ≈ 18 h): regen ‑25 %.  

* [[MECHANICS/Survival/Components/Hunger\|Hunger]]/[[MECHANICS/Survival/Components/Thirst\|Thirst]] severe: regen ‑50 %.  

* Overloaded Encumbrance: regen ‑60 %.  

* Warm camp meal: temporary +10 % regen.  

* Emberwine / Frostmead: situational +15 % regen (costs hydration).

#### Exhaustion Thresholds
| Current SP | Effect                                                   |
|------------|----------------------------------------------------------|
| > 15 %     | Normal—full moveset                                      |
| ≤ 15 %     | *Winded* – attack speed ‑10 %, dodge i‑frame ‑20 %       |
| 0          | *Exhausted* – cannot sprint/dodge; posture damage +40 %, regen slows 1 s |

---

###  Survival & Environmental Links

* **[[MECHANICS/Survival/Components/Temperature\|Temperature]] Extremes** - Cold raises SP costs to sprint/attack (muscle stiffness); extreme heat accelerates SP drain via dehydration.  

* **[[MECHANICS/Survival/Components/Injuries\|Injuries]]** - Leg fractures double sprint cost; arm fractures raise melee cost by 30 %.  

* **Encumbrance** - Each burden tier (+10 %, +20 %, +35 % cost) affects every stamina‑using action.  

* **[[MECHANICS/Survival/Components/Disease\|Disease]]** - Fevers impose a flat ‑25 % regen; “Weeping” doubles channel costs.

---

### Talents & Gear Interactions

* **Second Wind (VIT talent)** - On dropping below 15 % SP, regain 20 SP burst (60 s cooldown).  

* **Flow State (DEX talent)** - Successful dodge refreshes 8 SP.  

* **Iron Will (Mind/[[MECHANICS/The Player Character/Attributes/Faith\|Faith]] hybrid)** - Convert 5 % current Mana into Stamina per tick while channeling.  

* **Light Armor Set Bonus** - Sprint cost ‑10 %; dodge cost ‑2 SP.  

* **Stamina Bands** - Rare rings granting +15 max SP or +8 % regen.

---

### Practical Management Tips

1. **Plan bursts** - open with high‑cost attacks, then kite to regen.  

2. **Watch the weather** - cold nights? Pack Emberwine or risk stiff swings.  

3. **Rotate weapon sizes** - keep a low‑cost side‑arm for SP‑starved moments.  

4. **Rest smart** - proper bedroll sleep gives a temporary +5 % max SP.  

5. **Group synergy** - Faith invokers with stamina chants drastically extend frontline endurance.

---
## Design Rationale

*  **Tactical ebb and flow** – Stamina forces players to pace offense and defense.  
*  **Survival cohesion** – Hunger, thirst, fatigue, and encumbrance speak to the same resource, tightening the strategic loop.  
*  **Build diversity** – High‑VIT tanks tank; Dex rogues rely on efficient dodges; Mind‑based casters may dump SP but rely on Mana Shields.  

Stamina is the *heartbeat* of moment‑to‑moment gameplay in *Chronicle*: empty it and you feel every breath; master it and you dance through Velmoryth’s deadliest gauntlets with lethal grace.

