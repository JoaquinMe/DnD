---
class: Rogue
level: "3"
race: Human
size: Medium
gender: Male
alignment: True Neutral
background: Smuggler
hp: "26"
initiative: "3"
ac: "13"
person: Levy
subclass: Shadow Master
---
# Resumen
Controlado por: `=this.person`

| Name              | Class         | Lvl           | Race         | Size         | Gender         | Alignment         | Background         | HP         | AC         | Initiative         |
| ----------------- | ------------- | ------------- | ------------ | ------------ | -------------- | ----------------- | ------------------ | ---------- | ---------- | ------------------ |
| `=this.file.name` | `=this.class` | `=this.level` | `=this.race` | `=this.size` | `=this.gender` | `=this.alignment` | `=this.background` | `=this.hp` | `=this.ac` | `=this.initiative` |
# Passives

| Mods           | Modifier              | Roll                       |
| -------------- | --------------------- | -------------------------- |
| Perception Mod | `=this.perceptionmod` | `dice:d20 + perceptionmod` |
| Stealth Mod    | `=this.stealthmod`    | `dice:d20+stealthmod`      |
# Roleplay
## Personality Traits
- I am horribly awkward in social situations.
## Ideals
- Emotions must not cloud our sense of what is right and true, or our logical thinking
## Bonds
- My honor is my life
## Flaws
- I have trouble keeping my true feelings hidden
## Story
### Objetivos en Barovia
- Encontrar a su abuela y a su hermano([[Randolph Argstone]]).
### Dark Gift
[[Khirad, the Star of Secrets]]
# Referencias
perceptionmod::0
stealthmod::5