---
{"dg-publish":true,"permalink":"/mechanics/the-player-character/general-stats/encumbrance/","noteIcon":""}
---


---

<center>THE WEIGHT OF THE WORLD</center>

---

Encumbrance governs how much total **Bulk** (weight + volume abstraction) a character can carry before movement, [[MECHANICS/The Player Character/General Stats/Stamina\|stamina]], and survival rates begin to suffer.  
Every hero starts with a **Base Capacity** of **60 Bulk**; further head‑room is gained only through the **[[MECHANICS/The Player Character/Attributes/Vitality\|Vitality]]** attribute and its conditioning activities (fighting in heavy gear, healing wounds, etc.).

---

## Vitality‑to‑Capacity Scaling

| Vitality Score | Safe Carry Limit (Bulk) | Notes on Growth |
|----------------|-------------------------|-----------------|
| 6–9            | 60 (base)               | Untrained body; novice travellers. |
| 10–11          | 65                      | First plateau reached via light conditioning. |
| 12–13          | 70                      | Typical for medium‑armor soldiers. |
| 14–15          | 75                      | Seasoned fighters; comfortable in chain & shield. |
| 16–17          | 80                      | Knight‑plate carriers or hardened explorers. |
| 18–19          | 85                      | Veteran guardians; can tote [[MECHANICS/The Player Character/Equipment/Shields/Tower Shields\|tower shields]] + spare arms. |
| 20 +           | 90  (cap for mortals)   | Peak human conditioning; anything higher reserved for racial perks or rare boons. |

> **Rule of thumb:** every **+2 VIT** adds **+5 Bulk** of safe capacity until the hard cap.

---

## Encumbrance States & Penalties

| Load % of Safe Limit | State                | Mobility / Stamina              | Survival Drain ([[MECHANICS/Survival/Components/Hunger\|Hunger]] / [[MECHANICS/Survival/Components/Thirst\|Thirst]] / [[MECHANICS/Survival/Components/Fatigue\|Fatigue]]) |
|----------------------|----------------------|---------------------------------|-------------------------------------------|
| ≤ 100 %              | Unburdened           | Full sprint & dodge distance    | Normal tick                               |
| 101 – 110 %          | Lightly Burdened     | ‑10 % sprint speed    | +10 % tick                                |
| 111 – 130 %          | Burdened             | ‑20 % sprint, ‑1 dodge i‑frame  | +25 % tick                                |
| 131 – 150 %          | Heavily Burdened     | Cannot sprint; dodge becomes hop | +50 % tick; [[MECHANICS/Combat/Components/Posture\|posture]] damage +25 %          |
| > 150 %              | Overloaded           | Walk only; dodge disabled        | +100 % tick; stamina regen ‑75 %          |

+ Penalties apply **immediately** when crossing a threshold and reverse once weight is shed.  
-  Hunger/Thirst/Fatigue “tick” refers to how quickly those meters deplete relative to normal.

---

## Mitigation & Strategy

- **[[MECHANICS/The Player Character/Equipment/Utility Equipment/Whetstones\|Whetstones]], medical kits, and tents** weigh more but avert crises later—evaluate trip length vs. load.  

- **High‑VIT builds** naturally shoulder heavier plates, large [[MECHANICS/The Player Character/Equipment/Utility Equipment/Packs\|packs]], or spare weapons; low‑VIT rogues instead bank on speed and [[MECHANICS/The Player Character/Stealth\|Stealth]].  

- Races with innate bonuses (e.g., Machinations) or late‑tier **Strength [[MECHANICS/The Player Character/Skills and Talents/Talents/Talents\|talents]]** can momentarily ignore Lightly Burdened penalties, ideal for emergency loot hauls.  

- Encumbrance ties into **[[MECHANICS/Survival/Components/Temperature\|Temperature]]**: a Heavily Burdened traveller in a blizzard expends stamina faster to stay warm, risking exhaustion or frostbite.  

---

## Gameplay Loop

1. Plan expedition → weigh gear versus projected days afield.  

2. Monitor load as loot accumulates. Drop, stash, or mark valuables on your parchment map.  

3. Return to a smithy or safe hub to off‑load, repair equipment, and redistribute Bulk before the next foray.

Encumbrance turns inventory into a forward‑planning puzzle rather than a bottomless sack, reinforcing *Chronicle*’s ethos that **every mile, meal, and sword swing must be earned**.