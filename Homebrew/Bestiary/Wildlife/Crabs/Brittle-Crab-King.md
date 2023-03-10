---
ac: 0
alias: ["Brittle Crab King"]
cr: 3
cssclass: Bunkers, BnB, BunkersnBadasses
hp: 30
modifier: 
statblock: true
tags:
- BnB/Bestiary/Wildlife/Crab/Brittle-Crab
- BnB/Homebrew/Bestiary
title: Brittle Crab King
---



# Brittle Crab King
>[!tina] Bunkermaster Tina
> As you continue on your journey with your newfound trusty axe, you come across a large, frantic land crab. As you approach, the crab screeches and attacks you with its sharp pincers and lightning-fast scuttling movements.

## Statblock
```statblock
layout: BunkersBestiary
source: Bunkers-Wildlife
dice: true
Name: Brittle Crab King
Type: "Wildlife."

TitleOfMob: King Brittle Crabby
FlavorText: Only Semi-Brittle
TypeOfBoss: Scrub Crab Boss

BadassRank: 3
MovementType: move 2 swim 1
Health: 10
Shield: 10
Armor: 10
Traits: Tiny Armor. Impaled.
Weapon: Head, Pincers
Special: When first encountered, King Brittle Crab will summon 3 Brittle Crab.
SuperSpecial:
Actions:
- name: Pinch
  desc: "Brittle Crab King pinches at an adjacent target, dealing 4 (2d4) Damage."
Mayhem: 
- name: Headbutt and Slash
  desc: "Brittle Crab King will use its head and forelimbs to Attack an adjacent target, dealing 6 (2d6+6) Damage."
ImageBig: "[You've Found the King](../../../../../00-Vault-Hunter/2-Images/Entities/Wonderlands/Creatures/Brittle-Crab-King.png)"
```

```statblock
# Layout is needed to force the Bunkers Layout
layout: BunkersBestiary
# Source helps the Bestiary Organize the Entity
source: Bunkers-Treant
# Ensures Dice Rolls Turned on even if Off Elsewhere
dice: true
# Entity Stats
Name: Treant
Type: "Treant."
# Boss/Subtitle Sttuff Below

TitleOfMob: 
FlavorText: 
TypeOfBoss: 

BadassRank: 9
# Use move, swim, fly, hover, leap, climb, or swim + number i.e., swim 3 fly 4 hover 5 move 1
MovementType: move 3
# Will automatically switch to N/A if Empty
Health: 70
Shield: 
Armor: 
Traits: Wood. Large. 
Weapon: Branches.
Special:
SuperSpecial:
Actions:
- name: Ground Slam
  desc: "Treant slams the ground with its trunk, dealing 2d12 (2d12) Damage to all adjacent targets."
- name: Orbs
  desc: "Treant releases 6 blue orbs that seek out targets within 3 squares, dealing 1d6 Shock Damage each."
Mayhem: 
- name: Bramble
  desc: "Treant pushes 3 branches into the ground that sprout up to 2 squares away and turn into fully grown plants in 1 turn. Once fully grown, the plants explode when any target is adjacent, dealing 2d6 (2d6) Corrosive Damage."
- name: Ground Slam x2
  desc: "Treant slams the ground with its trunk twice, dealing 2d12 (2d12) Damage per slam to all adjacent targets."
ImageBig: "[Treat](../../../../../00-Vault-Hunter/2-Images/00-Sort/LittleMaelstrom_treant_in_the_style_of_bunkers_and_badasses_bor_3a5eb7c6-a0ad-4df9-8183-6b8362a4a571.png)"
```



```statblock
# Layouts until other style of releases should be BunkersBestiary
layout: BunkersBestiary
source: Bunkers-Example
dice: true
# If Its a Badass or a SuperBadass, make sure to put that First... Badass Potion Master... SuperBadass Treant
Name: "Super Badass Deep Dragon"
# "Landshark."
Type: "Dragon."
# Title of the Boss here, like King of the Hill or Wakisobi
TitleOfMob: "Cruncher of Rocks"
# Flavor Text Here such as Really Loves Fish
FlavorText: "Rocks means your bones actually"
# Miniboss, NPC, Made-Up Boss???
TypeOfBoss: "Miniboss"
# Self Explanatory, right? What is its BR
BadassRank: 21
# Options are move, flight, swim, burrow, teleport, hover, Leap,climb, 
MovementType: "move 4 flight 6 teleport 2"
# Hitpoints
Health: 200
# Shield Points
Shield: 50
# Armor Points
Armor: 50
# Any existing Traits. Badasses will automatically get assigned a trait, so dont add one unless it exists in base, like Flesh.
Traits: Large
# What weapon does it use?
Weapon: "Breath, Bite (+3 Damage)"
# Any special stuff we out to know?
Special: ""
# Super_Special is for use with some weird entities like Potion Master and some Bosses. Usually leave the name blank as "".
SuperSpecial:
- name: "Fixation"
  desc: "After performing an Air Bite the Dragon will become fixated on the target for two turns, and will pursue the target up to its maximum flight speed per turn."
# Main Actions. Leave Empty if None
Actions:
- name: Concoct
  desc: "Potion Master mixes a batch of ingredients into a slurry and then caps the Random Potion (Special) with a cork stopper."
- name: Bite
  desc: "If Landed, the Dragon charges up to 3 squares and Bites up to 2 adjacent targets for 1d10+3 (1d10+3) Damage per Bite."
- name: Air Bite
  desc: "If flying and adjacent to 1 target, the Dragon bites that one target for 2d10 (2d10) Damage. The dragon becomes fixated on this target for two turns."
# Mayhem Actions. Leave Empty if None
Mayhem: 
- name: Improved Concoction
  desc: "Potion Master mixes all the ingredients for an improved potion and then caps it with a stopper. +2 to the result of the Random Potion roll result (Special)." 
- name: Air Bite
  desc: "If flying and adjacent to 1 target, the Dragon bites that one target for 2d10 (2d10) Damage. The dragon enter _fixation_."
# Does this Entity Carry Super Special Loot? Leave Empty if None
Loot:
 - name: A Purple Scale
   desc: "This Deep Dragon was carying a strange, purple scale, embossed with a series of scratches."
# Does this Entity Have an Image? Accepts Wikilink or Markdown Link. Leave Empty if None
ImageBig: ""
```


## Lore
The Brittle Crab King is a fierce and feisty land crab native to the Snoring Valley region of the Mellow Steppes province. Though small in size, this crab packs a punch with its sharp pincers and lightning-fast scuttling movements. Its prey includes giant squirrels, fat-ass bass, and the occasional human. The Brittle Crab King is known for calling upon its numerous offspring to join the fight in battle.

In terms of appearance, the Brittle Crab King sports a hard, brown shell covered in small spikes. It can often be found lurking underground, waiting for unsuspecting prey to pass by. Once defeated, this crab's shell can be pried open to reveal an old hewn axe that was used to impale it long ago.

Normally not an overly aggressive species, the Brittle Crab King has recently been attacking anything that crosses its path as it searches frantically for its missing queen.

> [!quest]
> If spared from death in it's defeat, it may offer a quest to players to help find its beloved mate.
>
> See [The Queen of the Mellow Crustaceans](../../../Quests/Rescue/The-Queen-of-the-Mellow-Crustaceans.md)