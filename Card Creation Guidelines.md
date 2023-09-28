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

### CP Assignment

When creating cards for Quantum Nexus, it's crucial to consider the allocation of Domain Points and how they affect the CP (Command Points) assignment. Domain Points represent the card's proficiency in different domains, and they directly impact the CP cost of the card.

1. Allocate Domain Points: Determine how many to allocate to each domain: Technology, Magic, Psionics, and Divinity. These points reflect the card's thematic and mechanical qualities. Keep in mind that each domain point contributes to the CP cost.
2. Determine CP Contribution: Understand that each Domain Point allocated to a card adds to its CP cost. The specific CP contribution for each Domain Point can vary but typically falls within the range of 2 to 5 CP. This contribution reflects the card's specialization in a particular domain. For example if a card has 2 domain points it would have somewhere between 4 and 10 CP.
3. The actual point value would be up to the designer, but should fall within the values that are calculated in the step above. If in doubt, simply pick a random number within the range of 2 to 4 and multiply by the total number of domain points.

## Disciplines

Each domain has several associated disciplines, allowing for diverse card abilities. For each point assigned to a domain, select a relevant discipline within that domain. The total points assigned to chosen disciplines in a domain should not exceed those allocated to that domain. Each domain with a point must have one discipline selected.

### Technology Domain

- Cybernetics: Focusing on advanced mechanical enhancements and robotic units.
- Energy Weapons: Specializing in high-tech energy-based weaponry and tactics.
- Robotics: Emphasizing the use of powerful mechanized units, including mechs.
- Genetics: Manipulating the genetic makeup of units and assets for various effects.

### Magic Domain

- Elemental Magic: Harnessing the powers of fire, water, earth, and air for various effects.
- Enchantment: Enriching units and assets with magical enhancements and buffs.
- Summoning: Conjuring creatures or beings from other realms to fight for you.
- Alchemy: Transforming and transmuting objects and units using mystical concoctions.

### Psionics Domain

- Telekinesis: Controlling objects and units with the power of the mind.
- Mind Control: Dominating the thoughts and actions of enemy units.
- Precognition: Gaining insights into future events for strategic advantage.
- Astral Projection: Sending your consciousness to distant locations for reconnaissance and manipulation.

### Divinity Domain

- Holy Light: Channeling divine energy for healing and purification.
- Divine Wrath: Smiting enemies with powerful, righteous attacks.
- Blessings: Bestowing boons and protections upon allies.
- Divine Intervention: Calling upon higher powers for miraculous effects and divine guidance.

## Card Feel

Cards in Quantum Nexus are defined using three axes

- Malevolence: Cards can be Neutral, Malevolent (evil-themed), or Benevolent (good-themed).
- Utility: Cards can be Utility-focused (creating order), Neutral, or Disruptive (creating chaos).Combat: Cards can lean towards Offense, Neutrality, or Defense.
- Impact: Cards can be Constructive (focus on creation), Neutral, or Destructive (focus on card removal).

## Functional Attributes

Define a card's attributes, such as rule box effects, Rank, and CP, while considering the Domain Points allocated and the chosen disciplines.

### Attack and Defense

Attack and defense will use up the calculated CP at a rate of about 1 CP for every two Attack and/or Defense rounded down. The Attack and Defense values are summed for the CP calculation (Ceiling((Attack+Defense)/2)). The effects and the attack and defense values should calculate to the same as the deployment cost.

### Rulebox Effects

The rule box holds active abilities, passive abilities, interrupts, and mandatory interrupts. The rule box can hold multiples of these but each rule will subtract from the calculated CP after attack and defense are deducted.

#### Abilities

A cards abilities will always have a cost, even if that cost is zero. The ability will always have the form `Cost[, Cost] - Ability`. The cost of an ability can be used to partially balance a card by changing it. Abilities can have compound costs and costs don't strictly have to be CP, discarding a card, skipping a turn, and destroying a card are all valid costs. An example ability text would be `3CP - Force an opponent to discard a card`. A more advanced example with a compound cost would be `2CP, Discard 1 - Deal 3 damage to an enemy in Mid-range`.

#### Interrupts

Interrupts have a specific pattern that is used to describe who and what triggers it. The interrupt text has four parts:

`[Modifier] Target - Action`

Some examples include `Opposing Unit - Attack` and `Event - Deploy`.

##### Targets

Targets are the things that can trigger an interrupt.

