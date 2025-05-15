# Quantum Nexus: Card Creation Guidelines

## Note to the Reader

This is the Quantum Nexus: Card Creation Guidelines. This document is not meant to explain any rules that a player would need; it is solely intended to aid designers in creating captivating and interesting cards for Quantum Nexus. Players are welcome to read this document, but please know that these rules are not applied to any in-game scenario; they are solely intended for creating cards for Quantum Nexus.

## I. Introduction

Quantum Nexus is a strategic trading card game (TCG) that immerses players in a captivating sci-fi universe filled with advanced technology, mystical magic, potent psionics, and divine intervention. To contribute to this dynamic world, card creators must adhere to a set of core design principles and understand the fundamental building blocks of card creation.

### A. Core Design Principles

* **Card Control:** Each player retains complete ownership and control of their cards throughout the game. Players are not allowed to touch any other player's cards, and a player's cards are not allowed to leave that player's play area. This aligns with Section V.F of the Quantum Nexus Rulebook.
* **Predictable Gameplay:** The only random element in Quantum Nexus is initial card shuffles and the card draw during the Start of Round Step. This design choice eliminates luck-based mechanics like dice rolls or coin flips, ensuring that strategic decision-making and tactical planning are the primary factors that determine the outcome of battles.
* **Streamlined Combat:** Units in Quantum Nexus do not have health points. Instead, their resilience is represented by a Defense value. When a unit is attacked, its Defense is compared to the attacker's Attack value. The outcomes are specific:
    * If Attack is greater than Defense, the defending unit is destroyed.
    * If Attack equals Defense, the defending unit becomes Suppressed (it exhausts).
    * If Attack is less than Defense, the attacker becomes Disordered and is Pushed Back.
    This system, detailed in Section III.C.2 of the Rulebook, simplifies aspects of combat while offering tactical nuance.

## II. Battlefield, Range, and Movement

Understanding the battlefield, card range, and unit movement as defined in the current Quantum Nexus Rulebook is crucial for effective card design.

### A. Battlefield Structure
The Quantum Nexus battlefield for each player consists of a 3x2 grid, comprising six distinct quadrants (Front Left, Front Center, Front Right, Back Left, Back Center, Back Right). Units are deployed into their controller's own quadrants and never physically enter an opponent's play area or quadrants. For targeting purposes, a player's Front Row is considered to be facing each opponent's Front Row. (See Rulebook Section V.E).

### B. Range Types
Each Unit card designed to attack or affect other cards at a distance must have a defined range. These ranges dictate which quadrants it can target, relative to its current position. The official range definitions are in Section VIII (Glossary) of the Quantum Nexus Rulebook. Designers must use these current definitions:

* **Close Range:** A unit with a Close Range attack or ability can target its own current quadrant AND one existing quadrant directly Forward, Backward, Left, and Right of its current quadrant. A unit declaring an attack with Close Range may target its own unit in its own quadrant.
* **Mid Range:** A unit with a Mid Range attack or ability can target one existing quadrant directly Forward, Backward, Left, Right, Forward-Left Diagonal, Forward-Right Diagonal, Backward-Left Diagonal, and Backward-Right Diagonal from its current quadrant. Mid Range does not include the attacking unit's own current quadrant.
* **Far Range:** An attack range allowing a unit to target all quadrants located exactly two rows ahead of its current row, on an opponent's side of the battlefield. Units in a player's Front Row target all quadrants in the opponent's Back Row. Units in a player's Back Row target all quadrants in the opponent's Front Row. Far Range does not include the attacking unit's own current quadrant.

Careful consideration of these ranges is essential for balancing a unit's offensive and defensive capabilities and its tactical role.

### C. Movement
In the current Quantum Nexus rules (Section III.C.2), moving a unit is a specific single action a player can choose during their turn in the Activation Sequence.
* A player chooses one of their ready units.
* The unit moves one quadrant in a cardinal direction (Forward, Backward, Left, or Right) to an adjacent friendly quadrant.
* The destination quadrant may be occupied by other friendly units (respecting the "one Leader per quadrant" rule).
* The unit that moved then becomes exhausted as the cost of this action.
Card designs, particularly for units, should consider this action economy for movement. Abilities that grant movement or affect movement should be designed with this baseline rule in mind.

### D. Internal Design Tags (Formerly "Card Ranks")
The terms Terrestrial, Aerial, Orbital, and Interstellar are no longer mechanical "Card Ranks" that dictate player-facing rules like deployment zones or specific abilities.
For internal design purposes within these guidelines, these terms can be used as thematic tags to help inform a card's concept and its place within the "Card Feel Matrix" (see Section V.A). They should not appear on cards as a distinct mechanical property visible to players and are not referenced in the main rulebook.
* **Terrestrial (Internal Tag):** Suggests ground-based themes.
* **Aerial (Internal Tag):** Suggests flying or air-based themes.
* **Orbital (Internal Tag):** Suggests themes of affecting wider areas from a distance, traditionally associated with Asset-like concepts affecting quadrants.
* **Interstellar (Internal Tag):** Suggests themes of broad, battlefield-wide influence, traditionally associated with Asset-like concepts.

Deployment of cards is determined by their Card Type (Unit, Asset, Terrain, etc.) as per Section IV of the Quantum Nexus Rulebook.

### E. Game Round Structure (Formerly "Turn Sequence")
Designers must create cards that function within the current Game Round Structure detailed in Section III.C of the Quantum Nexus Rulebook. This structure is not based on distinct, shared phases like "Deployment Phase" or "Command Phase." Instead, it consists of:
1.  **Start of Round Step:** This occurs simultaneously for all players.
    * All previously exhausted cards are deactivated (readied).
    * Players gain their Command Points (CP) for the round (derived from their Mission Cards plus any other "start of round" effects).
    * Players draw cards until they have five cards in their hand.
    * Relevant triggered abilities resolve.
2.  **Activation Sequence:** Following the Start of Round Step, players take turns performing single actions.
    * The player with initiative takes the first single action.
    * Available single actions are: Deploy a Card, Activate an Active Ability, Declare an Attack, Play an Event Card, Move a Unit, or Pass.
    * After an action and any resulting triggered abilities fully resolve, the next player in clockwise order takes a single action.
    * This continues until all players consecutively Pass.
