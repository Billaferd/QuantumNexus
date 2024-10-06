# Quantum Nexus Card Creation Guidelines: In-Depth Guide

## I. Introduction

Quantum Nexus is a strategic trading card game (TCG) that immerses players in a captivating sci-fi universe filled with advanced technology, mystical magic, potent psionics, and divine intervention. To contribute to this dynamic world, card creators must adhere to a set of core design principles and understand the fundamental building blocks of card creation.

### A. Core Design Principles

 * Card Control: Each player retains complete ownership and control of their cards throughout the game. Players are not allowed to touch any other players cards and a players cards are not allowed to leave that players play area.
 * Predictable Gameplay: The only random element in Quantum Nexus is the initial card shuffle. This design choice eliminates luck-based mechanics like dice rolls, coin flips, or random card draws, ensuring that strategic decision-making and tactical planning are the primary factors that determine the outcome of battles.
 * Streamlined Combat: Units in Quantum Nexus do not have health points. Instead, their resilience is represented by a Defense value. When a unit is attacked, its Defense is compared directly to the attacker's Attack value. If the Attack exceeds the Defense, the defending unit is discarded. This streamlined system simplifies combat, reduces bookkeeping, and accelerates gameplay.

## II. Battlefield and Tactical Maneuvers

Understanding the battlefield and the mechanics of card range is crucial for effective card design.

 * A. Battlefield Structure: The Quantum Nexus battlefield consists of two separate 3x2 grids, one for each player. Each grid has six distinct quadrants where units can be deployed. The two front rows of opposing grids are considered adjacent for targeting purposes, but units never physically enter the opponent's play area.
 * B. Range Types: Each terrestrial and aerial unit card has a defined range that dictates which quadrants it can attack or affect with its abilities:
   * Close Range: Units can only target adjacent quadrants on their own side of the battlefield.
   * Mid Range: Units can target adjacent and diagonal quadrants on their own side, as well as any quadrant in the opponent's front row.
   * Far Range: Units can only target quadrants that are 2 rows away from its current position. If a unit is in the back row, it can only attack the enemies front row, if the unit is in the front row, it can attack the enemies back row. This range system adds a layer of tactical depth to the game, forcing players to carefully consider unit placement and movement to maximize their offensive and defensive capabilities.
 * C. Movement: Every terrestrial and aerial unit may choose to attack or move during the Combat Phase, it can move to any adjacent quadrant, but not diagonally.
 * D. Card Ranks: Each Card has one of 4 ranks, terrestrial, aerial, orbital, and interstellar. Terrestrial and aerial units are deployed to the battle field. Orbital and Interstellar units are deployed to the Load out. Events and Upgrades do not have a rank.
 * E. Turn Sequence: Each turn has four phases: Ready, Deployment, Command, and Battle.
  1. The Ready Phase sets the stage for your turn. CP resets, players draw cards, units deactivate.
  2. During the Deployment Phase, players play their units, upgrades, and other permanent cards from their hand.
  3. In the Command Phase, you activate abilities or deploy Events.
  4. The Battle Phase is where you declare attacks against opponent units.
  5. The players alternate turns during each phase. The phase ends when both players pass.
  6. The player who spent the least amount of CP in the previous phase goes first in the next phase.

## III. Card Types and Subtypes

Quantum Nexus features a diverse range of card types, each playing a unique role in shaping your strategies:

 * A. Card Types:
   * Units: The heart of your army, these cards represent characters or creatures that battle on the battlefield. Units possess Attack and Defense values, as well as a defined range (close, mid, or far). Units are deployed to the Battlefield, and must be either Terrestrial or Aerial rank.
     a. Leaders: These are special, powerful units with enhanced abilities and a significant impact on the battlefield. Due to their strength, only one Leader can be present in a single quadrant at a time. Additionally, each deck is limited to a maximum of 25 CP worth of Leader cards.
   * Upgrades: These cards modify other cards (usually units), boosting their stats or granting them additional abilities. Upgrades can be played on units in the battlefield or on other cards in your loadout, depending on their specific effects. Upgrades must declare the type that they augment.
   * Assets: These cards provide ongoing benefits or strategic advantages. They reside in your loadout and are not directly involved in combat, but their effects can significantly influence the course of the game. Assets are either Orbital or Interstellar rank.
   * Events: These powerful cards trigger immediate effects, such as manipulating the battlefield, or drawing additional cards. Events are played during the Command Phase and are discarded afterward. They do not have Passive abilities, but can have both Active Abilities (With no CP Activation Cost, but can have other activation costs) and Interrupts.
   * Terrain: These cards alter the battlefield itself, granting bonuses to specific units or imposing restrictions on enemy movement or abilities. Terrain cards are played on specific quadrants and remain in play until removed.
 * B. Subtypes: In addition to their main type, all cards have a subtype. Subtypes add further specificity to a card's identity and often interact with card abilities or effects. Examples of subtypes include "Mech," "Squad," and "Specialist."

## IV. Domain System

In Quantum Nexus, each card is intrinsically linked to one or more of four key domains: Technology, Magic, Psionics, and Divinity. These domains represent the fundamental forces and energies that shape the game's universe, and they play a crucial role in defining the abilities and capabilities of each card. 

### A. Domain Points (DP)

Domain Points are numerical values assigned to each card, indicating its affinity and mastery of specific domains. They influence a card's power level, abilities, and cost.The total Domain Points (DP) of a card is equal to the sum of points assigned to each domain.

* Domain Points form the basis of a cards cost, the Base CP of a card is calculated by multiplying the Domain Points used by 2. 
* Allocation Rules:
  * Total DP: Each card can have a maximum of 6 Domain Points in total.
  * Domain Limit: Each individual domain (Technology, Magic, Psionics, Divinity) can have a maximum of 4 points allocated to it.
  * Minimum Allocation: A card must have at least 1 point in a domain if that domain is mentioned in the card's name, subtype, flavor text, or abilities.
  * Balanced Distribution: Strive for a balanced distribution of points across relevant domains to ensure thematic consistency and avoid overly specialized cards.
  * Minimum 1 DP: Each card must have at least one Domain Point to ensure its connection to the game's core mechanics.
* Powerful Units: The more DP a card has, the more powerful a card inherently is. Strive for a mix of low medium and high DP cards.
  * Card Theme: The theme of the card is defined by the domain points. As the domain points increase in a specific domain the card should exhibit more powerful abilities in that domain. 1 DP is basic usage, 2 DP is intermediate usage, 3 DP is Advanced usage, and 4 points is a Mastery in that domain.
  * CP Cost Calculation: The Command Point (CP) cost of a card is directly influenced by its Domain Points. The Calculations is detailed in the Appendix.
   
