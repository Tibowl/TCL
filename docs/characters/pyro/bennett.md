---
description: A good-natured adventurer from Mondstadt who's unfortunately extremely unlucky.
---

## Resources

* [Bennett Mains Discord](https://discord.gg/qrjeEyejsd)
* [Full Bennett Guide: Bennett's Adventure Log](https://keqingmains.com/bennett/)

# Bennett

## ![](/assets/element_pyro.png) Bennett

![](/assets/character_bennett_wish.png)

## Base Stats

| Lv | Base HP | Base ATK | Base DEF | Energy Recharge% |
| :--- | :--- | :--- | :--- | :--- |
| 60 | 8168 | 126 | 508 | 13.30% |
| 60+ | 8719 | 134 | 542 | 13.30% |
| 70 | 9577 | 148 | 596 | 13.30% |
| 70+ | 10129 | 156 | 630 | 20% |
| 80 | 10987 | 169 | 684 | 20% |
| 80+ | 11539 | 178 | 718 | 26.70% |
| 90 | 12397 | 191 | 771 | 26.70% |

## Attacks

<Tabs>
<TabItem value="na" label="Strike of Fortune">
**Normal Attacks**  
Bennett performs up to 5 consecutive attacks.

| String | Talent 9% | Frames | MV/s | Poise Damage | Impulse Type |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1-Hit | 81.84% | 12 | 409.20%/s | 38.7 | 3 |
| 2-Hit | 78.53% | 32 | 300.69%/s | 37.8 | 3 |
| 3-Hit | 100.33% | 63 | 248.29%/s | 47.7 | 3 |
| 4-Hit | 109.65% | 118 | 188.31%/s | 52.2 | 3 |
| 5-Hit | 132.09% | 167 | 180.52%/s | 62.1 | 6 |

**Charged Attack**  
Consumes 20 stamina to unleash 2 consecutive strikes.

| String | Talent 9% | Frames | MV/s | Poise Damage | Impulse Type |
| :--- | :--- | :--- | :--- | :--- | :--- |
| CA | 102.7% + 111.55% | - | - | 2 + 6 |
| N1C | 296.09% | 100 | 177.65%/s | - | - |

* All frame counts are done against Ruin Guards.
* Enemies struck by Bennett's charged attack will be staggered or launched.

**Plunge Attack**  
Plunges from mid-air to strike the ground below, damaging opponents along the path and dealing AoE DMG upon impact.

| Damage Type | Talent 9% | Poise Damage | Impulse Type |
| :--- | :--- | :--- | :--- |
| Plunge DMG | 117.46% | 25 | 2 |
| Low Plunge DMG | 234.86% | 100 | 4 |
| High Plunge DMG | 293.36% | 150 | 7 |

</TabItem>

<TabItem value="e" label="Passion Overload"> 
Bennett puts all his fire and passion for adventuring into his sword. Results may vary based on how fired up he is...

**Press**  
A single, swift flame strike that deals Pyro DMG.

**Hold \(Short\)**  
Charges up, resulting in different effects when unleashed based on the Charge Level.  
• Level 1: Strikes twice, dealing Pyro DMG and launching opponents.  
• Level 2: Unleashes 3 consecutive attacks that deal impressive Pyro DMG, but the last attack triggers an explosion that launches both Bennett and the enemy.  
Bennett takes no damage from being launched.

| Attribute | Skill Press | Skill Hold \(Level 1\) | Skill Hold \(Level 2\) |
| :--- | :--- | :--- | :--- |
| Skill DMG \(T9%\) | 233.92% | 142.8% + 156.4% | 149.6% + 163.2% + 224.4% |
| MV/s \(T9%\) | 269.91%/s | 160.29%/s | 163.61%/s |
| Particles | 2~3 \(3:1\) | 3 \(-\) | 3 \(-\)  |
| Frames | 52 | 112 | 197 |
| GU | 2B | 2x 1A | 3x 1A |
| ICD | None | None | None |
| Snapshot | Dynamic | Dynamic | Dynamic |
| Damage Element | Pyro | Pyro | Pyro |
| Damage Type | Skill | Skill | Skill |
| CD | 5s | 7.5s | 10s |
| Poise Damage | 100 | 100 x2 | Hit: 100 x2 + 250 <br/> Explosion: 250 |
| Impulse Type | 4 | 3 + \(Air, 300, 900\) | Hit: 3 + \(Air, 300, 900\) + 8 <br/> Explosion: Air, 650, 950 |

**Notes**
* Max hold duration is 2 seconds, after which Bennett will use a Level 2 Passion Overload by default. 
* Having knockback resistance will prevent the explosion from knocking back Bennett after casting a Level 2 Passion Overload.
* When casting a Level 2 Passion Overload it will destroy one of the **Rain Swords** from Xingqiu's Elemental skill despite not dealing any damage.
* Frame counts are done against Ruin Guards.

</TabItem>

<TabItem value="q" label="Fantastic Voyage">
Bennett performs a jumping attack that deals Pyro DMG, creating an **Inspiration Field**.

**Inspiration Field**  
• If the health of a character within the AoE of **Inspiration Field** is less than or equal to 70%, their HP will continuously regenerate based on Bennett’s max HP.  
• However, if the health of the character is greater than 70%, gain an ATK bonus based on Bennett’s base ATK.  
• Continuously imbues characters within the AoE with Pyro.

| Attribute | Burst |
| :--- | :--- |
| Skill DMG \(T9%\) | 395.76% |
| Cast Frames | 51 |
| Energy Frame | 42 |
| CD Frame | 36 |
| GU | 2B |
| ICD | None |
| Snapshot | Snapshot |
| Damage Element | Pyro |
| Damage Type | Burst |
| Energy Cost | 60 |
| CD | 15s |
| Poise Damage | 200 |
| Impulse Type | 4 |

| Attribute | Field \(Talent 9%\) |
| :--- | :--- |
| HP Regeneration | 10.2% Max HP + 1174 |
| ATK Bonus Ratio | 95.2% **Base ATK** |
| Imbue | 1A |
| Duration | 12s |

**Notes**
* Bennett field does not apply the buffs instantaneously on swap. **Inspiration Field** applies the ATK bonus and healing on the same tick every second. If you swap after the tick occurs, you will need to wait for the next tick to receive the ATK bonus.
  * Additionally, **Inspiration Field**'s buff lingers for a bit after the visual of the circle fades away.
* **Inspiration Field's** ATK Bonus and **C6: Fire Ventures With Me** Pyro DMG Bonus will apply on its own damage calculation.
* The bonus ATK from **Inspiration Field** ONLY scales with Bennett's base attack.
* When in coop with multiple Bennetts, the bonus ATK prioritizes the **Inspiration Field** that applied the bonus first.
  * This means that even when two Bennett bursts overlap, the attack buff that was applied first will remain.

</TabItem>
</Tabs>

## Ascension Passives

<Tabs>
<TabItem value="passive" label="Passive">

### It Should Be Safe...

When dispatched on an expedition in Mondstadt, time consumed is reduced by 25%.

</TabItem>

<TabItem value="a1" label="Ascension 1">

### Rekindle

Decreases **Passion Overload**'s CD by 20%.

</TabItem>

<TabItem value="a4" label="Ascension 4">

### Fearnaught

Within the area created by **Fantastic Voyage**, **Passion Overload** takes on the following effects:
* CD is reduced by 50%.
* Bennett will not be launched by the effects of Charge Level 2.

**Note**
* This effect is tied to Bennett's Attack Bonus, not the field itself.

</TabItem>
</Tabs>

## Constellations

<Tabs>
<TabItem value="c1" label="C1">

### Grand Expectation

**Fantastic Voyage**'s ATK increase no longer has an HP restriction, and gains an additional 20% of Bennett's Base ATK.

</TabItem>

<TabItem value="c2" label="C2">

### Impasse Conqueror

When Bennett's HP falls below 70%, his Energy Recharge is increased by 30%.

</TabItem>

<TabItem value="c3" label="C3">

### Unstoppable Fervor

Increases the Level of **Passion Overload** by 3.
Maximum upgrade level is 15.

</TabItem>

<TabItem value="c4" label="C4">

### Unexpected Odyssey

Using a Normal Attack when executing the second attack of **Passion Overload**'s Charge Level 1 allows an additional attack to be performed.
This additional attack does 135% of the second attack's DMG.

| Attribute | Skill Hold \(Level 1\) + Normal Attack |
| :--- | :--- |
| Skill DMG \(T6%\) | 117.6% + 128.8% + 173.88% |
| Particles | 3 \(-\) | 
| GU | 3x 1A |
| ICD | 3 hits/2.5s |
| Snapshot | Dynamic | 
| Damage Element | Pyro |
| Damage Type | Skill |
| CD | 7.5s | 
| Poise Damage | 100 |
| Impulse Type | 6 |

</TabItem>

<TabItem value="c5" label="C5">

### True Explorer

Increases the Level of **Fantastic Voyage** by 3.
Maximum upgrade level is 15.

</TabItem>

<TabItem value="c6" label="C6">

### Fire Ventures With Me

Sword, Claymore, or Polearm-wielding characters inside **Fantastic Voyage**'s radius gain a 15% **Pyro DMG Bonus** and their weapons are infused with **Pyro**.

* Pyro Infusion lasts 2 seconds upon leaving **Inspiration Field**.
* The Pyro DMG bonus will apply to the Fantastic Voyage damage.
* Pyro infused autos have 1U worth of Pyro applcation.  
* The buff does not stack in coop.  
* The description of **Fire Ventures With Me** has a mistranslation. The 15% Pyro DMG Bonus applies to every character within its area of effect, regardless of weapon type.  

</TabItem>
</Tabs>

## Full Talent Values

<Tabs>
<TabItem value="na" label="Strike of Fortune">

### Normal Attacks

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1-Hit DMG | 44.55% | 48.17% | 51.80% | 56.98% | 60.61% | 64.75% | 70.45% | 76.15% | 81.84% | 88.06% | 94.28% |
| 2-Hit DMG | 42.74% | 46.22% | 49.70% | 54.67% | 58.15% | 62.12% | 67.59% | 73.06% | 78.53% | 84.49% | 90.45% |
| 3-Hit DMG | 54.61% | 59.06% | 63.50% | 69.85% | 74.30% | 79.37% | 86.36% | 93.34% | 100.33% | 107.95% | 115.57% |
| 4-Hit DMG | 59.68% | 64.54% | 69.40% | 76.34% | 81.20% | 86.75% | 94.38% | 102.02% | 109.65% | 117.98% | 126.31% |
| 5-Hit DMG | 71.90% | 77.75% | 83.60% | 91.96% | 97.81% | 104.50% | 113.70% | 122.89% | 132.09% | 142.12% | 152.15% |

### Charged Attack

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Charged Attack 1 DMG | 55.90% | 60.45% | 65.00% | 71.50% | 76.05% | 81.25% | 88.40% | 95.55% | 102.70% | 110.50% | 118.30% |
| Charged Attack 2 DMG | 60.72% | 65.66% | 70.60% | 77.66% | 82.60% | 88.25% | 96.02% | 103.78% | 111.55% | 120.02% | 128.49% |

**Stamina Cost**: 20

### Plunge

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Plunge DMG | 63.93% | 69.14% | 74.34% | 81.77% | 86.98% | 92.93% | 101.10% | 109.28% | 117.46% | 126.38% | 135.30% |
| Low Plunge DMG | 127.84% | 138.24% | 148.65% | 163.51% | 173.92% | 185.81% | 202.16% | 218.51% | 234.86% | 252.70% | 270.54% |
| High Plunge DMG | 159.68% | 172.67% | 185.67% | 204.24% | 217.23% | 232.09% | 252.51% | 272.93% | 293.36% | 315.64% | 337.92% |

</TabItem>

<TabItem value="e" label="Passion Overload">

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Press DMG | 137.60% | 147.92% | 158.24% | 172.00% | 182.32% | 192.64% | 206.40% | 220.16% | 233.92% | 247.68% | 261.44% | 275.20% | 292.40% |
| Charge Level 1 Hit 1 DMG | 84% | 90% | 96% | 105% | 111% | 117% | 126% | 134% | 142% | 151% | 159% | 168% | 178% |
| Charge Level 1 Hit 2 DMG | 92% | 98% | 105% | 115% | 121% | 128% | 138% | 147% | 156% | 165% | 174% | 184% | 195% |
| Charge Level 2 Hit 1 DMG | 88% | 94% | 101% | 110% | 116% | 123% | 132% | 140% | 149% | 158% | 167% | 176% | 187% |
| Charge Level 2 Hit 2 DMG | 96% | 103% | 110% | 120% | 127% | 134% | 144% | 153% | 163% | 172% | 182% | 192% | 204% |
| Explosion DMG | 132% | 141% | 151% | 165% | 174% | 184% | 198% | 211% | 224% | 237% | 250% | 264% | 280% |

**Cooldown**: 5.0/7.5/10.0s

</TabItem>

<TabItem value="q" label="Fantastic Voyage">

|  | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 | Lv6 | Lv7 | Lv8 | Lv9 | Lv10 | Lv11 | Lv12 | Lv13 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Skill DMG | 232.80% | 250.26% | 267.72% | 291.00% | 308.46% | 325.92% | 349.20% | 372.48% | 395.76% | 419.04% | 442.32% | 465.60% | 494.70% |
| Continuous Regeneration Per Second Scaling | 6.00% | 6.45% | 6.90% | 7.50% | 7.95% | 8.40% | 9.00% | 9.60% | 10.20% | 10.80% | 11.40% | 12.00% | 12.75% |
| Continuous Regeneration Per Second Additive | 577 | 635 | 698 | 765 | 837 | 914 | 996 | 1083 | 1174 | 1270 | 1371 | 1477 | 1588 |
| ATK Bonus Ratio | 56.0% | 60.2% | 64.4% | 70.0% | 74.2% | 78.4% | 84.0% | 89.6% | 95.2% | 100.8% | 106.4% | 112.0% | 119.0% |

**Duration**: 12s  
**Cooldown**: 15s  
**Energy Cost**: 60

</TabItem>
</Tabs>

## Evidence Vault

<Card item={require('../../evidence/characters/pyro/bennett.md')} />

