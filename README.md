<title>
  Devil May Cry 1 Mechanics
</title>
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Health
Dante starts with 1000 HP. Each whole blue orb adds 100 HP. The maximum HP attainable is 3000.

Dante and enemies do not die at 0 HP, they die at under 0 HP.

## Low HP
Dante cannot die in one hit if he has more than 300 HP. When he has more than 300 HP, and he takes an attack that does more damage than his remaining HP, he will not die, and his health will be set to 0. When his health is 300 HP or less though, a hit that takes him under 0 HP will kill him. A visual indication of this is when the border of HP bar turns red, as it is red when Dante's health is at 299 or lower. However, there is one case, which is when the HP value is exactly 300. In this case, Dante will be able to die from any hit that does 301 or more damage, even though the border of his HP bar is not red. 

# Devil Trigger Gauge
Each rune of DT is worth 120 points. When DT is activated, the value is converted to 200 points per rune and drains at a rate of 1 point per frame. During flight mode with Alastor, DT drains at 2 points per frame. During using Kick-13, it drains 5 points per frame, and during Inferno, it drains 9 points per frame.

## Stat Changes

|Damage you do to enemies| Damage Taken |
|---|---|
|2x| 3/4x |

## Health Restoration in DT

|Difficulty Mode | Amount |
|---|---|
|Easy|1 HP per 2 frames, 30 HP per second|
|Normal|1 HP per 4 frames, 15 HP per second|
|Hard|1 HP per 8 frames, 7.5 HP per second|
|Dante Must Die!| None |

# Difficulty Changes in regards to Damage

## Regular Enemies

| Difficulty Mode      | Damage you do | Damage taken |
| --- | --- | --- |
| Normal      | 1x |    1x   |
| Hard   | 1x  |   2x  |
|Dante Must Die!* | 1x | 2x |

*Enemies activating Devil Trigger triples their damage to Dante. For defensive values after Devil Triggering, Marionettes and Fetishes take 1/2 damage. Sin Scissors, Sin Scythes, Sargassos, Plasmas, and Green Beelzebubs take 1/3 damage. Blue Beelzebubs takes 1/6 damage. See Bestiary.

## Bosses 

| Difficulty Mode      | Damage you do | Damage taken |
| --- | --- | --- |
| Normal      | 1x |    1x   |
| Hard   |  1/3x, 1x*  |   2x  |
|Dante Must Die! | 1/3x | 5x |

* You do regular damage to bosses when you Devil Trigger and use a melee attack. DT'd firearm attacks and all nonDT attacks do 1/3 damage.


# Stylish Meter
Forget everything about the Stylish meter in DMC3 and onwards, the Stylish meter in DMC1 is basically a combo meter.

Each attack to an enemy will earn points in the visible Stylish meter. For High Time, Magma Drive, or Meteor, the next attack following these attacks will also add a bonus value. When an attack connects, you have 89 frames to maintain the Style meter by hitting an enemy with another attack. When another attack hits, it resets the timer back to 89 frames. Charging Roundtrip, charging Ifrit attacks, or taunting will pause the timer. 

Each attack has a designated number of red orbs it adds to the total. This is multiplied by the current Style meter multiplier to add to the total number of red orbs. This accumulated amount will never go away, even if you lose the Style meter. 

The only bosses that gain additional red orbs from the Stylish meter upon defeat are Nightmare and Shadow Nelo Angelo.

|Stylish Rank| Points Needed | Red Orb Multiplier|
|---|---|---|
|Dull| 11 or lower | 1x | 
|Cool!| 12-47 | 2x |
|Bravo!| 48-63 | 3x |
|Absolute!| 64-127 | 5x |
|Stylish!|128 or higher | 10x |

## Values List


# Mission End Ranking

# Firearms

## Ebony and Ivory
## Shotgun
## Grenadegun
## Needlegun

## Nightmare-$\beta$

When the Nightmare-$\beta$ is equipped, Dante's punch attacks with his left arm are doubled. This does not stack with Devil Trigger, unless it is activated when the attack hits.

# Devil Arms List

## Force Edge
Does 2/3 damage of Alastor

## Alastor
## Ifrit
### Charging
Charged attacks(Punches, Kicks, Magma Drive) will gain 10% damage per frame of charge, up to 590%. Punches and Kicks(not Magma Drive) will automatically have a 10% multiplier applied, even if there is zero charge. If any of these attacks automatically releases, a 400% multiplier is applied.

For Meteor, it gains (slightly less than) 2% of damage per frame of charge. If it automatically releases, a 400% multipler is applied. The exact value of charge per frame is 1/51.

## Sparda
Sparda does twice as much damage as Alastor, effectively being the same damage as Alastor.

In Mission 22, Sparda's attack range becomes 4x when in Devil Trigger.

# Some Enemy Mechanics

