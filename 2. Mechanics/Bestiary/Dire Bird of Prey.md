---
statblock: inline
---

```statblock
source: "Flee, Mortals!"
columns: 2
forceColumns: true
name: Dire Bird of Prey
size: Large
type: Beast
alignment: Unaligned
ac: 15
hp: 68
hit_dice: 8d10+24
speed: 20ft, fly 90ft
stats: [17,15,16,6,12,5]
cr: 3
skillsaves:
  - Athletics: 5
  - Perception: 5
languages: 
traits:
  - name: Exceptional Vision
    desc: "The bird has a +10 bonus to Wisdom (Perception) checks that rely on sight."
  - name: Flyby
    desc: "The bird doesn't provoke opportunity attacks when they fly out of an enemy's reach."
  - name: High Speed Dive(Recharges after a Rest)
    desc: "If the bird descends at least 30 feet on their turn, they can take a Dash action as a bonus action. When they do, they have advantage on the next attack they make before the end of their turn."
actions:
  - name: Multiattack
    desc: "The bird makes two attacks using Heavy Beak, Rending Talons, or both."
  - name: Heavy Beak
    desc: "Melee Weapon Attack: +5 to hit, reach 5ft., one target. Hit: 7 (1d8+3) piercing damage. On a critical hit, the target is dazed until the start of the bird's next turn."
  - name: Rending Talons
    desc: "Melee Weapon Attack: +5 to hit, reach 5ft., one target. Hit: 7 (1d8+3) slashing damage. If the target is medium or smaller, they are grappled (Escape DC 13). While grappling a target, the bird's Beak attacks against that target are made with advantage, and the bird can't attack another target. Each time the target makes a check to end the grapple, the target takes 4(1d8) slashing damage."
  - name: Crushing Grip
    desc: "The bird's powerful talons crush a grappled target. The target must make a DC 13 Strength saving throw, taking 17(5d6) bludgeoning damage on a failed save, or half as much on a successful one. If the target fails the save by 5 or more, they are also dazed until the end of their next turn."
```
