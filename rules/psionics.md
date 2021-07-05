---
layout: default
title: Psionics
parent: Rules
---

# Psionics

To use psionics, consider the following player rules:

* You must receive specialized training or be a member of a race with innate psionic abilities.
* You have an amount of **Psionic Dice** (d6) commensurate with your level of training.

## Using Psionic Powers

Psionic powers work similarly to [GLOG Magic](https://cairnrpg.com/hacks/glog-magic/). To use a **Psionic Power**:

* Choose the **Power** you wish to activate. The power's description may denote its duration with **D** and range with **R**.
* Choose how many **Psionic Dice** you wish to invest (up to a maximum of 4). Powers will refer to these as [dice]. Some powers will refer to their [sum] as well.
* Roll [dice]. For each die that shows a 4-6, you gain one [Fatigue](https://cairnrpg.com/cairn-srd/#deprivation--fatigue).
* If you get a series (e.g. 2-4 dice that match), something has gone very wrong. Look up the power's [sum] on the **Psionic Backlash** table, below.

### Psionic Backlash

| Sum  | Backlash |
| :---- | :-------- |
| 2    | Your nose bleeds profusely for the next hour and you cannot use any psionic powers for 1d6 hours. |
| 3    | For the next 24 hours, when using a psionic power, you gain a Fatigue on a roll of 3-6. |
| 4    | You can barely walk until you complete [dice] short or long rests. |
| 5    | You hear the surface thoughts of living creature within 30' of you. |
| 6    |          |
| 7    |          |
| 8    |          |
| 9    |          |
| 10   |          |
| 11   |          |
| 12   |          |
| 13   |          |
| 14   |          |
| 15   |          |
| 16   |          |
| 17   |          |
| 18   |          |
| 19   |          |
| 20   |          |
| 21   |          |
| 22   |          |
| 23   |          |
| 24   |          |

## Psionic Combat

On their turn, a character may activate both a **Psionic Attack Mode** and **Psionic Defense Mode** as an action. 

* Choose a **Psionic Attack Mode** and/or **Psionic Defense Mode**.
* Choose how many **Psionic Dice** you wish to invest into each (up to a maximum of 4, total).
* Roll [attack-mode-dice] and [defense-mode-dice]. For each die that shows a 4-6, you gain one [Fatigue](https://cairnrpg.com/cairn-srd/#deprivation--fatigue).

Since Psionic Attack and Defense Modes are Psionic Powers, not all characters will have all modes.

### Attack Modes

There are three **Psionic Powers** that may be used as **Psionic Attack Modes** during psionic combat. Each one is associated with an ability score.

* **Psychic Crush** (STR). Exert overwhelming force with your mind.
* **Synapse Overload** (DEX). Flood nervous system to induce paralysis.
* **Mind Spike** (WIL). Rend a creature's mind.

### Defense Modes

There are three **Psionic Powers** that may be used as **Psionic Defense Modes** during psionic combat. Each one is associated with an ability score.

* **Mental Barrier** (STR). Construct a physical barrier with your mind.
* **Mind Blank** (DEX). Empty your mind of external influences.
* **Intellect Fortress** (WIL). Protect your ego by placing in a protective shell.

### Resolution

A Psionic Attack Mode's effectiveness depends on the Psionic Defense Mode a target has active, if any. 

|                            | Mental Barrier (STR) | Mind Blank (DEX) | Intellect Fortress (WIL) | None   |
| :-------------------------- | :-------------------- | :---------------- | :------------------------ | :------ |
| **Psychic Crush (STR)**    | Diminished           | Augmented        | Normal                   | Normal |
| **Synapse Overload (DEX)** | Normal               | Diminished       | Augmented                | Normal |
| **Mind Spike (WIL)**       | Augmented            | Normal           | Diminished               | Normal |

* **Normal**. Deal [attack-mode-sum] minus [defense-mode-sum] damage to the defender's associated ability score.
* **Augmented**. Deal 2*[attack-mode-sum] minus [defense-mode-sum] damage to the defender's associated ability score.
* **Diminished**. Deal [attack-mode-sum] minus 2*[defense-mode-sum] damage to the defender's associated ability score.

Negative damage amounts are dealt to the attacker's associated ability score.
