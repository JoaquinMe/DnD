# Intro
>Aquí, el camino pasa de serpentear a través de las montañas, a descender a un valle. El camino parece terminar en una aldea cerca de un lago. Una bifurcación del camino parece llevar a un promontorio, en el cual parece estar un molino.
![[Pasted image 20240427181803.png]]

A medida que se acercan ven:
- Un carrito parecido al que vieron con "abuelita".
	- 200gp
	- 2 [[Dream Pastries]] de cada gusto
# Areas
## Planta Baja
Parece una casa normal.
- La mitad de la habitación está ocupada por un horno de ladrillo.
	- Está prendido, se puede sentir el calor y oler el olor a pancitos calientes.
	- Al lado del horno, hay varios condimentos e ingredientes.
		- Entre ellos, los huesos de los nenes(molidos)
- Hay una escalerita de madera que sube a los pisos superiores.
- Hay 3(tres) sillas
### Conversación con Bella
>[!note] Resumen
> Tratar de mantener la conversación sobre los PCs 
> - De donde son?
> - De donde vienen?
> - A donde van?
> - Como los trató Barovia?



- Su hermana(Ofelia) está trabajando arriba, no conviene molestarla.
- Madre(Morgantha) está viniendo de vender sus productos en Vallaki.
- Si hablan de la propiedad, se pone medio triste y tira excusas.
	- "De verdad planean echar a 3 mujeres seniles de aquí?"
## Primer Piso
- Está Ofelia amasando las empanadas.


## Segundo Piso
Están los dos nenes 
- Nikolai y Mirtle, desde afuera las cajas se abren facil

## Tercer Piso
Se ve como funciona el mecanismo que hace que el molino funcione.
No hay nada más.



# Pelea
```encounter
creatures:
  - 3 Night Hag
```
![[z_compendium/bestiary/fiend/night-hag#Statblock|night-hag]]

## Plan
### Objetivo de Hags
1. Incapacitate
2. Intimidate
3. Cripple
### Plan de Spells
**14 DC spellchecks/+6 to hit spells** 
>[!Info]
>Si alguna baja a 30 HP, usan su acción para hacer TP a ethereal plane
- Guardarse [[counterspell|Counterspell]] para los spellcasters.
- Abrir con 2 [[bestow-curse|Bestow Curse]](Desventaja en WIS Checks) a nivel 5 a los PCs mas potente
- [[eyebite|Eyebite]] (sickened)a nivel 6 al que está curseado

- [[polymorph|Polymorph]] (Level 4)([[frog|Frog]]) a todo lo que sea hostil

- Si falla, [[hold-person|Hold Person]] (Level 2)
- [[ray-of-sickness|Ray of Sickness]] a los holdeados

- Shape Change (Si no estan en hag form)
- Claw (+7/2d8+4(13)) a los paralizados por hold person (Las hags tienen ventaja y si pegan es crit)

- 2 Hags focusean a un PC con [[magic-missile|Magic Missile]]
- 1 Hag tira [[sleep|Sleep]] a ese PC





**Comparten Spells Slots**

| Level | Slots | Spells                                                                                                                                     |
| ----- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 0     | inf   | [[detect-magic\|Detect Magic]], [[magic-missile\|Magic Missile]]                                                                           |
| 0     | 2/day | [[plane-shift\|Plane Shift]](Self only),[[ray-of-enfeeblement\|Ray of Enfeeblement]], [[sleep\|Sleep]]                                     |
| 1     | 4     | [[identify\|Identify]], **[[ray-of-sickness\|Ray of Sickness]]**                                                                           |
| 2     | 3     | **[[hold-person\|Hold Person]]**, [[locate-object\|Locate Object]]                                                                         |
| 3     | 3     | [[bestow-curse\|Bestow Curse]], **[[counterspell\|Counterspell]]**, [[lightning-bolt\|Lightning Bolt]]                                     |
| 4     | 3     | [[phantasmal-killer\|Phantasmal Killer]], **[[polymorph\|Polymorph]]**, **[[hold-person\|Hold Person]]**                                   |
| 5     | 2     | [[lightning-bolt\|Lightning Bolt]], **[[bestow-curse\|Bestow Curse]]**, [[contact-other-plane\|Contact Other Plane]], [[scrying\|Scrying]] |
| 6     | 1     | **[[eyebite\|Eyebite]]**                                                                                                                   |
# Hag's Bargain

| Deal              | Value  | Description                                                                                                                                                                   |
| ----------------- | ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Your Final Breath | Medium | ==A PC that accepts this deal dies after two failed death saving throws, rather than three.==                                                                                 |
| Your Victories    | High   | ==A PC that accepts this deal can no longer make the final blow on a weakened enemy; even if their attack hits, the enemy is able to miraculously avoid taking any damage.==  |
| Your Luck         | Medium | Three times per day, the DM can impose disadvantage on a roll made by a PC that accepts this deal.                                                                            |
| Your Memory       | Low    | A PC that accepts this deal has disadvantage on any History, Arcana, Religion, or Nature checks made to recall information.                                                   |
| Your Body         | Low    | ==A PC that accepts this deal must provide the hags with a vial of blood or a lock of hair.==                                                                                 |
| Your Courage      | Low    | A PC that accepts this deal gains disadvantage on saving throws against any fear-related effects.                                                                             |
| Your Hope         | Medium | ==A PC that accepts this deal gains the flaw: “The world is a dark, terrible place, and no man’s fight can ever push back the darkness.”==                                    |
| Your Swiftness    | High   | A PC that accepts this deal gains disadvantage on initiative rolls.                                                                                                           |
| Your Voice        | High   | A PC that accepts this deal becomes mute and cannot cast spells that require verbal components.                                                                               |
| Your Tongue       | Medium | A PC that accepts this deal gains disadvantage on all social Charisma-based checks.                                                                                           |
| Your Breath       | High   | ==A PC that accepts this deal heals only half hitpoints from hit dice and magical healing, and regains only one-fourth of their total hit dice upon completing a long rest.== |
| Your Heart        | Low    | ==A PC that accepts this deal gains the flaw: “The suffering of others does little to stir me.”==                                                                             |
