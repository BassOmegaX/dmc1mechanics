<title>
  Devil May Cry 1 Mechanics
</title>
<link rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.css">

<script defer
  src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.js">
</script>

<script defer
  src="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/contrib/auto-render.min.js"
  onload="renderMathInElement(document.body);">
</script>

# Health
Dante starts with 1000 HP. Each whole blue orb adds 100 HP. The maximum HP attainable is 3000.

Dante and enemies do not die at 0 HP, they die at under 0 HP.

## Low HP
Dante cannot die in one hit if he has more than 300 HP. When he has more than 300 HP, and he takes an attack that does more damage than his remaining HP, he will not die, and his health will be set to 0. When his health is 300 HP or less though, a hit that takes him under 0 HP will kill him. A visual indication of this is when the border of HP bar turns red, as it is red when Dante's health is at 299 or lower. However, there is one case, which is when the HP value is exactly 300. In this case, Dante will be able to die from any hit that does 301 or more damage, even though the border of his HP bar is not red. 

# Devil Trigger

## Gauge Mechanics

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
|Dante Must Die!<sup>1</sup>  | 1x | 2x |

1. Enemies activating Devil Trigger triples their damage to Dante. For defensive values after Devil Triggering, Marionettes and Fetishes take 1/2 damage. Sin Scissors, Sin Scythes, Sargassos, Plasmas, and Green Beelzebubs take 1/3 damage. Blue Beelzebubs takes 1/6 damage. See Bestiary.

## Bosses 

| Difficulty Mode      | Damage you do | Damage taken |
| --- | --- | --- |
| Normal      | 1x |    1x   |
| Hard   |  1/3x, 1x<sup>1</sup>  |   2x  |
|Dante Must Die! | 1/3x | 5x |

1. You do regular damage to bosses when you Devil Trigger and use a melee attack. DT'd firearm attacks and all nonDT attacks do 1/3 damage.


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

TBA

## Green Orb Drop Mechanics

There are two counters related to green orb drops. There is a spawn counter and a type counter. When you start a new game or load a save, the spawn counter is set to 20 and the type counter is set to 0.

When you kill enemies, the spawn counter goes down by an amount depending on the enemy. 

| Enemy | Counter Drop | 
| --- | ---: | 
| Marionettes | 3 |
| Fetishes | 6 |
| Sin Scissors | 4 |
| Sin Scythe | 5 |
| Death Scissors | 10 |
| Death Scythe | 10 |
| Shadow | 10 |
| Frost | 10 |
| Sargasso | 1 |
| Small Beelzebub | 1 |
| Large Beelzebub | 3 |
| Blade | 4 |
| Plasma | 7 |
| Nobody | 8 |
| Phantom | 40 |
| Kyklops | 40 |
| Griffon | 40 |
| Nightmare | 40 |
| Nelo Angelo | 30 | 

Blades and Frosts have this value doubled when they are DT'd. So a DT'd Frost will lower the spawn counter by 20, and a DT'd blade will lower the spawn counter by 8.

After you kill an enemy and the game subtracts the value from the spawn counter, the game checks if the spawn counter is 0 or less. If it is, then it checks if Dante is at max HP. If he is not, then the game spawns a green orb. The game checks the type counter. If it is 6 or greater, then the green orb is a large green orb. When the game spawns a green orb, the spawn counter is reset to a value from 20 to 22 randomly. If the green orb is a large green orb, then the type counter is set to 0.

The type counter goes up by 1 every time you kill an enemy when the spawn counter is at 0 or lower. This increase happens after the check for the green orb spawn. If you are at max HP, it will still go up even though a green orb spawn didn't occur, so you can increase this rapidly by killing enemies at max HP. If you do spawn a green orb, regardless of the type, the type counter goes up by 2 instead. This occurs after if the type counter is supposed to reset.

The small green orb restores 250 HP. The large green orb restores 50% HP.

