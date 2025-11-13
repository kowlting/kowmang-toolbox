<!-- markdownlint-disable MD028 MD033 -->
# Converting GURPS Attributes Or Skill Rolls To The Expanse RPG Tests<!-- omit from toc -->

This document formalizes the conversion of a GURPS Attribute or Skill roll to a The Expanse RPG (TER) test.

Reading about attributes and skill rolls in GURPS rules (or just from the very synthetic [GURPS Wikipedia page](http://en.wikipedia.org/wiki/GURPS) and the Probability Table documented on this [GURPS Wiki](https://gurps.fandom.com/wiki/Success_Roll) page), we can consider that an average character with average attribute (10) has a 50/50 chance of achieving success with a 3d6 roll.

When considering TER mechanics, our average character would have a **+1** ability. So this means that for an **Average** difficulty test (Target Number 11), this same character would get an 50/50 chance to succeeds.

GURPS tests are listed using a **-x** to reflect either the specific difficulty related to that test or the difficulty related to the used skill. No such difference in TER. But this simple **-x** GURPS mod is pretty easy to transpose to TER: Any **x** minus GURPS modifier raises the TER test difficulty above Average by **(|x| / 2)** (rounded up).

| GURPS Mod. | TER Diff. Mod. | TER Diff. Lvl | TER TN |
| :--------: | :------------: | :-----------: | :----: |
|     -1     |  (0.5) **+1**  |  Challenging  |   13   |
|     -2     |  (1.0) **+1**  |  Challenging  |   13   |
|     -3     |  (1.5) **+2**  |     Hard      |   15   |
|     -4     |  (2.0) **+2**  |     Hard      |   15   |
|     -5     |  (2.5) **+3**  |  Formidable   |   17   |
|     -6     |  (3.0) **+3**  |  Formidable   |   17   |
|    etc.    |      etc.      |               |        |

This fits pretty well with TER spirit: Simple tests factoring circumpstancial modifiers into its difficulty, expressed as a TN raised or lowered by 2-point steps to make it easier for everyone to assess the test at hand and easily determine its difficulty, not falling in the trap of overthinking it.

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
