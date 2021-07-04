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
    or more than the equivalent of “Gargantuan” damage in points.

  - A character is “critically wounded” if their remaining armor is at
    or below a third of its total amount.

  - A character whose damage taken surpasses their armor will faint.

  - Healing a character restores part of their lost armor.

## Turns

This section describes what the envisioned combat flow currently looks
like.

  - Turns 1–5 — Action points are used primarily for positioning.
    Correctly placing and moving a character should allow a player to
    attain the first strike.

  - Turns 5–10 — All characters are in place. Characters are taken down
    one by one rather than dilluting damage. The majority of matches
    should end in this phase.

  - Turns 10– — An abundance of action points allows for explosive turns
    to break the stalemate.

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

  - A player whose all characters they control are fainted will lose the
    match.

  - A player will lose the match upon trying to draw from an empty deck.

  - A player can also choose to forfeit the match at any time.

## Effects

  - Effects are temporary character behaviour modifiers.

  - The duration of “Timed” effects is reduced at the end of the
    affected characters’ turns.

  - The duration of “Consumable” effects is reduced when a activation
    condition is met.

  - Applying an effect multiple times extends its duration or increases
    its stacks.

  - The primary source of effects are skills.

  - Effects may also be applied by the map itself under special
    circumstances.

| Name     | Type       | Effect                                                                       |
| -------- | ---------- | ---------------------------------------------------------------------------- |
| Ignite   | Permanent  | Damage the character at the end of their turns based on their Ignite stacks. |
|          |            |                                                                              |
| Glaciate | Timed      | The cost of using skills, attacking or walking is increased.                 |
| Tailwind | Timed      | The cost of using skills, attacking or walking is reduced.                   |
|          |            |                                                                              |
| Restrain | Timed      | The character is unable to attack or walk.                                   |
| Silence  | Timed      | The character is unable to use skills.                                       |
|          |            |                                                                              |
| Fortify  | Consumable | Minimize the damage dealt by the next incoming damage instance.              |
| Prowess  | Consumable | Maximize the damage dealt by the next outgoing damage instance.              |

## Keywords

Used to tie cards with similar abilities together.

| Name        | Effect                                                                          |
| ----------- | ------------------------------------------------------------------------------- |
| Bounty      | Activate the effect twice if the opponent leader is fainted, or once otherwise. |
| Resonance   | Activate the effect twice on even turns, or once otherwise.                     |
|             |                                                                                 |
| Defiance    | Activate the effect thrice if critically wounded, or once otherwise.            |
|             |                                                                                 |
| Channel     | Activate the effect by consuming the character’s attack action.                 |
| Delirium    | Activate the effect by reducing your maximum action points by one.              |
|             |                                                                                 |
| Inspiration | Randomly raise your power or armor for each character affected by the effect.   |

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

| Class     | Ranged | Power  | Armor  | Talent                         |
| --------- | ------ | ------ | ------ | ------------------------------ |
| Marksman  | Yes    | Large  | Tiny   | Raise the power of all allies. |
| Duelist   | No     | Medium | Small  | Gain an action point.          |
| Enchanter | Yes    | Small  | Medium | Draw two cards.                |
| Vanguard  | No     | Tiny   | Large  | Raise the armor of all allies. |

Currently, each faction has access to all but one of the classes,
depending on thematic and mechanic factors. This, however, is subject to
changes.

| Enchanter | Duelist | Specialist | Vanguard | Name                                      |
| :-------: | :-----: | :--------: | :------: | ----------------------------------------- |
|           |    •    |     •      |          | [The Ivory Tower](the-ivory-tower.md)     |
|     •     |         |     •      |    •     | [The Fairy Kingdom](the-fairy-kingdom.md) |
|     •     |    •    |            |    •     | [The Temple Order](the-temple-order.md)   |

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
