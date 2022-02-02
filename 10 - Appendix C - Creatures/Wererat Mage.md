---
name: Wererat Wizard
slug: wererat-wizard-page
---

```Monster {.two-column}
name: Wererat Wizard
slug: wererat-wizard
size: Medium
type: Humanoid
alignment: Any Alignment
ac: 12 (15 with mage armor)
hp: 49 (11d8)
speed: 30 ft.
str: 9
dex: 14
con: 11
int: 17
wis: 12
cha: 11
saves: Int +6, Wis +4
skills: Arcana +6, History +6
damageImmunities: bludgeoning, piercing, and slashing from nonmagical attacks that aren't silvered
senses: darkvision 60 ft., passive Perception 11
languages: any three languages and thieves' cant (can't speak in rat form)
challenge: 5
environments: Urban
traits:
  - name: Keen Smell
    description: The wererat has advantage on Wisdom (Perception) checks that rely on smell.
actions:
  - name: Multiattack (Humanoid or Hybrid Form Only)
    description: "The wererat makes three Arcane Burst attacks."
  - name: Arcane Burst (Humanoid or Hybrid Form Only)
    description: "Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft., one target. Hit: 19 (3d10 + 3) force damage."
  - name: Bite (Rat or Hybrid Form Only)
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target Hit: 4 (1d4 + 2) piercing damage. If the target is a humanoid, it must succeed on a DC 11 Constitution saving throw or be cursed with wererat lycanthropy."
  - name: Spellcasting (Humanoid or Hybrid Form Only)
    description: "The wererat casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):


        At will: <i>dancing lights</i>, <i>mage hand</i>, <i>prestidigitation</i>

        2/day each: <i>fireball</i>, <i>mage armor</i>, <i>unseen servant</i>, <i>ice storm</i>"
bonus-actions:
  - name: Change Shape
    description: "The wererat transforms into a rat-humanoid hybrid, into a giant rat, or back into its humanoid form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies."
image: WereratMage.jpg
token: WereratMageToken.png
column-after: actions
column-after-property: Bite (Rat or Hybrid Form Only)
```