Initiative for the first round is determined by a card flip; for subsequent rounds, it goes to the player who passed first to end the previous Activation Sequence (Rulebook Section III.D).
Card abilities, costs, and effects must be designed with this alternating single-action economy in mind.

## III. Card Types and Subtypes

Quantum Nexus features a diverse range of card types, each playing a unique role. Designers should adhere to the definitions and roles outlined in Section IV of the Quantum Nexus Rulebook.

### A. Card Types

* **Units:** The core of a player's forces. Units have Attack and Defense values and a defined range (if applicable). They are deployed to a player's quadrants on the Battlefield. (Rulebook Section IV.A)
    * **Leaders:** Special, powerful units. Only one of a player's Leaders can occupy one of their quadrants at a time. Each deck is limited to a maximum of 25 CP worth of Leader cards (Rulebook Section IV.A, II).
* **Upgrades:** Cards that modify a player's own Units or Assets, enhancing their stats or granting new abilities. They are deployed attached to the target card. (Rulebook Section IV.D)
* **Assets:** Persistent cards deployed to the player's Loadout Area. They provide ongoing benefits or activate special abilities. Assets have a Defense value but no Attack value and cannot inherently declare an Attack action. (Rulebook Section IV.B)
* **Events:** Played as a single action during the Activation Sequence by paying their CP cost. They provide powerful one-time effects and are then typically discarded. (Rulebook Section IV.C)
* **Terrain:** Deployed into a player's own quadrants on the Battlefield. They provide inherent defensive bonuses to units in their quadrant (+1 Defense per Terrain, max +2 from this source) and apply any other effects described in their rule box. A player can have a maximum of two of their own Terrain cards in any single quadrant. (Rulebook Section IV.E)
* **Mission Cards:** These are a distinct category of cards, crucial for deck construction (defining Unit domain point allowances), providing base CP per round, and offering a path to victory. (Design principles for Mission Cards are covered in a separate document; see Section XV).

### B. Subtypes
In addition to their main type, most cards have one or more subtypes (e.g., "Mech," "Bioweapon," "Celestial," "Technomancer"). Subtypes add specificity and can interact with card abilities or game rules, providing thematic and mechanical hooks. (Rulebook Section I.C).

## IV. Domain System

In Quantum Nexus, cards are thematically linked to one or more of four key domains: Technology, Magic, Psionics, and Divinity. These domains shape a card's identity, abilities, and flavor. The primary mechanical impact of Domains for players is in deck construction, where Mission Card domain point totals restrict the inclusion of Unit cards (Rulebook Section II.B, II.C).

For designers, the Domain system can serve as a strong thematic and conceptual framework.

### A. Domain Points (DP) - For Thematic Design and Budgeting
Domain Points (DP) are numerical values assigned to each card, indicating its affinity and mastery of specific domains. For designers, DP serve as an internal tool to quantify a card's thematic investment and conceptual power level. Domain Points are a key factor in determining a card's initial Design Budget (DB) as outlined in the "Progressive Budget Build" system (Section V.B), which then influences its final CP cost. Thematically, higher DP allocations should still guide designers towards more potent or domain-characteristic abilities.

* Allocation Rules (for thematic guidance):
    * Total DP: Consider a conceptual maximum (e.g., 6 DP total per card, though the costing system focuses on Total DP sum).
    * Domain Limit: Consider a conceptual maximum per domain (e.g., 4 points per domain).
    * Minimum Allocation: A card should conceptually have points in domains relevant to its name, art, or abilities.
    * Balanced Distribution: Aim for a thematic distribution reflecting the card's concept.
    * Card Theme: The conceptual DP can guide the power and nature of abilities within that domain (e.g., 1 DP = basic use, 4 DP = mastery).

### B. Domain Characteristics
The thematic characteristics of each domain should guide ability design:
* **Technology:** Themes of ranged weaponry, area effects, battlefield control, advanced machinery.
* **Magic:** Themes of versatile spellcasting, unit targeting, arcane power, enchantments.
* **Psionics:** Themes of mind control, telekinesis, psychic manipulation, mental assaults.
* **Divinity:** Themes of blessings, curses, holy/unholy power, large-scale interventions.

### C. Disciplines
Specific disciplines within each domain (e.g., Cybernetics under Technology, Elemental Magic under Magic) remain a valuable tool for designers to add thematic depth and inspire specific abilities. For each conceptual Domain Point allocated, designers can select relevant disciplines to further refine the card's theme.

(The lists of disciplines from the original guidelines are retained here for designer reference.)

**Technology:**
* Cybernetics: Biomechanics, Neural Interfaces, AI Integration, Augmentation, Prosthetics, Sensory Enhancement, Brain-Computer Interfaces
* Energy Weapons: Lasers, Particle Beams, Plasma Cannons, Sonic Disruptors, Railguns, Coilguns, Graviton Weapons
* Robotics: Autonomous Drones, Industrial Automatons, Mechs, Androids, Nanobots, Swarm Robotics, Synthetic Organisms, Cybernetic Organisms
* Genetics: Bioengineering, Cloning, Gene Therapy, Chimera Creation, Genetic Modification, Designer Babies, Eugenics, Biological Weapons
**Magic:**
* Elemental Magic: Pyromancy, Hydromancy, Aeromancy, Geomancy, Cryomancy, Electrokinesis, Umbrakinesis, Photokinesis
* Enchantment: Warding, Curses, Illusions, Charms, Hexes, Jinxes, Glamours, Compulsions
* Summoning: Conjuration, Necromancy, Demonology, Celestial Beings, Spirit Animals, Familiars, Elementals, Ethereal Entities
* Alchemy: Transmutation, Potion Brewing, Homunculus Creation, Philosopher's Stone, Elixir of Life, Panacea, Transfiguration, Quintessence
**Psionics:**
* Telekinesis: Object Manipulation, Pyrokinesis, Cryokinesis, Electrokinesis, Teleportation, Levitation, Force Fields, Matter Manipulation
* Mind Control: Illusion Casting, Suggestion, Domination, Psychic Assault, Mind Reading, Memory Manipulation, Empathy, Telepathy
* Precognition: Clairvoyance, Divination, Prophecy, Retrocognition, Future Sight, Premonition, Omen Reading, Augury
* Astral Projection: Out-of-Body Experiences, Dream Walking, Spirit Communication, Plane Shifting, Remote Viewing, Possession, Ethereal Travel, Soul Projection
**Divinity:**
* Divine/Unholy Power: Healing/Harm, Exorcism/Corruption, Sanctification/Desecration, Protection/Curses, Blessing/Blighting, Smiting, Resurrection/Necromancy
* Divine Wrath/Infernal Rage: Smiting, Banishment, Retribution, Divine Judgment, Heavenly Fire, Infernal Torment, Soul Imprisonment, Damnation
* Blessings/Curses: Augmentation/Corruption, Fortune/Misfortune, Fertility/Sterility, Resurrection/Necromancy, Divine Favor/Disfavor, Miraculous Healing/Disease, Prosperity/Poverty, Life/Death
* Divine/Infernal Intervention: Miracles/Chaos, Oracles/False Prophecies, Guidance/Temptation, Fate Manipulation, Angelic/Demonic Aid, Divine Inspiration/Corruption, Prophetic Visions/Nightmares, Heavenly/Hellish Portals

