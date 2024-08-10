---
statblock: inline
---
```statblock
source: "Flee, Mortals!"
columns: 2
forceColumns: true


name: Cloak
size: Medium
type: Human
alignment: Lawful Evil
ac: 17
hp: 78
hit_dice: 12d8 + 24
speed: 40 ft.
stats: [10,20,14,15,12,15]
cr: 4
saves:
  - Strength: 
  - Dexterity: 7
  - Constitution: 4
  - Intelligence: 
  - Wisdom: 
  - Charisma: 4
skillsaves:
  - Acrobatics: 7
  - Deception: 4
  - Insight: 3
  - Perception: 3
  - Stealth: 9
languages: Common
traits:
  - name: Exploit Opening (3/Day)
    desc: "When Cloak makes an attack, she has advantage on the attack roll."
actions:
  - name: Multiattack
    desc: "Cloak makes two Shortsword attacks."
  - name: Shortsword
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6 + 5) piercing damage plus 3 (1d6) poison damage, and the target is poisoned until the start of Cloak's next turn."
  - name: Light Crossbow
    desc: "Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. Hit: 8 (1d8+ 5) piercing damage. If the target is a creature who hasn't moved since the end of Cloak's last turn, the attack deals an extra 7 (2d6) piercing damage."
  - name: Iron Ring
    desc: "If not in the Cyst, Cloak teleports to the Cyst. If in the Cyst, she teleports to a place she has visited."
bonus_actions:
  - name: Cunning Action
    desc: "Cloak takes the Dash, Disengage, or Hide action."
reactions:
  - name: You Should've Been Watching Me
    desc: If a creature within 5 feet of Cloak hits one of her allies with an attack, Cloak makes a Shortsword attack against the creature. To use this reaction, Cloak must be able to see the ally and the attacker.
```
