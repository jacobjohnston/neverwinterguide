---
name: Wererat Assassin
slug: wererat-assassin-page
---

```Monster {.two-column}
name: Wererat Assassin
slug: wererat-assassin
size: Medium
type: humanoid (human, shapechanger)
alignment: lawful evil
ac: 14 (Studded Leather)
hp: 70 (9d10 + 21)
speed: 30 ft.
str: 11
dex: 17
con: 14
int: 11
wis: 11
cha: 12
saves: DEX +5, INT +3
skills: Perception +3, Stealth +5
damageImmunities: Bludgeoning, Piercing, and Slashing from Nonmagical Attacks that aren't Silvered
senses: Darkvision 60 ft., Passive Perception 13
languages: Common, Thieves' Cant (can't speak in rat form)
challenge: 4
environments:
traits:
  - name: Shapechanger
    description: "The wererat can use its action to polymorph into a rat-humanoid hybrid or into a giant rat, or back into its true form, which is humanoid. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn’t transformed. It reverts to its true form if it dies."
  - name: Keen Smell
    description: The wererat has advantage on Wisdom (Perception) checks that rely on smell.
actions:
  - name: Multiattack (Humanoid or Hybrid Form Only)
    description: "The wererat makes 2 attacks with its dagger."
  - name: Dagger (Humanoid or Hybrid Form Only)
    description: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  - name: Hand Crossbow (Humanoid or Hybrid Form Only)
    description: "Ranged Weapon Attack: +7 to hit, range 30/120 ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  - name: Bite (Rat or Hybrid Form Only)
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target Hit: 4 (1d4 + 2) piercing damage. If the target is a humanoid, it must succeed on a DC 11 Constitution saving throw or be cursed with wererat lycanthropy."
reactions:
  - name: Uncanny Dodge
    description: "The wererat halves the damage that its takes from an attack that hits it. It must be able to see the attacker."
image: WereratAssassin.jpg
token: WereratAssassinToken.png
column-after: actions
column-after-property: Hand Crossbow (Humanoid or Hybrid Form Only)
```