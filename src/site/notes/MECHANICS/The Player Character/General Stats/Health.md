---
{"dg-publish":true,"permalink":"/mechanics/the-player-character/general-stats/health/","noteIcon":""}
---


---

<center>*“Steel can be mended. Flesh must be earned back.”*  </center>

---

Health represents a character’s raw bodily integrity, the measure of tissue, bone, and spirit that keeps them in the fight. While **[[MECHANICS/The Player Character/Attributes/Vitality\|Vitality]]** reflects long‑term toughness and carrying power, **Health** is the *moment‑to‑moment* resource that determines whether you stand, stagger, or fall.  

---

### Calculation & Growth

Health never increases by spending points directly; instead it is a derivative of Vitality and innate racial qualities.

<center>Base HP = 50 + (Vitality × 5) + Race Bonus</center>

| Vitality | Base HP | Notes                                   |
|----------|---------|-----------------------------------------|
| 6        | 80      | Novice adventurer, minimal conditioning |
| 8        | 90      | Lightly trained                         |
| 10       | 100     | Average soldier                         |
| 12       | 110     | Seasoned fighter                        |
| 14       | 120     | Hardened veteran                        |
| 16       | 130     | Knight‑level constitution               |
| 18       | 140     | Elite guardian                          |
| 20       | 150     | Peak mortal physique                    |

*Racial modifiers*  

- Dwarves +10 HP (stocky resilience)  

- Machinations +0 HP (but gain a Soul‑Cage overflow buffer)  

- Undead ‑10 HP (decayed flesh) but immune to [[MECHANICS/The Player Character/Status Effects/Bleed\|bleed]]  

---

### How Health Interacts with Systems

#### Survival

* [[MECHANICS/Survival/Components/Hunger\|Hunger]], [[MECHANICS/Survival/Components/Thirst\|thirst]], [[MECHANICS/Survival/Components/Fatigue\|fatigue]], and extreme temperatures apply **Health‑Cap penalties** (max HP shrinks by 5 → 15 → 25 % as deprivation worsens).  

* Severe hypothermia or hyperthermia deals direct HP damage over time until shelter or warming items are used. Vitality mitigates rate but not the cap shrink.

#### Injuries & Disease

* **Minor injuries** (cuts, bruises) occur when a single hit deals ≥ 10 % of current HP.  

* **Major [[MECHANICS/Survival/Components/Injuries\|injuries]]** (fractures, deep lacerations) trigger at ≥ 35 %.  

* Diseases and poisons drain HP periodically or slow natural regeneration; curing them restores normal regen but does not heal lost HP.

#### Combat

* **[[MECHANICS/Combat/Components/Posture\|Posture]] Collapse** - When posture breaks, incoming critical hits ignore a flat chunk (e.g., 25 %) of *current* HP. More max HP widens the buffer.  

* **Low‑Health Fatigue** - Below 20 % HP, a character’s maximum stamina drops by 15 % to simulate pain and shock.  

* Bleed, [[MECHANICS/The Player Character/Status Effects/Poison\|poison]], and burns tick for percentages of max HP, scaling with Vitality: more HP buys time, but ticks remain proportionate.

---

### Losing & Regaining Health

| Method of Loss            | Speed / Severity | Notes                                          |
|---------------------------|------------------|------------------------------------------------|
| Direct weapon damage      | Instant          | Mitigated by [[MECHANICS/The Player Character/Equipment/Armor/Armor\|armor]] and resistances             |
| Bleed / Poison            | Gradual ticks    | Stacks; can kill if untreated                  |
| Starvation / Dehydration  | Slow cap shrink  | HP cannot exceed reduced cap until fed         |
| Frostbite / Heat‑stroke   | Periodic damage  | Accumulates until temperature stabilized       |
| Diseases                  | Slow–Medium      | Varies per [[MECHANICS/Survival/Components/Disease\|disease]]; some debuff healing rate   |

| Method of Recovery | Amount Restored | Requirements / Trade‑offs                 |
|--------------------|-----------------|-------------------------------------------|
| **Sleep**          | 5–20 % HP       | Bedroll quality & fatigue state matter    |
| **Cooked Meals**   | Gradual buff    | Well‑fed status: +2 HP per minute (30 m)  |
| **Healing Potions**| 25 / 50 / 100 % | Consumes potion; has cooldown             |
| **Holy / Arcane Heals** | 10–40 %     | Costs [[MECHANICS/The Player Character/General Stats/Mana\|mana]], reagent, or scroll            |
| **Greater Salves** | 15 % + faster regen | Requires alchemical kit & campfire   |

---

###  Design Rationale

* **Tangible Consequences** - Players feel every mis‑timed dodge or missed meal.  

* **Layered Risk** - HP is the visible pain bar; Vitality is the long game; injuries and diseases are the lingering threat.  

* **Encourages [[MECHANICS/Exploration/Components/Preparation\|Preparation]]** - Smart packing of [[MECHANICS/The Player Character/Equipment/Medical Supplies/Medical Supplies\|medical supplies]], warm gear, and food is rewarded with staying power.  

* **Supports Storytelling** - Visible wounds, limping animations, and reduced [[MECHANICS/The Player Character/General Stats/Stamina\|stamina]] at low HP reinforce the grim tone of Velmoryth.

---

###  Practical Advice for Players

* Carry **at least one** instant‑heal potion on deep expeditions, or a Greater Salve plus bandages to manage bleed.  

* High‑Vitality tanks can afford to absorb more hits, but they still need food and sleep to keep their HP cap from shrinking.  

* Undead may ignore bleed but should beware fire and daylight, which bypass many resistances and burn HP quickly.  

* Machinations rely on **maintenance kits**: if the Soul‑Cage buffer fails, raw HP damage comes next.  

* Low‑Vitality rogues must lean on dodge windows and parries—one major injury can cripple them for days.

---

Health is your most finite commodity in *Chronicle.* Lose it recklessly and Velmoryth will bury you; nurture it with planning and you’ll carve legends into its unforgiving wilds.