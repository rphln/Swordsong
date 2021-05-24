# Mechanics

## Teams

A team must be defined by the player before a match and is composed of
the six characters from two distinct parties.

## Preparation

At the start of a match, both players will go through a number of
preparatory phases.

1.  One of the players will be randomly chosen to be the “starting
    player”. This to determines the turn order, the draft order and the
    allocation of the map halves.

2.  In the draft phase, both players will take turns choosing their
    characters and positioning them in the map. No character may be
    chosen twice in a match.
    
    The draft order is defined as “O → S → S → O → O → S”, with “S”
    being the starting player and “O” their opponent.

3.  In the draw phase, the player will draw three cards from their deck,
    forming their starting hand.
    
    They may then shuffle any number of cards from their hand back into
    their deck and draw that many cards as replacements.

4.  After those phases, the match begins with the starting player’s
    turn.

## Combat

  - Once per turn, a character can walk to any tile within their speed
    score in distance.

  - Once per turn, a character can perform a basic attack against any
    opponent within their reach.

  - Once per turn, a character can perform a counter-attack when an
    opponent within their reach attacks them.

  - Each character receives an attack action and a movement action
    during each turn.

  - Upon being attacked, the defender will take damage equal to the
    power of the attacker.

  - A character whose damage taken surpasses their armor will be removed
    from the match as fainted.

## Action points

  - Each player starts with zero action points.

  - A player can have up to 10 action points.

  - A player will have their maximum action points increased by one at
    the beginning of each of their turns.

  - A player will have their action points fully restored at the
    beginning of each of their turns.

  - Action points are used exclusively for using skill cards.

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

Each character has a talent – a passive ability that activates under
certain circumstances.

  - Some talents activate as the character is deployed.

| Name      | Effect                                |
| --------- | ------------------------------------- |
| Ingenious | Gain an action point.                 |
| Mimicry   | Copy a talent from a random opponent. |
| Mnemonic  | Draw a card.                          |

  - Some talents activate as the character starts their turn.

| Name         | Effect                              |
| ------------ | ----------------------------------- |
| Forecast     | Raise your Storm counter.           |
| Adaptability | Alternate between ranged and melee. |

  - Some talents stay active for as long as the character stays
    unfainted.

| Name       | Effect                                      |
| ---------- | ------------------------------------------- |
| Intimidate | Lower the power and armor of all opponents. |
| Leadership | Raise the power and armor of all allies.    |

  - Some talents activate when the character faints.

| Name      | Effect                              |
| --------- | ----------------------------------- |
| Steadfast | Return to combat on your next turn. |

## Effects

Effects modify the behaviour of a character, lasting until some
condition is met. Applying the same effect multiple times does nothing.

| Name       | Effect                                                                                                      |
| ---------- | ----------------------------------------------------------------------------------------------------------- |
| Aggression | Until the start of your next turn, opponents able to attack you will do so at the beginning of their turns. |
| Concealed  | Until the start of your next turn or until you attack, opponents can’t target you.                          |
| Amplify    | Consume this effect to deal additional damage based on the current turn.                                    |
| Adrenaline | Consume this effect to move or attack without counting towards the turn’s limit.                            |
| Prowess    | Consume this effect to sharply increase your power on your next attack.                                     |
| Fortified  | Consume this effect to reduce the power of the next attack made against you to one.                         |
| Restrained | Until the start of your next turn, you can’t move or attack.                                                |

## Keywords

Used to tie cards with similar abilities together, generally defining a
party mechanic.

| Name      | Effect                                                                           |
| --------- | -------------------------------------------------------------------------------- |
| Storm     | Activate the specified effect once for each skill with Storm that has been used. |
| Channel   | Activate the specified effect unless you have Restrained, then gain Restrained.  |
| Exert     | Activate the specified effect by reducing your maximum action points by one.     |
| Threshold | Activate the specified effect twice if you’re below half health.                 |

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
| Fighter | No     | Tiny  | Huge  | Gain Aggression. |

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
