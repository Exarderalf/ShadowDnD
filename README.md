# ShadowDnD

## Attributes

Attributes represent the base representation of the mind and body of the character. Attributes are capped at level + 1 at the highest and -level - 1 at lowest. On character creation you have 4 points with the ability reduce into the negatives to gain more points. Attribute points gain 2 per level (subject to change) with the ability to reduce points in stats to gain more points.

### Physical

| Stat         | Description |
| ------------ | ----------- |
| Strength     | Physical strength used to strength based activities and can influence strength weapons. |
| Constitution | Bodily Fortitude (also used with hp)                                                    |
| Dexterity    | Bodily agility and finesse                                                              |
| Reaction     | Reaction times                                                                          |
| Senses       | Physical sensations                                                                     |

### Mental

| Stat            | Description                                         |
| --------------- | --------------------------------------------------- |
| Intelligence    | Mental capabilities (book smarts)                   |
| Wisdom          | Mental capabilities (street smarts)                 |
| Charisma        | Social appeal                                       |
| Tech            | Innate ability to use technology                    |
| Mental Agility  | Ability to visualise and manifest concepts (cook up a word) orum |

-------------------------------------

## AC

Combination of Dex and Reaction as well armor/shield worn. Possible flat footed for one round if surprised (failing both a spot/listen/hearing check and reaction save). Being flat footed can lose one or both of dex or reaction depending on failure scaling.

10 + dex + reaction + worn items

## Proficiency

Proficiency bonus = Math.floor(level / 2) minimum of 1

## Checks

Check points when starting a new character: 2 + number of attributes with positive points
Check points per level up: number of attributes with positive points / 2
Capped at: level + 1

| Skill        | Description |
| ------------ | ----------- |
| Athletics    |             |
| Acrobatics   |             |
| Intuition    |             |
| Composure    |             |
| Spot         |             |
| Listen       |             |
| Smell        |             |
| Ingenuity    |             |
| Stealth      |             |
| Persuasion   |             |
| Deception    |             |
| Intimidate   |             |
| Empathy      |             |
| Computer Use |             |
| Medicine     |             |

## Example Dice for DC checks

Make a Spot (Sens) Check.
```
You have a 2 in Spot and a -1 in Sens.
You roll 2 positive dice and 1 negative dice.
Positive dice rolls a 5 and 2.
Negative dice rolls a 6
Number of total successes: 0
```

```
You have a 2 in Spot and a -1 in Sens.
You roll 2 positive dice and 1 negative dice.
Positive dice rolls a 5 and 2.
Negative dice rolls a 2
Number of total successes: 1
```

```
You have a 2 in Spot and a -1 in Sens.
You roll 2 positive dice and 1 negative dice.
Positive dice rolls a 5 and 6.
Negative dice rolls a 2
Number of total successes: 2
```

```
You have a 2 in Spot and a -1 in Sens.
You roll 2 positive dice and 1 negative dice.
Positive dice rolls a 1 and 3.
Negative dice rolls a 6
Number of total successes: -1
```
