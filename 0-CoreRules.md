# 0 Tragedy Rules

## 0.0 Interpretting Rules
* **0.0.1** The rules of Tragedy provide the framework for how to use cards from other games in Tragedy, and so Tragedy rules take precedence.
* **0.0.2** When two Tragedy rules conflict, the rule with the earlier decimal outline numbering takes precedence.  If the later rule is exceptional, it instead takes precedence.  A rule is exceptional if it describes an exception or a conditional where a new rule implies instead of the base rule.
* **0.0.3** When two rule elements have the same name, they are the same rule element unless specified otherwise.
* **0.0.4** The base rules of a game apply to cards of that game, except when in conflict with the Tragedy rules.
* **0.0.5** Compatibility rules are lower precedence than the lower precedence of the two rules sets being made compatible.

## 0.1 Base Rules
* **0.1.1** Each player has a Deck of at least 40 cards of the same size.  
* **0.1.2** Each player starts with a Hand of seven cards drawn from the Deck.
* **0.1.3** The first player is determined randomly.  Play begins with the first player's turn and proceeds counterclockwise.
* **0.1.4** The player who is taking their turn is the active player.
* **0.1.5** Each player has each of the Zones listed in 0.3.
* **0.1.6** Each player starts with 0 Audience Favor.  When a player reaches 1000 Audience Favor, that player wins.

## 0.2 Cards
* **0.2.1** When in the Hand, a card may be eligible for one or more Roles.
* **0.2.2** When played, a card is played as a single Role chosen by the player from its eligible Roles.  The card becomes an Act in the Stack. If the chosen Role was not Act, it becomes the chosen Role in the appropriate Zone when resolved.  When playing a card is described as playing a Role, it means to play the card and select that Role.
* **0.2.3** Each card has properties.  A card may have different properties depending on its zone or any other game conditions.
* **0.2.4** Being tapped is a property of a card.  A card that is tapped cannot get tapped again until it is untapped.
* **0.2.5** Each card has a Value.  Value is a property of a card.
* **0.2.6** When a card is attached to another card, it is placed behind that card and is in the same Zone.  When a card is moved to another Zone, any cards that were attached become unattached.
* **0.2.7** A player controls a card that is in one of that player's Zones.

## 0.3 Zones
#### Deck
* **0.3.1** The Deck is a Zone.
    * **0.3.1.1** When a card is drawn, it is moved from the Deck to the Hand.
    * **0.3.1.2** When there are no cards in the Deck, and a card should be drawn, the Discard is shuffled and becomes the Deck, then the card is drawn.
    * **0.3.1.3** Except when there are no cards in the Deck or the Discard and a card should be drawn, the draw is skipped.
#### Hand
* **0.3.2** The Hand is a Zone.
    * **0.3.2.1** A card can only be played while it is in the Hand.
#### Actor Tableau
* **0.3.3** The Actor Tableau is a Zone.
    * **0.3.3.1** When a card is an Actor or Prop, it is in the Actor Tableau.
    * **0.3.3.2** A card in the Actor Tableau is in play.
#### Set Tableau
* **0.3.4** The Set Tableau is a Zone.
    * **0.3.4.1** When a card is a Set or a Set Piece, it is in the Set Tableau.
    * **0.3.4.2** A card in the Set Tableau is in play.
#### Discard
* 0.3.5 The Discard is a Zone.
    * **0.3.5.1** When a card is discarded, it is moved from the Hand to the Discard.
    * **0.3.5.2** When a card must be discarded, but the Hand is empty, the discard is skipped.
    * **0.3.5.3** When a card is removed from play, it is moved from the Zone it is in to the Discard.
#### Stack
* **0.3.6** The Stack is a Zone.
    * **0.3.6.1** When a card is played, it becomes an Act in the Stack.
    * **0.3.6.2** When an Act or Acts are on the Stack, each time each player has had priority in sequence without adding an Act to the Stack, the latest Act to have been added to the Stack is resolved.
    * **0.3.6.3** When an Act is resolved from the Stack, it may have some effect, then it is removed from the Stack.  If the effect does not include it being moved to another Zone, it is removed from play.
    * **0.3.6.4** When an Act is added or removed from the Stack, players get priority.

## 0.4 Roles
#### Actor
* **0.4.1** Actor is a Role.
    * **0.4.1.1** An Actor can only be played during the Enter Stage Phase while the Stack is empty.
#### Set
* **0.4.2** Set is a Role.
    * **0.4.2.1** A Set can only be played during the Enter Stage Phase while the Stack is empty.
#### Prop
* **0.4.3** Prop is a Role.
    * **0.4.3.1** A Prop can only be played during the Enter Stage Phase while the Stack is empty.
    * **0.4.3.2** A Prop must be attached to an Actor.  Which Actor it will be attached to is chosen when it is played.  An Actor can only have one Prop attached to it.  If a Prop is not attached to an Actor, it is removed from play.
#### Set Piece
* **0.4.4** Set Piece is a Role.
    * **0.4.4.1** A Set Piece can only be played during the Enter Stage Phase while the Stack is empty.
    * **0.4.3.2** A Set Piece must be attached to a Set.  Which Set it will be attached to is chosen when it is played.  A Set can only have one Set Piece attached to it.  If a Set Piece is not attached to a Set, it is removed from play.
#### Act
* **0.4.5** Act is a Role.

## 0.5 Turn Structure
#### Priority
* **0.5.1** Priority describes which player may choose first when players are able to make game choices.  When no player has priority, the game progresses through the Phases and Steps in listed order.
    * **0.5.1.1** When players get priority, the active player gains priority and each other player gains priority in counterclockwise order.
    * **0.5.1.2** If players get priority while a player already has priority, instead the player who has priority gains priority.
    * **0.5.1.3** A card can only be played by a player who has priority.
#### Before Performance
* **0.5.2** Before Performance is a Phase.
    * **0.5.2.1** The Untap Step is a Step. During the Untap Step, the active player untaps each tapped card he controls.
    * **0.5.2.2** The Upkeep Step is a Step. During the Upkeep Step, players get priority.
    * **0.5.2.3** The Draw Step is a Step.  During the Draw Step, the active player draws a card.
#### Performance
* **0.5.3** Performance is a Phase.
    * **0.5.3.1** During Performance, the active player gets priority.
    * **0.5.3.2** Once during each Performance, the active player may score.  A player can only score when he has priority.  To score, the player must tap one Actor he controls and one Set he controls, along with any attached Props and Set Pieces.  The Value of the Actor is added to the Value of the Props.  The Value of the Set is added to the Value of the Set Pieces.  The sums are multiplied together.  The product is added to the players Audience Favor.
#### After Performance
* **0.5.4** After Performance is a Phase.
    * **0.5.4.1** During the After Performance Phase, players get priority.
#### Enter Stage
* **0.5.4** Enter Stage is a Phase.
    * **0.5.4.1** During the Enter Stage Phase, players get priority.
#### End Scene
* **0.5.4** End Scene is a Phase.
    * **0.5.4.1** During the End Scene Phase, players get priority.