---
name: Wererat Mage
slug: wererat-mage-page
---

```Monster {.two-column}
name: Wererat Mage
slug: wererat-mage
size: Medium
type: humanoid (human, shapechanger)
alignment: lawful evil
ac: 12 (15 with mage armor)
hp: 36 (8d8)
speed: 30 ft.
str: 9
dex: 14
con: 11
int: 17
wis: 12
cha: 11
saves: INT +6, WIS +4
skills: Arcana +6, History +6
damageImmunities: Bludgeoning, Piercing, and Slashing from Nonmagical Attacks that aren't Silvered
senses: Darkvision 60 ft., Passive Perception 11
languages: Common (can't speak in rat form)
challenge: 4
environments:
traits:
  - name: Shapechanger
    description: "The wererat can use its action to polymorph into a rat-humanoid hybrid or into a giant rat, or back into its true form, which is humanoid. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn’t transformed. It reverts to its true form if it dies."
  - name: Keen Smell
    description: The wererat has advantage on Wisdom (Perception) checks that rely on smell.
  - name: Spellcasting (Humanoid or Hybrid Form Only)
    description: "The wererat is a 9th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 14, +6 to hit with spell attacks). The wererat has the following wizard spells prepared:


        Cantrips (at will): fire bolt, light, mage hand, prestidigitation


        1st level (4 slots): detect magic, mage armor, magic missile, shield


        2nd level (3 slots): misty step, suggestion


        3rd level (3 slots): counterspell, fireball, dispel magic


        4th level (3 slots): greater invisibility, ice storm


        5th level (2 slots): cone of cold"
actions:
  - name: Staff (Humanoid or Hybrid Form Only)
    description: "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands."
  - name: Bite (Rat or Hybrid Form Only)
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target Hit: 4 (1d4 + 2) piercing damage. If the target is a humanoid, it must succeed on a DC 11 Constitution saving throw or be cursed with wererat lycanthropy."
image: WereratMage.jpg
token: WereratMageToken.png
column-after: traits
```