### B. Domain Characteristics

Each domain possesses unique characteristics that shape the cards associated with it. Domain points drive the theme of the card.

* Technology: Wields an arsenal of ranged weaponry, devastating area-of-effect attacks, and sophisticated battlefield control systems. Technological prowess enables strategic dominance through calculated strikes and tactical maneuvers. However, close-quarters combat and opponents capable of bypassing or exploiting technological vulnerabilities pose significant challenges.
* Magic: Offers unparalleled versatility, precise unit targeting, and arcane spellcasting for close-to-mid-range engagements. Magical prowess allows for devastating offensive and defensive spells, empowering wielders to manipulate the battlefield to their advantage. However, overwhelming numbers or adversaries resistant to magical energies may prove difficult to overcome.
* Psionics: Masters of the mind, employing telekinetic manipulation and potent psychic abilities to dominate close-range encounters. Psionic prowess grants unmatched control over the battlefield, bending both allies and enemies to the wielder's will. However, opponents capable of resisting or nullifying mental influence pose a significant threat.
* Divinity: Commands divine blessings, holy/unholy powers, and celestial/infernal intervention, impacting the battlefield on a grand scale. Divine prowess allows for miraculous feats, righteous judgment, and otherworldly manifestations. However, the fickle nature of divine forces, potential sacrifices, and specific conditions for wielding such power introduce an element of unpredictability. (Encompasses all deities, celestial, infernal, etc.)

### C. Disciplines

Each domain is further divided into specific disciplines, allowing for greater specialization within each domain. For each Domain Point allocated to a card, you must select one relevant discipline from that domain.
  
* Technology:
  * Cybernetics: Biomechanics, Neural Interfaces, AI Integration, Augmentation, Prosthetics, Sensory Enhancement, Brain-Computer Interfaces
  * Energy Weapons: Lasers, Particle Beams, Plasma Cannons, Sonic Disruptors, Railguns, Coilguns, Graviton Weapons
  * Robotics: Autonomous Drones, Industrial Automatons, Mechs, Androids, Nanobots, Swarm Robotics, Synthetic Organisms, Cybernetic Organisms
  * Genetics: Bioengineering, Cloning, Gene Therapy, Chimera Creation, Genetic Modification, Designer Babies, Eugenics, Biological Weapons
* Magic:
  * Elemental Magic: Pyromancy, Hydromancy, Aeromancy, Geomancy, Cryomancy, Electrokinesis, Umbrakinesis, Photokinesis
  * Enchantment: Warding, Curses, Illusions, Charms, Hexes, Jinxes, Glamours, Compulsions
  * Summoning: Conjuration, Necromancy, Demonology, Celestial Beings, Spirit Animals, Familiars, Elementals, Ethereal Entities
  * Alchemy: Transmutation, Potion Brewing, Homunculus Creation, Philosopher's Stone, Elixir of Life, Panacea, Transfiguration, Quintessence
* Psionics:
  * Telekinesis: Object Manipulation, Pyrokinesis, Cryokinesis, Electrokinesis, Teleportation, Levitation, Force Fields, Matter Manipulation
  * Mind Control: Illusion Casting, Suggestion, Domination, Psychic Assault, Mind Reading, Memory Manipulation, Empathy, Telepathy
  * Precognition: Clairvoyance, Divination, Prophecy, Retrocognition, Future Sight, Premonition, Omen Reading, Augury
  * Astral Projection: Out-of-Body Experiences, Dream Walking, Spirit Communication, Plane Shifting, Remote Viewing, Possession, Ethereal Travel, Soul Projection
* Divinity:
  * Divine/Unholy Power: Healing/Harm, Exorcism/Corruption, Sanctification/Desecration, Protection/Curses, Blessing/Blighting, Smiting, Resurrection/Necromancy
  * Divine Wrath/Infernal Rage: Smiting, Banishment, Retribution, Divine Judgment, Heavenly Fire, Infernal Torment, Soul Imprisonment, Damnation
  * Blessings/Curses: Augmentation/Corruption, Fortune/Misfortune, Fertility/Sterility, Resurrection/Necromancy, Divine Favor/Disfavor, Miraculous Healing/Disease, Prosperity/Poverty, Life/Death
  * Divine/Infernal Intervention: Miracles/Chaos, Oracles/False Prophecies, Guidance/Temptation, Fate Manipulation, Angelic/Demonic Aid, Divine Inspiration/Corruption, Prophetic Visions/Nightmares, Heavenly/Hellish Portals

### D. Domain Point Allocation Example

Let's create a high-tech battle mech with psionic capabilities:

Technology: 3 DP (Primary domain)
Robotics: 2 DP
Energy Weapons: 1 DP

Psionics: 1 DP
Mind Control: 1 DP

This allocation reflects a primarily technological unit with a minor psionic element, totaling 4 DP.

## V. Card Feel and Attributes

Every card in Quantum Nexus should have a unique personality and impact on the game. Defining the card feel helps establish its role and how it contributes to the overall gameplay experience.

### A. Card Feel Axes

* Malevolence: This axis describes the card's moral alignment.
  * Neutral: Neither good nor evil, focused on achieving objectives through any means necessary.
  * Malevolent: Embraces dark powers, destructive tactics, and manipulation.
  * Benevolent: Upholds virtues, utilizes protective abilities, and focuses on healing or support.
* Utility: This axis indicates the card's strategic purpose.
  * Utility-focused: Creates order on the battlefield, disrupts enemy strategies, or provides tactical advantages.
  * Neutral: Possesses a balanced mix of utility and raw power.
  * Disruptive: Specializes in disrupting enemy plans, causing chaos, or creating unexpected situations.
* Combat: This axis reflects the card's role in battle.
  * Offense: Aggressive, focused on dealing eliminating enemy units.
  * Neutral: Balanced between offense and defense, adaptable to different situations.
  * Defense: Resilient, focused on protecting allies, and stalling enemy advances.
* Impact: This axis describes the card's overall effect on the game state.
  * Constructive: Creates new units, strengthens allies, or generates resources.
  * Neutral: Primarily focuses on direct interaction with enemy units or assets.
  * Destructive: Specializes in removing enemy units, destroying assets, or disrupting enemy plans.

#### Translating Card Feel into Mechanics

Card feel is an important part of Quantum Nexus and needs to be integrated into the creation of each card. 

##### 1. Malevolence