In additional to these, Death Scissors and Shadow always drop 1 large green orb, and Death Scythes drop 2 green orbs, independent of this green orb drop. So in total, the Death Scissors and Shadow can drop up to 2 green orbs, and the Death Scythe can drop up to 3 green orbs. 

# Mission End Ranking

There are five categories that affect the ranking given at the end of each mission:

1. Time
2. Red Orbs Collected
3. Damage Taken
4. Items Used
5. Secret Missions Completed

## Time and Red Orb Requirements

| Mission | Time  | Red Orbs |
| -------: | -----: | --------: |
| 1       | 6:00  | 400      |
| 2       | 7:00  | 450      |
| 3       | 3:00  | 550      |
| 4       | 4:00  | 550      |
| 5       | 2:00  | 100      |
| 6       | 3:30  | 250      |
| 7       | 3:00  | 650      |
| 8       | 3:00  | 585      |
| 9       | 8:00  | 1500     |
| 10      | 4:30  | 600      |
| 11      | 5:30  | 1000     |
| 12      | 4:00  | 700      |
| 13      | 2:30  | 200      |
| 14      | 5:00  | 500      |
| 15      | 10:00 | 1400     |
| 16      | 6:00  | 1000     |
| 17      | 7:00  | 600      |
| 18      | 6:00  | 900      |
| 19      | 3:30  | 500      |
| 20      | 4:30  | 700      |
| 21      | 5:00  | 700      |
| 22<sup id="fn1">1</sup>     | 5:00  | 0        |
| 23      | 7:00  | 600      |

<p id="footnote-1">
  <b>1.</b> The time limit has been extended to 8:00 for DMD mode only.
</p>

## Time

| Time | Ranking Points  |
| -------: | -----: |
| Meet time limit | 500 |
| At most 30 seconds over | 300 |
| At most 2 minutes over | 200 |
| At most 5 minutes over | 100 |
| Above 5 minutes over | 0  |

The mission timer keeps track of everything from mission start to mission end. This includes going into the menus, watching cutscenes, and loading times. 

The mission end screen displays the mission time in hours:minutes:seconds. The game keeps tracks of the number of frames from mission start to mission end, but it does not display this number. Each threshold is to the frame. So a 3 minute time limit is exactly 180 frames. A displayed time of 3:00 will only meet the threshold if it is 3:00 and 0 frames. This means most of the time, the displayed time should be less than the mission time requirement in order to get 500 ranking points, and the same for each threshold. 

## Red Orbs

| Red Orbs Percentage Collected | Ranking Points  |
| -------: | -----: |
| 100% or more | 500 |
| 80% or more | 300 |
| 50% or more | 200 |
| 30% or more | 100 |
| Under 30% | 0  |

## Damage Taken

| Damage Taken | Ranking Points  |
| -------: | -----: |
| 0 | 500 |
| 1 to 500 | 300 |
| 501 to 1000 | 200 |
| 1001 to 1500 | 100 |
| 1501 or more | 0  |

### Note on Damage over Time (Mission 3 and Mission 7)

 - Need to fully expand section

Mission 3 underwater damage over time and Mission 7 damage over time is low enough to not affect the ranking points on Normal mode. For Hard and DMD, environmental damage doubles. This makes it so that the damage over time does affect ranking. However, activating Devil Trigger reduces the damage low enough for it to not affect mission ranking.

## Item Penalty

| Item | Ranking Penalty  | 
| :------- | -----: | 
| Devil Star       | -100 |
| Holy Water       | -100 |
| Vital Star       | -300 |
| Yellow Orb       | -300 |
| Untouchable       | -500 |

## Secret Mission Points

| Secret Mission | Ranking Points | 
| :------- | -----: | 
| 1, 5, 6, 7, 8, 10, 11, 12 | 200 |
| 2, 3, 4, 9 | 100 |