## V. Card Feel and Attributes

Defining a card's feel helps establish its role and contributes to the gameplay experience.

### A. Card Feel Axes
These axes describe a card's conceptual alignment and purpose. This matrix is an internal design tool. The "Internal Design Tags" (formerly "Card Ranks" - see Section II.D) can inform these axes.
* **Malevolence:** Describes moral alignment (Neutral, Malevolent, Benevolent).
* **Utility:** Indicates strategic purpose (Utility-focused, Neutral, Disruptive).
* **Combat:** Reflects role in battle (Offense, Neutral, Defense).
* **Impact:** Describes overall effect on game state (Constructive, Neutral, Destructive).

#### Translating Card Feel into Mechanics
Thematic feel should translate into game mechanics. This section provides examples of how a card's position on these axes might inspire specific types of abilities or stat distributions, and the potential consequences for gameplay.

##### 1. Malevolence
* **Benevolent:**
    * Potential Abilities: Healing friendly units, providing protective effects (like increasing Defense or preventing targeting), enhancing other friendly units, generating CP for the player, or effects that offer symmetrical benefits. Consider how these abilities support a longer, more resilient game plan.
    * Example Consequence: A deck focused on Benevolent cards might excel at outlasting opponents but may lack raw aggressive power without support.
* **Malevolent:**
    * Potential Abilities: Direct damage to units, effects that force opponents to discard cards from hand or deck, applying negative states (beyond standard combat outcomes, if new states are designed), controlling opponent's units temporarily (if this mechanic is ever introduced, noting current rules V.F on card control), or denying resources.
    * Example Consequence: Malevolent cards can disrupt opponents heavily but might involve risks or costs to the player, or lead to a board state that is powerful but fragile if their key pieces are removed.
* **Neutral:**
    * Potential Abilities: Focus on efficiency, achieving objectives directly, or providing versatile tools that can be used offensively or defensively depending on the situation. Abilities might involve direct unit removal, battlefield repositioning, or conditional effects.
    * Example Consequence: Neutral cards often form the backbone of strategies, offering flexibility but perhaps lacking the extreme specialization of Benevolent or Malevolent cards.

##### 2. Utility
* **Utility-focused:**
    * Potential Abilities: Card draw, searching the deck (tutoring), manipulating the order of cards in a deck, returning cards from discard to hand/deck, countering opponent's abilities, or broad battlefield manipulation (e.g., moving multiple units, altering multiple quadrants with Terrain-like effects if on a non-Terrain card).
    * Example Consequence: High-utility cards can give a player significant control over game flow and consistency but might have lower direct board presence (e.g., lower stats on a Unit).
* **Disruptive:**
    * Potential Abilities: Forcing opponents to make suboptimal plays, negating abilities, increasing costs for the opponent, or temporarily disabling types of cards. Note: Rulebook Core Principle "Predictable Gameplay" excludes random elements beyond shuffles and draws.
    * Example Consequence: Disruptive strategies can frustrate opponents and break their combos but may not always advance your own primary win condition directly.
* **Neutral:**
    * Potential Abilities: A balance, perhaps a card that provides a small buff and also allows a card draw, or a unit with average stats that has a useful "enter the battlefield" effect.
    * Example Consequence: These cards aim for solid value without extreme specialization, adaptable to many game states.

