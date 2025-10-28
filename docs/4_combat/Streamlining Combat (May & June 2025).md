
# Underlying Concepts & Terms
- Melee is an Opposed Roll
- Each combatant chooses their <u>Approach</u> to the engagement
> <u>Approach</u> = a tactic, style or attitude the combatant uses this round 
- An approach has a guaranteed benefit, and a variable benefit depending on the width of the dice pool roll. Rolling a triple or more of a number which is less that the target attribute. e.g. rolling triple 2's with an Agility of 3.
> <u>Width</u> = the count of the same number result in the dice pool roll e.g. three of the same number equals a triple of that number.
> <u>Lowest, Widest</u> = the lower of any tied widest results. e.g. triple of 2's and 1's would take the 1's
- An approach can modify the number of successes or generate Advantages or other modifiers.
> <u>Advantages</u> = opportunity to modify the outcome, apply special moves, actions or reactions.
- <u>Net Successes</u> determine the winner, with momentum resolving a tie in the modified roll result
- Net Successes also determine the basic wound points inflicted. The weight/type of the weapon's grip converts successes into wound points. e.g. a knife is a light weapon, where 1, 2 or 3 successes create a 1pt wound, but 4 successes causes a 2pt wound.
> <u>Wound points</u> = the damage caused
> <u>Grip</u> = some weapons can be held and used in different ways. A Grip determines the effective reach and weight of the weapon as well as the special effects which it can trigger. e.g. a cutlass could be used 'at guard' grip for 'Melee' distance and as a 'Heavy' weapon, or at a 'pommel' grip for use 'Up Close', and as a 'Light' weight blow.