Note that Secret Mission 7 cannot be done while in a mission, so while it does give 200 ranking points, these points will never be applied to any mission. 

## Total Ranking Point Requirements

### All Difficulties except DMD

| Rank | Requirement |
| --- | --- |
| S | 1000 or more |
| A | 800 to 900 |
| B | 500 to 700 |
| C | 0 to 400 |
| D | Under 0 |

### DMD Difficulty

| Rank | Requirement |
| --- | ---: |
| S | 700 or more |
| A | 400 to 600 |
| B | 200 to 300 |
| C | 0 to 100 |
| D | Under 0 |

### Red Orbs Given

| Rank | Mission 1 to 8 | Mission 9 to 15 | Mission 16 to 22 | Mission 23 | 
| --- | ---: | ---: | ---: | ---: |
| S | 800 | 1500 | 2000 | 3000 |
| A | 400 | 800 | 1000 | 2000 |
| B | 200 | 350 | 500 | 1000 |
| C | 100 | 200 | 250 | 500 |
| D | 50 | 100 | 100 | 250 |

## Boss Bonus

The boss bonus is given in missions where a boss is defeated, but the following cutscene ends the mission. This means the player has defeated a boss but did not collect any red orbs from defeating the boss.

| Mission | Red Orbs|
| ---: | ---: | 
| 4 | 500 |
| 17 | 800 |
| 20 | 800 |
| 22 | 1000 |
| 23 | 1000 |

# Firearms

## Ebony and Ivory

TBA

## Shotgun

TBA

## Grenadegun

TBA

## Needlegun

TBA

## Nightmare-\(\beta\)

When the Nightmare-\(\beta\) is equipped, Dante's punch attacks with his left arm are doubled. This does not stack with Devil Trigger, unless it is activated when the attack hits.

# Devil Arms List

## Force Edge
Does 2/3 damage of Alastor

## Alastor

TBA-move list

## Ifrit

### Move List

TBA - move list

### Charging
Charged attacks(Punches, Kicks, Magma Drive) will gain 10% damage per frame of charge, up to 590%. Punches and Kicks(not Magma Drive) will automatically have a 10% multiplier applied, even if there is zero charge. If any of these attacks automatically releases, a 400% multiplier is applied.

For Meteor, it gains (slightly less than) 2% of damage per frame of charge. If it automatically releases, a 400% multipler is applied. The exact value of charge per frame is 1/51.

## Sparda

### Move List

Moves outside of M22

Moves in M22

### Stats

Sparda does twice as much damage as Alastor, effectively being the same damage as Alastor.

In Mission 22, Sparda's attack range becomes 4x when in Devil Trigger.

# Some Enemy Mechanics

## Sin Scissors, Sin Scythe, Death Scissors Death DT Refill

When these enemies die, the game keeps track of their height when they died. The height slowly decreases. When the height is lower than Dante's height, these enemies are considered fully dead. This is when events such as cutscenes trigger and the DT restoration after death.

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
| Hard | 390<sup>1</sup> |
| DMD! | 420 |
| DT Shadow | 450<sup>2</sup> |

1. 290 on PS2 versions outside of Japan.
2. 5450 on the 2018 HD versions.

## Frost

### Armor

Frosts have armor. This armor doubles their defense and they are resilient to stuns. Three attacks from the following while the Frost is in a neutral state will break their armor:

 - Alastor
    - Helm Breaker
    - Vortex
 - Ifrit
    - Any kick
    - Fully charged punch
  
### Arm

Frosts lose an arm at 500 HP. This stops the Frost from using some attacks (Check which ones). The needles from 8 directional needle attack is also halved. 

### Freeze

Frosts can freeze at 400 HP or less. If the freeze is not interrupted, it will restore 500 HP and its arm. 

## Nelo Angelo 

### Nelo Angelo 1 Teleportation

The arena fighting Nelo Angelo 1 has three levels. We begin at the bottom level, and throughout the fight, we go to the second and third level. 