##### 3. Combat
* **Offensive:**
    * Potential Abilities: Directly increasing Attack, granting abilities that ensure damage gets through (e.g., cannot be prevented, reduces defender's Defense before combat), attacking multiple times or multiple targets, or abilities that trigger upon destroying an enemy unit.
    * Example Consequence: Highly offensive units can pressure opponents quickly but may be vulnerable if they can't maintain momentum or are easily removed due to lower defenses.
* **Defensive:**
    * Potential Abilities: Increasing Defense, reducing incoming damage, forcing opponents to attack specific units (taunt-like effects), or abilities that punish attackers. Note: Healing damage is not a standard mechanic as units are typically Destroyed or Suppressed, not incrementally damaged. Specific card effects might introduce novel interactions.
    * Example Consequence: Defensive units are key to protecting valuable assets or preventing mission completion/deck out but might lack the ability to close out a game without offensive support.
* **Neutral:**
    * Potential Abilities: Units with balanced stats and perhaps a versatile combat-related ability, like one that can choose to buff its Attack or Defense for a turn.
    * Example Consequence: These units offer flexibility, able to switch roles as needed, but might not excel in either offense or defense as much as specialized units.

##### 4. Impact
* **Constructive:**
    * Potential Abilities: Generating additional CP, putting more units onto the battlefield (e.g., from hand for free, or creating non-card game markers if that were ever a concept, noting standard play uses cards), significantly buffing multiple allies, or accelerating mission completion through non-combat means.
    * Example Consequence: Constructive cards build a strong board presence or resource advantage over time, but can be slow to start or vulnerable to aggressive disruption.
* **Destructive:**
    * Potential Abilities: Removing multiple enemy units, destroying Assets or Terrain, wiping specific types of cards from the board, or significantly setting back an opponent's progress towards their missions.
    * Example Consequence: Destructive cards can clear the way for your own strategy or stall an opponent but might be costly or leave you with fewer resources if they don't sufficiently cripple the opponent.
* **Neutral:**
    * Potential Abilities: Focused on one-for-one trades, direct interaction with single targets, or effects that maintain equilibrium rather than drastically shifting it.
    * Example Consequence: These cards are about maintaining parity or gaining small, incremental advantages.

### B. Card Calculations - Command Point (CP) Cost and Ability Budgeting: The Progressive Budget Build System

> **DESIGN TEAM NOTE:** This section outlines the **"Progressive Budget Build - Version 2 (Dynamic Scaling)"** system, which is the official starting framework for calculating a card's printed Command Point (CP) cost and balancing its stats and abilities. This system replaces any previous methodologies or placeholder notes regarding an internal review.
>
> **Crucially, all specific numerical values presented within this section and its examples (e.g., DB allocations per DP, DB costs for stats, specific abilities, and keywords, and the final DB-to-CP conversion factor) are initial placeholders.** These values serve as a starting point for design work. They **require, and will undergo, rigorous calibration, extensive playtesting, and iterative refinement** by the design team to ensure game balance and achieve the desired strategic depth aligned with the current Quantum Nexus Rulebook. Designers should use this framework for new card creation, understanding that the underlying values will evolve based on playtesting data and balance adjustments.

**1. Overview of the "Progressive Budget Build" System**

The "Progressive Budget Build" system determines a card's playable CP cost by first establishing its total **Total Design Budget (TDB)**. This TDB is an internal design currency (Design Budget points, or DB) derived from the card's foundational nature, its Domain Points (DP), its role (e.g., Leader), and its rarity (duplicate limit). Designers then "spend" this TDB on the card's stats (Attack and Defense) and its various abilities and keywords. The total amount of DB spent directly translates into the card's final CP cost, up to the limit of the TDB. This ensures that a card's cost accurately reflects its allocated power and complexity within defined parameters.

**2. Phase 1: Establishing the Card's Total Design Budget (TDB)**

* **Step 1.1: Foundational Design Budget (FDB)**
    * Every card begins with a small, flat FDB, representing a baseline for its existence.
    * *Placeholder Value:* All cards start with **5 FDB**.

* **Step 1.2: DP-Driven Design Budget (DDB) from Total Domain Points**
    * Each point of Total DP (as defined in Section IV.A of these guidelines and Section II.B, II.C of the Rulebook) contributes a set amount to the card's DDB.
    * *Placeholder Value:* Each Total DP grants **+5 DDB**.

* **Step 1.3: Calculating Base Design Budget (BDB)**
    * `BDB = FDB + DDB`.

* **Step 1.4: Role and Rarity Design Budget Modifiers (DBM)**
    * **Leadership Modifier:** If a card has the 'Leader' subtype (Rulebook Section IV.A), it receives a DBM.
        * *Placeholder Value:* `Leadership DBM = +3 DB (flat) + (20% of the card's BDB)`. (The design team should establish a consistent rounding rule for DBM components if percentages result in fractions, e.g., round to nearest 0.5 DB or whole DB).
    * **Rarity (Duplicate Limit) Modifier:** Cards with stricter duplicate limits (Rulebook Section I.C, II.A) receive a DBM.
        * *Placeholder Values:*
            * 1-of per deck: **+8 DB**
            * 2-of per deck: **+4 DB**
            * 3+-of per deck: **+0 DB**

* **Step 1.5: Calculating Total Design Budget (TDB)**
    * `TDB = BDB + Leadership DBM (if applicable) + Rarity DBM (if applicable)`.
    * This TDB represents the **maximum DB** that can be spent on the card.

**3. Phase 2: Spending the Total Design Budget (TDB)**

* **Step 2.1: Costing Stats (Attack & Defense) in DB**
    * Designers assign Attack and/or Defense values appropriate for the card type.
    * *Placeholder Values:*
        * `Cost_A_DB` (Cost per Attack point) = **2 DB**.
        * `Cost_D_DB` (Cost per Defense point) = **1.5 DB**.
    * `DB_Spent_On_Stats = (Attack Value * Cost_A_DB) + (Defense Value * Cost_D_DB)`.
    * *Calibration Note:* These costs must be balanced against the new combat mechanics (Rulebook Section III.C.2).

* **Step 2.2: Costing Abilities & Keywords in DB**
    * Designers select abilities (Active, Passive, Triggered) and Keywords for the card.
    * **A Master List of DB Costs for Abilities and Keywords must be developed and maintained by the design team.** This list will assign a DB cost to each defined game effect, considering its impact on action economy, board state, resource manipulation, etc., within the current ruleset. (Initial placeholder costs for sample abilities are used in the Section XI example).
    * `DB_Spent_On_Abilities = Sum of DB costs for all chosen abilities and keywords from the Master List`.

* **Step 2.3: Calculating Total Actual DB Spent & Budget Constraint**
    * `Total_Actual_DB_Spent = DB_Spent_On_Stats + DB_Spent_On_Abilities`.
    * **Hard Constraint:** `Total_Actual_DB_Spent` **must be less than or equal to** the card's `TDB`. Designers must adjust stats, abilities, or the card's classification (DP, rarity, role, which influence TDB) to meet this budget.

**4. Phase 3: Calculating Final Playable Command Point (CP) Cost**

* **Step 3.1: Conversion from Total Actual DB Spent to CP**
    * `Final CP = Total_Actual_DB_Spent / CP_Conversion_Factor`.
    * *Placeholder Value:* `CP_Conversion_Factor` = **5** (i.e., 5 DB translates to 1 CP).

* **Step 3.2: Rounding**
    * The resulting CP value should be rounded to a whole number.
    * *Placeholder Rule for Examples:* Round values ending in .5 or higher up to the next whole number; round values ending in .4 or lower down to the previous whole number (standard rounding). The design team must establish a final, consistent rounding rule.

**5. Impact on Design Freedom and Self-Balancing**

This "Progressive Budget Build" system supports key design goals:
* **DP as Strength Indicator:** Higher DP leads to a higher TDB, allowing for inherently stronger or more complex cards.
* **Stats Considered:** Attack and Defense have explicit DB costs.
* **Self-Balancing:** The Final CP cost directly reflects the `Total_Actual_DB_Spent`. If designers choose less DB-costly stats and abilities (thus "underspending" their potential TDB), the card will have a lower Final CP. If they utilize their TDB fully with high-cost features, the Final CP will be higher.
* **Designer Freedom:** Designers determine a card's TDB via DP/role/rarity choices, then have freedom to allocate that TDB between various stats, abilities, and keywords, each with (eventually calibrated) DB costs. Design becomes a process of balancing desired functionality against the available budget.

### C. Functional Attributes
Each card possesses specific attributes that define its capabilities.
* Range (If Applicable to Card Type, e.g., Units): Must conform to current Rulebook definitions (see Section II.B of these Guidelines). The choice of range will have an associated DB cost from the Master List.
* Attack (If Applicable, e.g., Units): The offensive strength. Its value contributes to `DB_Spent_On_Stats`.
* Defense (If Applicable, e.g., Units, Assets): Resilience against attacks or effects. Its value contributes to `DB_Spent_On_Stats`.
* Rule Box: Contains the card's abilities.
    * Active Abilities: Require a player to choose them as a single action during the Activation Sequence and pay all associated costs (CP, exhausting the card, etc.) as specified by the ability (Rulebook Section III.C.2). Each Active Ability will have a DB cost from the Master List.
    * Passive Abilities: Always in effect once the card is in play under the correct conditions. Do not require activation. Each Passive Ability will have a DB cost from the Master List.
    * Triggered Abilities (includes Interrupts): Activate in response to specific game events. Mandatory triggers must be announced and resolved. Optional Interrupts may have costs and allow a choice to activate (Rulebook Section VII.A). Each Triggered Ability will have a DB cost from the Master List.
* Ability Costs (Gameplay vs. Design):
    * **Design Budget (DB) Cost:** An internal value from the Master List representing how much of a card's TDB an ability consumes in its design.
    * **Gameplay Activation Cost:** For Active Abilities, this is the CP (and potentially other resources like exhausting the card, sacrificing, etc.) a player must pay to use the ability during a game. This gameplay cost is separate from its DB design cost but may influence the assignment of its DB cost on the Master List. Printed CP cost of a card is determined by the "Progressive Budget Build" system.

## VI. Card Count Limits (Deckbuilding Restrictions)

The number of copies of a particular card a player can include in their deck is a crucial balancing factor.
* As per the current Quantum Nexus Rulebook (Section I.C, II.A), duplicate limits are printed on each card. No card may ever break these limits.
* Designers will determine this limit (e.g., 1 for very powerful/unique effects, 2 for strong cards, 3 or more for foundational cards) based on the card's intended power level, role, and impact on deck diversity and game balance.
* A card's duplicate limit (rarity) directly contributes a modifier to its Total Design Budget (TDB) as detailed in Section V.B, allowing rarer cards a potentially higher budget for stats and abilities.

## VII. Abilities

Abilities are the core of a card's function and strategic interest.

### A. Types of Abilities
* **Active Abilities:**
    * Chosen by the player as a single action during their turn in the Activation Sequence.
    * Must have clearly defined activation costs (CP, exhausting the card, other resources like discarding cards, sacrificing units, etc.).
    * Effects should be clear and resolve fully.
* **Passive Abilities:**
    * Are continuously active while the card is in play and conditions are met.
    * Do not require player activation.
* **Triggered Abilities (Including Interrupts):**
    * Activate automatically when their specific trigger conditions (defined on the card or by game rules) are met.
    * Resolution follows the layered trigger resolution rules (Rulebook Section VII.A).
    * Mandatory triggered abilities must resolve.
    * Optional Interrupts may allow the player to choose to activate them, potentially by paying a cost (Rulebook Section VII.A).

### B. Ability Design and Costing: Design Budget (DB) System for Balancing Abilities
* **Concept and Theme:** Abilities must align with the card's overall concept, domain, subtype, and flavor. All distinct abilities should be clearly named in the rule box if they are complex or targetable by other effects.
* **Power Level and Balance:** The impact of an ability on the game state must be carefully considered. More powerful or versatile abilities will generally have a higher Design Budget (DB) cost from the Master List (see Section V.B).
* **Design Budget (DB) System:**
    * As detailed in Section V.B ("Progressive Budget Build"), each card has a Total Design Budget (TDB) derived from its DP, role, and rarity.
    * Stats, abilities, and keywords consume DB from this TDB.
    * Each ability or keyword will have a specific DB cost assigned to it on a **Master List of DB Costs**, which must be developed and calibrated by the design team. This DB cost reflects its power, complexity, impact on action economy (especially for Active Abilities), and any associated gameplay activation costs.
    * More impactful abilities will consume more DB. The total DB cost of all a card's features (stats, abilities, keywords) determines its final playable CP cost.
* **Clarity:** Ability text must be precise and unambiguous, using established game terminology consistently. Refer to "Precision Matters" in the Rulebook Core Principles.

## VIII. Keywords and Their Impact on Gameplay

Keywords are shorthand for specific, predefined abilities or characteristics.
* **Purpose:** Keywords streamline card text and establish consistent mechanics.
* **Defining Keywords:** If a new keyword is introduced, its rules must be clearly defined, either on the card itself if it's a one-off, or in the main Rulebook Glossary if it's intended for wider use.
* **Balancing Keywords:** The impact of a keyword must be factored into the card's overall balance via its assigned DB cost within the "Progressive Budget Build" system (Section V.B). Each keyword will have an associated DB cost on the **Master List of DB Costs**.
    * Positive keywords (e.g., granting an advantage) would have a DB cost.
    * Negative keywords (e.g., imposing a drawback) might conceptually have a negative DB cost (i.e., they refund DB to the budget, allowing for better stats or other abilities for its cost), or a very low positive DB cost if their drawback is minor. This needs careful consideration during Master List calibration.
    * Neutral keywords (e.g., defining a specific mode of operation) would also have a DB cost reflecting their complexity or utility.

> **DESIGN TEAM NOTE:** A Master List of official game Keywords and their Design Budget (DB) costs will be developed and maintained by the design team as part of the "Progressive Budget Build" system's calibration (see Section V.B).

## IX. Flavor Attributes

Thematic elements are vital for an immersive experience.
* **A. Name:** Should be evocative, memorable, and reflect the card's theme and mechanics.
* **B. Image:** Art descriptions provided by designers should be detailed enough to guide an artist, capturing theme, mood, domain elements, and action.
* **C. Flavor Text:** Short, impactful text that adds lore or personality without affecting game mechanics.

## X. Synergies

Designing for synergies creates strategic depth and rewards creative deck-building. This section illustrates how different synergistic approaches can be fostered through card design.
### A. Types of Synergies
* **Theme-Based Synergies:** Cards sharing lore or conceptual themes can have abilities that naturally complement each other. Example: A "Scrap Welder" unit might get stronger if you have many "Mech" subtype cards in your discard pile. Consequence: Encourages thematic deck building but might be narrow if the theme isn't well-supported.
* **Domain Synergies:** Cards within the same domain (Technology, Magic, etc.) can be designed to enhance each other. Example: A Magic Asset might reduce the CP cost of Magic Events. Consequence: Promotes domain-focused decks, potentially at the cost of inter-domain flexibility unless designed for.
* **Subtype Synergies:** Cards sharing a common subtype (e.g., "Drone," "Soldier," "Spirit") can have abilities that specifically benefit or are triggered by other cards of that subtype. Example: A "Drone Swarm Leader" might give +1 Attack to all other friendly "Drone" units. Consequence: Leads to strong tribal archetypes but can be vulnerable if the key "leader" or enabler is removed.
* **Leader Abilities:** Leaders should be designed with abilities that create clear strategic directions or synergize strongly with particular types of units, domains, or strategies. Example: A Leader might allow you to pay CP to ready exhausted units of its specific Faction subtype. Consequence: Makes the Leader a central, high-value target for the opponent.
* **Upgrade Interactions:** Upgrades should be designed to create powerful and interesting effects when attached to suitable Units or Assets. Example: An Upgrade granting "attacks target all units in target quadrant" would be very different on a low-attack unit versus a high-attack unit. Consequence: Adds a layer of resource management and decision-making about when and where to deploy Upgrades.
* **Event and Terrain Interactions:** Events can be designed to have amplified effects if certain Terrain types are in play, or if specific unit subtypes are present. Terrain can offer benefits tailored to certain domains or strategies. Example: An Event "EMP Burst" might destroy all Technology Assets, but if you control a "Shielded Command Center" Terrain, your Assets are protected. Consequence: Adds tactical depth based on board state.
* **Inter-Domain Synergies:** Design opportunities exist for cards that bridge domains, creating less obvious but potentially powerful interactions. Example: A Technology unit that benefits from the number of distinct spells (Magic) cast in a turn. Consequence: Encourages more complex, multi-domain deck building.
* **Ability Combos:** Design abilities on different cards that, when used in sequence or combination, produce a more powerful effect than if used separately. Example: Card A places a "Target Lock" on an enemy unit. Card B deals double damage to units with a "Target Lock." Consequence: Rewards skillful sequencing and can create powerful game-swinging moments, but requires drawing and playing multiple specific cards.

### B. Balancing Synergies
Synergies should be rewarding but not so overwhelmingly powerful or easy to achieve that they stifle strategic diversity. Avoid infinite loops or game-breaking two-card combos unless they are extremely difficult to set up or are a core, intended high-risk/high-reward strategy. The DB cost of abilities that enable strong synergies should reflect this potential.

### C. Discovery and Exploration
Aim to include some less obvious synergies that players can discover through experimentation, rewarding deeper game knowledge and creative deck-building.

### D. Playtesting and Feedback
Thorough playtesting is essential to ensure synergies work as intended, are appropriately powerful, and do not lead to unintended negative play experiences.

## XI. Card Creation Example

This example uses the **"Progressive Budget Build - Version 2 (Dynamic Scaling)"** system outlined in Section V.B and the **placeholder values defined therein for illustrative purposes.**

* **Concept:** A high-tech aerial unit for long-range attacks and reconnaissance.
* **Card Type and Subtype:** Unit - Drone
* **Domain Points (DP):** Technology 4 (Total DP = 4)
* **Rarity (Assumed for example):** 3+-of per deck (Standard)
* **Leadership:** Not a Leader

**1. Calculate Total Design Budget (TDB):**
    * FDB (Foundational Design Budget) = 5 DB
    * DDB (DP-Driven, for 4 DP) = 4 DP * 5 DB/DP = 20 DB
    * BDB (Base Design Budget) = 5 FDB + 20 DDB = 25 DB
    * Leadership DBM = +0 DB (Not a Leader)
    * Rarity DBM (for 3+-of) = +0 DB
    * **TDB = 25 DB + 0 DB + 0 DB = 25 DB**

**2. Spend TDB on Stats and Abilities:**

    * **Target Stats: Attack 4, Defense 1**
        * DB for Attack 4 = 4 * 2 DB/Attack (`Cost_A_DB`) = 8 DB
        * DB for Defense 1 = 1 * 1.5 DB/Defense (`Cost_D_DB`) = 1.5 DB
        * `DB_Spent_On_Stats` = 8 + 1.5 = **9.5 DB**

    * **Target Abilities & Keywords:**
        * "Far Range" Attribute: *Placeholder DB Cost:* **6 DB**
        * Passive: "Reconnaissance Scan" (Original concept: Look at top of opponent's deck, may bottom it): *Initial Placeholder DB Cost:* **7 DB**
        * Active: "Targeted Laser Strike" (Gameplay Activation Cost: 2 CP, Exhaust this Unit) - Choose a unit. It gets -2 Defense this turn. *Placeholder DB Cost:* **5 DB**
        * Keyword: "Flying" (Assumed implies special targeting): *Initial Placeholder DB Cost:* **4 DB**
        * Initial `DB_Spent_On_Abilities` = 6 (Far Range) + 7 (Scan) + 5 (Laser Strike) + 4 (Flying) = **22 DB**.

    * **Initial Total Actual DB Spent & Budget Check:**
        * `Total_Actual_DB_Spent` = 9.5 (Stats) + 22 (Abilities) = **31.5 DB**.
        * Budget Check: Available TDB = 25 DB. Actual DB Spent = 31.5 DB.
        * **Result: Over budget by 6.5 DB.**

    * **Design Iteration Example for Sky Warden Drone:**
        The initial concept exceeds the TDB for a 4DP common Unit. The designer must make adjustments to fit within the 25 DB budget.
        * *Decision:* Remove the "Flying" keyword (saves 4 DB) and simplify "Reconnaissance Scan" to "At the start of your Activation Sequence, you may look at the top card of an opponent's deck" (reducing its complexity and placeholder DB cost from 7 DB to 4 DB, saving 3 DB). Total DB saved = 7 DB.
        * Revised `DB_Spent_On_Abilities` = 6 (Far Range) + 4 (Simplified Scan) + 5 (Laser Strike) = **15 DB**.
        * Revised `Total_Actual_DB_Spent` = 9.5 (Stats) + 15 (Abilities) = **24.5 DB**.
        * This revised design (24.5 DB) is now within the TDB of 25 DB.

**3. Calculate Final CP (Using the iterated design):**

    * `Total_Actual_DB_Spent` = 24.5 DB.
    * `CP_Conversion_Factor` (Placeholder) = 5.
    * `Final CP = 24.5 DB / 5 = 4.9 CP`.
    * Rounding (Placeholder: standard rounding, halves up): **Final CP = 5**.

* **Final Sky Warden Drone (Example for Guidelines):**
    * **CP Cost:** 5
    * **Card Type:** Unit - Drone
    * **Domain Points:** Technology 4
    * **Stats:** Attack 4, Defense 1
    * **Range:** Far
    * **Abilities:**
        * Passive: "Reconnaissance Scan (Lite)" - At the start of your Activation Sequence, you may look at the top card of an opponent's deck.
        * Active: "Targeted Laser Strike" - (Activation Cost during gameplay: 2 CP, Exhaust this Unit) - Choose a unit. It gets -2 Defense this turn.
    * **Flavor Text:** "Its silent vigil maps the unseen paths to victory."
    * **Image Description:** A sleek, angular drone with multiple optical sensors and a prominent energy emitter, patrolling high above a futuristic cityscape, with data streams faintly visible around its sensors.
* **Key Design Considerations Note for Example:**
    This Sky Warden Drone has a final playable cost of 5 CP. Its 4 Domain Points (as a common, non-Leader card) provided a Total Design Budget (TDB) of 25 DB using the system's placeholder values. The chosen stats (A4/D1) cost 9.5 DB. The initial desired abilities (Far Range, full Reconnaissance Scan, Targeted Laser Strike, and Flying) would have cost 22 DB, leading to a total of 31.5 DB, exceeding the available TDB.
    Through design iteration, the "Flying" keyword was removed and "Reconnaissance Scan" was simplified to reduce their combined DB cost. The final set of abilities cost 15 DB.
    The `Total_Actual_DB_Spent` of 24.5 DB, when divided by the placeholder `CP_Conversion_Factor` of 5, yielded its 5 CP cost. This example illustrates the trade-offs inherent in the "Progressive Budget Build" system. **All Design Budget (DB) costs for abilities/keywords and system parameters are placeholders requiring team calibration through extensive playtesting.**

## XII. Advanced Card Mechanics (Conceptual)

These are ideas for designers to explore, ensuring they align with the core rules and balance. Any new mechanics would require DB costs to be defined on the Master List.
* Keywords and Status Effects: Consider if new keywords (like "Stealth," "Precise," "Shielded X") or unique status effects (beyond "Suppressed" or "Disordered") could add depth. Any new persistent keyword or status effect would need clear rules defined, potentially in the main Rulebook, and an associated DB cost.
* Combo Potential: Design cards that might have non-obvious but powerful interactions.
* Conditional Effects: Abilities that trigger or vary based on game state (e.g., number of cards in hand, specific Mission Cards completed, presence of certain subtypes or domains in play).
* Transforming Cards: Units or Assets that might change into a different version of themselves (new stats/abilities) if certain conditions are met. This would require clear rules on how transformation occurs and how it's costed in DB.

## XIII. Design Considerations

* **Balance:** Crucial. Strive for balance between card types, domains, individual card power, and strategies. The goal is a diverse and healthy metagame. The "Progressive Budget Build" system is a tool to aid this, but final balance comes from careful calibration and playtesting.
* **Originality:** Aim for innovative mechanics and thematic concepts.
* **Flavor:** Ensure mechanics, art, name, and flavor text create a cohesive and immersive whole.
* **Engagement:** Design cards that offer interesting decisions, promote interaction, and are enjoyable to play with and against.
* **Accessibility:** Card text should be clear and use consistent terminology. Complex abilities should be worded as unambiguously as possible.

## XIV. Playtesting and Iteration

Playtesting is non-negotiable.
* **Internal Playtesting:** Test new designs rigorously within the design team, focusing initially on the calibration of DB costs within the "Progressive Budget Build" system.
* **Wider Playtesting:** If possible, involve a broader group of trusted testers once initial DB cost calibrations are more stable.
* **Iterative Refinement:** Be prepared to modify or discard designs based on playtest feedback to achieve balance and optimal playability. The Master DB Cost Lists for abilities and keywords will be living documents, updated based on playtesting insights.

## XV. Mission Card Design

> DESIGN TEAM NOTE: The principles and specific parameters for designing Mission Cards (including balancing their CP values provided to players each round, objective complexity, passive effects, and any abilities they grant) are detailed in a separate, official "Quantum Nexus: Mission Card Design Document."
>
> Designers assigned to create or revise Mission Cards must consult this dedicated document. These Card Creation Guidelines focus on the design of cards that form a player's main deck.

## XVI. Conclusion

The Quantum Nexus card creation process is a blend of creativity, strategic design, and rigorous refinement. By adhering to these evolving guidelines, understanding the core Quantum Nexus Rulebook, utilizing the "Progressive Budget Build" system, and embracing iterative playtesting, designers can craft unique, balanced, and engaging cards that enrich this dynamic sci-fi universe.

## Appendix

### A. Glossary of Design Terms
(This glossary is for designer use and may contain terms not in the player-facing Rulebook. It will be updated to reflect finalized internal terminology based on the "Progressive Budget Build" system.)

* **Activation Sequence:** The part of a Game Round where players take alternating single actions. (Rulebook term)
* **Base Design Budget (BDB):** An intermediate value in card costing, derived from a card's Foundational Design Budget (FDB) and its DP-Driven Design Budget (DDB).
* **Card Feel Matrix:** An internal design tool using axes like Malevolence, Utility, Combat, and Impact to guide a card's thematic and mechanical identity.
* **Command Points (CP):** The primary resource in the game, gained each round (primarily from Mission Cards) and spent to deploy cards and activate abilities. (Rulebook term) The playable CP cost printed on cards is determined by the "Progressive Budget Build" system.
* **`CP_Conversion_Factor`:** The rate at which `Total_Actual_DB_Spent` is converted to playable CP in the "Progressive Budget Build" system. (Placeholder value needs calibration).
* **Design Budget (DB):** An internal design currency used within the "Progressive Budget Build" system to quantify the cost of stats, abilities, and keywords during card creation.
* **Domain Points (DP):** A numerical value indicating a card's thematic connection to the four domains. DP contribute to a card's Total Design Budget (TDB) and are used in player-facing rules for Mission Card setup and Unit inclusion.
* **DP-Driven Design Budget (DDB):** The portion of a card's Design Budget derived directly from its Total Domain Points.
* **Foundational Design Budget (FDB):** A small, flat DB amount all cards start with in the "Progressive Budget Build" system.
* **Internal Design Tags (Formerly "Ranks"):** Terms like "Terrestrial," "Aerial," used by designers for thematic categorization, not as player-facing mechanics.
* **Master DB Cost List(s):** Essential companion documents (to be developed) detailing the DB cost for every standard ability effect and keyword in the game, used with the "Progressive Budget Build" system.
* **Total Actual DB Spent:** The sum of all DB costs for a card's chosen stats, abilities, and keywords. This value is used to calculate the Final CP cost.
* **Total Design Budget (TDB):** The maximum DB a card can have in the "Progressive Budget Build" system, derived from its Base Design Budget (BDB) and modifiers for role (Leader) and rarity (duplicate limit). A card's `Total_Actual_DB_Spent` cannot exceed its TDB.
* *[Obsolete Term for Costing System:] Ability Point (AP).*

### B. Design Tips
* Start with a Clear Concept: Define the card's role, theme, and intended interactions.
* Prioritize Fun and Engagement: Design cards that create interesting decisions and enjoyable gameplay moments.
* Embrace Simplicity Where Possible: Complex interactions are good, but individual card text should strive for clarity.
* Consider All Game States: How does the card perform in the early, mid, and late game? When ahead, behind, or at parity?
* Design for the Current Rulebook: All mechanics must function cleanly within the latest version of the Quantum Nexus Rulebook. The "Progressive Budget Build" system aims to cost features based on their impact within these rules.
* Iterate Relentlessly: Playtesting will reveal what works and what doesn't. Be prepared to change any aspect of a card, including re-evaluating its DB costs against the Master Lists as those lists themselves get calibrated.

*(Previous Appendices C, D, and E, which detailed AP costs for abilities and keywords under an old system, are now obsolete. They are superseded by the need to develop and maintain comprehensive **Master DB Cost Lists for Abilities and Keywords** as integral components of the "Progressive Budget Build" system.)*

### F. Design Considerations for Different Card Types

When using the "Progressive Budget Build" system, consider these nuances for different card types:

1.  **Units**
    * **Stats and Role:** Balance Attack and Defense DB costs according to the unit's intended role (offensive, defensive, utility). Consider its synergy with the current combat outcomes (Suppressed, Disordered, Pushed Back).
    * **Abilities:** Design abilities that complement its stats and role. Active Abilities consume an action slot in the Activation Sequence, which should be a major factor in their DB cost on the Master List.
    * **Range:** The choice of range (Close, Mid, Far as per current Rulebook) will have a DB cost from the Master List.
2.  **Leaders**
    * **Impact:** The Leadership DBM grants Leaders a higher TDB, allowing for more significant or numerous abilities. Their abilities should be impactful, aligning with their unique status and deckbuilding restrictions.
    * **Synergy:** Design abilities that synergize with specific domains, subtypes, or strategies.
3.  **Upgrades**
    * **Enhancement Focus:** Should clearly enhance a player's own Unit or Asset. Balance the DB cost of its stat boosts or granted abilities against its TDB (which, for an Upgrade, will likely be based on its DP and Rarity only, not Leadership).
4.  **Assets**
    * **Persistent Value:** Effects should provide ongoing or strategically valuable activated abilities from the Loadout Area. Assets typically only have a Defense stat; their `DB_Spent_On_Stats` will reflect this. Their TDB will allow for DB to be spent on their persistent or activated abilities.
    * **Survivability:** Their Defense value's DB cost should be balanced against their impact.
5.  **Events**
    * **Immediate Impact:** Events have no stats and are transient. Their TDB (derived from DP and Rarity) is spent entirely on the DB cost of their one-time effect(s). The DB cost of Event effects on the Master List must be carefully calibrated for their immediate impact relative to cards that remain in play.
    * **Action Economy:** Playing an Event is a single action; its effect's DB cost must reflect this.
6.  **Terrain**
    * **Battlefield Impact:** Terrain cards modify quadrants. Beyond the inherent +1 Defense bonus per Terrain card (which is a game rule, not something bought with DB for that specific Terrain card, though its existence might influence general Terrain TDB baselines), their printed rule box effects will have DB costs. Their TDB will be spent on these unique quadrant-altering abilities. Adhere to the limit of two Terrain per player per quadrant.

By considering these design considerations for each card type within the "Progressive Budget Build" system, you can ensure that your creations are balanced, engaging, and contribute to the rich tapestry of Quantum Nexus gameplay. The Master DB Cost Lists will be essential in reflecting these type-specific considerations.