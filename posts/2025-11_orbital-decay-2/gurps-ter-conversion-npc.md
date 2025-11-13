<!-- markdownlint-disable MD028 MD033 -->
# Converting GURPS Transhuman Space Characters To The Expanse RPG<!-- omit from toc -->

This document formalizes the conversion of a Non-Player Character (NPC) from the GURPS game system to The Expanse RPG (TER) game system.

It draws from various sources. Here are some of those that got me on this path:

- ["Converting from GURPS to..." at forum.rpg.net](https://forum.rpg.net/index.php?threads/converting-from-gurps-to.81265/)
- ["Conversions and Adaptation" at sjgames.com](https://www.sjgames.com/gurps/faq/FAQ3-4.html)
- ["How can I adapt GURPS 4e materials to D&D 5e?" at rpg.stackexchange.com](https://rpg.stackexchange.com/questions/77140/how-can-i-adapt-gurps-4e-materials-to-dd-5e)

The steps detailed in the following sections result from my attempts to transpose NPCs from the 'Orbital Decay' scenario. I came up with some (🤔'most') of those steps *after* having played the scenario with my group, using other resembling NPCs taken from other TER sourcebooks or scenarios. I wanted to check what I could have done differently so as to stick more to the original characters.

This document might be useful to anyone willing to play this scenario without too much effort, reusing some or all of what I propose here. It could also help anyone interested in using some GURPS material for TER.

I used a sprinkling of the following reference material from both game systems:

- **SJG03995 GURPS 4th Edition Basic Set - Characters**
- **SJG03695 GURPS Transhuman Space**
- **SJG00895 GURPS TS Scenario 'Orbital Decay'**
- **GRR6601e The Expanse Roleplaying Game**
- **['GURPS Advantage Listings' at sjgames.com](https://www.sjgames.com/gurps/img/Adv-Dis-Skills.pdf)**
- **['GURPS 4th Edition Update' *Advantage Conversion Table* at sjgames.com](https://www.sjgames.com/gurps/resources/4eupdate.pdf)**
- **['GURPS Wiki' at fandom.com](https://gurps.fandom.com/wiki)**

## Step 1: Role And Concept

Understand what the character role is in its context. GURPS uses a more detailed and realistic set of skills whereas TER has more abstracted roles and narrative-driven characters. This will help choosing *Ability Focuses*, *Talents* or *Specializations* in later steps.

You also have to determine the *Threat Level* this NPC can pose to the Player Characters. This will also help adjust Abilities, Focuses, etc. accordingly.

For each GURPS NPC, there is usually an associated points value. The following table gives you a proposed corresponding *Threat Level* and the corresponding range of character levels.

| GURPS Pts |       Threat Level       |
| :-------: | :----------------------: |
|   50-75   |     **Minor** (1-3)      |
|  75-100   |     **Minor** (3-4)      |
|  100-150  |    **Moderate** (5-7)    |
|  150-250  | **Moderate/Major** (7-9) |
|  300-400  |  **Major/Dire** (9-12)   |
|   400+    | **Dire/Legendary** (12+) |

You can use this *Threat Level* in the following steps to adjust the results of the conversion, if need be (see the different *Crosscheck* sections).

## Step 2: Attributes To Abilities

Here is a proposal to adapt the four primary GURPS *Attributes* to the nine TER *Abilities*. Let's start by trying to consider the possible relationship between those.

| GURPS             | The Expanse RPG                         |
| ----------------- | --------------------------------------- |
| Strength (ST)     | Strength                                |
| Dexterity (DX)    | Dexterity, Accuracy, Fighting           |
| Intelligence (IQ) | Intelligence, Perception, Communication |
| Health (HT)       | Constitution, Willpower                 |

Apart from GURPS's ST, for all other Attribute to Ability relationships we have to split DX, IQ, and HT based on perceived character's role and concept.

Let's now consider the respective scales of Attributes and Abilities:

- GURPS Attributes are centered on **10** (average human).
- TER Abilities range from -2 to +4, with **0** as average.

We can use the following conversion table (or any other mapping you find more appropriate):

|   GURPS   |  TER  |
| :-------: | :---: |
| $\leq$ 7  |  -2   |
|     8     |  -1   |
| **9-10**  | **0** |
|    11     |  +1   |
|    12     |  +2   |
|   13-14   |  +3   |
| $\geq$ 15 |  +4   |

When splitting DX, IQ and HT, determine which TER corresponding Ability is the most important one for the character concept and assign the corresponding value, and distribute lower values to the other split Abilities.

> **EXAMPLE** - A GURPS Technician character with DX 12 could translate into a TER character with Dexterity +2, Accuracy +1 and Fighting 0. With a GURPS IQ 12, the TER version could have Intelligence +2, Perception +1 and Communication 0. Now considering a GURPS Soldier character with the same DX and IQ, those could translate to Fighting +2, Accuracy +1 and Dexterity 0 (or vice-versa) as well as Perception +2, Intelligence +1, and Communication 0 (or vice-versa).

### Abilities Crosscheck

Check that the total of *Ability* points fall in or close to the range given by the *Threat* and *Abilities* columns in the [NPC Generator Cheat Sheet](ter-refcard-npc-generator-cheat-sheet.md) and adjust as you see fit, if need be by raising or lowering the *Threat Level* or some *Abilities*.

## Step 3: Skills To Focuses

We can now try to match some of the most important GURPS skills a character has (select up to five or six) to a TER Ability Focus. Try to stick to GURPS skills that the character would use frequently or that are central to their concept.

Here is a list with most of the GURPS skills found in the "Orbital Decay" scenario and proposed corresponding TER Ability Focus(es).

| GURPS Skill                              | TER Ability (Focus)                        |
| :--------------------------------------- | :----------------------------------------- |
| Acting                                   | Communication (Deception)                  |
| Area Knowledge (Earth Orbit)             | Intelligence (Navigation)                  |
| Artist                                   | Intelligence (Art)                         |
| Astrogation                              | Intelligence (Navigation)                  |
| Biochemistry                             | Intelligence (Science)                     |
| Brawling                                 | Fighting (Brawling)                        |
| Camouflage                               | Dexterity (Stealth)                        |
| Carousing                                | Communication (Etiquette)                  |
| Computer Hacking                         | Intelligence (Security)                    |
| Computer Operation                       | Intelligence (Technology)                  |
| Cryptanalysis                            | Intelligence (Cryptography)                |
| Demolitions                              | Intelligence (Demolitions)                 |
| Disguise                                 | Communication (Disguise)                   |
| Electronics Operation (Communications)   | Intelligence (Technology)                  |
| Electronics Operation (Security Systems) | Intelligence (Security)                    |
| English (native)                         | Communication (Expression)                 |
| Escape                                   | Dexterity (Stealth)                        |
| Fast-Talk                                | Communication (Persuasion, Bargaining)     |
| First Aid                                | Intelligence (Medicine)                    |
| Freight Handling                         | Strength (Might)                           |
| Free Fall                                | Dexterity (Free-Fall)                      |
| Genetics (Genetic Engineering)           | Intelligence (Science)                     |
| Guns (Pistols)                           | Accuracy (Pistols)                         |
| Intelligence Analysis                    | Intelligence (Evaluation)                  |
| Interrogation                            | Communication (Investigation)              |
| Intimidation                             | Strength (Intimidation)                    |
| Karate                                   | Fighting (Brawling)                        |
| Knife                                    | Fighting (Light Weapons)                   |
| Knife Throwing                           | Accuracy (Throwing)                        |
| Leadership                               | Communication (Leadership)                 |
| Mechanic (Fission Drives and Reactors)   | Intelligence (Engineering)                 |
| Piloting (High Performance Spacecraft)   | Dexterity (Piloting)                       |
| Physiology                               | Intelligence (Science)                     |
| Politics                                 | Intelligence (Current Affairs)             |
| Research                                 | Intelligence (Research)                    |
| Sex Appeal                               | Communication (Seduction)                  |
| Sign Language                            | Communication (Expression)                 |
| Sleight of Hand                          | Dexterity (Sleight of Hand)                |
| Stealth                                  | Dexterity (Stealth)                        |
| Streetwise                               | Intelligence (Current Affairs, Evaluation) |
| Strategy                                 | Intelligence (Tactics)                     |
| Tactics                                  | Intelligence (Tactics)                     |
| Teaching                                 | Communication (Expression)                 |
| Vacc Suit                                | Dexterity (Free-Fall)                      |

Sources: For GURPS skills, I used GURPS 4th Ed. Basic Set Characters chapter 4 (p. 167) for details or confirmation of the skills usages. I did not had to use GURPS TS as there are in fact very few skills described in there. For TER Ability Focuses, TER chapter 3 (p. 46).

> **EXAMPLE** - A GURPS TS Shuttle pilot skills set is composed of *Astrogation*, *Carousing*, *Computer Operation*, *Electronics Operation (Communications)*, *Free Fall*, *Games (InVids)*, *Piloting (High Performance Spacecraft)*, and *Vacc Suit*. Out of those eight skills, only seven appear in our conversion table. Let's select five of those that we think are central to this character and convert them: *Astrogation*, *Computer Operation*, *Electronics Operation (Communications)*, *Free Fall*, and *Piloting (High Performance Spacecraft)*. The following Ability Focuses could be used to flesh out a character with a similar concept in TER: Intelligence (Navigation, Technology), Dexterity (Free-Fall, Piloting)

### Focuses Crosscheck

Check that the total number of Focuses fall in or close to the range given by the *Threat* and *Focuses* [NPC Generator Cheat Sheet](ter-refcard-npc-generator-cheat-sheet.md) and adjust as you see fit, if need be by removing or adding Focuses or adapting the *Threat Level*. Keep in mind that some Focuses could be determined as central to the considered NPC role/concept.

## Steps 4: GURPS Traits to TER

GURPS Character Traits (Advantage, Disadvantage, Quirks) do not transpose as easily to TER. Or not directly: Sometimes it matches with a TER Talent, or Ability bonus, or a purely narrative tag or specific condition for the GM to have the character behave accordingly.

The following table is a tentative proposal to match all traits covered in GURPS *Orbital Decay* to some equivalent in TER.

| GURPS Trait                          | Category     | TER Equivalent                                                  |
| :----------------------------------- | :----------- | :-------------------------------------------------------------- |
| Albinism                             | Disadvantage | Roleplaying hint: React agressively to light.                   |
| Alertness                            | Advantage    | Ability: Perception +1                                          |
| Appearance (Attractive)              | Advantage    | Talent: Attractive (Novice)                                     |
| Berserk                              | Disadvantage | Roleplaying hint: All-out attacks with no thought for defense.  |
| Charisma +2                          | Advantage    | Ability: Communication +1                                       |
| Combat Reflexes                      | Advantage    | Talent: Quick Reflexes (Novice).                                |
| Dependents (Daughters)               | Disadvantage | Roleplaying hint: Have dependents in mind when taking action.   |
| Resistant: Disease [5]               | Advantage    | Focus: Constitution (Stamina)                                   |
| Duty                                 | Disadvantage | Roleplaying hint: Acts as Drive & Goals for a Player Character. |
| Fanaticism                           | Disadvantage | Ability: Willpower -1                                           |
| Gluttony                             | Disadvantage | Roleplaying hint: Can't help eating. Disctracted by food.       |
| Hard to Kill                         | Advantage    | Ability: Constitution +1                                        |
| High Pain Threshold                  | Advantage    | Talent: Commando (Novice)                                       |
| Intuition                            | Advantage    | Focus: Perception (Intuition)                                   |
| Longevity                            | Advantage    | *Not applicable*                                                |
| Luck (15)                            | Advantage    | Ability: Fortune +5                                             |
| Night Vision                         | Advantage    | Focus: Perception (Seeing)                                      |
| Overconfidence                       | Disadvantage | Roleplaying hint: Acts boldly.                                  |
| Panimmunity (Resistant: Disease [2]) | Advantage    | Focus: Constitution (Stamina)                                   |
| Reputation (Playboy)                 | Disadvantage | Ability: Communication -1                                       |
| Sense of Duty                        | Disadvantage | Roleplaying hint: Acts as Drive & Goals for a Player Character. |
| Shyness                              | Disadvantage | Ability: Communication -1                                       |
| Strong Will                          | Advantage    | Ability: Willpower +1                                           |

### Cumulative Traits

Some of the extensive array of GURPS Traits could be transposed into the same TER traits and/or abilities. Here are some of the most evident ones and how you could handle it:

- **Alertness & Combat Reflexes**: Consider also raising TER Quick Reflexes talent to Expert.
- **Appearance (Attractive) & Sex Appeal**: Consider also raising TER Attractive talent to Expert.

### Talents Crosscheck

As for Focuses in Step 4, check that the total number of Talents fall in or close to the range given by the *Threat* and *Talents* [NPC Generator Cheat Sheet](ter-refcard-npc-generator-cheat-sheet.md) and adjust as you see fit, if need be by removing or adding Talents or adapting the *Threat Level*. Each *Novice* level count for one (1), *Expert* for two (2), and *Master* for three (3) Talent points. As for *Focuses*, keep in mind that some Talent derived from GURPS Traits could be determined as central to the considered NPC role/concept.

Since some of those GURPS Traits could translate into TER Ability bonus/malus and/or additional Focuses, you should again crosscheck the resulting Abilities and Focuses total points and adjust if you think its warranted.

## Step 5: Specializations

Major NPCs could also have some specialization. Do not bother to do this for every single NPCs but those that can play a significant role in your series. As a guideline, you can use the *Spec* column from [NPC Generator Cheat Sheet](ter-refcard-npc-generator-cheat-sheet.md) to determine the number of Specializations the NPC would be entitled. Check that the Requirements are fulfilled.

## Step 6: Rounding Out

Most NPCs have at least one favorite Stunt, usually a combat-oriented one. If there are any specific GURPS Advantage, or Skill for which you have not yet found an equivalent, trying searching through the stunts described in TER manual in Chapter 5 **Action Stunts** section (p. 94). Minor or Moderate threat level should have one or two preferred stunts, while Major and above should have three of them. But as long as you think the chosen stunts fit with the NPC concept from step 1, you are on the right track.

<style>
table :is(td, th, tr) {
  padding-top: 0.2em!important;
  padding-bottom: 0.2em!important;
}
th {
  background-color: #004962!important;
  color: white!important;
}
tr:nth-child(odd) {
  background-color: #B6D2DE!important;
  color: black!important;
}
tr:nth-child(even) {
  background-color: #E7F1F5!important;
  color: black!important;
}
.title {
  width: 100%;
}
</style>
