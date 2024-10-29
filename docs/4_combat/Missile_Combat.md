 
![[70732.png]]
"Fast is fine, but accuracy is everything"
# Getting Started
- ==Each round is ~1 second
- Initiation: 3 Beats
- Async resolution
- Sequence of shots

! Dealing with Armor (since it is not an opposed roll)
! Cover -> Rd or Ad? (Ad but successes are 4 each which leads to most likely a blocking)

- Actions before shots are fired

# Sim Shot (Shoot-Out)
## 1st Shot State -> 3 Beats to Shot
> are effective rounds taken immediately before shots are fired

// how to establish entering the 3 beats in a more narrative context?

### State: Unsettled -> Ready -> Zone
- Everyone needs a moment, a beat ahead of taking a shot

| State     | Nerve Modifier<br>Rd | Sighted<br>bonus Bd | Aimed<br>bonus Bd |
| --------- | -------------------- | ------------------- | ----------------- |
| Unsettled | 5-Nerve Rd           | X                   | X                 |
| Ready     | 4-Nerve Rd           | +1Bd                | X                 |
| In Zone   | 3-Nerve Rd           | +1Bd                | +2Bd              |
> Traits: Courageous, Rash etc add +1 to Nerve in this context
> Drunk: adds +2 to Nerve (with 1-3Rd depending on scale)


Examples
- Rotten Thomas Nerve 4
	- 2Rd when unsettled
	- 0 when Ready
	- -2Rd when in the Zone
- Nervy Saul Nerve 3
	- 3Rd when unsettled
	- 1Rd when ready
	- -1Rd when in the Zone

### Aiming
1. Shoot!
	1. Can be taken from any state, no addition modifiers
2. Sighted shot
	1. Can be added from Ready or Zone, modifiers apply
	2. Target must be visible
3. Aimed shot
	1. Can only be taken from Zone, modifiers apply
	2. Target must be visible, or target point selected
		1. If target appears nearby, then change target Rd added to the aim bonus

### Actions per Beat
Asm = Action Speed modifier

- Action
- Take Triggering Direct Action, which can trigger a Response
- Option to trigger Response Actions 
- Or complete Beat

| Non-Triggering Actions | Duration | State                     | Modifiers/Outcome                           |
| ---------------------- | -------- | ------------------------- | ------------------------------------------- |
| Steel Nerves           | Beat     | Unsettled to Ready        |                                             |
| Get Eye In/Take breath | Beat     | From Ready to in Zone     |                                             |
| Intimidate/threaten    | Min 2    | to Ready                  | Comp Reputation/10 +/- 1Rd to opponent      |
| Persuade               | Min 2    | no change                 | TBC time taken too long<br>-> extend beats? |
| Aim prepared gun       | Beat     | From Ready/Zone to aiming | aimed state                                 |
| Hands up               | Beat     |                           |                                             |
|                        |          |                           |                                             |

| Perform Dramatic Action |     |
| ----------------------- | --- |

| Actions                                                                    | Duration       | Trigger<br>Option? | Action<br>Asm | Response<br>Asm | Shot <br>Modifier |
| -------------------------------------------------------------------------- | -------------- | ------------------ | ------------- | --------------- | ----------------- |
| <u>Shot Actions</u>                                                        |                |                    |               |                 |                   |
| Fire a drawn gun                                                           | Quick          | Yes                | +4            | 0               |                   |
| Quick Draw & fire                                                          | Quick          | Yes                | +2            | -2              | +3Rd              |
| Draw & fire                                                                | Full           | Yes                | 0             | -4              | +1Rd              |
| Draw/Ready, sight & fire                                                   | Full           | Yes                | -2            | -6              | 1Bd + 1Rd         |
| Sight and fire a drawn gun                                                 | Full           | Yes                | 2             | -2              | -1Rd              |
|                                                                            |                |                    |               |                 |                   |
| <u>Movement Actions</u>                                                    |                |                    |               |                 |                   |
| Lean from cover, fire drawn                                                | Quick movement | Yes                | -2            | -6              | +2Rd              |
| Dive for cover                                                             | Min 2 beats    | Yes                | +2            | -2              | 4Rd               |
| Stand-up from prone                                                        | Full           | Yes                | -2            | -6              | 2Rd               |
| Spin to face target                                                        | Full           |                    | 0             | -4              | 2Rd               |
| Move into full cover from partial                                          | Quick          |                    | -2            |                 |                   |
| Movement combined with action                                              | Full           |                    | -4            |                 |                   |
|                                                                            |                |                    |               |                 |                   |
| <u>Secondary Quick Actions</u>                                             |                |                    |               |                 |                   |
| Addition of a Quick action to a Beat action                                |                |                    | -2            |                 |                   |
| Drawn/ready, change to close target point & fire                           | Quick          |                    | 0             | -4              | +2Rd              |
| Drawn/ready, change to further target point & fire                         | Quick          |                    | -2            | -6              | +4Rd              |
| Snap 2nd shot (if wpn supports)<br>Only possible with another Quick Action | Quick          |                    | -4            |                 | +2Rd              |
|                                                                            |                |                    |               |                 |                   |
| Draw & hold/sight                                                          | Full           | Yes                | 0             | -2              |                   |