*   **Benevolent:**
    *   **Abilities:** Focus on healing, protection (e.g., granting shields or defensive buffs), unit enhancement, resource generation for the player, or effects that benefit both players.
    *   **Stats:** Could have balanced or even defensively-oriented stats, emphasizing resilience over aggression.
    *   **Keywords:** "Defender" (must be attacked if able), "Lifelink" (player gains CP equal to damage dealt by this unit), "Regeneration" (restores Defense at the start of the turn).
*   **Malevolent:**
    *   **Abilities:** Emphasize direct damage, unit destruction, opponent resource denial, forcing discards, negative status effects, or control over opponent's units/actions.
    *   **Stats:** Might favor high Attack over Defense, reflecting an aggressive nature. 
    *   **Keywords:** "Berserk" (gains Attack when damaged), "Life Drain" (player gains CP equal to damage dealt), "Poison" (deals damage over time).
*   **Neutral:**
    *   **Abilities:**  Offer a mix of beneficial and detrimental effects, focused on achieving objectives regardless of moral alignment.
    *   **Stats:**  Could be balanced or specialized depending on the card's role.
    *   **Keywords:** Adapt keywords from either Benevolent or Malevolent categories to fit the specific card's function.

##### 2. Utility

*   **Utility-Focused:**
    *   **Abilities:** Centered around card draw, battlefield manipulation (e.g., moving units, returning units to hand), resource acceleration, or disrupting opponent's plans through counterplay or denial.
    *   **Stats:** Might be less important than abilities for this category, potentially having lower stats to compensate for strong utility.
    *   **Keywords:**  "Scout" (reveal cards from the opponent's deck), "Teleport" (move to another quadrant), "Phase Shift" (cannot be targeted).
*   **Disruptive:**
    *   **Abilities:**  Focus on disrupting opponent's strategies, forcing suboptimal plays, or creating chaos. Examples include discarding cards from the opponent's hand, negating abilities, or introducing random elements.
    *   **Stats:**  Similar to Utility-Focused, stats might be secondary to disruptive effects.
    *   **Keywords:**  "Chaos" (randomizes targets or effects), "Silence" (prevents abilities from activating).
*   **Neutral:**
    *   **Abilities:**  Offer a balance between direct power and strategic utility.
    *   **Stats:**  Could have a mix of stats, adaptable to various situations.
    *   **Keywords:** Can use keywords from either Utility-Focused or Disruptive categories, depending on the card's design.

##### 3. Combat

*   **Offensive:**
    *   **Abilities:** Prioritize dealing damage, destroying units, or enhancing attack capabilities.
    *   **Stats:** Typically have high Attack values, possibly at the expense of Defense. 
    *   **Keywords:** "Double Strike" (attacks twice), "First Strike" (attacks before the defender), "Pierce" (ignores some Defense).
*   **Defensive:**
    *   **Abilities:**  Focus on protecting themselves or other units, mitigating damage, or hindering enemy attacks.
    *   **Stats:** Usually have high Defense, potentially with lower Attack.
    *   **Keywords:**  "Provoke" (forces enemies to attack this unit), "Shield" (absorbs damage), "Guardian" (protects adjacent units). 
*   **Neutral:**
    *   **Abilities:**  Have a mix of offensive and defensive capabilities or abilities that adapt to the situation. 
    *   **Stats:**  Balanced or specialized stats depending on the intended role.
    *   **Keywords:** Could use keywords from either Offensive or Defensive categories as appropriate.

##### 4. Impact

*   **Constructive:**
    *   **Abilities:**  Generate resources (e.g., CP), create new units (e.g., tokens), buff allies, heal, or otherwise contribute to a positive game state.
    *   **Stats:**  Stats could be secondary to the card's constructive effects.
    *   **Keywords:**  "Inspire" (grants buffs to allies when played), "Resourceful" (generates additional CP).
*   **Destructive:**
    *   **Abilities:** Focus on removing enemy units from play, destroying assets, or otherwise hindering the opponent's game plan.
    *   **Stats:** High Attack or abilities that compensate for lower stats to ensure destructive potential.
    *   **Keywords:**  "Destroy" (removes a unit or asset from the game), "Wither" (reduces enemy Attack), "Curse" (applies negative effects).
*   **Neutral:**
    *   **Abilities:**  Have a balance between constructive and destructive elements or effects that interact directly with the current game state.
    *   **Stats:** Stats could vary based on the card's intended function.
    *   **Keywords:** Can utilize keywords from either Constructive or Destructive categories as needed.

These examples are not exhaustive, and creativity in combining mechanics is encouraged. The sources emphasize the importance of playtesting and iteration, suggesting that card feel should be a guiding principle throughout the design process, subject to refinement based on actual gameplay experience.

#### Card Feel Example

Consider a 'Corrupted AI' card:

Malevolence: Malevolent (AI gone rogue, causing harm)
Utility: Disruptive (interferes with opponent's strategies)
Combat: Offense (focuses on dealing damage)
Impact: Destructive (removes enemy units or resources)

This combination creates a threatening, aggressive card that disrupts the opponent's plans.

### B. Card Calculations

Card calculations involve several steps to determine the final CP cost and available Ability Points (AP):

1. Base CP: Multiply the assigned Domain Points (DP) by 2.
2. Stat Points: Attack and Defense cost 0.5 CP per point. Calculate the total stat point cost by adding Attack and Defense, then dividing by 2.
3. Adjusted CP: Subtract half of the sum of the stat point cost from the Base CP. `BaseCP - ((Attack + Defense) / 2)`.
4. Card Count Factor: Divide 1 by the number of duplicates allowed, then multiply by 0.8.
5. Leadership Factor: If the card is a Leader, the factor is 1; otherwise, it's 0.
6. Ability Points (AP): Calculate AP using the following formula: `AdjustedCP + (AdjustedCP * Card Count Factor) + (AdjustedCP * 0.5 * Leadership Factor)`.
7. Final CP: Add any remaining AP (from ability purchases) to the Base CP to get the final cost. If the remaining AP is negative, subtract it from the Base CP. `BaseCP + Ability Purchase Cost`.

#### Card Calculation Example

Let's calculate the AP for our battle mech:

Base CP: 4 DP * 2 = 8 CP
Stats: Attack 3, Defense 2 (2.5 CP)
Adjusted CP: 8 - 2.5 = 5.5 CP
Card Count: 2 (duplicate factor: 0.4)
Not a Leader (Leadership Factor: 0)

AP = 5.5 + (5.5 * 0.4) + 0 = 7.7 AP
This gives us 7.7 AP to spend on abilities and keywords.

### C. Functional Attributes

Each card possesses specific attributes that define its capabilities and interactions in the game:

* Rank: Determines where the card can be deployed and influences its range options. Rank is used heavily in the thematic descriptions of the card and needs to be considered carefully.
  * Terrestrial: Can be deployed to the battlefield and typically has close or mid-range abilities.
  * Aerial: Can be deployed to the battlefield, often possesses the "Flying" keyword, and usually has mid to far-range abilities.
  * Orbital: Deployed to the loadout, affects entire quadrants on the battlefield.
  * Interstellar: Deployed to the loadout, affects entire battlefield sections (rows or columns) or targets other Orbital / Interstellar cards.
* Range (If Applicable):
  * Close: Can target adjacent quadrants.
  * Mid: Can target adjacent and diagonal quadrants.
  * Far: Can target two rows away. If the unit is in the back row it can target the opponents front row and if it is in the front row, it can target the opponent's back row.
* Attack: The offensive strength of a unit, used to determine the outcome of battles.
* Defense: A unit's resilience against attacks. When a unit's Defense is exceeded by an attacker's Attack, it is discarded.
* Rule Box: This section contains the card's abilities, including active, passive, and interrupts. The rule box is crucial for understanding how a card functions and interacts with other cards and the game state.
  * Active Abilities: These abilities require a player to activate them, often at a CP cost. They provide strategic choices and allow players to influence the game's flow.
  * Passive Abilities: These abilities are always in effect and do not require activation. They provide continuous benefits or drawbacks, shaping the card's overall impact on the game.
  * Interrupts: These abilities trigger automatically when specific events occur, adding dynamic reactions and strategic depth to gameplay.
* Ability Costs: Each ability, whether active or interrupt, has a cost associated with it. The cost reflects the ability's power and impact on the game. Stronger abilities generally have higher costs. The abilities available are calculated using the AP system detailed below, and active abilities have an activation cost in ether CP, resources (Discards, Unit Sacrifice, etc), or a combination of both.

## VI. Card Count Limits

In Quantum Nexus, the scarcity of a card plays a significant role in its power level and strategic value. This scarcity is represented by the card count, which dictates how many copies of a particular card can be included in a player's deck. This number ranges from 1 to 10.

### A. Card Count

* 1: Unique cards, allowing only one copy in a deck. These cards often possess powerful effects and are highly sought after.
* 2: Limited cards, allowing two copies in a deck. These cards offer valuable abilities while maintaining some level of scarcity.
* 3 or more: Common cards with no strict limit on copies in a deck. These cards form the backbone of many strategies and provide essential functions.

### B. Card Count and Ability Points (AP)

Card Count directly influences a card's ability points (AP), which determine the strength and flexibility of its abilities. The fewer cards allowed, the more AP it receives, allowing for more potent effects or a wider range of abilities. The formula for calculating additional AP based on card count is as follows:
Bonus AP = 0.8 * (1 / Card Count)

### C. Example

A card with a count of 1 receives an 80% bonus to its base AP, while a card with a count of 2 receives a 40% bonus. Cards with no count limit receive no bonus AP.

This system ensures that rare and powerful cards remain balanced while providing players with incentives to experiment with different deck compositions and explore unique strategies.

## VII. Abilities

Abilities are the core of what makes each Quantum Nexus card unique and strategically interesting. They define how a card interacts with the battlefield, other cards, and the overall game state. Abilities  can be Active (triggered by the player), Passive (always in effect), or Interrupts (triggered in response to specific events). Abilities and Keywords are purchased by using the AP system. This system is used exclusively for determining which abilities and keywords a card may have. It is never used outside of card creation.

### A. Types of Abilities

* Active Abilities:
  * Require the player to consciously activate them, often during their turn.
  * Must have a Command Point (CP) cost associated for activation.
  * May include other activation costs such as Discard, Sacrifice, etc.
  * Never mentions AP when it is written on the card.
  * Offer a wide range of effect
    * Healing or buffing allies
    * Drawing cards
    * Manipulating the battlefield (moving units, altering terrain)
* Passive Abilities:
  * Never mentions AP when it is written on the card.
  * Always in effect, requiring no activation.
  * Provide ongoing benefits or sometimes drawbacks:
    * Increased Attack or Defense
    * Immunity to certain effects
    * Conditional triggers (e.g., "When this unit is attacked...")
* Interrupts:
  * Trigger automatically in response to specific events or actions.
  * Do not have a CP cost.
  * Offer reactive counterplay or unexpected twists:
    * Canceling an opponent's ability
    * Modifying an attack

### B. Ability Design and Costing

* Concept and Theme:
  * Abilities should align with the card's overall theme and flavor.
  * All abilities need to be named 
  * Start with a clear idea of what the ability should do.
  * Ensure it aligns with the card's domain (Technology, Magic, Psionics, Divinity), subtype, and overall flavor.
* Power Level and Balance:
  * Consider the impact the ability will have on the game.
  * More powerful or versatile abilities should have higher costs.
* Ability Point (AP) System:
  * Each ability has an AP cost based on its complexity and power level, which is like a budget for its abilities. After calculating the Total CP for a card (including the cost of Attack and Defense), the remaining CP is converted into AP. This AP pool is then used to select and add abilities to the card.
  * Each card has a pool of Ability Points (AP) determined by its Domain Points, rarity, and whether it's a Leader.
  * Each ability uses up AP from the pool, the number of points is based on:
    * Its strength and complexity.
    * Its CP activation cost (for active abilities).
    * Any additional costs or sacrifices (e.g., discarding cards).
  * The total AP used to purchase a card's abilities cannot exceed its available AP.
* Ability Cost Reference Table: (See Appendix D for a detailed table)
  * This table provides guidelines for assigning AP costs based on the type and power of the ability, as well as additional factors like CP cost and sacrifices.
  * Remember that AP is only used to determine the abilities available in the card. AP should not be mentioned in any part of the game. It is only relevant to the creation of cards as a balancing factor.
  * It's a starting point; adjust costs during playtesting for balance.

## VIII. Keywords and Their Impact on Gameplay

Keywords are special designations given to cards or abilities that have specific meanings and effects within the game. These keywords can significantly impact gameplay by enhancing a card's power, introducing strategic trade-offs, or creating unique interactions.

### Types of Keywords

* Positive Keywords: These keywords grant beneficial effects to the card they are associated with. Examples include "Flying," which allows a unit to avoid ground attacks, or "Regeneration," which heals the unit each turn.
* Negative Keywords: These keywords impose drawbacks or limitations on the card they are associated with. Examples include "Vulnerable," which increases the damage a unit takes, or "Cursed," which weakens its abilities.
* Neutral Keywords: These keywords introduce unique mechanics or interactions without inherently benefiting or hindering the card. Examples include "Echo," which allows a card to be played twice, or "Transmute," which transforms a card into another.

### Ability Points (AP) and Keywords

Each keyword has an associated AP cost, which is added or subtracted from the card's total AP pool depending on the keyword's effect.

 * Positive keywords add their AP cost to the card's AP pool, making the card more powerful but potentially more expensive to play. There cost can be subtracted if an ability or attack results in this ability being applied to an offensive unit.
 * Negative keywords subtract their AP cost from the card's AP pool, making the card less powerful but potentially cheaper to play. The AP can be added to the pool if an ability or attack results in an opposing unit having a negative keyword applied to them.
 * Neutral keywords always add to the AP pool and are never subtracted.

Important Note: The AP costs listed in Appendix E are just examples. The actual AP cost of a keyword may vary depending on its specific effect and the overall balance of the game.

### Ability Assignment Example

Using our 7.7 AP, let's design abilities for the battle mech:

Active Ability (4 AP): Psionic Overload (2 CP) - Deal 2 damage to a target unit and reduce its Attack by 1 until your next turn.
Passive Ability (2 AP): Adaptive Armor - This unit gains +1 Defense against Technology domain attacks.
Keyword (1 AP): Sturdy - This unit cannot be moved by opponent's abilities.

Total AP used: 7, leaving 0.7 AP unused (which is fine, as we don't need to use every fraction of an AP).

## VIII. Flavor Attributes

Beyond the mechanical aspects of a card, its flavor attributes are crucial for creating an immersive and engaging experience for players.

* A. Name:
  * The name of a card should be evocative, memorable, and reflect its thematic essence.
  * It should provide a hint about the card's abilities, domain, or role in the game.
  * Consider using names that are unique, catchy, and relevant to the Quantum Nexus universe.
* B. Image:
  * A detailed description of the card's artwork is essential for conveying its visual identity.
  * The image should capture the card's theme, mood, and overall feel.
  * Consider using elements that evoke the card's domain, such as technological gadgets, magical symbols, psionic auras, or divine iconography.
  * Ensure that the image is visually appealing, well-composed, and complements the card's mechanical attributes.
* C. Flavor Text:
  * Flavor text is a short quote or description that adds personality and lore to the card.
  * It can provide insights into the card's backstory, abilities, or significance within the Quantum Nexus universe.
  * Keep the flavor text concise and impactful, using evocative language and imagery.

### Flavor Example

Name: Mindshatter Juggernaut

Flavor Text: 'Its thunderous steps herald not just physical destruction, but the unraveling of minds.'

This name and flavor text reinforce the mech's combination of technological might and psionic abilities.

## IX. Synergies

Synergies are the backbone of strategic deck-building in Quantum Nexus. They encourage players to discover and create powerful combinations of cards that work together to achieve specific goals or unleash devastating effects.

 ### A. Types of Synergies

* Theme-Based Synergies: Cards with similar themes or lore can naturally complement each other's abilities, creating cohesive and thematic decks.
* Domain Synergies: Cards from the same domain often share synergies that enhance their individual strengths or create powerful combined effects.
* Subtype Synergies: Cards with the same subtype may benefit from playing alongside each other, encouraging players to build focused decks around specific unit types.
* Leader Abilities: Leader cards often possess abilities that synergize with specific unit types or domains, incentivizing players to build decks that maximize the leader's potential.
* Upgrade Interactions: Upgrades can be tailored to specific units or abilities, creating potent combinations that enhance a deck's overall effectiveness.
* Event and Terrain Interactions: Events can trigger additional effects when certain units or terrain are in play, while terrain cards can grant bonuses to specific domains or unit types.
* Inter-Domain Synergies: Some cards transcend their primary domain and synergize effectively with cards from other domains, creating unexpected and powerful interactions.
* Ability Combos: Certain card abilities can be combined to create devastating combos that can quickly swing the tide of battle.

 ### B. Balancing Synergies

  It is crucial to balance synergies carefully to prevent them from becoming too overpowered or overshadowing other strategies. Synergistic effects should be strong but not so dominant that they make other approaches unviable.

 ### C. Discovery and Exploration

  Quantum Nexus encourages players to discover and explore synergies through experimentation and gameplay. Hidden or unexpected synergies can add an element of surprise and excitement to the game, rewarding creative deck-building and strategic thinking.

### D. Playtesting and Feedback

  Thorough playtesting is essential to ensure that synergies work as intended and do not create unbalanced scenarios. Gathering feedback from players can help identify potential issues and refine card designs for optimal gameplay.

By crafting cards that synergize effectively with each other, you can create a rich and engaging gameplay experience where players are constantly discovering new strategies and combos to master.

### Synergy Example

Our battle mech could synergize well with:

- Technology cards that buff mechanical units
- Psionic cards that enhance mind control abilities
- Cards that benefit from or trigger off damage dealt to enemy units

For instance, a 'Psionic Amplifier' upgrade could enhance the 'Psionic Overload' ability, increasing its damage and Attack reduction.

## X. Card Creation Example

*Concept*:

A high-tech aerial unit that specializes in long-range attacks and reconnaissance, equipped with advanced scanning technology and powerful weaponry.

*Card Type and Subtype*:

Unit - Drone

*Domain Points (DP)*:

* Technology (4): This unit heavily relies on advanced technology for its capabilities.
  * Disciplines:
    * Energy Weapons (2): Focuses on its long-range energy-based attacks.
    * Robotics (2): Reflects its autonomous nature and advanced systems.

*Base CP Cost*:

* 8 (4 DP * 2)

*Card Feel*:

* Malevolence: Neutral (a tool, not inherently good or evil).
* Utility: Utility-focused (provides reconnaissance and tactical advantage).
* Combat: Offense (prioritizes dealing damage from afar).
* Impact: Neutral (primarily focused on direct interaction with enemy units).

*Attributes*:

* Rank: Aerial (can be deployed to the battlefield or remain in the air).
* Range: Far (targets the opposing row from a safe distance).
* Attack: 4 (high offensive power, specializing in long-range attacks).
* Defense: 1 (low defense due to its fragile nature).
* Keyword: Flying (cannot be targeted by units without the "Flying" keyword).

*Adjusted CP*:

* Adjusted CP = Base CP - ((Attack + Defense) / 2) = 8 - (5 / 2) = 5.5

*Ability Points (AP)*:

* Duplicate Factor: Let's assume a duplicate count of 3, so the factor is (1 / 3) * 0.8 = 0.2667 (approximately).
* Leadership Factor: 0 (not a Leader card)
* Ability Points = 5.5 + (5.5 * 0.2667) + 0 = 6.967 (approximately)

*Abilities*:

* Passive Ability (Purchased for 2 AP):
  * *Scan*: At the start of your turn, reveal a random card from your opponent's hand. (Provides valuable information and fits the reconnaissance theme)
* Active Ability (Purchased for 5 AP):
  * *Precision Strike (2 CP)*: Reduce a unit in the opposing front row's Defense to 0.

*Final CP Cost*:

* We used 7 AP, slightly under the limit. The final CP cost remains the same as the Base CP, which is 8.

*Name*:

Sky Sentinel (Evokes its aerial nature and protective role)

*Image Description*:

A sleek, metallic drone with glowing energy cannons mounted on its wings. It hovers above the battlefield, scanning the terrain with its sensors.

*Flavor Text*:

"Its unblinking eye sees all, its silent wings bring swift retribution."

*Key Design Considerations*:

* Balance: The Sky Sentinel's high attack and "Flying" keyword are balanced by its low defense and vulnerability to cards that can target flying units.
* Synergy: This card could synergize well with other Technology cards that buff attack power or provide additional reconnaissance capabilities.
* Flavor: The name, image, and flavor text all reinforce the card's theme of a high-tech, aerial guardian.

## XI. Advanced Card Mechanics

Beyond the basic abilities outlined in Section IV, Quantum Nexus allows for more sophisticated card mechanics that can create unique and engaging gameplay experiences.

* Keywords and Status Effects:
  * Keywords like "Flying," "Haste," or "Stealth" can be used to define special abilities or traits for units.
  * Status effects like "Poisoned," "Stunned," or "Blessed" can temporarily alter a unit's stats or behavior.
* Combo Potential:
  * Consider how your card might synergize with other cards in unexpected ways, creating powerful combos that reward strategic thinking and deck-building prowess.
  * Think about how your card might counter or disrupt common strategies, adding an element of surprise and counterplay to the game.
* Conditional Effects:
  * Abilities that trigger under specific conditions can add a layer of complexity and decision-making to gameplay.
  * Examples include effects that activate when a certain number of units are on the battlefield, when a specific card is played, or when a certain attack is executedt.
* Transforming Cards:
  * Some cards might transform into different forms under certain conditions, adding a dynamic element to gameplay and creating opportunities for unexpected twists.

## XII. Design Considerations

When crafting your cards, keep these key design considerations in mind:

* Balance: Strive for a balance of power between different card types, domains, and abilities. No single card or strategy should be overwhelmingly dominant.
* Originality: Aim for unique and innovative card concepts that stand out from existing cards.
* Flavor: Ensure that the card's mechanics and flavor attributes align seamlessly, creating a cohesive and immersive experience.
* Engagement: Design cards that are fun and engaging to play, offering interesting choices and interactions.
* Accessibility: Make sure that the card's mechanics are easy to understand and that the card's overall design is visually appealing.

## XIII. Playtesting and Iteration

Playtesting is a crucial step in the card creation process. It allows you to test your designs in a real-world environment, gather feedback, and refine your cards to achieve optimal balance and playability.

* Internal Playtesting: Test your cards with a small group of players to identify any obvious issues or imbalances.
* Public Playtesting: If possible, share your card designs with a wider audience to gather more diverse feedback.
* Iterative Refinement: Use the feedback you receive to iterate on your designs, adjusting CP costs, ability effects, and flavor attributes as needed.

By embracing playtesting and iteration, you can ensure that your cards contribute to a vibrant and balanced gameplay experience in Quantum Nexus.

## XIV. Conclusion

The Quantum Nexus card creation process is a journey of creativity, strategy, and iteration. By following these guidelines and considering the intricate details of card design, you can craft unique and powerful cards that will leave a lasting impact on the game's evolving universe.

## Appendix

### A. Glossary of Terms
* Attack: A unit's offensive strength, used to determine the outcome of battles.
* Command Points (CP): CP represent the resource cost required to play a card from your hand onto the battlefield or into your loadout.
* Defense: A unit's resilience against attacks.
* Disciplines: Specialized areas within each domain that grant specific abilities.
* Domain Points (DP): DP represent a card's inherent connection and mastery of the four domains: Technology, Magic, Psionics, and Divinity. They determine the card's theme, flavor, and potential abilities.
* Interrupt: An ability that triggers automatically when a specific condition is met.
* Loadout: The area where Asset cards are played.
* Malevolence: A card feel axis describing the card's moral alignment (Neutral, Malevolent, or Benevolent).
* Passive Ability: An ability that is always in effect and does not require activation.
* Quadrant: One of six sections on the battlefield where units can be deployed.
* Rank: Determines where a card can be played (Terrestrial, Aerial, Orbital, or Interstellar).
* Range: The distance a unit or ability can target (Close, Mid, or Far).
* Rule Box: The area on a card that contains its abilities, effects, and keywords.
* Subtype: A more specific classification within a card type (e.g., Mech, Squad, Specialist).
* Synergy: The interaction between two or more cards that creates a combined effect greater than the sum of their parts.
* Utility: A card feel axis describing the card's strategic purpose (Utility-focused, Neutral, or Disruptive).
* Activation Cost: The cost (usually in CP, but can also include discarding cards, sacrificing units, etc.) that a player must pay to activate an active ability.
* Card Advantage: The strategic advantage gained by having more cards in hand or on the battlefield than your opponent.
Combo: A powerful combination of two or more cards that create a synergistic effect greater than the sum of their parts.
* Exile: To remove a card from the game entirely, usually face down and unable to be interacted with further.
* Face Down: A card that is not visible to either player, often used for hidden effects or randomization.
* Flying: A keyword that allows a unit to avoid ground attacks and only be blocked by other units with the Flying keyword.
* Haste: A keyword that allows a unit to attack or use activated abilities during the same phase it was deployed on.
* Mill: An ability or effect that forces a player to discard cards from their deck.
* Ramp: Strategies or cards that accelerate a player's resource generation (CP) to enable playing more powerful cards earlier in the game.
* Stealth: A keyword that makes a unit unblockable unless the defending player controls a unit with the "Detector" keyword.
* Token: A temporary unit created by a card effect, usually with lower stats and simpler abilities than regular units.
* Tutor: An ability or effect that allows a player to search their deck for a specific card and add it to their hand.

### B. Design Tips

* Start with a Concept: Begin with a clear idea of the card's theme, mechanics, and role in the game.
* Balance Power and Cost: Ensure that the card's CP cost is appropriate for its overall power level.
* Consider Synergies: Design cards that interact with other cards in your set or existing cards.
* Embrace Flavor: Use evocative names, images, and flavor text to bring your card to life.
* Playtest Thoroughly: Test your cards against various opponents and strategies to ensure balance and fun.
* Iterate and Refine: Be open to feedback and make adjustments to your designs as needed.

By combining creativity with a solid understanding of the Quantum Nexus guidelines, you can create compelling and memorable cards that will enrich the game's universe and provide endless hours of strategic fun for players.

### C: Ability Cost Reference Table

| Ability Type | AP Cost Base | Activation Cost Modifier | Interrupt Type Modifier | Additional Cost Modifiers | Notes |
|---|---|---|---|---|---|
| Active Abilities |  |  |  |  |  |
| Increase Attack | 1-6 | -1 AP per 2 CP | N/A | +1-3 AP per additional effect | Varies based on attack stat, range, target (single vs. multiple), ignoring Defense, etc. |
| Destroy a Unit | 4-8 | -1 AP per 2 CP | N/A | +1 AP per additional unit | Higher cost for stronger units, Leaders, or units with specific keywords. |
| Draw Cards | 1-4 | -1 AP per 2 CP | N/A |  | Higher cost for drawing multiple cards, specific card types. |
| Discard Cards | 1-3 | -1 AP per 2 CP | N/A |  | Higher cost for discarding multiple cards, specific card types, or from opponent's hand. |
| Move Units | 1-3 | -1 AP per 2 CP | N/A |  | Higher cost for moving multiple units or to a specific location. |
| Grant a Buff/Debuff | 1-5 | -1 AP per 2 CP | N/A | +1-2 AP per additional target | Varies based on the strength, duration, and target of the effect. |
| Transform | 4-7 | -1 AP per 2 CP | N/A |  | Higher cost for more powerful or versatile transformations. |
| Counter or Cancel an Ability/Effect | 3-6 | -1 AP per 2 CP |  |  | Varies based on the power of the countered effect. |
| Special Effects (e.g., Stun, Poison, Silence) | 2-6 | -1 AP per 2 CP | N/A |  | Varies based on the strength, duration, and conditionality of the effect. |
| Conditional Effects | 1-4 | N/A | N/A |  | Lower cost for stricter conditions or less powerful effects. |
| Unique or Powerful Effects | 6+ | -1 AP per 3 CP | N/A |  | High cost for game-changing abilities. Balance carefully to avoid overpowered cards. |
| Domain-Specific Abilities | 1-5 | -1 AP per 2 CP | N/A |  | Consider the domain's overall power and the ability's specific effect. |
| Additional Costs and Sacrifices | +1-3 AP per cost | N/A | N/A |  | Add AP for each additional CP cost, card sacrificed, or specific requirement (e.g., discarding an Upgrade, having a specific Terrain in play). |
| Interrupts |  |  |  |  |  |
| On Deploy | 1-2 | N/A | -1 AP |  | Triggered when the card itself is deployed. |
| On Attack | 2-4 | N/A | -2 AP |  | Triggered when the card attacks. |
| On Discard/Destroy | 1-3 | N/A | -1 AP |  | Triggered when the card is discarded or destroyed. |
| On Specific Condition (e.g., turn start/end) | 1-4 | N/A | -1 AP |  | Triggered under specific conditions not directly tied to actions. |

Important Note: This table is still a guideline. The final AP cost for an ability should always be determined through playtesting and careful consideration of its overall impact on the game.

### D. Keyword Cost Reference Table

| Keyword | Description | AP Cost | Type | Notes |
|---|---|---|---|---|
| Phase Shift | This unit cannot be targeted by attacks or abilities for the rest of the turn. | 1-2 | Positive | Useful for protecting valuable units or setting up combos. |
| Quantum Entanglement | When this unit is targeted by an attack, you may redirect that attack to another friendly unit you control. | 2-3 | Positive | Offers flexibility and defensive options. |
| Temporal Anomaly | This unit takes an additional turn after this one. | 3-4 | Positive | Powerful ability with high potential for game-changing plays. |
| Dimensional Rift | When this unit attacks, you may exile a target card from your opponent's hand. | 2-3 | Positive | Disrupts opponent's strategy and provides card advantage. |
| Etherial Construct | This unit cannot be blocked by units without the "Etherial" subtype. | 1-2 | Positive | Strong against decks without Etherial units, but vulnerable to those that do. |
| Syphon Power | Whenever a unit you control with a higher rank than this unit is destroyed, this unit gains a +1/+1 counter. | 2-3 | Positive | Encourages synergistic deck building around unit ranks. |
| Overcharge | When you activate this ability, pay X additional CP. This ability gains additional effects based on the amount of CP paid. | 3-4 | Positive | Scales with available resources, offering flexible decision-making. |
| Adaptive Armor | This unit gains +1 defense for each different domain among units you control. | 2-3 | Positive | Rewards diverse deck building across multiple domains. |
| Multi-Domain Expertise | This unit's abilities cost 1 less AP to activate for each different domain among units you control. | 3-4 | Positive | Powerful in multi-domain decks, less impactful in mono-domain decks. |
| Quantum Decoherence | This unit loses all abilities for the rest of the turn. | 1-2 | Negative | Can be used to disrupt powerful abilities or as a self-imposed downside for a stronger unit. |
| Temporal Paradox | This unit skips its next turn. | 2-3 | Negative | Situational drawback, potentially used for delayed effects or to avoid negative effects on the next turn. |
| Dimensional Instability | When this unit is destroyed, exile a random card from your hand. | 3-4 | Negative | High-risk, high-reward effect that can disrupt the player's hand. |
| Energy Drain | Whenever this unit attacks, you lose 1 CP. | 1-2 | Negative | Balances aggressive abilities by limiting resource generation. |
| Corrupted Circuitry | This unit's abilities cost 1 more AP to activate. | 2-3 | Negative | Weakens the unit's abilities, but can be mitigated by other card effects. |
| Anti-Synergy | Whenever you play a card with the same domain as this unit, this unit loses a +1/+1 counter. | 2-3 | Negative | Discourages playing multiple cards of the same domain. |
| Unstable Anomaly | At the beginning of your upkeep, this unit deals 1 damage to itself. | 3-4 | Negative | Detrimental effect that can be mitigated by healing or defensive abilities. |
| Fragile Construct | This unit has -1 defense. | 1-2 | Negative | Makes the unit easier to destroy, but can be balanced by other stats or abilities. |
| Transmute | When you activate this ability, you may pay X CP. If you do, exile this card and search your library for a card with a CP cost of X or less and put it onto the battlefield. | 2-3 | Neutral | Flexible ability that allows for card advantage and resource management. |
| Echo | Exile this card from your hand as you cast it. At the beginning of your next upkeep, you may cast this card from exile without paying its CP cost. | 1-2 | Neutral | Provides a second chance to play the card, but requires careful timing and planning. |
| Modular (X) | This card enters the battlefield with X +1/+1 counters. You may remove a +1/+1 counter from this card to activate an ability of another target card you control. | Variable | Neutral | Encourages synergistic combinations with other cards. |
| Temporal Echo | Create a copy of this unit that lasts until the end of your next turn. | 3-4 | Positive | Creates a temporary advantage in combat or board presence. |
| Quantum Siphon | When this unit deals damage, you gain CP equal to the damage dealt. | 2-3 | Positive | Rewards aggressive play and resource generation. |
| Dimensional Anchor | Prevent all damage that would be dealt to and dealt by this unit this turn. | 2-3 | Positive | Strong defensive ability, but prevents offensive actions as well. |
| Chrono-Lock | This unit cannot be targeted by abilities that would alter its power or toughness. | 1-2 | Positive | Protects against common removal or weakening effects. |
| Domain Expertise | This unit gains +1/+1 for each domain among cards in your graveyard. | 2-3 | Positive | Rewards diverse deck building and graveyard manipulation. |
| Quantum Overload | This unit deals damage to itself equal to its power at the end of each turn. | 3-4 | Negative | High-risk, high-reward effect that requires careful management. |
| Time Dilation | This unit's activate abilities cost 1 more AP to activate. | 2-3 | Negative | Balances powerful abilities by increasing their activation cost. |
| Domain Disruption | Choose a domain. Units of the chosen domain cannot activate their abilities this turn. | 2-3 | Negative | Disruptive effect that can swing the tide of battle. |
| Temporal Distortion | Whenever a unit with the same domain as this unit enters the battlefield under your control, exile it. | 3-4 | Negative | Punishes playing multiple units of the same domain. |
| Etherial Weakness | This unit takes double damage from sources with the "Etherial" subtype. | 1-2 | Negative | Weakness to a specific subtype, creates strategic counterplay opportunities. |

E. Card Template
Use this template as a starting point for designing your Quantum Nexus cards:
Card Name:

Name:

Type:

Domain Points:

- Domain 1 (DP): Discipline 1, Discipline 2 (if applicable)
- Domain 2 (DP): Discipline 1, Discipline 2 (if applicable)

CP Cost:

Card Feel:
- Malevolence:
- Utility:
- Combat:
- Impact:

Keywords: 

Rank: (If Applicable)

Range (If Applicable):

Attack:

Defense:

Rule Box:

- CP X - Ability 1
- CP X - Ability 2
- ...

Flavor Text:

Image Description:

Design Considerations:

Remember, this is just a template. Feel free to customize it to fit your specific card designs and creative vision.
By leveraging the resources and information provided in this Appendix, you can further enhance your card creation skills and contribute to the ever-expanding universe of Quantum Nexus.

### F. Design Considerations for Different Card Types

Each card type in Quantum Nexus serves a distinct purpose and requires specific design considerations to ensure balance and strategic depth.
1. Units
 * Attack and Defense Balance:
   * Strive for a balance between offensive and defensive capabilities based on the unit's role and intended playstyle.
   * Consider the unit's rank and domain when determining appropriate stats.
 * Ability Synergy:
   * Design abilities that complement the unit's stats and playstyle.
   * Consider how the unit might synergize with other units, leaders, or terrain cards.
 * Range and Deployment:
   * Choose a range that fits the unit's theme and tactical role.
   * Consider whether the unit should be deployed in the front or back row.
  * Terrestrial and Aerial units have a range, attack and defense stat, Orbital and Interstellar have only a defense stat.
2. Leaders
 * Unique and Impactful Abilities:
   * Leader abilities should be powerful and game-changing, reflecting their leadership role.
   * Consider abilities that buff allies, debuff enemies, or manipulate the battlefield in significant ways.
 * Synergy with Domain and Subtype:
   * Leader abilities should synergize with the domain and subtype they belong to.
   * For example, a Technology Leader might grant bonuses to Mech units or enhance Energy Weapons.
 * Cost Reduction:
   * Remember that Leaders receive a 50% cost reduction due to their unique status. Balance their abilities accordingly.
3. Upgrades
 * Targeted Enhancement:
   * Design upgrades that specifically target and enhance certain unit types, domains, or abilities.
   * Consider both stat boosts (Attack, Defense) and additional effects (keywords, abilities).
 * Flexibility and Versatility:
   * Some upgrades might offer choices or conditional effects to increase their adaptability.
 * Cost-Effectiveness:
   * Balance the upgrade's cost with the benefits it provides to ensure it's a worthwhile investment.
4. Assets
 * Ongoing Benefits:
   * Assets should provide continuous or recurring effects that influence the battlefield or support your overall strategy.
   * Consider effects like resource generation, card draw, or passive buffs/debuffs.
 * Defensive Measures:
   * Assets typically have a Defense value to protect them from targeted removal.
 * Strategic Placement:
   * Consider whether the asset should affect specific quadrants, sections, or the entire battlefield.
   * Orbital units can affect entire quadrants on the battlefield.
   * Interstellar units can affect entire Rows or Columns of the battlefield.
5. Events
 * Immediate Impact:
   * Events should have a significant and immediate effect on the game state.
   * Consider effects like unit removal, disrupting enemy plans, or shifting the battlefield's dynamics.
 * Cost and Timing:
   * Balance the event's cost with its power level and consider the optimal timing for its use during the Command Phase.
6. Terrain
 * Battlefield Modification:
   * Terrain cards should alter the battlefield in meaningful ways, creating strategic advantages or disadvantages for certain units or playstyles.
 * Synergy with Domains and Unit Types:
   * Design terrain cards that interact with specific domains or unit types, encouraging diverse deck-building strategies.

By considering these design considerations for each card type, you can ensure that your creations are balanced, engaging, and contribute to the rich tapestry of Quantum Nexus gameplay.