> <u>Momentum</u> -> M0 = win draws, M1 means +2Bd & 1Rd to pool, M2 +4Bd & 2Rd to pool
> <u>Stagger</u>
> <u>Actions</u> -> max number of Actions per round = AGL (main roll is 1 action, all other Advantage labeled as actions or Parry's count as actions) Option to take an additional 1 action but adds +1 stagger to self


Missile is Unopposed, resolved in Speed sequence
- Range, target size and movement plus conditions represent the Rd 'effective opposition'

Physical thrown weapons have a min PHY requirement, damage is dropped 1 level for PHY which is less than needed



# Sequence
1. Approach
2. Roll & Outcome
3. Advantages
# The Approach to Combat

1. Narrative situation determines starting position
	1. Distance
	2. Surprise
	3. Establishing who has **Momentum**, if narrative doesn't determine, then calculate combined speed to determine momentum order
		1. Highest speed wins momentum
		2. Ties to Actors
2. **Recover** 1 stagger step per round as free action
3. Each opponent declares their **Approach** for the round
	1. Declare in speed order or the order which makes sense for the narrative
	2. Establishing who has **Momentum**, if narrative doesn't determine
		1. Speed + Approach modifier
		2. Highest speed wins momentum
		3. Ties to Actors
3. **Movement** before the resolution roll
	1. In speed order, any combatant that has a Step can use it to change the range
	2. This continues in sequence if more moves available.
4. **Resolve in reverse momentum order**
	1. Declare grip
	2. Check **Widest result** **≤ Attribute** to determines variable outcome
		1. A single or pair will fail to achieve the intent of the approach
		2. A triple will achieve the intent of the approach
		3. A quad or higher will achieve a strong result
		4. 6's always count as successes
	3. Keep or Use **Advantages**
		1. Earned from success of roll vs chosen Approach
		2. Purchased with Drama pts
5. **Create the pools**
	1. Choose skill used to oppose the opponent
		1. Strike -> weapon strike
		2. Brawl -> unarmed strike
		3. Athletics -> evasion
		4. Strength & Stamina -> grapple
		5. Ranged -> shoot
	2. Calculate Bd & Rd
		1. Inc Situational modifiers
		2. Inc modifiers from the Weapon & Grip choice vs Distance/Positioning
		3. Inc Stagger modifiers
		4. Carry any negative Rd into positive Bd (e.g. -1Rd = +1Bd)

6. **Calculate the Outcome**

`Table of Approaches`

[[Approaches (Aug 2025)]]

TBD where movement is blocked, e.g. already up close, but someone moves away and you have a pre-move step. Should not lose the step, keep asking until everyone has nothing remaining or both skip.

All momentum changes are applied immediately
Opponent causes no specials -> crush/cut etc. Evade effectively puts the opponents at a reach which doesn't allow specials...
When a 'free' optional action is taken it still counts towards the Action limit for a turn

>> add a line to explain the goal and risk/reward for each approach

`Positioning/Range Modifier table`

| <br>At chosen Grip<br>Weapon Reach | Up Close | Melee Distance | At Distance | One Step <br>Beyond | Beyond<br>Reach |
| :--------------------------------- | :------: | :------------: | :---------: | :-----------------: | :-------------: |
| Unarmed                            |    --    |    **4Rd**     |   **6Rd**   |         n/a         |       n/a       |
| Up Close                           |    --    |     *1Rd*      |   **4Rd**   |         n/a         |       n/a       |
| Melee                              |  *2Rd*   |       --       |    *2Rd*    |       **6Rd**       |       n/a       |
| Distanced                          | **4Rd**  |     *2Rd*      |     n/a     |       **2Rd**       |       n/a       |

# Outcome
- Calculate Net Successes
	- Positive results from Bd pool
	- Minus negative results from Rd pool
	- Plus or minus modifiers from the result of their Approach
- Compare
	- Highest wins
	- Ties resolved by Momentum, resolving as 1 pt success
		- Note: A Steal Momentum outcome happens immediately, and will precede this resolution.
	- If loser has <0 net successes
		- <0 successes gives opponent +1 Advantage
- Apply most of the results of the Approach immediately, 'saving' the Advantages to be selected in momentum order

> Advantages can now be applied ... TBD resolving in momentum order? or is it logical as the sequence continues
## Winner
1. Hit location is determined by the widest, lowest number in the winner's Bd pool
	1. Note: Target Location Advantage can shift the hit location.
	2. Armor/cover/blockage is determined by coverage on any given location
2. Calculate wound points inflicted, calculate the steps in this order - ==IN TESTING
	1. Base damage = stagger value
	2. Weapon damage
		1. Unarmed = 0
		2. Limited = 0
		3. Light = 1
		4. Mid = 2
		5. Heavy = 3
		6. V Heavy = 4
		7. Extreme = 5
	3. Plus Special Impacts damage bonus
		1. ≥Pair of 5's or 6's can trigger special weapon damage when a weapon is used at its effective reach
	4. Apply Hit Location modifiers
3. Reduce by any Block pts
	1. Roll Ad
		1. Note: Parry or Defend Advantages can modify the Ad pool
	2. Add any modifiers from Approach outcome
	3. Reduce Wound inflicted by total Block
4. Net result is the number of wound points inflicted

==EDITED OUT Net Successes TBC not required, as the 5/6 successes will generate more outcomes in the Special category. A mix of 5/6 will generate less outcome than a wider 5 or 6, but that might be ok.
	1. Weapon 'weight' or 'lethality' translates net successes into wounds
		1. Unarmed 1-4 successes = 1(+)-3 or (successes-3), min of 1
		2. Limited 1-3 successes = 1(+)-2 or (successes-2), min of 1
		3. Light 1-2 successes = 1(+)-1 or (successes-1), min of 1
		4. Medium 1:1 success = 1(+) 
		5. High/Heavy = 2(+)
		6. Very Heavy = 3(+)
		7. Extreme = 4(+) 

#### Hit Location Table
[[Damage Inflicted (Oct 2025)]]

#### Weapon Special Impacts

>hit location & effect = narrative opportunity
- **Triggered with a pair(+) of either 5's or 6's**
- Only when using a weapon at it's specified grip reach
- And when a wound is inflicted before the application of the special TBC
- Generate's **persistent** Rd associated with wounds

[[Damage Inflicted (Oct 2025)]]


> TBD should a weapon effect be applied even if you lose the opposed roll? This will make combat more messy & maybe quicker

If wound damage -> breaks, bruises etc equal Flesh Bd = KO
#### Stagger Ladder
> Staggered is a progression, from Off-balance to KO'ed

[[Ladders (Aug 2025)]]

- Outcomes can include +Stagger 
- Staggers are cumulative over the course of round
	- Note: for an opponent that are large/strong/agile
		- Stagger Bonus -> they can deliver 'double' stagger when an outcome adds +Stagger
		- Stagger Defense -> they require 'double' to stagger them
- Limited/Single/Double
	- Limited - no effect on someone who requires a Double
	- Double - requires additional +staggers to move to Staggered or Reeling (once at Reeling, effectively as Single)

#### Impact of Different Size Combatants

| To Stagger  | vs Stagger  |            |            |            |            |
| ----------- | :---------: | :--------: | :--------: | :--------: | :--------: |
|             | **Limited** | **Single** | **Strong** | **Double** | **Triple** |
| **Limited** |   No mod    |     -1     |     -2     |     -3     |     -4     |
| **Single**  |     +1      |   No mod   |     -1     |     -2     |     -3     |
| **Strong**  |     +2      |     +1     |   No mod   |     -1     |     -2     |
| **Double**  |     +3      |     +2     |     +1     |   No mod   |     -1     |
| **Triple**  |     +4      |     +3     |     +2     |     +1     |   No mod   |
- Since staggers are cumulative across the round, a negative can be overcome with multiple stagger outcomes

### Recovery
- Recovering from Stagger
- You can[[trade momentum for recovering from stagger
- Penalty for each stage

# Advantages
- Gained as a result of the width of the main roll
- Modified by the Approach to combat
- Or purchased 1:1 with drama/luck points
- (Ranged only) Can reduce successes by 1 for a Target Location advantage, multiple possible
- Actors get +1 Advantage per round

[[Advantages (Aug 2025)]]


### Fumbled Failures

If <u>negative two (-2) net successes</u> look at the Lowest, Widest pattern for the result

| Height |                                          |       Width        |                    |                  |
| :----: | ---------------------------------------- | :----------------: | :----------------: | :--------------: |
|        |                                          |       ≥Quad        |        Trip        |     ≤ Double     |
|   6    | **No Effect**                            |        n/a         |        n/a         |                  |
|   5    | **Disadvantaged**<br>Entangled           |        +3Rd        |        +2Rd        |       +1Rd       |
|   4    | **Slip/Trip**                            |  +3 stagger steps  |  +2 stagger step   | +1 stagger steps |
|   3    | **Weapon/Shield**                        | Throw 2 moves away |    Drop at feet    | Nearly drop +2Rd |
|   2    | **Strike friend<br>(if no friend,self)** | 2pt wound no armor | 1pt wound no armor |    1pt wound     |
|   1    | **Strike self**                          | 2pt wound no armor | 1pt wound no armor |    1pt wound     |
|        |                                          |                    |                    |                  |

# Grapple

- Held or Unheld is not a Grapple action, it is an Advantage or state
Once held or holding... Grapple Approach can be chosen


- ==What opposes what, doesn't matter... but results determine which action wins... TBD
- Symmetric test
	- TBC is an opposed roll with net successes being used as grapple points = an opposed test unlike melee combat TBC
- Asymmetric tests
	- A losing S&S doesn't contribute successes, but advantages can be applied to gain successes
	- and the other attack can also be successful? TBC
- Allows for concentration on struggle or 2nd actions
- Actions consider stagger differences
- Grapple actions include Strength & Stamina successes
- Break actions include Wound points received

Held opponents can't use any grip apart from an Up Close (which means no Melee grips with the 2Rd mods) need to use a grip intended for Up Close

> Grapple pts
- Grappling 'tug of war'
	- An advantage or Grapple approach is needed to attempt to change the situation
	- Grapple points are cumulative over the round, either to the end of the round or the uncontested point of change 
	- The net points needed to achieve a change are modified by the Stagger difference
		- 1 net for single vs limited ()
		- 0 net for single vs single
		- 2 net for single vs strong
		- or 2 for strong vs double
		- 3 net successes for single vs double
	- A change can be
		- To break the hold
		- To move up the Grapple Ladder
		- To execute a Grapple Outcome
	- 


1. On a successful Grapple, keep a track of the location as this is the starting point of the hold
#### Grapple Ladder
Each combatant can be on the ladder at the same time - both parties can be held and attempting to restrain the other.

1. **Un-held**
	1. No effect
2. **Held**
	1. Partial hold
	2. Attacking a held characters is -1Rd
	3. Both parties can be Held
	4. Holding requires 1+ free hand
	5. Takes an Advantage (Grab & Hold)
	6. Limits some movement & approaches
	7. When someone is 1st held, their stagger is reduced by 1 step if they are on their feet (stagger ≤3)
	8. Can be broken with enough Grapple points to overcome stagger difference
3. **Grappled**
	1. Firmly held with a 4Rd disadvantage
	2. Holder also has a 4Rd disadvantage on actions other than Grapple
	3. Requires 2 hands (or a specific situation narrative)
	4. Grappled can be broken with enough Grapple points to overcome the stagger difference
	5. A Grappled state can be held until either released or broken
	6. The target location of the grapple can be changed while being held
		1. e.g. moving from Arms to Head in preparation for Strangle
4. **From Grappled to an Outcome**
	1. Option to **Throw**
		1. Successful outcome puts the target to their Knees L3 Stagger, or Floored L4 Stagger with the use of 1 additional grapple point
			1. The grappler attempts to throw their opponent, who directly resists with Strength & Stamina = opposed roll
				1. Grappler rolls 2 successes, with a minor on their approach = +1 grapple from Approach + 1 advantage
				2. Opponent rolls 1 success, with a failure on their approach = 1 success + -1 grapple and no advantages
				3. Net outcome = Grappler has net 1 +1 from their approach, +1 from the opponents failed approach = net 3
				4. As similar sized opponents, this is enough to throw the opponent (1 pt) to the floor (1pt) holding on to the floored opponent (1pt)
		2. Option to keep holding opponent for an additional grapple point, they are held and not grappled.
	2. Option to **Overpower**
		1. Held with a 4Rd disadvantage
		2. And at a minimum Knocked-Back effect (a further 2Rd)
		3. If also Actor who is overpowered is also holding their opponent, reduce by current grapple status on opponent by 1 step (this can mean the hold is released)
	3. Option to **Strangle**
		1. Max Flesh X2 pts needed to be applied
		2. If Head location locked
		3. Knocked-out
		4. Option to complete the job...


. Pin arms/grab arm/weapon?
. Should breaking a grapple break hold? or an additional -1G needed?
. When grappled, stagger mods cap at 4Rd for Grapple

- an additional 1G break = release hold
- Effects of overpower last beyond any release
-

|                                              |
| -------------------------------------------- |
| Grapple causes 'grapple' damage              |
| At stagger + stagger difference + specials   |
| If Grapple ≥4 held -> grappled               |
| If Grapple ≥8 held -> Outcome                |
| Resistance can push the value back down      |
| Advantages can push up                       |
| Damage caused changes Grapple by damage done |



# Misc Question

### Damage & Armor
==... Is damage generated from successes + weapon -> rolled vs armor? (Streets of Peril?)


Grapple vs Weapon/Ranged
Melee vs Ranged

Multiple Combatants
- You can save/use Advantages from one combat in the other
	- e.g. triggering a Parry vs an unopposed 2nd opponent

TBD - how to soften the impact of unarmed vs limited Flesh points?

## Ramp
White dice 5/6 -> Red dice 4/5/6 -> Black dice 4/5/6++
- Capped at 6 dice
- Trained +2
- Expert +2
- Elite +2

## Momentum

Win a tie by momentum -> equals a min 1pt net result

Momentum adds current momentum to successes, but capped by skill/training
- Untrained = max 1
- Trained = max 2
- Expert = max 3



Should there be a reach modifier for the length of weapon even at the effective distances -> maybe modifying momentum

How to reflect the targeted capabilities and weakness of weapons
- Dane axe vs soft/horses but not good vs flex/hard -> other than through specials?


# Actor Survival
- Use Luck to save from death
	- 3Rd Cheated Death - 3 month recovery
	- Note: knock on into the Skills... 

# Armor updated vs 5's & 6's


# Missile Combat

- Speed
	- Opposed or unopposed
- Actions
- Aiming Approach
- Advantages
Nerve
- Under fire

0(+)... 0,1,2,3
1(+)... 1,2,3,4
0(++)... 0,2,4,6
1(++)...1,3,5,7



---
Variable Outcome
Advantages

Optional Before roll Steps resolved before rolls, taken in sequence

Consider flattening the connection between the Att and Skill for physical skills, but add bonus to damage or outcome if higher stat.
vs Mental and Social which benefit from the skill bonus but no subsequent upside.
e.g. Strike is capped at 3 from Phy attribute, but Phy 4/5 add +1 wound point, and 6+ adds +2 wound ?

BUT with Stagger added back into damage calculation this might double count...


## From script writing

- Consider adding a success for each sequential run of momentum. Then you start to look for reasons and ways to change the impact of momentum. 
- Gives fresh opportunity for advantages to redress the balance. 
- More about:
	- Stealing momentum
	- Countering momentum
	- Digging deep
	- Finding fresh hope
	- Being encouraged
	- Helping each other

More recovery in the approaches. 

---


| Combat Ranges |          |       |           |                 |           |       |     |      |     |
| ------------- | :------: | :---: | :-------: | :-------------: | :-------: | :---: | :-: | :--: | :-: |
| **Ranges**    |    PB    |  PB   |    PB     |       PB        |   Close   | Short | Mid | Long | Far |
| **Reach**     | Up Close | Melee | Distanced | One Step Beyond | Beyond... |       |     |      |     |