// note: Response actions are 4Asm slower

==TBD -> Each Beat can include Movement, a Full action and additional Quick action(s)

2nd shot Asm = Prior action Asm - modifier


#### Response Action
> If an opponent takes a Triggering Action you can choose a Response Action instead.
- Although it is a response, the First Shot calculation is made to determine shot order
- It is possible for a Response Action to occur before the Triggering Action in 'extreme' circumstances
> If no response action chosen, complete the action outcome

## First Shot
1. Is it clear who gets 1st shot?
	1. Declare 1-3 beats in sequence, simultaneously revealing
2. Declare!
	1. If both non-triggering, resolve and move to next Beat
	2. If both are triggering actions, resolve into combat
	3. If one is triggering action, other party/parties have option to choose Response Action, resolve into combat
3. Resolve in Action Speed Order
	1. Add up Asm
		- Base 'Action' speed
		- -1 for each Medium or Serious Flesh wound
		- + Action speed modifier (Asm)
		- + Weapon modifier
	2. Highest goes 1st, in descending order
	3. Ties happen simultaneously


## Resolving a Shot
### Modifiers
> Cumulative/each situation contributes Rd

#### 1st Shot State
#### Action (triggering or response)
- A modifier applied as a result of the establishing action
#### Situation Modifiers
##### Range, Target & Conditions

|                        Situation                        |    -2Rd     |     0      |          2 Rd           |      4 Rd       |        6 Rd         |   8 Rd     |
| :-----------------------------------------------------: | :---------: | :--------: | :---------------------: | :-------------: | :-----------------: | :--------: |
|                          Range                          | Point Blank |   Close    |          Short          |       Mid       |        Long         |    Far     |
| Visibility<br>≥ mid range<br>reduce Rd each step closer |             |   Clear    |       Mist/Glare        |    Rain/Dusk    |    Fog/Near Dark    |    Dark    |
|               Movement<br>Shooter/Target                |             | Stationary |     Walk<br>Moving      |   Jog<br>Dive   | Dash<br>Zig Zagging | Run/Gallop |
|                     Size of Target                      |   ≥Large    |   Torso    |      Small Target       |      Head       |     Bull's Eye      |            |
|                 Wind <br> Physical Wpn                  |             |   Light    |         Modest          |     Strong      |        Storm        |  Extreme   |
|                  Wind <br> Powered Wpn                  |             |            | Strong<br>(≥ mid range) |      Storm      |       Extreme       |            |
|                     Changing Target                     |             |            |         Nearby          | Far<br>or Aimed |                     |            |

##### Under fire
> been shot at in the <u>last</u> round

- A shot which hits or is net 0 counts as direct fire
- A shot which misses at a net -1 or -2 or more counts as indirect fire
- A shot which misses at -3 or more, provides no suppression effect

| Situation                    | Modifier                |
| ---------------------------- | ----------------------- |
| Each wound <u>this</u> round | WOUND Rd                |
| Under direct fire            | (6 - Nerve) Rd          |
| Under indirect fire          | (4 - Nerve) Rd<br>Max 0 |
| KO'ed this action            | 2X Wound Rd             |
> note: for subsequent rounds, the Rd of the wound adds in as a condition. But doesn't count in the turn it happens.

#### Semi & Auto Fire


### Resolving a shot

Build a dice pool from Base & Resistance
1. **Base pool** = Attribute + Skill or background (capped by the attribute)
2. **Resistance pool** = persistent penalties + difficulty of the challenge + situational modifiers
Consider any Boost results

### **Results of Ranged Combat**

The results of a ranged attack are resolved just like melee;
- ≥1 net successes = Success
- Zero or less success = Miss

Damage is calculated as
- number of successes
- plus weapon modifier dependent on the widest width 
- (... old notes says... of the lowest, widest number - not sure what this adds, which is used for hit location to avoid hits being in the head)


## Boosts and Reactions pattern requirements

- 6's are used to succeed and can't be re-used for additional damage or reactions, with the exception of the Lucky 6's which trade Luck for successes

