---
title: D&D 5E Home Ship Rules
author: [Matthew Terrance Carlos Boyea]
date: "2024-03"
lang: en
subject: ttrpg
---
# Ship Rules
## Ship Stats
### Size
A ship’s size category is determined by its length or width, whichever is longer. For example, a ship that is 20ft long and 10ft wide would defer to 20ft and would be of Gargantuan size.
### Space
A ship occupies the spaces specified by its length and width. For example, a ship that is 20ft long and 10ft wide would occupy a 20ft by 10ft rectangle of space.

A ship can’t move into a space that is too small to accommodate it. If it tries to do so, [it crashes](#crashing).
### Capacity
A ship’s stat block indicates how many creatures and how much cargo it can carry.

A ship could cary more people or cargo, but crew would have disadvantage for skill checks at the DM's discretion.
### Ability Scores
Strength represents size and weight. Dexterity represents ease of handling. Constitution representes the durability and quality of construction.
### Wind Rating
A ship will have a Wind Rating, which specifies the magnitude of [wind](#wind) that the vessel can safely travle in.
## Ship Components
### Type
#### Hull
A ship’s hull is its basic frame, on which the other components are mounted.

If it drops to 0 HP, the ship is [wrecked](#wrecking).
#### Control
A control component may be used to steer and/or move a ship.
See [Controls](#controls).
#### Weapon
A weapon component may be used to inflict damage.
See [Weapons](#weapons).
### Armor Class
Each component has its own Armor Class (AC), meant to reflect its size, the materials used to construct it, and any defensive plating or armor used to augment its toughness.
### Hit Points (HP)
A component becomes unusable when it drops to 0 HP.
### Damage Threshold
A component has immunity to all damage unless it takes an amount of damage equal to or greater than its damage threshold.
### Crew
A component must be manned by one or more crew to perform an action.
### Ability Check
A component may require an ability check to determine the outcome of its usage.

If an ability check is to be performed by more than 1 crew member, roll once and add the average of the crew's ability scores together, rounding up.
## Ship Combat
### Initiative
Each ship rolls for initiative at the start of combat, adding its Dexterity modifier.

All creatures on the ship take their turn in initiative order during the ship's turn.
### Water
Water has direction and magnitude measured in ft per round.

A ship moves with the water at the end of its turn, unless it is anchored.
### Wind
Wind has direction and magnitude measured in ft per round, referred to as wind units (wu).

|Wind Speed|Wind Units (wu)|
|:---|:---|
|calm|0ft|
|light|1/2ft|
|moderate|1ft|
|strong|2ft|
|severe|3ft|
|storm|6ft|
|hurricane|8ft|
Table: Wind Magnitude

A ship's [controls](#controls) and [weapons](#weapons) may be affected by the wind, as specified by each component.
### Direction
Each ship faces a direction. A ship's [controls](#controls) and [weapons](#weapons) may be affected by its direction, as specified by each component.
### Controls
Any creature onboard the ship and within range of a control may use their action to crew the control.

At the end of the ship's turn, the ship adds each effect of its controls in the order listed by the statblock.

The creatures that crewed each control may specify where within the possible range the ship travels to.
#### Speed
Speed specifies the range within which a creature may move the ship in a round if crewed. For example, control: oars may move the ship within a 20ft cone in the direction that the ship is facing.
#### Move
Move specifies the distance a ship will move if conditions are met. For example, a control: sails may move the ship in a 20ft line in the direction that the ship is facing, if the sails are open.
#### Turn
Turn specifies the range within a control may rotate the ship in a round.
### Weapons
Any creature onboard the ship and within range of a weapon may use their action to interact with it, as specified by the component text.
### Crashing
If a ship moves into the space occupied by a creature, vehicle, or object, it may crash at the DM's discretion. The ship will not crash if the object is two sizes smaller than it.

When a ship crashes, it must make a DC 10 Constitution saving throw. If it fails, it must take damage to its hull or ram based on the size of the crash object as shown on the Crash Damage table.

If the crash object is equal or bigger size, the ship stops moving.

If the crash object is a lesser size, it moves to the nearest unoccupied space that is not in the ship's path, or is destroyed.

The crash object must make a Dexterity saving throw DC 10 + the ship's Strength modifier, taking damage based on the ship's size (as shown on the Crash Damage table) on a failed save, or half as much damage on a successful one.

|Size|Bludgeoning Damage|
|:---|:---|
|tiny|none|
|small|1d6|
|medium|1d10|
|large|4d10|
|huge|8d10|
|gargantuan|16d10|
Table: Crash Damage
### Wrecking
If a ship's hull drops to 0 HP, the ship is wrecked.

When a ship is wrecked, it will begin sinking based on the size of the ship as shown on the Sink Time table.

According to the DM's discretion, a ship may be saved before it sinks completely, returning it to 1 HP.

If a ship completely sinks, it becomes a [shipwreck](#shipwreck).

|Size|Sink Time|
|:---|:---|
|tiny|instantaneous|
|small|instantaneous|
|medium|1 round|
|large|1+CON rounds|
|huge|2+CON rounds|
|gargantuan|3+CON rounds|
Table: Sink Time
## Ship Travel
### Water
### Wind
### Controls
### Activities
#### Crew
#### Navigation
#### Spotting
#### Stealth
#### Repair
#### Cartography
#### Fishing
#### Downtime
### Hazards
#### Water Depth
#### Water Current
#### Sandbar
#### Kelp Forest
#### Coral Reef
#### Storm
#### Whirlpool
#### Shipwreck
#### Blue Hole
#### Kraken's Grave
#### Lure Lights

# Ship Statblocks

## Rowboat
*Large vehicle (10ft by 5ft)*
**Creature Capacity** 4
**Cargo Capacity** 0.25ton (500lb)
**Wind Rating** moderate

| STR | DEX | CON |
|:---:|:---:|:---:|
|11(+0)|8(-1)|11(+0)|

**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious

### Hull: Wood
**Armor Class** 11
**Hit Points** 50

### Control: Oars
**Armor Class** 13
**Hit Points** 20; crews one less per 10 damage taken
#### Crew 1: Row
**Speed** 25ft line
**Turn** 60deg
**Travel Pace** 2.5mph
#### Crew 2: Row
**Speed** 35ft line
**Turn** 120deg
**Travel Pace** 3.5mph

## Canoe
*Huge vehicle (15ft by 5ft)*
**Creature Capcity** 2
**Cargo Capacity** 0.2ton (400lb)
**Wind Rating** moderate

| STR | DEX | CON |
|:---:|:---:|:---:|
|8(-1)|12(+1)|12(+1)|

**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious

### Hull: Wood
**Armor Class** 13
**Hit Points** 40

### Control: Oars
**Armor Class** 14
**Hit Points** 20; crews one less per 10 damage taken
#### Crew 1: Row
**Speed** 20ft cone
**Turn** 180deg
**Travel Pace** 2mph
#### Crew 2: Row
**Speed** 30ft cone
**Turn** 180deg
**Travel Pace** 3mph

## Keelboat (Cargo Boat)
*Gargantuan vehicle (50ft by 15ft)*
**Creature Capacity** 30
**Cargo Capacity** 12 tons
**Wind Rating** strong

| STR | DEX | CON |
|:---:|:---:|:---:|
|15(+2)|7(-2)|13(+1)|

**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious

### Hull: Wood
**Armor Class** 15
**Hit Points** 100 (damage threshold 10)

### Control: Sail
**Armor Class** 12
**Hit Points**100; -5wu moved per 20 damage taken
#### Crew 1: Open Sail
While open, the sail has:
**Move** 15wu line; 25wu line sailing downwind; 0wu line sailing upwind
**Travel Pace** 1mph * wu
#### Crew 1: Close Sail
While closed, the sail has:
**Armor Class** 14

### Control: Oars
**Armor Class** 15
**Hit Points** 80; crews one less per 20 damage taken
#### Crew 1: Row
**Speed** 30ft cone
**Travel Pace** 3mph
#### Crew 2: Row
**Speed** 35ft cone
**Turn** 30deg
**Travel Pace** 3.5mph
#### Crew 4: Row
**Speed** 40ft cone
**Turn** 60deg
**Travel Pace** 4mph

### Control: Helm
#### Crew 1: Turn
**Armor Class** 12
**Hit Points** 50
**Turn** 60deg

### Weapon: Ballista
**Armor Class** 15
**Hit Points** 50
*Ranged Weapon Attack:* +6 to hit, range 120/480ft, one target.
*Hit:* 16(3d10) piercing damage.

## Longship (Small War Boat)
*Gargantuan vehicle (70ft by 20ft)*
**Creature Capacity** 60
**Cargo Capacity** 10 tons
**Wind Rating** severe
| STR | DEX | CON |
|:---:|:---:|:---:|
|17(+3)|6(-2)|16(+3)|
**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious
### Hull: Wood
### Control: Sail
### Control: Oars
### Control: Helm
### Weapon: Ballista (2)
### Weapon: Mangonel
## Galley (Large War Boat)
*Gargantuan vehicle (130ft by 20ft)*
**Creature Capacity** 80
**Cargo Capacity** 200 tons
**Wind Rating** severe
| STR | DEX | CON |
|:---:|:---:|:---:|
|19(+4)|4(-3)|19(+4)|
**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious
### Hull: Wood
### Control: Sails
### Control: Oars
### Control: Helm
### Weapon: Ram
### Weapon: Ballista (4)
### Weapon: Mangonel (2)
## Sloop (Sailboat)
*Gargantuan vehicle (50ft by 15ft)*
**Creature Capacity** 16
**Cargo Capacity** 8 tons
**Wind Rating** severe
| STR | DEX | CON |
|:---:|:---:|:---:|
|14(+2)|12(+1)|13(+1)|
**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious
### Hull: Wood
### Control: Sails
### Control: Helm
### Weapon: Ballista
### Weapon: Cannon (2)
## Schooner (Sailing Ship)
*Gargantuan vehicle (120ft by 20ft)*
**Creature Capacity** 80
**Cargo Capacity** 150 tons
**Wind Rating** storm
| STR | DEX | CON |
|:---:|:---:|:---:|
|20(+5)|7(-2)|17(+3)|
**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious
## Brigantine (War Ship)
*Gargantuan vehicle (140ft by 20ft)*
**Creature Capacity** 120
**Cargo Capacity** 200 tons
**Wind Rating** storm
| STR | DEX | CON |
|:---:|:---:|:---:|
|23(+6)|5(-3)|20(+5)|
**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious
## Galleon (Cargo Ship)
*Gargantuan vehicle (160ft by 25ft)*
**Creature Capacity** 160
**Cargo Capacity** 400 tons
**Wind Rating** storm
| STR | DEX | CON |
|:---:|:---:|:---:|
|26(+8)|3(-4)|22(+6)|
**Damage Immunities** poison, psychic
**Condition Immunities** blinded, charmed, deafened, exhaustion, frightened, incapacitated, paralyzed, petrified, poisoned, prone, stunned, unconscious


