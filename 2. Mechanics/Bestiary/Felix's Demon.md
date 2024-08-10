---
statblock: inline
---
```statblock
source: "St. Andral's Orphanage"
columns: 2
forceColumns: true


name: Felix's Demon
size: Medium
type: Fiend
alignment: Chaotic Evil
ac: 14
hp: 50
hit_dice: 6d8+18
speed: 30ft., climb 30ft.
stats: [8,14,11,12,14,10]
cr: 4
skillsaves:
  - Deception: 2
  - Intimidation: 2
damage_vulnerabilities: "radiant"
damage_resistances: "acid, cold, fire, lightning, thunder, bludgeoning, piercing, slashing from nonmagical attacks"
damage_immunities: "necrotic, poison"
condition_immunities: "charmed, exhaustion, frightened, grappled, paralyzed, petrified, poisoned, prone,restrained, unconscious"
languages: "Abyssal, Common, Infernal"
senses: "darkvision 60ft., passive Perception 12"
traits:
  - name: The Demon's Locket.
    desc: "The demon is magically connected to this locket, like a genie to a lamp. While inside the locket and while the locket is closed, the demon is unconscious. While inside the locket and while the locket is open, the demon can exit the locket and interact with the world, but only for 3 turns, after which it must return to the locket or be destroyed. This ability recharges after a long rest within the locket. In order to free itself from the locket, the demon must trade its place in the locket with a pure and compassionate soul (someone of a Lawful Good alignment) in a ritual process that takes approximately 3-4 months."
  - name: Symbiote
    desc: "Si el locket está abierto y en contacto físico con otra criatura. el demonio tiene la habilidad de poseer esa criatura."
actions:
  - name: Shadow Claws
    desc: "Melee Weapon Attack: +5 to hit, reach 10ft., one target. Hit 17 (4d6+3) slashing damage."
  - name: Life Drain (3/Day)
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit 10 (3d6) necrotic damage. On a hit, the demon gains hit points equal to half the damage done by the attack."
  - name: Possesion.
    desc: "One humanoid that is in contact with The Demon's Locket must succeed on a DC 13 Charisma saving throw or be possessed by the demon as per the Symbiote trait. The demon now controls the body but does not deprive the target of awareness or share the target's knowledge or memories. The possession lasts until the body drops to O hit points, the demon ends it as a bonus action, or the demon is forced out by an effect like the dispel evil and good spell. The target is immune to Possession for 24 hours after succeeding on the saving throw or after the possession ends."
```