Nelo Angelo 1 has 1500 HP. When his HP is under 1000, he will teleport to the second level if idle. If he is attacked while his HP is under 1000, he will automatically teleport. Similarly, when his HP is under 500, he will teleport to the third level if idle, and if he is attacked while his HP is under 500, he will automatically teleport. With some attacks that do enough damage, such as Holy Water, he can skip the second level and go from the first level to third level directly.

### Hit Counter

When Nelo Angelo gets hit, he has a counter that increases by 1 for each hit. When it exceeds a certain value(16 for Nelo 1 and Shadow Nelo, 8 for Nelo 2 and 3), Nelo Angelo can block in the middle of a combo. This counter resets to 0 when Nelo teleports or charges a meteor.

### Parry Stun Probabilities

For all Nelo Angelo encounters except the third fight, hitting his sword gives a 13/16 probability of being stunned. For the third Nelo Angelo fight, hitting his sword gives a 5/8 probability of being stunned.

## Griffon 

### Knockdown

When Griffon is hit by a Devil Arm attack, excluding Air Raid, Vortex, and Roundtrip, he has a counter that increases by 2 for each hit. When this value reaches a certain threshold, Griffon gets knocked down.

The threshold is 30 for Griffon 1 and 20 for Griffon 3. Griffon 2 cannot be knocked down.

1. The counter also increases by 1 sometimes if he is hit in the air by a firearm. I believe that it has to hit his head hitbox for it to count.

### Griffon 2 Clone Mechanics

The clone that Griffon 2 sends at you has 15 HP. The damage you do to the clone depends on the last hit you do to Griffon. If the last hit to Griffon is an uncharged handgun, then each attack to the clone does 1 damage. If the last hit to Griffon is any other firearm attack, including charged handgun, then each attack to the clone does 2 damage. If the last hit to Griffon is any other attack, then the each attack to the clone does 8 damage. Letting the clone hit Dante reduces its HP by 2, but it will not kill the clone. Letting the clone take Dante up does not affect the HP. Note that the clone like every other enemy dies at negative HP, not 0 HP. 

On the PS2 versions, the initial value for damage to the clone is set to 8 damage per hit. On all HD versions, the initial value is set to 1 damage per hit. 

### Griffon 3 Defense

Griffon 3 begins with 10000 HP. When he reaches 1500 HP, his defense doubles and he takes half damage from all attacks. Note that this phase change cannot occur while Griffon is knocked down.

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

* 900 on the PS2 North American, PS2 PAL, and PS2 Korean versions. A red bottom core causes the top core(regardless of color) to reset to 900.

Note that there is a bug with a red bottom core when refilling the core values.

#### Red Core Refill Bug

On all versions of the game except PS2 North American, PS2 PAL, and PS2 Korean, a red bottom core does not refill correctly. A red bottom core refills the **top** core to 900. This does not change the color of the top core, but it will cause it to break and turn to the next color in one hit. On the PS2 North American, PS2 PAL, and PS2 Korean versions, this bug is fixed, and a red bottom core does not affect the top core.

### Final Core

When Nightmare 3 initially gets his hp to -1 or lower, he reveals his final core. This core is always red in color, but it does not have the double defense the other cores have when they turn red. Nightmare restores 2000 HP. The attack that reveals the final core has its damage applied to the 2000 HP restored. This means if the last hit to Nightmare before the final core does 500 damage, then 500 damage is applied to the 2000 HP and Nightmare has 1500 HP remaining. The final core has 2000. When it reaches under 1000, it breaks. Before breaking, the core can only shoot lasers. After breaking, it will start to shoot out projectiles and slugs in the middle of shooting lasers.

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
- Stylish Meter, list all attacks and values
- Devil Arm list and attacks
- Bestiary
    - Damage Numbers
- Nightmare
  - Attack Cycle
  - Underworld