## Death Scissor

The Death Scissor has 5000 HP and two horns. The first horn breaks in the following conditions:

| Attack | Breaking Condition | Additional Effect |
|---|---|---|
| Sword Attacks | Two hits to the front, or one hit to the back | If the Death Scissor's HP is above 4000, it becomes 4000. | 
| Firearms, Air Raid, Vortex| Any hit that brings the Death Scissor HP to 4000 or lower |  |

The second horn breaks under this condition:

| Attack | Breaking Condition | Additional Effect |
|---|---|---|
| Sword Attacks | Five hits to the front, or one hit to the back | If the Death Scissor's HP is above 2000, it becomes 2000. | 
| Firearms, Air Raid, Vortex| Any hit that brings the Death Scissor HP to 1500 or lower |  |

When the horn breaks, the Death Scissor becomes red(invincible state) and starts the corkscrew attack.

Any attack to the Death Scissor's back does double damage.

TODO: Check Ifrit attacks

## Death Scythe

The Death Scythe has 3000 HP. If the Death Scythe has over 500 HP, any attack that would bring it to under 500 HP would instead just set the Death Scythe's HP to 500. Once this threshold has been met, the Death Scythe will be able to gather the 3 scythes on the ground and start its 4 scythe phase.

## Shadow Critical Hit

When the Shadow starts its horizontal spike attack, it sets a counter to 0. By just standing on the horizontal spike, this counter goes up by 1 per frame. The contribution from standing on the spike is at most 121. When the Shadow is attacked while Dante stands on the spike, the counter goes up by an additional 3(10 in the 2018 HD version) per frame for 8 frames, so it effectively adds 24(80 in the 2018 HD version) to this counter for each attack. When the following threshold is exceeded, the Shadow turns red.  

| Difficulty | Threshold | 
|---|---|
| Normal | 280 |
| Hard | 390* |
| DMD! | 420 |
| DT Shadow | 450** |

*290 on PS2 versions outside of Japan.
  
**5450 on the 2018 HD versions.

## Nelo Angelo Hit Counter

When Nelo Angelo gets hit, he has a counter that increases by 1 for each hit. When it exceeds a certain value(16 for Nelo 1 and Shadow Nelo, 8 for Nelo 2 and 3), Nelo Angelo can block in the middle of a combo. This counter resets to 0 when Nelo teleports or charges a meteor.

## Griffon Knockdown

When Griffon is hit by a Devil Arm attack, excluding Air Raid, Vortex, and Roundtrip, he has a counter that increases by 2 for each hit. When this value reaches 30 for Griffon 1 or 20 for Griffon 3, he is knocked down.

* The counter also increases by 1 sometimes if he is hit in the air by a firearm. I believe that it has to hit his head hitbox for it to count.

## Nightmare

### Core Mechanics

Nightmare has 2 cores, a top core and a bottom core. The top core begins with 6000 and the bottom core begins with 8000. When these values are under 4000 or 5000 respectively, the respective core turns green. When it is under 1000, the respective core turns red. Nightmare's cores cannot turn red on the first fight. Each attack done to the core lowers the value by the base damage of the attack, not the actual damage value. Since charged Ifrit attacks have multipliers, they have the highest ratio of damage to Nightmare's HP to core breakage damage.

When the cores change color, they also change Nightmare's attacks.

**Top Core**

|Values| Color | Effect|
|---|---|---|
|4000-6000 | Blue | Ice Beam attack lasts the shortest. |
|1000-3999| Green | Ice Beam attack lasts longer and Nightmare moves back and forth during this attack. |
| 999 or under | Red | HP Damage taken is 1/2x. Stylish meter gain is doubled. Ice Beam attack lasts the longest. |

**Bottom Core**

|Values| Color | Effect|
|---|---|---|
|5000-8000 | Blue |  |
|1000-4999 | Green | The projectile attack has better aim. The damage Dante takes from this attack is lowered from 150 to 60. |
| 999 or under | Red | HP Damage taken is 1/2x. Stylish meter gain is doubled.  |

Certain events will reset the core values. The events are:
1. When Dante returns from Nightmare's underworld
2. Nightmare fight begins
3. Trish's cutscene in Nightmare 3

|Core Location|Color|Reset Value|
|---|---|---:|
|Top|Blue | 6000|
|Top|Green|3900|
|Top|Red|900|
|Bottom|Blue|8000|
|Bottom|Green|4900|
|Bottom|Red|4900*|

* 900 on the PS2 North American, PS2 PAL, and PS2 Korean versions

Note that there is a bug with a red bottom core when refilling the core values.

#### Red Core Refill Bug

On all versions of the game except PS2 North American, PS2 PAL, and PS2 Korean, a red bottom core does not refill correctly. A red bottom core refills the **top** core to 900. This does not change the color of the top core, but it will cause it to break and turn to the next color in one hit. On the PS2 North American, PS2 PAL, and PS2 Korean versions, this bug is fixed, and a red bottom core refills the values correctly.

