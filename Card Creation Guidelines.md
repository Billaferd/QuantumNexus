# Card Creation Guidelines for Quantum Nexus

## Introduction

Quantum Nexus is a trading card game that adheres to the following tenants of design.

1. Cards will never cross the table to an opponent's side. Every player will always be in full possession of their cards.

2. No randomness, ever. There will never be any randomness except for the card shuffle. There will never be dice rolls, coin flips, or card flips. The only exception is when the first player is selected through card flips at the start.

3. There are no health points, defense is not a measure of health, and players should not have to bookkeep health on their units.

## General Info

### Battlefield

The battlefield is split into 3x2 field of 6 quadrants. Each row or column of quadrants is referred to as a section.

### Range

Close-range attacks and abilities can only target quadrants directly above and directly to each side. Mid-range abilities and attacks can target the quadrants above and to the sides, bit they can also target the top right and left diagonals. Far-ranged cards can only target one row away. This means that a far-ranged card in the back row can target the opponents front row and if it is in the front row, it can target the opponents back row.

## Card Types

Quantum Nexus features five card types, each with its unique role:

### Unit Cards

These cards represent characters and creatures critical for both offense and defense. Unit cards have Attack and Defense values, as well as a defined Range (close, mid, or far). Units can only be deployed onto the battlefield.

### Leader Cards

Leader cards are power cards that are similar to units. They do get a 50% discount on the costs though, because only 1 of any type is allowed, and only one leader at all is allowed in a single quadrant at a time. Their effects generally affect all units in their quadrant.

### Upgrade Cards

Upgrade cards enhance units and other cards, boosting their capabilities. Upgrade cards also have Attack and Defense values. Upgrade cards can be deployed onto the battlefield or loadout depending on the target of the upgrade.

### Asset Cards

Asset cards provide ongoing effects that influence the battlefield. They have a Defense value to protect them. Asset cards can only be deployed to the loadout. If they interact with a quadrant or section it must be chosen either at deployment or at the beginning of each turn.

### Event Cards

Event cards create temporary effects that last for a single turn, introducing dynamic elements to the game.

### Terrain Cards

Terrain cards grant bonuses to units on the battlefield, altering the strategic landscape. Terrain cards can only be deployed to the battlefield.

## Card Subtypes

All cards have a subtype. Subtypes allow the card's primary type to be more specific. All of the main types share the same subtypes. This will enable players to take in the information since it is familiar.

### Examples

| Subtype | Description |
|---------|-------------|
| Mech | Mechanized Infantry |
| Squad | Soldiers that act as a group |
| Specialist | A soldier who operates independently and has specialized skills |

## Rank

Specify if the card is Terrestrial, Aerial, Orbital, or Interstellar. All cards must have a rank.

Terrestrial cards are any card type that can be deployed into the battlefield and typically have close or mid-range attacks and abilities, although they can have a far range at times as well.

Aerial cards can also be any card type deployed on the battlefield; these cards typically have mid to far-range attacks and abilities and have the flying keyword.

Orbital Cards can be any card type that can be deployed to the loadout and typically affect an entire quadrant at a time on the battlefield.

Interstellar cards can be any card type deployed to the loadout and typically target Orbital type cards or affect entire battlefield sections (Rows or Columns).

## Domain Point Allocation

In Quantum Nexus, cards are allocated Domain Points from four domains: Technology, Magic, Psionics, and Divinity.

- **Total Domain Points**: Each card can have a **maximum of 6 Domain Points** in total.
- **Individual Domain Limit**: No single domain can exceed **4 points**.
- **Balanced Distribution**: Ensure a balanced distribution of points across the domains relevant to the card's theme and abilities.
- **Minimum Allocation**: Cards must allocate at least 1 point to any domain that is mentioned in their attributes, abilities, name, or description.
- **Domain Point Representation**: Domain Points represent the card's proficiency and thematic alignment with the respective domain.

When creating cards, it's important to balance the Domain Points to reflect the card's capabilities and thematic elements without exceeding the maximum allowed points.

### Technology

Technology cards generally attack at a distance; mid and far-range attacks are much more common than close-range attacks. Technology abilities are generally destructive and lack precision most of the time. Technological cards can be precise, but this is not as common as abilities that affect entire quadrants or even battlefield sections. Technology users rely on Aerial, Orbital or Interstellar cards for battlefield dominance. Terrestrial cards, although rare, are generally heavily armoured and mid-ranged.

### Magic

The magic domain primarily deals in the close to mid-range. Far-range is available but not very common. Magic users have powerful, precise abilities that excel at the removal of specific targets. Magic users have issues against large crowds. Terrestrial cards are the most common, but aerial cards are also used. It is scarce for magic users to unleash their orbital or interstellar powers.

### Psionics

Psionics users rely on extremely close range but can also take care of large crowds and single threats. They tend to rely on control of the battlefield and use their opponent's minds against them. Anything other than terrestrial cards is rare.

## Divinity

