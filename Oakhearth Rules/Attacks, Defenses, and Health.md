## Attacks
### Making Attacks
To attack:
1. Choose target within range (melee/ranged)
2. Make appropriate check:
   - Martial: Attack Check
   - Spell: Spell Check

### Attack Types
#### Martial Attacks
- **Unarmed Strikes**: Use body (punches, kicks, etc.)
- **Weapon Attacks**: Use equipped weapons
  - May draw weapon as part of attack

#### Spell Attacks
- Use Spell Check mechanics
- Follow specific spell rules

### Attack Ranges
#### Melee Attacks
- Default range: 1 space
- Some weapon properties or abilities may extend this range

#### Ranged Attacks
- Range set by weapon/spell


#### Weapon Ranges
A Weapon that can be used to make a Ranged Attack has a Range shown in parentheses after its Ammo, Toss, or Thrown property.

**Range Tiers**
- Normal Range (First number): Attack any target within this range normally
- Long Range (Second number): Attack with Disadvantage against targets in this extended range
  - Cannot attack beyond long range

### Determining if an Attack Hits
When a creature makes an Attack, the result of the Attack Check or Spell Check is compared to the target’s Defense to determine whether or not the Attack Hits the target. The Attack Hits if the result of the Attack Check is equal to or greater than the target’s Defense.

### Degrees of Success
When your Attack Check exceeds the target's AC by 5 or more, you deal +1 damage. For every full 5 points above this, deal +1 more damage. For example, against defense 10, a total roll of 25 deals +3 damage.

These bonuses are called:
- Heavy Hit: +5 over AC
- Brutal Hit: +10 or more over AC. This also ignores any Damage Reduction
(A Brutal Hit also counts as a Heavy Hit for the sake of effects)

### Critical Hits
On an Attack Check where you roll a natural 20:
- Automatically hits the target
- Ignores Damage Reduction  
- Deals +2 bonus damage

## Defenses
When a creature makes an Attack Check or Spell Check to attempt to deal damage to a target, the creature’s Check is compared against the target’s Defense to determine if the Attack hits the target.

### Armor Class (AC)
Armor Class represents the difficulty of physically hitting or touching a creature 

#### Physical Defense Calculation
- 8 + Combat Proficiency + Agility + Armor Bonus + Shield Bonus


## Damage Reduction (DRd)
Damage Reduction is most often given by armor. It reduces the damage of an Attack by an amount equal to the DRd value (minimum of 0). A Brutal Hit (10 or more over the Defense) or Critical Hit (a 20 on the d20) bypasses DRd and deals full damage. It  typically only applies to Physical and Elemental Damage unless stated otherwise.


## Resistance and Vulnerability
### Resistance

- Resistance (Immune): Reduce the damage taken to 0.
- Resistance (Half):Damage taken of the specified type is halved (rounded up).
- Resistance (X): Reduce damage taken by X from the given damage type each time the creature takes damage.  

### Vulnerability
- Vulnerability (Double): Increase the damage taken by 2 times (double damage).  
- Vulnerability (X): Increase damage taken by X each time the creature takes damage of that type. 

## Health Points (HP)
Health Points represent a creature's ability to sustain damage. 

### HP at 1st Level and Onward
A PC has a number of Health Points equal to 6 + Character Level + Might.   A PC might also gain additional HP from its Ancestry or Class.  
**Health Point Formula:**  
- 6 + Level + Might  
- (+ possible HP from Class Features)  
- (+ possible HP from Ancestry Traits)  


### Temporary Health Points (Temp. HP)
Temporary Health Points (Temp HP) are additional Health Points that persist for a limited duration.  
When you take damage, your Temp HP is reduced first, and then any remaining damage carries over to reduce your HP.  
**Stacking:**
- Temp HP doesn’t stack.  
- If you gain Temp HP from different effects, you choose which effect to gain Temp HP from and ignore the Temp HP granted by the other effects.  

**Duration**
- Temp HP lasts until you complete a Long Rest or it is reduced to 0 by taking damage.  
- An effect that grants Temp HP may state a shorter duration, such as:  
	  - 1 minute  
	  - Until you complete a Quick Rest or Short Rest  
	  - Some other duration  
- When the duration expires, all Temp HP gained immediately vanish. 

### Health Thresholds  
Certain game mechanics affect creatures while their current HP is within certain thresholds.  
- **Bloodied:** HP is equal to or lower than 1/2 its maximum HP.  
- **Well-Bloodied:** HP is equal to or lower than 1/4 its maximum HP.  
- **Death’s Door:** HP is equal to or lower than 0 HP, to a minimum of its Death Threshold.  

A creature’s **Death Threshold** is equal to 0 HP minus its Prime Modifier.  

### Death's Door
When you’re reduced to 0 HP or lower, you suffer the following effects: 
- You immediately gain Exhaustion 1. 
- You can’t spend more than 1 AP until the end of your next turn, until you’re restored to 1 HP or higher.
- You can no longer Concentrate. 
- Death Save: At the end of each of your turns, you make a Death Save. Failure:
	- You take 1 True damage. 
	- Critical Failure: You fall Unconscious until you’re restored to 1 HP

**Making Death Saves**
When a creature makes a Death Save, it rolls a d20, and if the result is 10 or higher it succeeds on its Save. A creature makes Death Saves until it’s restored to 1 HP or higher, becomes Stabilized, or dies.


**Death's Door Out of Combat**
When Combat ends, any creature on Death’s Door must immediately make a Death Save. They repeat this Death Save every 12 seconds until they become Stabilized, are restored to 1 HP or higher, or die.
- Failure: The creature takes 1 True damage and falls Unconscious until it becomes Stabilized. 
- Success: The creature becomes Stabilized.

**NPC’s on Death’s Door**
Monsters and NPCs normally die when they’re reduced to 0 HP, however the Game Master can choose to implement Death’s Door on special enemies. They would drop down to 1 AP and be on Death’s Door in that same weakened state, leaving a window for them to still talk to the party and get out any last words before someone puts them out of their misery.

## Misc. Damage Rules
### Damage Type Categories
Damage types are organized into categories, such as Physical, Elemental, and Mystical.
- Physical Damage:  Slashing, Piercing, and Bludgeoning damage.
- Elemental Damage: Cold, Corrosion, Fire, Lightning, Sonic, and Poison.
- Mystical Damage: Radiant, Psychic, and Umbral.

### Managing Damage Multiples
**Multiple Damage Types**: When dealing bonus damage on an Attack Check or Spell Check deals more than 1 type of damage, you choose which of those damage types the bonus damage increases.

**Bonus Damage Against Multiple Targets**: If you add bonus damage to an Attack that targets multiple targets, the bonus damage only applies to one target of your choice. The Attack still benefits from Critical Hits, Heavy Hits, and beyond against each target. 

**Shared Damage**: When 2 or more creatures share damage, divide the total damage by the number of creatures (rounding up), and distribute the damage equally among the creatures.

### Damage Calculation Order
1. Start with the Base Damage of the Attack
2. Add up any damage from Heavy Hits, Brutal Hits or higher, and Critical Hits
3. Add any damage from Action Points spent (Maneuvers, Class Features, AP Enhancements, etc.)
4. Add any + damage from Passives (Weapon Passives, Class Features, Magic Items, etc.)
5. Subtract any damage from Resistances and Vulnerabilities
6. Subtract damage from any Damage Reduction
