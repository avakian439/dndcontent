### **Encounter 1

Having breached the outer perimeter of the Gene Vault, the fireteam reaches the facility's first line of internal defense: a Cognitive Synchronization Chamber. Four towering **Noetic Suppression Towers** surround the central plaza, each slowly cycling through varying charge states while bathing the area in disruptive psychic interference. These towers were originally designed to incapacitate unauthorized organic personnel by overwhelming higher brain functions, preventing intruders from advancing deeper into the facility.

The vault's primary gate has entered lockdown and can only be opened by synchronizing the suppression network. Each tower is linked to the others through a deterministic calibration network; adjusting one tower alters the charge state of two others. As towers reach critical charge they become active, projecting fields of cognitive disruption that inflict psychic damage and debilitating headaches upon anyone within their radius before slowly discharging themselves.

There is no enemy commander in this encounter. Instead, the suppression network itself serves as the obstacle. Players must coordinate their calibrations, anticipate the passive charging cycle, and equalize all four towers while enduring the hazards created by their activation. The encounter teaches players that environmental systems are as dangerous as enemies, that patience can be just as important as action, and that understanding the vault's technology is the key to progressing further.

# Arena Layout

The encounter takes place on a circular platform carved into the side of a snow-covered mountain.

Four **Noetic Suppression Towers** are positioned at the cardinal directions.

Adjacent to each tower is a single **Calibration Console**.

```
           T1           ○           □T4 □ ○           ○ □ T2           ◎           □           ○           T3
```

○ = Tower

□ = Calibration Console

◎ = Central Synchronization Node

Players must stand adjacent to a console to calibrate its corresponding tower.

---

# Objective

The encounter ends immediately once every tower possesses the same number of charges for 1 round.

Valid synchronized states include

```
0 0 0 0  1 1 1 1  2 2 2 2  3 3 3 3
```

Although in practice the encounter will almost always finish at **1** or **2** charges because towers at 3 immediately become hazardous.

Victory is checked after all end-of-round tower effects resolve at the start of next turn. (if at the start of next round all towers have the same charge level encounter is complete)

---

# Initial State

The towers always begin with the following charge values.

| Tower | Charges |
| ----- | ------- |
| T 1   | 3       |
| T 2   | 0       |
| T 3   | 3       |
| T 4   | 0       |

Players can immediately begin calibrating.

---

# Charge States

Each tower stores between **0 and 3 charges**.

## Inactive (0–2 Charges)

Inactive towers are dormant.

They:

- Do not emit psychic energy
- May always be calibrated
- Gain one charge automatically at the end of every round

---

## Critical Charge (3)

A tower reaching 3 charges does **not** activate immediately.

Instead, it is marked for activation.

At the **start of the following round**, it becomes Active.

This gives the players one round to anticipate which areas will become dangerous.

---

## Active

Once Active, a tower remains active until its charge reaches **0**.

While active it:

- Emits a Noetic Suppression Field in its sector
- Deals psychic damage to creatures inside
- Applies **Cognitive Strain** (your chosen debuff)
- Loses one charge at the end of each round
- Does **not** gain passive charge

Because active towers discharge themselves, players can deliberately allow towers to "burn out" if doing so helps synchronize the network.

---

# Round Structure

Each round follows the same sequence.

---

## 1. Activation Phase

Any tower currently at **3 charges** becomes Active.

Describe the tower unfolding from the ground.

Panels separate.

The central emitter rises.

Orange energy begins arcing between the antennae.

A low-frequency hum fills the arena.

---

## 2. Player Phase

Players may move normally.

A creature adjacent to a Calibration Console may use its Action to calibrate the associated tower.

Each console can only be used once per round.

---

## Calibration

Calibrating a tower immediately performs three operations.

### The selected tower

Gains **+1 Charge**

---

### Linked tower (positive)

Gains **+1 Charge**

---

### Linked tower (negative)

Loses **1 Charge**

Charges are always clamped between 0 and 3.

Calibration affects Active towers exactly the same as inactive ones.

---

## Tower Link Pattern

Each tower always affects the same two towers.

|Console|Tower|+1|-1|
|---|---|---|---|
|T 1|+1|T 2|T 4|
|T 2|+1|T 3|T 1|
|T 3|+1|T 4|T 2|
|T 4|+1|T 1|T 3|

Because the relationships never change, observant players can quickly learn the network.

The puzzle is intended to reward planning rather than experimentation.

---

## 3. End of Round

Each tower updates.

Inactive towers:

```
Charge +1
```

Active towers:

```
Charge -1
```

If an Active tower reaches 0, it deactivates immediately after resolving its effects.

Victory is checked.

---

# Noetic Suppression Field

Each Active tower projects a circular field around itself.

Creatures beginning their turn within the field must make an Intelligence saving throw.

Failure results in:

- Psychic damage
- Cognitive Strain

Suggested Cognitive Strain:

- Disadvantage on Intelligence checks
- Disadvantage on Wisdom (Perception)
- Inability to maintain concentration on failed saves

The damage should pressure movement without threatening an immediate wipe.

Players should quickly realize:

> **Standing in an active field is survivable, but doing so repeatedly is not.**

---

# DM Guidance

This encounter is designed to feel less like solving a puzzle and more like operating unfamiliar machinery under pressure.

Avoid telling the players the solution.

Instead, emphasize observable cause and effect.

Whenever a console is used, clearly describe every charge transfer.

Example:

> "As the console accepts your command, Tower Two brightens, while a pulse of energy races along buried conduits. Tower Three hums louder, but Tower One momentarily dims."

Players should be able to deduce the relationships naturally after only a few calibrations.

### **Encounter 2

Beyond the synchronization chamber lies an observation hall occupied by a **Malakhim Flayer**, a stationary security construct tasked with preventing unauthorized access to the Gene Vault's inner sanctum. The Flayer is protected by an impenetrable energy barrier that renders it completely immune to damage, making conventional assault impossible.

Shortly after the encounter begins, an **Archangel Lancer** enters the battlefield carrying an experimental **Shield Relay**. When deployed, this relay projects a high-frequency energy barrier around the lancer. If the players destroy the lancer while the barrier remains active, they override the relay's security protocols, converting it into a portable barrier that can be carried and repositioned.

The Flayer periodically unleashes a devastating **Cognitive Erasure Pulse**, a massive radial psychic shockwave that ignores conventional resistances and threatens every creature caught within its radius. The only way to survive—and to damage the boss—is to deliberately intercept the pulse using the stolen portable barrier. When the pulse collides with the barrier, its energy is reflected back into the Flayer's shielding matrix, triggering a catastrophic cognitive backlash. The Flayer is temporarily stunned, its barrier collapses, and the players are granted a brief damage phase before the system recovers.


### **Encounter 3

the boss arena is triangular in shape and split into 3 smaller triangles and a square, each triangle has a pillar, a cognitive disruption tower, these towers activate at different intervals to deal massive psychic damage to anyone inside their respective section, the boss may accelerate or decelerate the activation. the towers are only vulnerable to damage when active so the players will need a way to shield themselves from the damage, for that 3 special enemies will spawn in each section, an archangel lancer, these guys have a special action in which they deploy a temporary barrier, the players will need to kill the archangel while their respective barrier is active in order to override it and steal it. the towers dont have much HP but the players will need to destroy them in tandem (almost) for Chasan, the boss, will initiate the damage phase 2 turns after the first one is destroyed. Each destroyed tower takes 1 turn to repair for a total of 3 turns if all are destroyed (if 2 towers are destroyed the damage phase will last 2 turns and so on), while repairing Chasan is vulnerable to damage.