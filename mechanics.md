# Mechanics

## Preparation

A team must be defined by the player before a match and is composed of
any six characters. At the start of a match, both players will go
through a number of preparation phases.

1.  One of the players will be randomly chosen to be the “starting
    player”. This determines the turn order, the draft order and the
    allocation of the map halves.

2.  In the draft phase, both players will take turns choosing their
    characters and positioning them in the map. No character may be
    chosen twice in a match. The first character to be placed in the
    field by each player is designated as their team’s leader.
    
    The draft order is defined as “O → S → S → O → O → S”, with “S”
    being the starting player and “O” their opponent.

3.  In the draw phase, the player will draw three cards from their deck,
    forming their starting hand.
    
    They may then shuffle any number of cards from their hand back into
    their deck and draw that many cards as replacements.

4.  The match then begins with the starting player’s turn.

## Combat

  - Each player starts with zero action points.

  - A player can have up to 10 action points.

  - A player will have their maximum action points increased by one at
    the beginning of each of their turns.

  - A player will have their action points fully restored at the
    beginning of each of their turns.

  - Once per turn, a character can walk to any tile within their speed
    score in distance by using an action point.

  - Once per turn, a character can perform a basic attack against any
    opponent within their reach by using two action points.

  - Once per turn, a character will perform a counter-attack when an
    opponent within their reach attacks them.

  - Upon being attacked, the defender will take damage equal to the
    power of the attacker.

  - A character whose damage taken surpasses their armor will faint.

## Cards

  - Each character has four copies of their class skill card.

  - Each character has three copies of each of their unique skill cards.

  - A deck is made by shuffling the card pools of the characters fielded
    in a match.

  - A player can freely use skill cards during their turns for as long
    as they have enough action points to do so.

  - A player will draw a card from their deck at the beginning of each
    of their turns.

  - A player can have up to 7 cards in their hand at time. Cards drawn
    while their hand is full are discarded.

## Defeat

  - A player whose all characters they control are fainted will lose the
    match.

  - A player will lose the match upon trying to draw from an empty deck.

  - A player can also choose to forfeit the match at any time.

## Talents

Each character has a talent — a special ability that automatically
activates before the first turn if they are designated as their team’s
leader.

| Name         | Effect                                      |
| ------------ | ------------------------------------------- |
| Copycat      | Copy your opponent’s leader’s talent.       |
| Ingenious    | Gain an action point.                       |
| Inspiring    | Raise the power and armor of all allies.    |
| Intimidating | Lower the power and armor of all opponents. |
| Mnemonic     | Draw two cards.                             |

## Effects

Effects modify a character’s behavior, lasting until a condition is met.
Applying the same effect multiple times does nothing.

| Name       | Effect                                                                                        |
| ---------- | --------------------------------------------------------------------------------------------- |
| Adrenaline | Allows the character to move or attack once without counting towards the turn’s limit.        |
| Amplify    | Supplements the next outgoing damage instance based on the current round.                     |
| Concealed  | Removes the character from combat until your next turn.                                       |
| Fortified  | Prevents all but one damage point from the next incoming damage instance.                     |
| Prowess    | Maximizes the attack score on the next outgoing damage instance.                              |
| Taunt      | Causes all opponents within range to automatically attack the character until your next turn. |

## Keywords

Used to tie cards with similar abilities together, generally defining a
faction mechanic.

| Name      | Effect                                                                              |
| --------- | ----------------------------------------------------------------------------------- |
| Channel   | Activate the specified effect by consuming the character’s attack action.           |
| Echo      | Activate the specified effect twice on even turns, or once otherwise.               |
| Exert     | Activate the specified effect by reducing your maximum action points by one.        |
| Storm     | Activate the specified effect once for each skill with Storm that has been used.    |
| Threshold | Activate the specified effect twice if you’re below half health, or once otherwise. |

## Classes

A character class determines what they can do and how they fare in
combat.

  - Ranged characters can only target units that are exactly two tiles
    away from them. They can move up to three tiles per turn.

  - Melee characters can only target units that are exactly one tile
    away from them. They can move up to five tiles per turn.

| Class   | Ranged | Power | Armor | Basic skill      |
| ------- | ------ | ----- | ----- | ---------------- |
| Caster  | Yes    | Huge  | Tiny  | Gain Amplify.    |
| Ranger  | Yes    | Large | Small | Gain Concealed.  |
| Hunter  | No     | Small | Large | Gain Adrenaline. |
| Fighter | No     | Tiny  | Huge  | Gain Taunt.      |

## Scores

Power and armor scores are split into six tiers. When a skill or a
talent modifies a character’s power or armor, it does so by raising or
lowering them to another tier.

Scores are bounded by the tiers, therefore it is impossible to lower
them below the “Tiny” tier or raise them above the “Gargantuan” tier.

| Tier       | Power | Armor |
| ---------- | ----: | ----: |
| Tiny       |    10 |    52 |
| Small      |    12 |    62 |
| Medium     |    14 |    72 |
| Large      |    16 |    82 |
| Huge       |    18 |    92 |
| Gargantuan |    20 |   102 |

## Factions

| Caster | Ranger | Hunter | Fighter | Keyword   | Name                                      |
| :----: | :----: | :----: | :-----: | --------- | ----------------------------------------- |
|        |   ✓    |   ✓    |    ✓    | Threshold | [The Wind Walkers](the-wind-walkers.md)   |
|   ✓    |        |   ✓    |    ✓    | Channel   | [The Temple Order](the-temple-order.md)   |
|   ✓    |   ✓    |        |    ✓    | Echo      | [The Ivory Tower](the-ivory-tower.md)     |
|   ✓    |   ✓    |   ✓    |         | Exert     | [The Flower Garden](the-flower-garden.md) |
