---
class: Fighter
level: "3"
race: Human
size: Medium
gender: Male
alignment: Neutral Good
background: Witcher
hp: "28"
ac: "17"
initiative: "4"
person: Elias
subclass: Bone Knight
---
# Resumen
Controlado por: `=this.person`

| Name              | Class         | Lvl           | Race         | Height       | Gender         | Alignment         | Background         | HP         | AC         | Initiative         |
| ----------------- | ------------- | ------------- | ------------ | ------------ | -------------- | ----------------- | ------------------ | ---------- | ---------- | ------------------ |
| `=this.file.name` | `=this.class` | `=this.level` | `=this.race` | `=this.size` | `=this.gender` | `=this.alignment` | `=this.background` | `=this.hp` | `=this.ac` | `=this.initiative` |
# Passives

| Mods           | Modifier               | Roll                       |
| -------------- | ---------------------- | -------------------------- |
| Perception Mod | +`=this.perceptionmod` | `dice:d20 + perceptionmod` |
| Stealth Mod    | +`=this.stealthmod`    | `dice:d20+stealthmod`      |
# Roleplay
## Personality Traits
- I face problems head on. A simple direct solution is the best path to success.
## Ideals
- I kill monsters to make the world a safer place, and to exorcise my own demons.
- Todas las criaturas merecen una segunda oportunidad.
## Bonds
- Someone saved my life on the battlefield. I will never leave a friend behind.
## Flaws
- I'll never forget the betrayal my company suffered and the enemies who dealt it.
## Story
### Secreto
- Como obtuvo 
### Objetivo en Barovia
- Encontrar al traidor que traicionó a [[Grupo Inquisitor(DM)]]
- Encontrar a sus compañeros vivos de [[Grupo Inquisitor(DM)]]
- Conocer su misión original.
### Dark Power
Quiere venganza(matar al traidor)
- Algún Dark Power que ofrezca
# Referencias
perceptionmod::4
stealthmod::6