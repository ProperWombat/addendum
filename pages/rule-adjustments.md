# Rule Adjustments

## Difficulty Scaling with Party Size

Default rules are written with 1 to 4 players in mind.
This table is for scaling the large monsters which will take damage from the entire party.
|Players | Max Enemy Stats | Enemy Stat Scaling | Multi Hit Rule|
| ----------- | ----------- | ----------- | ----------- |
| 1 to 4|  (14,3,18,18,18)|  x1|  Keep only the highest damage dice|
| ~6|  (21,3,27,27,27)|  x1.5|  Keep the highest ⌈n/3⌉ |
| ~8|  (28,3,36,36,36)|  x2.0|  Keep the highest ⌈n/3⌉ |
Consider using many weaker enemies or a multi-entity monster to spread out the party’s damage during a boss encounter. Also consider that a party will lose members during a fight which will decrease the damage output.
Be mindful of the player average damage per roll compared to the monster’s armor. An armor of 4 negates all damage from a d4 rendering it invincible to unarmed and impaired attacks. This could work well on monsters which are impervious to real world attacks and weak to CTRL attacks.

### Multiple Attacks

If multiple attackers target the same entity, roll all n damage dice and keep the highest ⌈n/3⌉ results. To find the highest ⌈n/3⌉ count the number of dice rolled, divide by 3 then round up to the next integer. The armor score of the attacked entity is applied to each attack.

#### Examples

| Attack rolls after armor | Keep only Highest |  Keep the highest ⌈n/3⌉ |
| ----------- | ----------- | ----------- |
| 1 | 1 | 1 |
| 3,2,1 | 3 | 3 |
| 4,3,2,1 | 4 | 4 + 3 |
| 6,5,4,3,2,1 | 6 | 6 + 5 |
| 7,6,5,4,3,2,1 | 7 | 7 + 6 + 5 |
| 12,11,10,9,8,7,6,5,4,3,2,1 | 12 | 12 + 11 + 10 + 9 |

## Anomalies and Magic

This module uses the [magic mechanics](https://goblinarchives.github.io/LiminalHorror/Liminal%20Horror%20System/Magic/) from Liminal Horror for anomalies. If a player rolls a 20 for their weapon during character creation they gain access to an anomaly. Players should discuss the function and usability of the anomaly with the Facilitator. Some anomalies may be mundane (safe) and can be used many times a day without negative effects. Others may require CTRL saves and could cause deprivation or fatigue.
