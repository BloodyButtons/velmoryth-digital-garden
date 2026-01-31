---
{"dg-publish":true,"permalink":"/mechanics/combat/components/dodging/","noteIcon":""}
---


---

<center>THE ART OF EVASION</center> 

---

A **dodge** in *Chronicle* is not a momentary invincibility trick, it’s a **brief, calculated movement** that relies on physical spacing, timing, and resource management. Rather than disappearing into i-frames, players must **physically move** out of an attack’s arc to avoid damage. This middle-ground approach allows for a **partial grace window** of reduced damage or hitbox adjustment, but still punishes sloppy positioning.

---

### **Core Concept**

- **Collision-Based**: Every enemy strike has a real weapon arc. If you’re in the path, you will get hit- unless your dodge repositions you in time.  

- **Minimal Leniency**: A well-timed dodge might offer minor damage reduction (“glancing blow”) or a fleetingly smaller hitbox, but never total immunity. If you remain partially in harm’s way, you’ll take at least partial damage or [[MECHANICS/Combat/Components/Posture\|Posture]] loss.

---

### **Implementation**

 1. [[MECHANICS/The Player Character/General Stats/Stamina\|Stamina]]
 
   - **Stamina Cost**: Each dodge consumes stamina, abusing it leads to *exhaustion windows*, disabling advanced moves for a short time.  

   - **Survival Ties**: [[MECHANICS/Survival/Components/Hunger\|Hunger]], [[MECHANICS/Survival/Components/Thirst\|Thirst]], and [[MECHANICS/Survival/Components/Fatigue\|Fatigue]] directly affect how quickly stamina recovers, anchoring dodges to the game’s broader survival ethos.

2. **Partial Damage Mitigation** 
   
   - **Successful Dodge**: If you clear the attack, you avoid all damage.

  - **Perfect Dodge**:  If you clear the attack *at the very last possible moment*, you avoid all damage and gain a short burst of stamina and posture.
 
   - **Near Miss**: Clipping the weapon’s arc yields partial damage or posture depletion, rather than a full-hit penalty.

   - **Fail**: If you mistime or dodge incorrectly, you will be staggered (albeit not as much as you would normally if you ran out of stamina or posture.) You will take 1.25x the amount of normal damage.

### **Synergy with Posture & Combat Tempo**

- **Posture Retention**: Unlike [[MECHANICS/Combat/Components/Blocking\|Blocking]], a successful dodge means **zero Posture damage** if fully clear.  

- **[[MECHANICS/Combat/Components/Weapon Tempo\|Weapon Tempo]]**: Heavier weapons can’t be spammed to chase a dodging enemy, while faster weapons might more easily keep up and punish repeated evades.  

- **[[MECHANICS/Combat/Components/Critical Windows\|Critical Windows]]**: Expertly timed dodges can set up an enemy for a devastating stagger if you respond before they recover their stance.


### **Ties to Immersion & Survival**

- **First-Person Realism**: Seeing a sword swing inches past your face drives home the lethal atmosphere. No i-frame illusions, just you, an enemy’s steel, and the distance you create.  

- **Minimal UI Cues**: Subtle audio or visual feedback indicates a glancing blow or perfect dodge, upholding *Chronicle*’s [[MECHANICS/The Core Pillars/Immersion\|Immersion]] pillar.  

- **World Level Scaling**: As difficulty rises, enemy attacks become more varied and precise. You must refine timing, spacing, and stamina usage to survive relentless assaults.

### Conclusion 

Dodging demands awareness, reflexes, and strategic stamina management. One misstep can be fatal in *Chronicle*’s unforgiving world.  Landing a perfect dodge feels earned, no gamey invincibility. It’s your expertise at reading telegraphs and controlling space.  **By tying into Posture and Survival stats, dodge remains consistent with *Chronicle*’s design philosophy: *every action costs something*, and *every advantage must be earned*.

In essence, **dodging** in *Chronicle* merges collision-based evasion with minimal mechanical forgiveness, rewarding those who hone their timing and spatial judgment without ever granting them a magical escape hatch. It is a lethal waltz where one false step can mean death, but a perfect sidestep can secure victory.