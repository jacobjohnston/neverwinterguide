---
name: Wererat Assassin
slug: wererat-assassin-page
---

```Monster {.two-column}
name: Wererat Assassin
slug: wererat-assassin
size: Medium
type: Humanoid
alignment: Any Alignment
ac: 16 (Studded Leather)
hp: 75 (9d10 + 26)
speed: 30 ft.
str: 11
dex: 18
con: 14
int: 11
wis: 11
cha: 12
saves: Dex +7, Int +3
skills: Perception +3, Stealth +7
damageImmunities: bludgeoning, piercing, and slashing from nonmagical attacks that aren't silvered
senses: darkvision 60 ft., passive Perception 13
languages: common, thieves' cant (can't speak in rat form)
challenge: 4
environments: Urban
traits:
  - name: Keen Smell
    description: The wererat has advantage on Wisdom (Perception) checks that rely on smell.
actions:
  - name: Multiattack (Humanoid or Hybrid Form Only)
    description: "The wererat makes 3 attacks with its dagger."
  - name: Dagger (Humanoid or Hybrid Form Only)
    description: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4 + 4) piercing damage."
  - name: Hand Crossbow (Humanoid or Hybrid Form Only)
    description: "Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  - name: Bite (Rat or Hybrid Form Only)
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target Hit: 4 (1d4 + 2) piercing damage. If the target is a humanoid, it must succeed on a DC 11 Constitution saving throw or be cursed with wererat lycanthropy."
bonus-actions:
  - name: Change Shape
    description: "The wererat transforms into a rat-humanoid hybrid, into a giant rat, or back into its humanoid form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies."
reactions:
  - name: Uncanny Dodge
    description: "The wererat halves the damage that it takes from an attack that hits it. It must be able to see the attacker."
image: WereratAssassin.jpg
token: WereratAssassinToken.png
column-after: actions
```
