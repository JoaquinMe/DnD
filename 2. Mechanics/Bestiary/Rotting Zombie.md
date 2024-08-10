---
statblock: inline
---
```statblock
source: "Flee, Mortals!"
columns: 2
forceColumns: true


name: "Rotting Zombie"
size: medium
type: undead
alignment: Neutral Evil
ac: 8
hp: 6
hit_dice:
speed: 20ft.
stats: [13,6,12,3,6,5]
cr: 1/4
saves:
  - Strength:
  - Dexterity: 
  - Constitution: 
  - Intelligence: 
  - Wisdom: 
  - Charisma: 
skillsaves:
  - Athletics:
  - Perception:
damage_immunities: Poison
condition_immunities: Exhaustion, Poisoned
languages: understands the languages they knew in life, can't speak
traits:
  - name: Minion
    desc: "If the zombie takes damage from an attack or as the result of a failed saving throw, their hit points are reduced to 0. If the zombie takes damage from another effect, they die if the damage equals or exceeds their hit point maximum; otherwise they take no damage."
  - name: Overwhelm
    desc: "If an enemy starts their turn within 5 feet of three or more rotting zombies who can see them, the enemy's speed is reduced by 5 feet for each rotting zombie within 5 feet of them until the start of their next turn. If this reduces the enemy's walking speed to 0, they are restrained for the duration."
  - name: Rise Again
    desc: "The first time a zombie is reduced to 0 hit points by damage other than radiant damage but their body isn't destroyed, they regain hit points equal to their hit point maximum, and they fall prone and are incapacitated until the start of their next turn."
actions:
  - name: Slam (Group Attack). 
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 bludgeoning damage."
```