Divine cards are mostly far-ranged and indirect. They rely on their deities for intervention and excel at inflicting status ailments. They cannot single out specific targets but they can lay waster to large sections of the battlefield.

### CP Assignment

When creating cards for Quantum Nexus, it's crucial to consider the allocation of Domain Points and how they affect the CP (Command Points) assignment. Domain Points represent the card's proficiency in different domains, and they directly impact the CP cost of the card.

1. Allocate Domain Points: Determine how many to allocate to each domain: Technology, Magic, Psionics, and Divinity. These points reflect the card's thematic and mechanical qualities. Keep in mind that each domain point contributes to the CP cost.
2. Determine CP Contribution: Understand that each Domain Point allocated to a card adds to its CP cost. The specific CP contribution for each Domain Point can vary but typically falls within the range of 2 to 4 CP. This contribution reflects the card's specialization in a particular domain. For example, if a card has two domain points it would have somewhere between 4 and 8 CP.
3. The actual point value would be up to the designer, but should fall within the values that are calculated in the step above. If in doubt, simply pick a random number within the range of 2 to 4 and multiply by the total number of domain points.
4. The derived cost must be balanced by the cost for stats and abilities. `Domain Points * modifier = Attack + Defense + Abilities + Range`.

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

### Range

If a card requires a range then the close range value is free or 0, the Mid range value is worth 2 points and the Far range value is worth 4 points.

### Attack and Defense

Attack and defense will cost a rate of about 1 purchase point for every two Attack and/or Defense rounded down. The Attack and Defense values are summed for the purchase calculation Attack+Defense.

### Rule Box Effects

The rule box holds active abilities, passive abilities, interrupts, and mandatory interrupts. The rule box can hold multiples of these but each rule will add to the purchase cost. The purchase cost of the rule box effects and the attack/defense values should be equal to the numeric value of the deployment cost. The total cost of the attack/defense values and all of the rule box effects must be equal to the numeric value of the deployment cost.

## Abilities in Quantum Nexus

Abilities are a key component of Quantum Nexus cards, providing unique actions and effects that can influence the game. Each ability must adhere to the following structure and rules:

#### Active Abilities

Active abilities require a player’s decision to use and often have a cost associated with them, which may include Command Points (CP), discarding a card, skipping a turn, or destroying a card.
The format for active abilities is: Cost[, Cost] - Ability. For example, “3CP - Force an opponent to discard a card” or “2CP, Discard 1 - Deal 3 damage to an enemy in Mid-range.”

The cost of an ability is a balancing tool and can be adjusted to ensure fair play.

#### Passive Abilities

Passive abilities are always in effect and do not require a player’s action or cost to activate. They provide ongoing effects such as buffs, debuffs, or status changes, automatically applied based on the card’s presence or certain conditions. Passive abilities do not involve revealing information or performing actions that would normally require a player's decision or input.

Passive abilities are written as a statement of fact without a cost. For example, “Units in this quadrant gain +1 attack.”

#### Interrupts

Interrupts occur automatically when a specific event or condition is met during the game. These abilities do not require a cost to activate but are not always active like passive abilities. They are written with a trigger condition followed by the effect. For example, “When this unit enters the battlefield, reveal the top card of the opponent's deck.”

Interrupts have a specific pattern that is used to describe who and what triggers it. The interrupt text has four parts:

`[Modifier] Target - Action`

Some examples include `Opposing Unit - Attack` and `Event - Deploy`.

#### Designing Abilities

When designing a card, ensure that the abilities align with these definitions.

- Active abilities should involve a strategic choice and a cost, providing players with opportunities to actively influence the game.
- Passive abilities should offer continuous support or hindrance, enhancing the strategic depth of the game without additional resource expenditure.
- Triggered abilities should create interactions based on game events, adding layers of strategy without the need for player activation.

##### Targets

Targets are the things that can trigger an interrupt.

| Target      | Description                                          |
| ----------- | ---------------------------------------------------- |
| this        | The card that the text is printed on.                |
| Player      | The player that played this card.                    |
| Opponent    | An opposing player                                   |
| Unit        | A unit in play                                       |
| Leader | A leader in play |
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

#### Effects

