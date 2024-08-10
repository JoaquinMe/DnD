# The Party
```dataview
TABLE WITHOUT ID file.link AS "Character", person AS Person, race AS Race, class AS Class,subclass AS Subclass, level AS Level, background AS Background
FROM "1. The Party/Curse of Strahd/Players"
```

## Plot Hooks
>[!columns|2 no-t]
>>[!info] [[Dorian Zsolt(DM)]]
>>- Busca encontrar a su grupo, al traidor y su misión original
>>- ==Darle pistas cada tanto== 
>
>>[!info] [[Reynauld Argstone(DM)]]
>>- Quiere encontrar a sus parientes (Hermano y Abuela)
>>- Busca desenmascarar una red de trata
>>- ==Que hable con vistanis(no todos son malos)==
>
>>[!info] [[Din(DM)]]
>>- Quiere encontrar a alguno de sus scouts
>>- ==Hacer que se encuentre con alguno==
>
>>[!info] [[Sek'Kuar(DM)]]
>>- Quiere hacer [[true-resurrection|True Resurrection]] a la madre
>>- ==Tirar un par de sueños/visiones/cosas esquizo==
>
 

# Magic
## ==Concentration Check==
- CON Save DC= 10 ó 1/2x(daño obtenido) el que sea más alto.
- Daño de muchas fuentes-> un save para cada una
## Reminders
- VSM?
- Rango?
- Tiempo de casteo?
- Tiempo de duración?
- La gente sabe del efecto?
- El caster está concentrado?
- (Combate) No puede castear 2 spells con nivel por turno
- (Combate) Chequear concentración
# Combate
--- start-multi-column: ID_9njh
column-settings
Number of Columns: 2
Largest Column: right

## Movement

| Acción            | Costo               |
| ----------------- | ------------------- |
| Move              | 5ft per 5ft         |
| Swim              | 10ft per 5ft        |
| Crawl             | 10ft per 5ft        |
| High Jump         | 5ft per 5ft         |
| Climb             | 10ft per 5ft        |
| Drop Prone        | 0ft                 |
| Stand Up          | Half Movement Speed |
| Long Jump         | 5ft per 5ft         |
| Difficult Terrain | +1ft per ft         |
| Crawl             | +1ft per ft         |
## Damage Types

| Tipo        |
| ----------- |
| Acid        |
| Blugdeoning |
| Cold        |
| Fire        |
| Force       |
| Lightning   |
| Necrotic    |
| Piercing    |
| Poison      |
| Psychic     |
| Radiant     |
| Slashing    |
| Thunder     |


--- column-break ---
## Actions

| Action        | Description                                                                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Attack        | Use any attack or cast a spell listed on your character sheet.                                                                                   |
| Help          | Give an ally advantage on the next ability check you are helping with, or advange to attack an enemy you are within 5ft of until your next turn. |
| Grapple       | Lo agarra, se mueve con el. Athletics(atacante) vs Acrobatics/Athletics(defensor).==Cuenta como ataque==                                         |
| Shove         | Lo deja prone o empuja. Athletics(atacante) vs Acrobatics/Athletics(defensor).==Cuenta como ataque==                                             |
| Dash          | Añade su velocidad a su velocidad del turno.(Duplica velocidad)                                                                                  |
| Disengage     | Make a clean escape from the targets around you without provoking an opportunity attack.                                                         |
| Dodge         | Until your next turn, attacks made against you have disadvantage and you have advantage on dexterity saving throws.                              |
| Hide          | Make a stealth check to hide from enemies.                                                                                                       |
| Ready         | Preparar un trigger para alguna acción. Especificar el trigger y la acción.                                                                      |
| Search        | Perception o investigation check                                                                                                                 |
| Use an Object | Usar poción, algún objeto, etc...                                                                                                                |
| Use Shield    | Equipar/Desequipar un escudo                                                                                                                     |
| Use Feature   | Usar una feat                                                                                                                                    |
| <br>Improvise | Cualquier cosa que no esté en la lista                                                                                                           |
## Improvised Damages

| Dice  | Examples                                                                                                                               |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------- |
| 1d10  | Burned by coals, hit by a falling bookcase, pricked by a poison needle                                                                 |
| 2d10  | Being struck by lightning, stumbling into a fire pit                                                                                   |
| 4d10  | Hit by falling rubble in a collapsing tunnel, stumbling into a vat of acid                                                             |
| 10d10 | Crushed by compacting walls, hit by whirling steel blades, wading through a lava stream                                                |
| 18d10 | Being submerged in lava, being hit by a crashing flying fortress                                                                       |
| 24d10 | Tumbling into a vortex of fire on the Elemental Plane of Fire, being crushed in the jaws of a godlike creature or a moon-sized monster |


--- end-multi-column





## Conditions

| Condition     | Ability Checks                              | Saving Throws                   | Attack Rolls                                | Attacks Against                            | Movement                            | Special                                                                                  |
| ------------- | ------------------------------------------- | ------------------------------- | ------------------------------------------- | ------------------------------------------ | ----------------------------------- | ---------------------------------------------------------------------------------------- |
| Blinded       | Fails if sight required                     |                                 | Disadvantage                                | Advantage                                  |                                     | Can't see                                                                                |
| Charmed       | Charmer has advantage<br>on social checks   |                                 | Can't target charmer                        |                                            |                                     |                                                                                          |
| Deafened      | Fails if hearing required                   |                                 |                                             |                                            |                                     | Can't hear                                                                               |
| Frightened    | Disadvantage while<br>source on sight       |                                 | Disadvantage while<br>source on sight       |                                            | Can't move closer to source         |                                                                                          |
| Grappled      |                                             |                                 |                                             | Speed=0;<br>No speed boosts                |                                     |                                                                                          |
| Incapacitated | Can't take actions;<br>Can't take reactions |                                 | Can't take actions;<br>Can't take reactions |                                            |                                     |                                                                                          |
| Invisible     | Heavily Obscured                            |                                 | Advantage                                   | Disadvantage                               |                                     |                                                                                          |
| Paralyzed     | Can't take actions;<br>Can't take reactions | Auto-Fail STR;<br>Auto-Fail DEX | Can't take actions;<br>Can't take reactions | Advantage;<br>Hits within 5' auto-crit     | Can't move                          | Can't speak                                                                              |
| Petrified     | Can't take actions;<br>Can't take reactions | Auto-Fail STR;<br>Auto-Fail DEX | Can't take actions;<br>Can't take reactions | Advantage                                  | Can't move                          | Turn to stone;<br>Resist all damage;<br>Immune to poison&disease;<br>Weightx10; Dont Age |
| Poisoned      | Disadvantage                                |                                 | Disadvantage                                |                                            |                                     |                                                                                          |
| Prone         |                                             |                                 | Disadvantage                                | Advantage within 5';<br>Else, disadvantage | Crawl Only                          |                                                                                          |
| Restrained    |                                             | Disadvantage DEX                | Disadvantage                                | Advantage                                  | Speed becomes 0;<br>No speed boosts |                                                                                          |
| Stunned       | Can't take actions;<br>Can't take reactions | Auto-Fail STR;<br>Auto-Fail DEX | Can't take actions;<br>Can't take reactions | Advantage                                  | Can't move                          | Speak falteringly                                                                        |
| Unconscious   | Can't take actions;<br>Can't take reactions | Auto-Fail STR;<br>Auto-Fail DEX | Can't take actions;<br>Can't take reactions | Advantage;<br>Hits within 5' autocrit      | Can't Move                          | Can't speak; Unaware of surroundings                                                     |


# General
--- start-multi-column: ID_lkrj
```column-settings
Number of Columns: 3
Largest Column: middle
```
## Skills&Abilities
| Ability      | Skills                                                                                                                                                                                                                                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Strength     | [Athletics](app://obsidian.md/rules/skills.md#Athletics)                                                                                                                                                                                                                                                 |
| Dexterity    | [Acrobatics](app://obsidian.md/rules/skills.md#Acrobatics), [Sleight of Hand](app://obsidian.md/rules/skills.md#Sleight%20of%20Hand), [Stealth](app://obsidian.md/rules/skills.md#Stealth)                                                                                                               |
| Intelligence | [Arcana](app://obsidian.md/rules/skills.md#Arcana), [History](app://obsidian.md/rules/skills.md#History), [Investigation](app://obsidian.md/rules/skills.md#Investigation), [Nature](app://obsidian.md/rules/skills.md#Nature), [Religion](app://obsidian.md/rules/skills.md#Religion)                   |
| Wisdom       | [Animal Handling](app://obsidian.md/rules/skills.md#Animal%20Handling), [Insight](app://obsidian.md/rules/skills.md#Insight), [Medicine](app://obsidian.md/rules/skills.md#Medicine), [Perception](app://obsidian.md/rules/skills.md#Perception), [Survival](app://obsidian.md/rules/skills.md#Survival) |
| Charisma     | [Deception](app://obsidian.md/rules/skills.md#Deception), [Intimidation](app://obsidian.md/rules/skills.md#Intimidation), [Performance](app://obsidian.md/rules/skills.md#Performance), [Persuasion](app://obsidian.md/rules/skills.md#Persuasion)                                                       |
## Exhaustion
*Long rest reduces level by 1*

| Level | Description                       |
| ----- | --------------------------------- |
| 1     | Disadvantag on ability checks     |
| 2     | Speed halved                      |
| 3     | Disadvantage on attacks and saves |
| 4     | HP Max Halved                     |
| 5     | Speed reduced to zero             |
| 6     | Death                             |

--- column-break ---
## Sight
| Light Conditions |                      Normal Vision                       |                       Darkvision                        |  Truesight   |                      Devil's Sight                      |
| :--------------- | :------------------------------------------------------: | :-----------------------------------------------------: | :----------: | :-----------------------------------------------------: |
| Bright Light     |                       See normally                       |                      See normally                       | See normally |                      See normally                       |
| Dim Light        | Disadvantage on PER checks; <br>-5 to passive perception |                      See normally                       | See normally | Disadvantage on PER checks;<br>-5 to passive perception |
| Darkness         |                         Blinded                          | Disadvantage on PER checks;<br>-5 to passive perception | See normally |                  See normally (120ft)                   |
| Magical Darkness |                         Blinded                          |                     Varies by Spell                     | See normally |                  See normally (120ft)                   |
--- column-break ---
## Learning About

| Monster Type | Skill    |
| ------------ | -------- |
| Aberration   | Arcana   |
| Beast        | Nature   |
| Celestial    | Religion |
| Construct    | History  |
| Dragon       | History  |
| Elemental    | Arcana   |
| Fey          | Arcana   |
| Fiend        | Religion |
| Giant        | History  |
| Humanoid     | History  |
| Monstrosity  | Arcana   |
| Ooze         | Nature   |
| Plant        | Nature   |
| Undead       | Religion |
## Resting

| Rest type  | Duration | Effect                                                                           |
| ---------- | -------- | -------------------------------------------------------------------------------- |
| Short Rest | 1hr      | Rollear hit dice, se curan esa cantidad                                          |
| Long Rest  | 8hr      | Full heal. Full spell slots.<br>Ganan la mitad de la cantidad total de hit dice. |
--- end-multi-column



# Session History
```dataview
TABLE Date
FROM "2. Session Journals"
SORT Date DESC
```





