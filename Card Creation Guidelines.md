# Card Creation Guidelines for Quantum Nexus

## Card Types

Quantum Nexus features five card types, each with its unique role:

### Unit Cards

These cards represent characters and creatures critical for both offence and defence. Unit cards have Attack and Defense values, as well as a defined Range (close, mid, or far).

### Upgrade Cards

Upgrade cards enhance units and other cards, boosting their capabilities. Upgrade cards also have Attack and Defense values.

### Asset Cards

Asset cards provide ongoing effects that influence the battlefield. They have a Defense value to protect them.

### Event Cards

Event cards create temporary effects that last for a single turn, introducing dynamic elements to the game.

### Terrain Cards

Terrain cards grant bonuses to units on the battlefield, altering the strategic landscape.

## Domain Point Allocation

In Quantum Nexus, cards are allocated Domain Points from four domains: Technology, Magic, Psionics, and Divinity. 

Each card can have between 0 and 6 points across these domains, ensuring a balanced distribution with no domain exceeding 4 points.

Domain Points represent how advanced a card is in a particular domain. Cards must allocate at least 1 point to any domain mentioned in their attributes, abilities, name, or description.

## Disciplines

Each domain has several associated disciplines, allowing for diverse card abilities. For each point assigned to a domain, select a relevant discipline within that domain. The total points assigned to chosen disciplines in a domain should not exceed those allocated to that domain.

## Card Feel

Cards in Quantum Nexus are defined using three axes

- Malevolence: Cards can be Neutral, Malevolent (evil-themed), or Benevolent (good-themed).
- Utility: Cards can be Utility-focused (creating order), Neutral, or Disruptive (creating chaos).Combat: Cards can lean towards Offense, Neutrality, or Defense.
- Impact: Cards can be Constructive (focus on creation), Neutral, or Destructive (focus on card removal).

## Functional Attributes

Define a card's attributes, such as rule box effects, Rank, and CP, while considering the Domain Points allocated and the chosen disciplines.

### CP Assignment

When creating cards for Quantum Nexus, it's crucial to consider the allocation of Domain Points and how they affect the CP (Command Points) assignment. Domain Points represent the card's proficiency in different domains, and they directly impact the CP cost of the card.

1. Allocate Domain Points: Determine how many to allocate to each domain: Technology, Magic, Psionics, and Divinity. These points reflect the card's thematic and mechanical qualities. Keep in mind that each domain point contributes to the CP cost.

2. Determine CP Contribution: Understand that each Domain Point allocated to a card adds to its CP cost. The specific CP contribution for each Domain Point can vary but typically falls within the range of 2 to 5 CP. This contribution reflects the card's specialization in a particular domain. For example if a card has 2 domain points it would have somewhere between 4 and 10 CP.

3. The calculated CP will be used as the actual deployment cost for the card.

4. The values assigned to the attack, defense and rule box effects will need to roughly equal the deployment cost.

### Attack and Defense

Attack and defence will use up the calculated CP at a rate of about 1 CP for every two Attack and/or Defense rounded down.

### Rulebox Effects

The rule box holds active abilities, passive abilities, interrupts, and mandatory interrupts. The rule box can hold multiples of these but each rule will subtract from the calculated CP after attack and defense are deducted.

### Rank

Specify if the card is Terrestrial, Aerial, Orbital, or Interstellar.

## Flavor Attributes

Finally, the card name can be assigned while considering everything that was decided earlier.

A detailed description of the card image needs to be created.

A set of flavour text no longer than 255 characters must also be drafted.

## Example

First, we will select the card type. In this case it will be a Unit type card.

Second we determine Domain Points, for this example we will allocate 1 point to Technology and 1 point to Divinity.

We can select one discipline from technology and divinity each. In this case we will use Nano-technology and Divine Aura.

We have two total domain points so that means we have between 4 and 10 CP available. Let's start at 6 CP, for the deployment cost.

For the general feel we will select the following values:

- Malevolence: Malevolent
- Utility: Neutral
- Impact: Destructive

We will assign 1 defence and 2 attack to the card. This will use about 1 CP. We are leaving 5 for the rule box effects.

For the rule pox effects, we will assign an interrupt of `this - deploy,` triggering every time this specific unit enters play. This interrupt will cause the player to pick up a card. This is equal to about 2 CP with the interrupt type providing a 1x multiplier. That is three CP used so far. For the last three we will use the `this - discard` interrupt and assign the effect: Opponent discards one card from the top of their deck. This costs about 3 CP.

This will be a close ranged terrestrial unit.

The name of this card will be Blessed Scourge.

The image description will be: A scourge of nano-bots with a divine light radiating out of them.

The flavour text will be: Creeping across the land, the scourge brings us news.