| Keyword             | Effect                                           | Cost |
| ------------------- | ------------------------------------------------ | ---- |
| **Attack Boost**    | Increases a unit's attack damage.                | 4    |
| **Defense Boost**   | Enhances a unit's defensive capabilities.         | 4    |
| **Speed Boost**     | Accelerates a unit's movement and attacks.       | 5    |
| **Evasion**         | Grants a chance to dodge enemy attacks.          | 4    |
| **Counterattack**   | Enables a unit to retaliate when attacked.       | 4    |
| **Elemental Resistance** | Provides protection against specific elemental damage. | 4    |
| **Status Immunity** | Grants immunity to status effects.               | 4    |
| **Double Attack**   | Allows a unit to attack twice in a turn.         | 5    |
| **Aura of Protection** | Extends buffs to nearby allied units.          | 5    |
| **Barrier**         | Creates a temporary shield that absorbs damage.  | 5    |
| **Invisibility**    | Renders a unit invisible and immune to targeting for a duration. | 6 |
| **Attack Reduction** | Lowers a unit's attack power.                   | 4    |
| **Defense Reduction** | Weakens a unit's defensive capabilities.        | 4    |
| **Silence**         | Prevents the use of abilities or spells.         | 5    |
| **Poison**          | Inflicts damage over time to the affected unit.  | 4    |
| **Stun**            | Temporarily incapacitates a unit, preventing actions. | 5    |
| **Fear**            | Causes a unit to move away from the source of fear. | 5    |
| **Debuff Transfer** | Moves a debuff from one unit to another.         | 6    |
| **Elemental Vulnerability** | Increases damage from specific elemental attacks. | 4    |
| **Disarm**          | Prevents a unit from attacking for a duration.   | 5    |
| **Freeze**          | Immobilizes a unit, rendering it unable to move or act. | 6    |
| **Cursed**          | Inflicts a long-lasting debuff with various negative effects. | 7 |
| **Mind Control**    | Takes control of an enemy unit, making it fight for the controller. | 7 |

## Flavor Attributes

Finally, the card name can be assigned while considering everything that was decided earlier.

A detailed description of the card image needs to be created.

A set of flavour text no longer than 255 characters must also be drafted.

## Synergies

Cards should be cohesive and exhibit some types of synergy.

1. **Theme-Based Synergies**:
   - Consider the theme or lore of your cards and how they can naturally work together. For example, cards with a "mechanical" theme might have synergies that involve repairing or enhancing each other.

2. **Domain Synergies**:
   - Cards from the same domain can have built-in synergies. For instance, technology-based cards could synergize by combining their abilities to create powerful tech combos.

3. **Subtype Synergies**:
   - Subtypes can create natural synergies. Cards with the "Squad" subtype might gain bonuses when played alongside other Squad units, encouraging players to build cohesive teams.

4. **Leader Abilities**:
   - Leader cards often have abilities that benefit specific types of units or domains. Design leader abilities that enhance the strengths of other cards in your deck.

5. **Upgrade Cards**:
   - Create upgrades that can be applied to units or assets, boosting their abilities. Players should be able to strategize which upgrades to use on which cards to maximize their effectiveness.

6. **Event and Terrain Synergies**:
   - Design events and terrain cards that interact with other card types. Events might trigger additional effects when specific units are in play, while terrain cards could grant bonuses to units of a certain domain.

7. **Inter-Domain Synergies**:
   - Encourage cross-domain synergies where cards from different domains work well together. For example, a magic card could enhance the abilities of a technology-based unit, highlighting the interplay between magic and technology.

8. **Ability Combos**:
   - Create cards with abilities that naturally combo with other cards. For instance, one card might have an ability that freezes an opponent, and another card has an ability to shatter frozen units, allowing for a powerful synergy.

9. **Balancing Synergies**:
   - Ensure that synergies are balanced and not overpowered. Synergistic effects should be powerful but not so dominant that they make other strategies obsolete.

10. **Exploration and Discovery**:
    - Allow players to discover synergies through gameplay. Having hidden or unexpected synergies can add an element of strategy and surprise to the game.

11. **Feedback and Testing**:
    - Playtest your cards thoroughly to ensure that the synergies work as intended and don't lead to unbalanced gameplay. Be open to feedback from players to refine your designs.

12. **Variety of Synergies**:
    - Create a variety of synergies, including long-term strategies, short-term combos, and conditional synergies. This diversity keeps gameplay engaging and dynamic.

13. **Communication**:
    - Ensure that synergies are communicated clearly on the cards themselves. Players should be able to understand how different cards work together without ambiguity.

## Example

First, we will select the card type. In this case, it will be a Unit type card. The subtype will be Squad because these nano-bots operate as a group even though they are extremely small. This will appear on the card as `Unit - Squad`.

Second, we determine Domain Points; for this example, we will allocate 1 point to Technology and 1 point to Divinity.

We can select one discipline from technology and divinity each. In this case, we will use Nano-technology and Divine Aura.

We have two total domain points, so we have between 4 and 10 CP available. Let's start at 10 CP for the deployment cost.

For the general feel, we will select the following values:

- Malevolence: Malevolent
- Utility: Neutral
- Impact: Destructive

We will assign 1 defense and 2 attack to the card. This will use 2 CP. We are leaving 5 for the rule box effects.

For the rule box effects, we will assign an interrupt of `this - deploy,` triggering every time this specific unit enters play. This interrupt will cause the player to pick up a card. This equals about 4 CP, with the interrupt type providing a 1x multiplier. That is three CP used so far. For the last three, we will use the `this - discard` interrupt and assign the effect: Opponent discards one card from the top of their deck. This costs about 4 CP.

This will be a close ranged terrestrial unit.

The name of this card will be Blessed Scourge.

The image description will be: A scourge of nano-bots with a divine light radiating out of them.

The flavour text will be: Creeping across the land, the scourge brings us news.