| Target      | Description                                          |
| ----------- | ---------------------------------------------------- |
| this        | The card that the text is printed on.                |
| Player      | The player that played this card.                    |
| Opponent    | An opposing player                                   |
| Unit        | A unit in play                                       |
| Event       | An event currently in play                           |
| Terrain     | A terrain card currently in play                     |
| Deck        | One of the players deck of cards                     |
| Asset       | An asset that is currently in play                   |
| Upgrade     | An upgrade currently in play                         |
| Hand        | One of the players hand of cards                     |
| Discard     | One of the players discard piles                     |
| Battlefield | Either the whole battlefield or one of the quadrants |
| Loadout     | One of the players loadouts                          |

##### Modifiers

Modifiers add specificity to the target.

| Modifier | Description                                                  |
| -------- | ------------------------------------------------------------ |
| Opposing | Something that is controlled by an enemy or opposing player. |
| Friendly | Something that is controlled by the player or an ally.       |

##### Actions

| Action    | Description                                      |
| --------- | ------------------------------------------------ |
| Deploy    | When a player is deploying a card                |
| Attack    | When a unit is performing a basic attack         |
| Ability   | When a player activates a card ability           |
| Interrupt | When an interrupt activates                      |
| Discard   | When a card is discarded                         |
| Destroy   | When a card is destroyed by an ability or attack |

### Examples

These are some examples of abilities and base costs associated with them.

#### Abilities

| Passive Ability                                                         | CP Cost (Approx.) |
| ----------------------------------------------------------------------- | ----------------- |
| Enhanced Attack (e.g., +1 Attack)                                       | 2 CP              |
| Enhanced Defense (e.g., +1 Defense)                                     | 2 CP              |
| Enhanced Range (e.g., +1 Range for ranged units)                        | 3 CP              |
| Card Draw (e.g., Draw 1 card at the start of your turn)                 | 4 CP              |
| Resource Generation (e.g., Gain 1 CP at the start of your turn)         | 3 CP              |
| Damage Reduction (e.g., Reduce incoming damage by 1)                    | 4 CP              |
| Status Effect Immunity (e.g., Immune to poison, stun, etc.)             | 5 CP              |
| Retaliation (e.g., Deal 1 damage to attackers)                          | 4 CP              |
| Bonus Damage (e.g., +1 damage to specific types of units)               | 3 CP              |
| Resource Cost Reduction (e.g., Reduce CP cost of abilities by 1)        | 5 CP              |
| Critical Hit Bonus (e.g., Deal double damage on critical hits)          | 6 CP              |
| Debuff Infliction (e.g., Apply a debuff on hit)                         | 4 CP              |
| Buff Dispelling (e.g., Remove one enemy buff at the start of your turn) | 6 CP              |
| Terrain Interaction (e.g., Gain bonuses from specific terrains)         | 4 CP              |

### Rank

Specify if the card is Terrestrial, Aerial, Orbital, or Interstellar.

Terrestrial cards are any card type that can be deployed into the battlefield and typically have close or mid-range attacks and abilities, although they can have a far range at times as well.

Aerial cards can also be any card type deployed on the battlefield; these cards typically have mid to far-range attacks and abilities and have the flying keyword.

Orbital Cards can be any card type that can be deployed to the loadout and typically affect an entire quadrant at a time on the battlefield.

Interstellar cards can be any card type deployed to the loadout and typically target Orbital type cards or affect entire battlefield sections (Rows or Columns).

## Flavor Attributes

Finally, the card name can be assigned while considering everything that was decided earlier.

A detailed description of the card image needs to be created.

A set of flavour text no longer than 255 characters must also be drafted.

## Example

First, we will select the card type. In this case, it will be a Unit type card.

Second, we determine Domain Points; for this example, we will allocate 1 point to Technology and 1 point to Divinity.

We can select one discipline from technology and divinity each. In this case, we will use Nano-technology and Divine Aura.

We have two total domain points, so we have between 4 and 10 CP available. Let's start at 6 CP for the deployment cost.

For the general feel, we will select the following values:

- Malevolence: Malevolent
- Utility: Neutral
- Impact: Destructive

We will assign 1 defence and 2 attack to the card. This will use about 1 CP. We are leaving 5 for the rule box effects.

For the rule pox effects, we will assign an interrupt of `this - deploy,` triggering every time this specific unit enters play. This interrupt will cause the player to pick up a card. This equals about 2 CP, with the interrupt type providing a 1x multiplier. That is three CP used so far. For the last three, we will use the `this - discard` interrupt and assign the effect: Opponent discards one card from the top of their deck. This costs about 3 CP.

This will be a close ranged terrestrial unit.

The name of this card will be Blessed Scourge.

The image description will be: A scourge of nano-bots with a divine light radiating out of them.

The flavour text will be: Creeping across the land, the scourge brings us news.