### Final Core

When Nightmare 3 initially gets his hp to -1 or lower, he reveals his final core. This core is always red in color, but it does not have the double defense the other cores have when they turn red. Nightmare restores 2000 HP. The attack that reveals the final core has its damage applied to the 2000 HP restored. The final core has 2000. When it reaches under 1000, it breaks, but this does not appear to do anything outside of visual. 

# Bestiary

## Marionettes and Bloody Mari

### HP

|HP|Percentage|
|---:|---:|
|800|1/16|
|1000|7/16|
|1100|1/16|
|1200|3/16|
|1250|1/16|
|1400|1/16|
|1500|2/16|

* Indigo Marionettes have double HP from these values.
* Bloody Maris have triple HP from these values.

### Devil Trigger Bonus
* Damage to Dante triples
* HP is refilled to 3000(9000 for Bloody Maris)
* Damage taken is halved
* Super armor except for Dante's melee attacks in Devil Trigger
* Can no longer block handgun shots
* Devil Trigger gauge recovery from attacking the enemy is doubled
  
## Fetish

### HP
2000

### Devil Trigger Bonus
* Damage to Dante triples
* HP is refilled to 6000
* Damage taken is halved
* Super armor except for Dante's melee attacks in Devil Trigger
* Devil Trigger gauge recovery from attacking the enemy becomes 1.5x

## Sin Scissors

### HP

|HP|Percentage|
|---:|---:|
|800|7/16|
|1000|5/16|
|1200|2/16|
|1400|2/16|

#### Easy Mode HP

|HP|Percentage|
|---:|---:|
|1600|3/16|
|1800|4/16|
|2000|3/16|
|2200|2/16|
|2400|2/16|
|2600|1/16|
|2800|1/16|

### Devil Trigger Bonus
* Damage to Dante triples
* Damage taken becomes 1/3x
* Increased attack frequency

## Sin Scythe

### HP

|HP|Percentage|
|---:|---:|
|800|10/16|
|1000|6/16|

#### Easy Mode HP

|HP|Percentage|
|---:|---:|
|1200|6/16|
|1300|4/16|
|1400|4/16|
|1500|2/16|


### Devil Trigger Bonus
* Damage to Dante triples
* Damage taken becomes 1/3x
* Increased attack frequency
* More likely to be a low position(?)

## Death Scissors

### HP
5000

### Devil Trigger Bonus
* Damage to Dante triples

## Death Scythe

### HP
3000

## Sargasso

### HP
1000 (small)
2000 (big)

### Devil Trigger Bonus
* Damage to Dante triples
* Damage taken becomes 1/3x

  
## Shadow

### HP
3000 
* 1500 First encounter on Normal

### Devil Trigger Bonus
* Damage to Dante triples
* Automatically uses magical spike attack when Dante is close
  
  
## Beelzebub

## Kyklops
### HP
1080
540 (Easy Mode)

## Blade

|HP|Percentage|
|---:|---:|
|1200|1/3|
|1300|1/3|
|1500|1/3|

Large Blade

|HP|Percentage|
|---:|---:|
|3000|2/3|
|3300|1/3|

## Plasma 
1000

## Frost
3000

## Nobody
2400

## Phantom

### HP

|HP|Encounter|
|---:|---:|
|4500|Mission 3|
|2000|Mission 4, Mission 7|
|2250|Fountain Room on Hard, DMD!, Nightmare's underworld|
|5500|Mission 8|

#### Easy Mode HP

|HP|Encounter|
|---:|---:|
|3375|Mission 3|
|1500|Mission 4, Mission 7|
|2250|Fountain Room on Hard, DMD!, Nightmare's underworld|
|4125|Mission 8|

## Nelo Angelo
1500
2100
2500 (2100 Easy Mode)
1000 (Nightmare's Underworld)

## Griffon
8000
4000
10000
4000 (Nightmare's Underworld)

Easy Mode
6000
4000
10000
2000 (Nightmare's Underworld)

## Nightmare 

### HP
7000
2000(Final Core)

## Devil Trigger Bonus
* Damage to Dante becomes 2x

## Mundus 
10000, First Fight
10000, Second Fight
2000, Third Fight

# TO DO
- Table of Contents
- Formatting
- Damage as in PS2 NTSC-U and PAL
- Mission End Ranking
- Stylish Meter, list all attacks and values
- Devil Arm list and attacks
- Bestiary
    - Damage Numbers
- Bosses
    - Boss Mechanics
    - Nelo's hit counter
    - Griffins knockdown counter
    - Griffin 3's HP and defense mechanics
- Nightmare
  - Attack Cycle
  - Cores
  - Underworld
