# Mechanics

## Preparation

A team must be defined by the player before a match and is composed of
any six characters. At the start of a match, both players will go
through a number of preparation phases.

1.  One of the players will be randomly chosen to be the "starting
    player". This determines the turn order, the draft order and the
    allocation of the map halves.

2.  In the draft phase, both players will take turns choosing their
    characters and positioning them in the map. No character may be
    chosen twice in a match.

    The draft order is "O → S → S → O → O → S", with "S" being the
    starting player and "O" their opponent.

    Once the draft is finished, both players must simultaneously select
    one of their fielded characters to occupy the role of their team's
    assistant.

3.  In the draw phase, the player will draw three cards from their deck,
    forming their starting hand.

    They may then shuffle any number of cards from their hand back into
    their deck and draw that many cards as replacements.

4.  The match then begins with the starting player's turn.

## Combat

- Each player starts the match with no action points.

- A player can have up to 10 action points.

- Unused action points will not carry over to the next turn.

- A player will have their maximum action points increased by one at
  the beginning of their turns.

- A player will have their action points fully restored at the
  beginning of their turns.

- Once per turn, a character can walk to any tile within their speed
  score in distance by using an action point.

- Once per turn, a character can perform an attack against an opponent
  within their reach by using two action points.

- A character will simultaneously perform a counter-attack when an
  opponent within their reach attacks them.

- Upon being attacked, the defender will take damage equal to the
  power of the attacker.

- Any single damage instance may not deal less than one damage point
  or more than the equivalent of "Gargantuan" damage in points.

- A character is "critically damaged" if their remaining armor is
  below a third of its total amount.

- A character whose damage taken surpasses their armor will faint.

- Healing a character restores part of their lost armor.

- Traps detonate upon being stepped on, affecting the characters on
  that tile and adjacent ones. A character will stop walking upon
  stepping on a trap.

## Rounds

A "round" is an unit equivalent to a number of turns equal to number of
players in a match. In matches with multiple participants, defeated
players' turns are also counted.

This section describes what the envisioned combat flow currently looks
like.

- Rounds 1--5 --- Action points are used primarily for positioning.
  Correctly placing and moving a character should allow a player to
  attain the first strike.

- Rounds 5--10 --- All characters are in place. Characters are taken
  down one by one rather than dilluting damage. The majority of
  matches should end in this phase.

- Rounds 10-- --- An abundance of action points allows for explosive
  turns to break the stalemate.

## Cards

- Each character has four copies of their primary skill card and three
  copies of each of their secondary skill cards.

- A deck is made by shuffling the card pools of the characters fielded
  in a match.

- A player can freely use skill cards during their turns for as long
  as they have enough action points to do so.

- A player will draw a card from their deck at the beginning of each
  of their turns.

- A player can have up to 9 cards in their hand at time. Drawing a
  card while having a full hand causes the leftmost card in the hand
  to be discarded.

## Defeat

A set of conditions may be assigned to each player at the start of a
match; failing any of them will cause that player to be defeated. A
player may also choose to forfeit the match at any time.

- "At least one character must remain."

- "At least one outpost must remain."

## Effects

Effects modify the behaviour of a character. Though usually applied by
skills, they may also come from the map itself.

- Receiving an effect increases its duration by a round.

- The duration of each modifier is discounted at the end of every
  turn.

| Name     | Effect                                                         |
| -------- | -------------------------------------------------------------- |
| Ignite   | Damage the character upon using skills, attacking or walking.  |
|          |                                                                |
| Glaciate | The cost of using skills, attacking or walking is increased.   |
| Tailwind | The cost of using skills, attacking or walking is reduced.     |
|          |                                                                |
| Restrain | The character is unable to attack or walk.                     |
| Silence  | The character is unable to use skills.                         |
|          |                                                                |
| Fortify  | Minimize the damage dealt by incoming damage instances.        |
| Prowess  | Maximize the damage dealt by outgoing damage instances.        |
|          |                                                                |
| Bounty   | When the character is defeated, each opponent draws two cards. |
| Defiance | When the character is defeated, return them to combat.         |

## Archetypes

Each character belongs to an archetype, which guides how they behave in
combat.

- Upon designating a character as their team's assistant, the score of
  their affinity is raised for each allied character.

- Ranged characters can only target units that are exactly two tiles
  away from them. They can move up to three tiles per turn.

- Melee characters can only target units that are exactly one tile
  away from them. They can move up to five tiles per turn.

| Archetype  | Ranged? | Affinity | Power  | Armor  |
| ---------- | ------- | -------- | ------ | ------ |
| Enchanter  | Yes     | Power    | Huge   | Small  |
| Duelist    | No      | Power    | Large  | Medium |
| Specialist | Yes     | Armor    | Medium | Large  |
| Vanguard   | No      | Armor    | Small  | Huge   |

The following table describes how the archetypes are distributed across
the factions.

| Enchanter | Duelist | Specialist | Vanguard | Faction                                   |
| :-------: | :-----: | :--------: | :------: | ----------------------------------------- |
|           |    •    |     •      |          | [The Ivory Tower](the-ivory-tower.md)     |
|     •     |         |     •      |    •     | [The Fairy Kingdom](the-fairy-kingdom.md) |
|     •     |    •    |            |    •     | [The Temple Order](the-temple-order.md)   |

The "Familiar" and "Calamity" archetypes are used for unconventional
characters, such as bosses or summons, and their specifics may vary on a
per-case basis.

| Archetype | Power      | Armor      |
| --------- | ---------- | ---------- |
| Calamity  | Gargantuan | Gargantuan |
| Familiar  | Tiny       | Tiny       |

## Scores

Power and armor scores are split into six tiers. When a skill or a
talent modifies a character's power or armor, it does so by raising or
lowering them to another tier.

Scores are bounded by the tiers, therefore it is impossible to lower
them below the "Tiny" tier or raise them above the "Gargantuan" tier.

| Tier       | Power | Armor |
| ---------- | ----: | ----: |
| Tiny       |    10 |    52 |
| Small      |    12 |    62 |
| Medium     |    14 |    72 |
| Large      |    16 |    82 |
| Huge       |    18 |    92 |
| Gargantuan |    20 |   102 |

The armor values are defined such that any defender can withstand...

- At least 6 hits from an attacker with the same power score as the
  defender's armor.
- At least 3 hits from an attacker with the maximal power score.
