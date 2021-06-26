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

  - Each player starts the match with 4 action points.

  - A player can have up to 10 action points.

  - Unused action points will not carry over to the next turn.

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

  - Healing a character restores part of their lost armor and removes
    all negative effects.

## Cards

  - Each character has four copies of their primary skill card and three
    copies of each of their secondary skill cards.

  - A deck is made by shuffling the card pools of the characters fielded
    in a match.

  - A player can freely use skill cards during their turns for as long
    as they have enough action points to do so.

  - A player will draw a card from their deck at the beginning of each
    of their turns.

  - A player can have up to 7 cards in their hand at time. Drawing a
    card while having a full hand causes the leftmost card in the hand
    to be discarded.

## Defeat

  - A player whose all characters they control are fainted will lose the
    match.

  - A player will lose the match upon trying to draw from an empty deck.

  - A player can also choose to forfeit the match at any time.

## Effects

Effects modify a character’s behavior, lasting until a condition is met.
Applying the same effect multiple times does nothing.

| Name     | Duration   | Type      | Effect                                                                              |
| -------- | ---------- | --------- | ----------------------------------------------------------------------------------- |
| Alacrity | Consumable |           | The character can attack or walk an additional time.                                |
|          |            |           |                                                                                     |
| Fortify  | Consumable | Combat    | Prevents all but one damage point from the next incoming damage instance.           |
| Prowess  | Consumable | Combat    | Maximizes the characters’s power score on their next outgoing damage instance.      |
|          |            |           |                                                                                     |
| Taunt    | Temporary  | Round     | The opponents able to attack the character will automatically do so on their turns. |
|          |            |           |                                                                                     |
| Restrain | Temporary  | Round     | The character can’t attack or walk during their turn.                               |
| Silence  | Temporary  | Round     | The character can’t use skills during their turn.                                   |
|          |            |           |                                                                                     |
| Coldcage | Temporary  | Round     | The cost of using skills, attacking or walking is increased.                        |
| Tailwind | Temporary  | Round     | The cost of using skills, attacking or walking is reduced.                          |
|          |            |           |                                                                                     |
| Burn     | Permanent  | Stackable | The character takes damage at the start of their turns based on their Burn stacks.  |

## Keywords

Used to tie cards with similar abilities together.

| Name      | Effect                                                                      |
| --------- | --------------------------------------------------------------------------- |
| Defiance  | Activate the effect thrice if there’s no other allies, or once otherwise.   |
| Threshold | Activate the effect twice if you’re below half health, or once otherwise.   |
|           |                                                                             |
| Channel   | Activate the effect by consuming the character’s attack action.             |
| Resonance | Activate the effect twice on even turns, or once otherwise.                 |
|           |                                                                             |
| Overheat  | Activate the effect by gaining a Burn stack.                                |
| Tempering | Activate the effect twice by consuming your Burn stacks, or once otherwise. |
|           |                                                                             |
| Delirium  | Activate the effect by reducing your maximum action points by one.          |
| Offering  | Activate the effect by discarding a card.                                   |

## Classes

A character class determines what they can do and how they fare in
combat.

  - Ranged characters can only target units that are exactly two tiles
    away from them. They can move up to three tiles per turn.

  - Melee characters can only target units that are exactly one tile
    away from them. They can move up to five tiles per turn.

Each class confers a talent — an ability that activates before the first
turn if a character of that class is designated as their team’s leader.
Having talents bound to classes — as opposed to characters — should
provide a small disincentive in terms of flexibility when stacking many
characters of the same class in a team.

| Class     | Ranged | Power | Armor | Talent                         |
| --------- | ------ | ----- | ----- | ------------------------------ |
| Marksman  | Yes    | Huge  | Tiny  | Raise the power of all allies. |
| Duelist   | No     | Large | Small | Gain an action point.          |
| Supporter | Yes    | Small | Large | Draw two cards.                |
| Vanguard  | No     | Tiny  | Huge  | Raise the armor of all allies. |

Currently, each faction has access to all but one of the classes,
depending on thematic and mechanic factors. This, however, is subject to
changes.

| Marksman | Duelist | Supporter | Vanguard | Name                                      |
| :------: | :-----: | :-------: | :------: | ----------------------------------------- |
|          |    •    |     •     |    •     | [The Daybreakers](the-daybreakers.md)     |
|    •     |         |     •     |    •     | [The Nightbringers](the-nightbringers.md) |
|    •     |    •    |           |    •     | [The Dollhouse](the-dollhouse.md)         |
|    •     |    •    |     •     |          | [The Wayfarers](the-wayfarers.md)         |

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

The armor value is defined such that a defender can withstand…

  - At least six hits from an attacker with the same power as the
    defender’s armor.
  - At least three hits from an attacker with “Gargantuan” power.
