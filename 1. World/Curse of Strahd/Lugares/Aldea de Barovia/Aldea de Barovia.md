```leaflet
id: AldeaDeBarovia 
image: [[VillageOfBarovia.jpg]]
defaultZoom: 9
minZoom:9
maxZoom:10
unit: feet
width: 1008px
height:1279px
marker: default,-2.230261977213859,0.910091161893783,La casa del alcalde,,,
marker: default,-1.6853315726976261,0.910091161893783,La casa de María la loca,,,
marker: default,-1.5212665046712333,0.9921239914472841,La tienda de Bildrath,,,
marker: default,-1.237701416015625,1.01171875,Sangre de la Viña,,,
marker: default,-0.753326416015625,0.546875,La casa del alcalde,,,
marker: default,-0.393951416015625,0.53515625,El cementerio,,,
marker: default,-0.455724572260345,1.7053973090516519,Death House,,,
```


# Lugares de la aldea
- [[El cementerio]]
- [[La casa de María la loca]]
- [[La casa del alcalde]]
- [[La iglesia]]
- [[La tienda de Bildrath]]
- [[Sangre de la Viña]]
- [[La casa de Vasili von Holtz(Barovia)]]
# Eventos
```dataview
LIST
FROM "1. World/Curse of Strahd/Lugares/Aldea de Barovia/Eventos"
```
# NPCs
```dataview
TABLE location as Location, gender as Gender
FROM "2. Mechanics/NPCs/Aldea de Barovia"
```

# Habitantes de Barovia
Al entrar a una casa no marcada, rollear para ver que encuentran los PCs

| `dice:d20` | Resultado                       |                                      |
| ---------- | ------------------------------- | ------------------------------------ |
| 1-3        | Nadie                           |                                      |
| 4-8        | `encounter: 2d4: Swarm of Rats` | [[swarm-of-rats\|Swarm of Rats]]     |
| 9-16       | Barovian Villagers              | `dice:1d4`Adultos y `dice:2d4` Niños |
| 17-20      | `encounter: 2d4: Strahd Zombie` | [[strahd-zombie-cos\|Strahd Zombie]] |