| Missile Weapon Type | Pattern up to max AGL |
| :------------------ | :-------------------: |
| V. Heavy            |        'quad+'        |
| Heavy               |   'trips+' at AGL-1   |
| Medium/Light        |        'trip+'        |

### Missile Boosts

| Name            | Condition                                                             | Benefit                                                                                 |
| --------------- | --------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **Lucky Sixes** | If ≥3 '6's rolled<br>(either party)<br>No additional pattern required | 1 + 1 success per LUCK point spent<br>(e.g. spending a 2pt LUCK 'wound' = +3 successes) |
| **Target**      | If successful                                                         | Adjust hit location by 1(+)<br>(logical not numbers)                                    |
| Solid Shot      | if successful                                                         | +2(+) Knock-down                                                                        |

### Additional Wound Points

[[Boosts]]

Triple <= Power

| Name                    | Condition | Outcome                       |
| ----------------------- | --------- | ----------------------------- |
| Improv Wpn/Power 1      |           | plus 0(+) wound pt, max +1 pt |
| Light Wpn/Power 2       |           | plus 1 wound pt               |
| Mid Wpn/Power 3         |           | plus 2 wound pts              |
| Heavy/Power 4           |           | plus 2(+) wound pts           |
| Very Heavy/Power 5      |           | plus 3(+) wound pts           |
| Extremely Heavy/Power 6 |           | plus 4(+) wound pts           |

## Consequences

### Hit

#### Location

#### Defense/Armor/Cover

- Hit Locations covered
- Strength of cover
	- Size of cover represented in AD 
	- Strength of cover represented in AD. 
	- Size-based cover has infinite block, while a strength-based cover has absorption. 
- Visibility

### Knock-down

| Range | Outcome                         | Type      | Outcome       |
| :---- | :------------------------------ | :-------- | ------------- |
| PB    | +2 Knock-down if gut/chest/head | V. Heavy  | +2 Kd         |
| Close | +1 Knock-down if gut/chest/head | Heavy     | +1 Kd         |
| Mid   | -1 Knock-down                   | Medium    | 0             |
| Long  | -2 Knock-down                   | Light/Imp | -1 Knock-down |
| Far   | -3 Knock-down                   |           |               |

### Reactions

### Suppression

## Subsequence Shots - TBD

- Aim is lost after 1st round unless held with a Reaction
- Actions are taken in the same order as the 1st shot is resolved

### Re-Loading
- Type of weapon has significant impact
- ~1 round for 2 shells, a magazine
---

### Missile Common Reactions
Triple <= AGL

| Name                        | Condition          | Benefit                                                 |
| --------------------------- | ------------------ | ------------------------------------------------------- |
| Hold Aim                    | If aiming          | Improve into next shot -1(+)Rd<br>(on top of aim bonus) |
| Free sighting               |                    | +1(+)Bd on next shot                                    |
| Next shot/action            |                    | Move up step on the action order                        |
| Move/Step                   |                    | Make a short move                                       |
| Use Cover                   | If cover available | 2Ad while in cover                                      |
| Duck into Cover             |                    | 4Ad while in cover<br>2Rd on next (immediate) action    |
| Recover footing             |                    | 1 step of Knock-down                                    |
| Quick Action: Snap shot     |                    | -0(+)Rd                                                 |
| Quick action                |                    |                                                         |
| Punch/Strike<br>Pistol whip | If at Up Close     | Inflict 1pt wound<br>+ if next shot is quick, +2Rd      |
| Change target               |                    | free quick action, (no modifier)                        |
| Calm Nerves                 |                    | +1 Nerve next shot                                      |

### Trained/Expert Reactions
Triple <= AGL

| Name           | Condition                        | Benefit                     |
| -------------- | -------------------------------- | --------------------------- |
| Improve Aim    | If aiming                        | -2Rd on next shot           |
| Suppression    |                                  | TBD                         |
| Trick shot     | If expert & appropriate location | Hit specific feature        |
| Disarm         | If expert & target location arm  | Hit a weapon or weapon hand |
| Holster weapon |                                  |                             |
| Dive & roll    |                                  |                             |
| Switch Target  |                                  | no penalty                  |

- If quick fire, semi or full auto add **Suppression fire**
	- Lay down additional fire on a target (or close targets)
	- Being under fire adds 2Rd
	- Being under heavy fire adds 4Rd


### Damage
- Fill the damage spaces based on the wound received
- If there isn't a slot, move up to the higher level
	- If a 1pt wound is upgraded, mark it as a B bruised would which can be recovered overnight
- <u>Any 2pt or higher</u> wound is bleeding, and need staunching or treated in some way
- Depending on location and impact/weapon, option to take a break rather than bleeding. (break doesn't run on, but the healing time is much longer)
- 