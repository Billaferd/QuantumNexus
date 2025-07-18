### **Quantum Nexus: Card Creation Guidelines**

Note to the Reader

This is the Quantum Nexus: Card Creation Guidelines. This document is not meant to explain any rules that a player would need; it is solely intended to aid designers in creating captivating and interesting cards for Quantum Nexus. Players are welcome to read this document, but please know that these rules are not applied to any in-game scenario; they are solely intended for creating cards for Quantum Nexus.


### **I. Introduction**

Quantum Nexus is a strategic trading card game (TCG) that immerses players in a captivating sci-fi universe filled with advanced technology, mystical magic, potent psionics, divine intervention, rampant biology, and the creeping decay of entropy. To contribute to this dynamic world, card creators must adhere to a set of core design principles and understand the fundamental building blocks of card creation.


#### **A. Core Design Principles**

- **Card Control:** Each player retains complete ownership and control of their cards throughout the game. Players are not allowed to touch any other player's cards, and a player's cards are not allowed to leave that player's play area. This aligns with Section V.F of the Quantum Nexus Rulebook.

- **Predictable Gameplay:** The only random element in Quantum Nexus is initial card shuffles and the card draw during the Start of Round Step. This design choice eliminates luck-based mechanics like dice rolls or coin flips, ensuring that strategic decision-making and tactical planning are the primary factors that determine the outcome of battles.

- **Streamlined Combat:** Units in Quantum Nexus do not have health points. Instead, their resilience is represented by a Defense value. When a unit is attacked, its Defense is compared to the attacker's Attack value. The outcomes are specific:

* If Attack is greater than Defense, the defending unit is destroyed.

* If Attack equals Defense, the defending unit becomes Suppressed (it exhausts), and it can be destroyed by any attack until it is no longer Suppressed.

* If Attack is less than Defense, the attack fails and there is no consequence other than the attackers becoming exhausted.


### **II. Battlefield, Range, and Movement**

Understanding the battlefield, card range, and unit movement as defined in the current Quantum Nexus Rulebook is crucial for effective card design.


#### **A. Battlefield Structure**

The Quantum Nexus battlefield for each player consists of a 3x2 grid, comprising six distinct quadrants (Front Left, Front Center, Front Right, Back Left, Back Center, Back Right). Units are deployed into their controller's own quadrants and never physically enter an opponent's play area or quadrants. For targeting purposes, a player's Front Row is considered to be facing each opponent's Front Row. (See Rulebook Section V.E).


#### **B. Range Types**

Each Unit card designed to attack or affect other cards at a distance must have a defined range. These ranges dictate which quadrants it can target, relative to its current position. The official range definitions are in Section VIII (Glossary) of the Quantum Nexus Rulebook. Designers must use these current definitions:

- **Close Range:** A unit with a Close Range attack or ability can target its own current quadrant AND one existing quadrant directly Forward, Backward, Left, and Right of its current quadrant. A unit declaring an attack with Close Range may target its own unit in its own quadrant.

- **Mid Range:** A unit with a Mid Range attack or ability can target one existing quadrant directly Forward, Backward, Left, Right, Forward-Left Diagonal, Forward-Right Diagonal, Backward-Left Diagonal, and Backward-Right Diagonal from its current quadrant. Mid Range does not include the attacking unit's own current quadrant.

- **Far Range:** An attack range allowing a unit to target all quadrants located exactly two rows ahead of its current row, on an opponent's side of the battlefield. Units in a player's Front Row target all quadrants in the opponent's Back Row. Units in a player's Back Row target all quadrants in the opponent's Front Row. Far Range does not include the attacking unit's own current quadrant.

Careful consideration of these ranges is essential for balancing a unit's offensive and defensive capabilities and its tactical role.


#### **C. Movement**

In the current Quantum Nexus rules (Section III.C.2), moving a unit is a specific single action a player can choose during their turn in the Activation Sequence.

- A player chooses one of their ready units.

- The unit moves one quadrant in a cardinal direction (Forward, Backward, Left, or Right) to an adjacent friendly quadrant.

- The destination quadrant may be occupied by other friendly units (respecting the "one Leader per quadrant" rule).

- The unit that moved then becomes exhausted as the cost of this action.

Card designs, particularly for units, should consider this action economy for movement. Abilities that grant movement or affect movement should be designed with this baseline rule in mind.


#### **D. Internal Design Tags & Card Type Theming**

The terms **Terrestrial, Aerial, Orbital,** and **Interstellar** are internal design tags used to guide a card's thematic concept and its relationship to the game's mechanical card types. These tags should not appear on cards as a player-facing property.

- **Terrestrial & Aerial (Battlefield Presence):**

* **Thematic Guide:** These tags suggest concepts that operate directly on a planet's surface or in its atmosphere—ground troops, tanks, flyers, beasts, etc. They represent direct, physical presence and engagement.

* **Mechanical Tie-in:** These themes are best suited for card types that are deployed onto the **Battlefield** grid: **Units** and **Terrain**. A "Terrestrial" card is typically a ground unit, while an "Aerial" card is a flying unit. Both occupy quadrant space and interact directly with the board.

- **Orbital & Interstellar (Strategic Influence):**

* **Thematic Guide:** These tags suggest concepts that exert influence from a distance—orbiting satellites, command ships, fleet-wide directives, or battlefield-wide phenomena. They represent strategic assets and overarching effects rather than individual combatants.

* **Mechanical Tie-in:** These themes are best suited for card types that are deployed to the **Loadout Area** or have non-physical effects: **Assets** and **Events**. An "Orbital" Asset could be a targeting satellite providing a bonus. An "Interstellar" Event could be a solar flare affecting all players.


#### **E. Game Round Structure**

Designers must create cards that function within the Game Round Structure detailed in Section III.C of the Quantum Nexus Rulebook. This structure is not based on distinct, shared phases like "Deployment Phase" or "Command Phase." Instead, it consists of:

- **Start of Round Step:** This occurs simultaneously for all players.

* All previously exhausted cards are deactivated (readied).

* Players gain their Command Points (CP) for the round (derived from their Mission Cards plus any other "start of round" effects).

* Players draw cards until they have five cards in their hand.

* Relevant triggered abilities resolve. This happens in a layered fashion: first, any abilities triggered by the simultaneous refresh actions (like drawing a card) resolve, followed by the resolution of any abilities that specifically trigger "at the start of the Game Round."

- **Activation Sequence:** Following the Start of Round Step, players take turns performing single actions.

* The player with initiative takes the first single action.

* Available single actions are: Deploy a Card, Activate an Active Ability, Declare an Attack, Play an Event Card, Move a Unit, or Pass.

* After an action and any resulting triggered abilities fully resolve, the next player in clockwise order takes a single action.

* This continues until all players consecutively Pass.

Initiative for the first round is determined by a card flip; for subsequent rounds, it goes to the player who passed first to end the previous Activation Sequence (Rulebook Section III.D). Card abilities, costs, and effects must be designed with this alternating single-action economy in mind.


### **III. Card Types, Subtypes, and Factions**

Quantum Nexus features a diverse range of card types, each playing a unique role. Designers should adhere to the definitions and roles outlined in Section IV of the Quantum Nexus Rulebook.


#### **A. Card Types**

- **Units:** The core of a player's forces. Units have Attack and Defense values and a defined range (if applicable). As a 'Deploy a Card' action, Units are always deployed into a quadrant on the player's **Back Row**. To engage further, a unit must be moved from the Back Row to the Front Row by using a "Move a Unit" action during one of the player's subsequent activations. A single quadrant has a capacity of four standard-sized units, which must be respected when deploying or moving units.

- **Leaders:** Special, powerful units. Only one of a player's Leaders can occupy one of their quadrants at a time. Each deck is limited to a maximum of 25 CP worth of Leader cards (Rulebook Section IV.A, II).

- **Upgrades:** Cards that modify a player's own Units or Assets, enhancing their stats or granting new abilities. They are deployed attached to the target card. (Rulebook Section IV.D)

- **Assets:** Persistent cards deployed to the player's Loadout Area. They provide ongoing benefits or activate special abilities. Assets have a Defense value but no Attack value and cannot inherently declare an Attack action. (Rulebook Section IV.B)

- **Events:** Played as a single action during the Activation Sequence by paying their CP cost. They provide powerful one-time effects and are then typically discarded. (Rulebook Section IV.C)

- **Terrain:** Deployed into a player's own quadrants on the Battlefield. Terrain does not take up a unit slot, instead this is a separate and distinct constraint. A player can have a maximum of two of their own Terrain cards in any single quadrant. If a non-numerical effect from a Terrain card active in a quadrant explicitly negates, prevents, or forbids an action, state, or condition that another non-numerical effect active in or targeting that same quadrant (whether from another Terrain card, a Unit ability, an Event card, or any other game source) explicitly permits, enables, or creates, and the rules do not specify a hierarchy (e.g., 'card effects override game rules'), then neither of those specific, directly conflicting effects is applied. (Rulebook Section IV.E)

- **Mission Cards:** These are a distinct category of cards, crucial for deck construction (defining Unit domain point allowances), providing base CP per round, and offering powerful strategic abilities. (Design principles for Mission Cards are covered in a separate document; see Section XV).


#### **B. Subtypes**

In addition to their main type, most cards have one or more subtypes (e.g., "Mech," "Bioweapon," "Celestial," "Technomancer"). Subtypes add specificity and can interact with card abilities or game rules, providing thematic and mechanical hooks. (Rulebook Section I.C).


### **IV. Domain System: Philosophy and Identity**

In Quantum Nexus, cards are thematically linked to one or more of six key domains: **Technology, Magic, Psionics, Divinity, Biology, and Entropy**. These domains shape a card's identity, abilities, and flavor. The primary mechanical impact of Domains for players is in deck construction, where Mission Card domain point totals restrict the inclusion of playable cards (Rulebook Section II.B, II.C).

Our design is built on two interconnected layers: the **Domain Pie** and **Domain Points (DP)**.

- **The Domain Pie (The "What"):** This is the high-level **philosophical boundary** for each of the six domains. It defines what a domain is fundamentally about. It dictates the types of abilities and themes a domain can access (its strengths) and, critically, what it _cannot_ access (its weaknesses). The Domain Pie establishes a domain's core identity.

- **Domain Points (The "How Much"):** This is the measure of **commitment and power** within a domain's allowed "slice" of the pie. A card's total DP across all domains **cannot exceed 6**, and no single domain can have more than 4 points assigned to it. The DP value dictates the magnitude, efficiency, and complexity of its abilities. A higher DP value doesn't unlock abilities from other domains; it unlocks a more powerful and focused version of what its own domain already does best.

In short: **The Domain Pie sets the menu, and the Domain Points tell you how powerful a dish from that menu you can order.**


#### **A. The Technology Domain**

**Core Philosophy:** Technology is the domain of **building, optimization, and resource generation**. It creates resilient, synergistic engines that start slow but become overwhelmingly powerful in the late game. It is methodical, logical, and persistent.

**Strengths:**

- Assets & Upgrades: Excels at deploying, protecting, and benefiting from these card types.

- CP Generation: The primary domain for generating additional Command Points through non-combat means.

- Resilience: Gets the most durable units for their cost, often featuring high Defense and keywords like Steadfast.

**Weaknesses:**

- Inefficient Unit Removal: Cannot have cheap, direct "destroy target unit" Event cards. Removal must come from combat or specific, often clunky, machine-based interactions.

- No Hand Interaction: Cannot have cards that force opponents to look at or discard cards from their hand.

- Poor Tempo: Is inherently slow. It cannot have cheap, aggressive units with high Attack for their cost.

|                              |                                                                |                                                                                                                                                                                                                                           |
| ---------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Domain Level (DP)**        | **Thematic Representation**                                    | **Example Card Attributes (Abilities, Stats, etc.)**                                                                                                                                                                                      |
| 1: Basic Component           | An efficient, single-purpose part of a larger machine.         | **Stats:** A unit with low Attack but decent Defense for its cost (e.g., 1/3).\<br> **Ability:** A simple, direct effect like "+1 Defense" on an Upgrade, or "The next Asset you play costs 1 less CP."                                   |
| 2: Integrated System         | Components working together in a synergistic engine.           | **Stats:** A mid-cost unit with solid defensive keywords like Steadfast.\<br> **Ability:** Effects that rely on other tech cards, such as "This unit gets +1/+1 for each Asset you control," or "Your 'Construct' units have +1 Defense." |
| 3: Advanced Infrastructure   | A powerful, self-sustaining engine providing repeatable value. | **Ability:** Powerful active abilities on Assets, like "Active: Exhaust this Asset. Gain 1 CP and draw a card." or passive effects on Upgrades like "Attached unit's Active abilities cost 1 less CP to activate."                        |
| 4: Technological Singularity | An apex creation; the ultimate expression of the engine.       | **Ability:** Game-defining passive or interrupt effects on high-cost Leaders or unique units. For example, "Interrupt: When this unit would be destroyed, you may instead destroy an Upgrade attached to it and prevent the destruction." |


#### **B. The Magic Domain**

**Core Philosophy:** Magic is the domain of **rule-bending, card advantage, and powerful one-time Events**. It sacrifices board presence and unit durability for spectacular, game-altering effects. It is chaotic, powerful, and fleeting.

**Strengths:**

- Event Cards: Has exclusive access to the most powerful and flexible Event cards.

- Card Draw & Filtering: The primary domain for drawing extra cards and searching the deck.

- Non-Standard Removal: Excels at effects that bypass combat, such as returning units to hand.

**Weaknesses:**

- Fragile Units: Magic-based units are "glass cannons" with low base Defense values for their cost.

- Inefficient Board Presence: Cannot have cost-effective units with high base stats. Its power is in its spells.

- Limited Asset Interaction: Cannot have efficient ways to destroy or interact with an opponent's Assets.

|                          |                                                            |                                                                                                                                                                                                                                    |
| ------------------------ | ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Domain Level (DP)**    | **Thematic Representation**                                | **Example Card Attributes (Abilities, Stats, etc.)**                                                                                                                                                                               |
| 1: Cantrip / Minor Glyph | A simple, fleeting spell with a minor effect.              | **Ability:** An Event that lets you "Look at the top two cards of your deck; put one into your hand and the other on the bottom," or an effect that grants a unit a temporary, non-combat keyword for a turn.                      |
| 2: Standard Spellcraft   | The core repertoire of a spellcaster.                      | **Stats:** A "glass cannon" unit with low Defense but a strong ability (e.g., "When you play an Event, this unit gets +2 Attack this turn").\<br> **Ability:** An Event that lets you "Draw 2 cards," or "Destroy target Upgrade." |
| 3: Advanced Ritual       | A complex spell that directly warps the rules of the game. | **Ability:** An Event that can "Return target unit with CP cost 5 or less to its owner's hand," or an Asset that allows you to "Copy the next Event you play this turn."                                                           |
| 4: Arcane Mastery        | A game-ending spell of immense power.                      | **Ability:** A very high-cost Event with an effect like "Destroy all Assets and Terrains in play," or "Target opponent reveals their hand and discards all Event and Asset cards."                                                 |


#### **C. The Psionics Domain**

**Core Philosophy:** Psionics is the domain of **control, manipulation, and information**. It wins by out-thinking and disabling the opponent, not by overwhelming them with brute force. It is precise, subtle, and tactical.

**Strengths:**

- Combat Manipulation: The master of combat "tricks" and applying status effects like Suppressed.

- Information Warfare: The only domain that can look at an opponent's hand or deck.

- "Soft" Control: Excels at disabling enemy units without destroying them (preventing abilities, movement, etc.).

**Weaknesses:**

- Poor Non-Unit Interaction: Cannot have efficient ways to destroy Assets, Upgrades, or Terrain.

- Lacks Brute Force: Cannot have effects that deal large amounts of direct damage or provide huge, sweeping Attack buffs.

- No CP Generation: Cannot have cards that generate extra CP. It must work within the standard resource curve.

|                            |                                                               |                                                                                                                                                                                                                             |
| -------------------------- | ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Domain Level (DP)**      | **Thematic Representation**                                   | **Example Card Attributes (Abilities, Stats, etc.)**                                                                                                                                                                        |
| 1: Basic ESP / Telekinesis | A minor mental push or a brief glimpse of the future.         | **Ability:** A simple combat trick Event like "Target friendly unit gets +2 Attack this turn." or "Look at the top card of any player's deck."                                                                              |
| 2: Focused Mind            | A trained mind capable of tactical influence.                 | **Ability:** Effects that apply status effects ("Active: Exhaust this unit. Inflict Suppressed on target unit.") or provide crucial information ("Interrupt: When this unit is deployed, look at target opponent's hand."). |
| 3: Mental Domination       | Proactive control that shuts down an opponent's options.      | **Stats:** A unit with low Attack but a powerful passive ability like "Enemy units in this unit's quadrant cannot use Active abilities."\<br> **Ability:** An Event like "Target enemy unit cannot attack this Game Round." |
| 4: Psionic Supremacy       | Total command of the battlefield through sheer force of will. | **Ability:** A Leader-only passive aura like "Enemy units in this unit's column lose all keywords," or an Event that allows you to "Look at target opponent's hand and choose a non-Leader card. They discard that card."   |


#### **D. The Divinity Domain**

**Core Philosophy:** Divinity is the domain of **faith, attrition, and otherworldly miracles**. Power is granted as a reward for devotion, manifesting as resilience, recursion, and profound, board-sweeping judgments. It is reactive, inevitable, and awe-inspiring.

**Strengths:**

- Recursion & Resilience: The best domain at bringing cards back from the discard pile and surviving destruction.

- Symmetrical Effects: Excels at board-wipes or effects that harm all units, as its strategy is built to benefit from the chaos.

- Ignoring Defenses: Can have effects that destroy units regardless of their stats, representing divine judgment.

**Weaknesses:**

- Poor Resource Engine: Cannot have efficient card draw or CP generation. Its advantage must be generated on the board.

- Lacks Proactivity: Is fundamentally reactive or "grindy." It cannot have cheap, fast, aggressive units.

- No "Targeted" Disruption: Its disruptive effects are often broad and sweeping, not precise.

|                                 |                                                                 |                                                                                                                                                                                                                                       |
| ------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Domain Level (DP)**           | **Thematic Representation**                                     | **Example Card Attributes (Abilities, Stats, etc.)**                                                                                                                                                                                  |
| 1: Pledge of Faith              | A small prayer or minor reward for martyrdom.                   | **Stats:** A low-cost unit with an on-death trigger.\<br> **Ability:** "Interrupt: When this unit is destroyed, you gain 1 CP," or an Event like "Choose a friendly unit. The next time it would be destroyed this round, it is not." |
| 2: Demonstrated Devotion        | A tangible miracle granted for continued faith.                 | **Ability:** Single-target recursion like "Return a unit with CP cost 3 or less from your discard pile to your hand," or an effect that removes all negative status effects from a friendly unit.                                     |
| 3: Divine Intervention          | A major, board-altering miracle.                                | **Ability:** A powerful, symmetrical Event like "Each player sacrifices a unit," or "Destroy all Upgrades in play." A Divinity deck is built to break the symmetry and benefit more from these effects.                               |
| 4: The Avatar / Absolute Decree | The direct will of a god, creating an inevitable win condition. | **Ability:** A high-cost Leader with a passive like "At the start of your turn, you may return one unit from your discard pile to play exhausted," or a Mission with a unique, alternate win condition.                               |


#### **E. The Biology Domain**

**Core Philosophy:** Biology is the domain of **adaptation, consumption, and propagation**. It does not build or pray; it grows. It wins by overwhelming opponents with a tide of rapidly evolving creatures, turning the battlefield itself into a toxic extension of its own life, and using the fallen as raw material for new growth. It is primal, relentless, and ever-changing.

**Strengths:**

- Adaptive Growth: The premier domain for units that grow stronger from taking damage, primarily through the **Adapt** keyword and other effects that add +1/+1 counters.

- Swarming & Propagation: Uniquely excels at creating numerous cheap-to-mid-cost units and generating new "token" units from the destruction of foes.

- Battlefield Corruption: The primary domain for deploying hazardous **Bio-Terrain** that can harm enemies while benefiting its own units.

- Debilitating Effects: Specializes in weakening effects, such as using toxins to reduce an enemy's stats before an attack.

**Weaknesses:**

- Lacks "Finisher" Events: Cannot have powerful, high-cost Event cards that can win the game outright or reset the board. Its power lies on the board, not in hand.

- No Direct Control or Range: Cannot manipulate an opponent's hand or directly control enemy units. It also has almost no access to **Far Range** combat.

- No Resource Generation or Recursion: Cannot have cards that generate extra CP. It also cannot return specific, powerful units from the discard pile; its "recursion" is creating new life from fallen biomass.

- No Mechanical Upgrades: The concept of attaching external hardware is antithetical to its nature; it cannot use Upgrade cards.

|                                               |                                                                                  |                                                                                                                                                                                    |
| --------------------------------------------- | -------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Domain Level (DP)**                         | **Thematic Representation**                                                      | **Example Card Attributes (Abilities, Stats, etc.)**                                                                                                                               |
| 1: Simple Organism / Basic Instinct           | A low-cost unit with a simple survival trait.                                    | **Ability:** Access to units with Adapt (1) or the Swarm keyword.                                                                                                                  |
| 2: Coordinated Pack / Evolving Threat         | The emergence of group tactics and predatory evolution.                          | **Ability:** Introduction of the Consume keyword for minor benefits (e.g., "Consume: This unit gets +1/+1"). Access to keywords that reward having multiple Biology units in play. |
| 3: Weaponized Predator / Corrupting Ecosystem | Biology as a weapon, able to twist the environment to its will.                  | **Ability:** More potent Adapt (2) abilities. The ability to deploy hazardous Bio-Terrain. Consume abilities that create new token units.                                          |
| 4: Apex Lifeform / Unstoppable Plague         | The ultimate expression of biological dominance; a world-ending force of nature. | **Ability:** Access to the most powerful Adapt and Consume effects. High-cost "Bio-Titan" Leader units. Event cards that grant mass-mutation to your entire board for a turn.      |


#### **F. The Entropy Domain**

**Core Philosophy:** Entropy is the domain of **dissolution, corruption, and inevitable decay**. It wins not by overpowering the opponent, but by systematically unmaking their ability to function, purging their key assets from existence entirely. It is reactive, insidious, and absolute.

**Strengths:**

- **Data Corruption:** The premier domain for applying negative states that blank a card's rule box, turning a complex threat into a useless, vanilla body.

- **Permanent Removal:** Uniquely excels at removing cards from the game entirely, bypassing the discard pile and preventing all forms of recursion.

- **Ability/Event Denial:** The best domain at canceling or preventing opponent's abilities and Events from resolving.

**Weaknesses:**

- **Poor Board Presence:** Its units are exceptionally fragile, with low stats. It cannot win a direct, fair fight.

- **Reactive Nature:** Is fundamentally reactive and slow. It struggles against hyper-aggressive strategies that don't rely on complex abilities.

- **No Resource Engine:** Cannot have cards that generate extra CP or provide card draw.

|                       |                                                         |                                                                                                                                                                                                                          |
| --------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Domain Level (DP)** | **Thematic Representation**                             | **Example Card Attributes (Abilities, Stats, etc.)**                                                                                                                                                                     |
| 1: Minor Glitch       | A brief flicker in the signal, a single corrupted file. | **Ability:** A simple, one-time Event like "Target unit's rule box is treated as blank this turn."                                                                                                                       |
| 2: System Noise       | Injecting persistent, low-level decay into the system.  | **Ability:** Introduction of the **Static** state. An active ability like "Pay 1 CP. Apply **Static** to target unit."                                                                                                   |
| 3: Signal Loss        | Mastering the synergy of corruption and deletion.       | **Ability:** More efficient ways to apply **Static**. Powerful effects that can "Remove target unit with **Static** from the game." The ability to cancel a triggered ability.                                           |
| 4: Final Silence      | Becoming the embodiment of informational oblivion.      | **Ability:** A Leader with a passive aura like "Whenever an opponent's unit gains **Static**, you may pay 1 CP to remove it from the game." A powerful Event that can "Cancel target Event and remove it from the game." |


#### **G. Mixed-Domain Design Principles**

A mixed-domain card should be a **fusion of both domains' identities**. It combines the strengths of its parent domains at their respective DP levels to create an effect that feels unique and synergistic, while still respecting the weaknesses of both.

**Example 1: 2 Technology / 2 Divinity**

- **Core Fusion:** "Sacred Engineering." Technology designed to channel or be protected by divine power.

- **DP Level Breakdown:** DP 2 Technology (Integrated Systems) + DP 2 Divinity (Demonstrated Devotion).

- **Example Card:**

* **Name:** Sacred Systems Core

* **Type:** Upgrade

* **Domains:** Tech 2, Div 2

* **Cost:** 3 CP

* **Rule Box:** Attached unit gets +2 Defense.\<br> Interrupt: Once per Game Round, when an opponent's Event would affect the attached unit, you may pay 1 CP to negate that Event's effect on this unit.

- **Design Rationale:** This Upgrade embodies the shared theme of **resilience**. The "+2 Defense" represents an advanced, **integrated system** (Tech 2). The interrupt ability is a single-target "miracle" of protection, a **demonstrated devotion** (Div 2) that feels divinely inspired.

**Example 2: 2 Biology / 2 Psionics**

- **Core Fusion:** "Apex Predator." Biology's relentless evolution guided by Psionic precision and cunning.

- **DP Level Breakdown:** DP 2 Biology (Evolving Threat) + DP 2 Psionics (Focused Mind).

- **Example Card:**

* **Name:** Pheromone Stalker

* **Type:** Unit

* **Domains:** Bio 2, Psi 2

* **Cost:** 4 CP

* **Rule Box:** This unit has **Taunt**. **Adapt (1)**.

- **Design Rationale:** This fusion combines Biology's resilience and growth (**Adapt**) with Psionics' ability to manipulate and control the battlefield (**Taunt**). The creature uses psychic pheromones to force enemies to engage it, and its biology adapts to the ensuing damage, making it a growing, tactical threat. This is a perfect blend of Biology's reactive survivability and Psionics' proactive control.

**Example 3: 2 Entropy / 2 Divinity**

- **Core Fusion:** "Faith in Oblivion." A martyr whose devotion delivers a curse of silence rather than a blessing.

- **DP Level Breakdown:** DP 2 Entropy (System Noise) + DP 2 Divinity (Demonstrated Devotion).

- **Example Card:**

* **Name:** Acolyte of the Final Word

* **Type:** Unit

* **Domains:** Entropy 2, Div 2

* **Cost:** 3 CP

* **Rule Box:** "**Zeal**. **Martyrdom:** When this unit is destroyed by an opponent's card effect or attack, you may apply **Static** to the unit that destroyed it."

- **Design Rationale:** This fusion combines Divinity's signature resilience (**Zeal**) and its core **Martyrdom** mechanic with Entropy's unique debuff (**Static**). The card is difficult to remove, and doing so punishes the opponent by corrupting one of their key pieces, perfectly blending the two philosophies.


### **V. Card Feel and Attributes**

Defining a card's feel helps establish its role and contributes to the gameplay experience.


#### **A. Card Feel Axes**

These axes describe a card's conceptual alignment and purpose. This matrix is an internal design tool. The "Internal Design Tags" (see Section II.D) can inform these axes.

- **Malevolence:** Describes moral alignment (Neutral, Malevolent, Benevolent).

- **Utility:** Indicates strategic purpose (Utility-focused, Neutral, Disruptive).

- **Combat:** Reflects role in battle (Offense, Neutral, Defense).

- **Impact:** Describes overall effect on game state (Constructive, Neutral, Destructive).

**Note:** The potential abilities described in the axes below are general examples and must always adhere to the strict strengths and weaknesses defined for each Domain in Section IV.

**Translating Card Feel into Mechanics**

Thematic feel should translate into game mechanics. This section provides examples of how a card's position on these axes might inspire specific types of abilities or stat distributions, and the potential consequences for gameplay.

- **Malevolence**

* **Benevolent:**

- **Potential Abilities:** Healing friendly units, providing protective effects (like increasing Defense or preventing targeting), enhancing other friendly units, generating CP for the player, or effects that offer symmetrical benefits. Consider how these abilities support a longer, more resilient game plan.

- **Example Consequence:** A deck focused on Benevolent cards might excel at outlasting opponents but may lack raw aggressive power without support.

* **Malevolent:**

- **Potential Abilities:** Direct damage to units, effects that force opponents to discard cards from hand or deck, applying negative states (beyond standard combat outcomes, if new states are designed), controlling opponent's units temporarily (if this mechanic is ever introduced, noting current rules V.F on card control), or denying resources.

- **Example Consequence:** Malevolent cards can disrupt opponents heavily but might involve risks or costs to the player, or lead to a board state that is powerful but fragile if their key pieces are removed.

* **Neutral:**

- **Potential Abilities:** Focus on efficiency, achieving objectives directly, or providing versatile tools that can be used offensively or defensively depending on the situation. Abilities might involve direct unit removal, battlefield repositioning, or conditional effects.

- **Example Consequence:** Neutral cards often form the backbone of strategies, offering flexibility but perhaps lacking the extreme specialization of Benevolent or Malevolent cards.

* **Utility**

- **Utility-focused:**

* **Potential Abilities:** Card draw, searching the deck (tutoring), manipulating the order of cards in a deck, returning cards from discard to hand/deck, countering opponent's abilities, or broad battlefield manipulation (e.g., moving multiple units, altering multiple quadrants with Terrain-like effects if on a non-Terrain card).

* **Example Consequence:** High-utility cards can give a player significant control over game flow and consistency but might have lower direct board presence (e.g., lower stats on a Unit).

- **Disruptive:**

* **Potential Abilities:** Forcing opponents to make suboptimal plays, negating abilities, increasing costs for the opponent, or temporarily disabling types of cards. Note: Rulebook Core Principle "Predictable Gameplay" excludes random elements beyond shuffles and draws.

* **Example Consequence:** Disruptive strategies can frustrate opponents and break their combos but may not always advance your own primary win condition directly.

- **Neutral:**

* **Potential Abilities:** A balance, perhaps a card that provides a small buff and also allows a card draw, or a unit with average stats that has a useful "enter the battlefield" effect.

* **Example Consequence:** These cards aim for solid value without extreme specialization, adaptable to many game states.

- **Combat**

* **Offensive:**

- **Potential Abilities:** Directly increasing Attack, granting abilities that ensure damage gets through (e.g., cannot be prevented, reduces defender's Defense before combat), attacking multiple times or multiple targets, or abilities that trigger upon destroying an enemy unit.

- **Example Consequence:** Highly offensive units can pressure opponents quickly but may be vulnerable if they can't maintain momentum or are easily removed due to lower defenses.

* **Defensive:**

- **Potential Abilities:** Increasing Defense, reducing incoming damage, forcing opponents to attack specific units (taunt-like effects), or abilities that punish attackers. Note: Healing damage is not a standard mechanic as units are typically Destroyed or Suppressed, not incrementally damaged. Specific card effects might introduce novel interactions.

- **Example Consequence:** Defensive units are key to protecting valuable assets or preventing mission completion/deck out but might lack the ability to close out a game without offensive support.

* **Neutral:**

- **Potential Abilities:** Units with balanced stats and perhaps a versatile combat-related ability, like one that can choose to buff its Attack or Defense for a turn.

- **Example Consequence:** These units offer flexibility, able to switch roles as needed, but might not excel in either offense or defense as much as specialized units.

* **Impact**

- **Constructive:**

* **Potential Abilities:** Generating additional CP, putting more units onto the battlefield (e.g., from hand for free, or creating non-card game markers if that were ever a concept, noting standard play uses cards), significantly buffing multiple allies, or accelerating mission completion through non-combat means.

* **Example Consequence:** Constructive cards build a strong board presence or resource advantage over time, but can be slow to start or vulnerable to aggressive disruption.

- **Destructive:**

* **Potential Abilities:** Removing multiple enemy units, destroying Assets or Terrain, wiping specific types of cards from the board, or significantly setting back an opponent's progress towards their missions.

* **Example Consequence:** Destructive cards can clear the way for your own strategy or stall an opponent but might be costly or leave you with fewer resources if they don't sufficiently cripple the opponent.

- **Neutral:**

* **Potential Abilities:** Focused on one-for-one trades, direct interaction with single targets, or effects that maintain equilibrium rather than drastically shifting it.

* **Example Consequence:** These cards are about maintaining parity or gaining small, incremental advantages.


#### **B. Functional Attributes**

Each card possesses specific attributes that define its capabilities. The Command Point (CP) cost of a card must be carefully balanced against the sum of its functional parts: its stats, its abilities, and its keywords. More powerful or impactful attributes will naturally lead to a higher CP cost.

- **Range** (If Applicable to Card Type, e.g., Units): Must conform to current Rulebook definitions (see Section II.B of these Guidelines). The choice of range is a significant factor in a unit's power level.

- **Attack** (If Applicable, e.g., Units): The offensive strength. Its value is a primary driver of a card's cost.

- **Defense** (If Applicable, e.g., Units, Assets): Resilience against attacks or effects. Its value must be balanced against the card's overall power and CP cost.

- **Rule Box:** Contains the card's abilities.

* **Active Abilities:** Require a player to choose them as a single action during the Activation Sequence and pay all associated costs (CP, exhausting the card, etc.) as specified by the ability (Rulebook Section III.C.2).

* **Passive Abilities:** Always in effect once the card is in play under the correct conditions. Do not require activation.

* **Triggered Abilities (includes Interrupts):** Activate in response to specific game events. Mandatory triggers must be announced and resolved. Optional Interrupts may have costs and allow a choice to activate (Rulebook Section VII.A).


#### **C: Baseline Budgeting Tool**

To ensure consistency in card balance, designers should use this internal budgeting tool as a starting point. This is not a rigid formula but a guideline to help calibrate the Command Point (CP) cost of a card against its functional attributes. This tool helps prevent the creation of cards that are significantly over- or under-powered for their cost.

The Core Formula: **1 CP = 10 Budget Points**

A card's total budget is determined by its CP cost. The designer then "spends" this budget on the card's stats and keywords.

**Attribute Costs (Illustrative Values):**

- 1 Attack Point: 10 points

- 1 Defense Point: 8 points

- Keyword - Horde: 25 points

- Keyword - Phalanx: 15 points

- Keyword - Steadfast: 20 points

- Keyword - Skirmisher: 25 points

- Keyword - Infiltrator: 30 points

- Keyword - Nullify: 25 points

  - Note: This is a highly synergistic keyword whose value increases based on the ease of applying the Static state.

- **Rule Box Ability:** The cost of a rule box ability is subjective and must be estimated based on its impact on Card Advantage, Tempo, and Board State. As a guideline: a simple, one-time effect might cost 10-20 points, while a powerful effect like "Draw a card" is worth approximately 35 points.

**Example in Practice: Analyzing a Hypothetical Card**

Let's analyze a hypothetical Unit card, "Agile Scout," to demonstrate how this system identifies imbalance:

- **Proposed Stats:** 3 CP, 0 Attack, 2 Defense, with keywords Infiltrator and an ability "Interrupt: When this unit is deployed, draw a card."

- **Budget Calculation:**

* The 3 CP cost provides a **Budget of 30 points**.

* The "spent" value is calculated as:

- 0 Attack = 0 points

- 2 Defense = 16 points (2 \* 8)

- Keyword Infiltrator = 30 points

- Ability "Draw a card" = \~35 points

* **Total Spent Value:** 16 + 30 + 35 = **81 points**

- **Analysis:** This system immediately highlights that the hypothetical "Agile Scout" provides over 80 points of value on a 30-point budget. This marks it as critically undercosted. The designer would see they need to either increase its CP cost significantly (to 8 CP) or, more practically, remove value (such as the "Draw a card" ability) to make it balanced at a lower CP cost. This tool provides a consistent power-for-cost ratio and a common language for the design team to discuss balance.


### **VI. Card Count Limits (Deckbuilding Restrictions)**

The number of copies of a particular card a player can include in their deck is a crucial balancing factor.

As per the current Quantum Nexus Rulebook (Section I.C, II.A), duplicate limits are printed on each card. No card may ever break these limits.

Designers will determine this limit (e.g., 1 for very powerful/unique effects, 2 for strong cards, 3 or more for foundational cards) based on the card's intended power level, role, and impact on deck diversity and game balance. A card's rarity (duplicate limit) is a key lever for controlling its prevalence and power in the game.


### **VII. Abilities**

Abilities are the core of a card's function and strategic interest.


#### **A. Types of Abilities**

- **Active Abilities:**

* Chosen by the player as a single action during their turn in the Activation Sequence.

* Must have clearly defined activation costs (CP, exhausting the card, other resources like discarding cards, sacrificing units, etc.).

* Effects should be clear and resolve fully.

- **Passive Abilities:**

* Are continuously active while the card is in play and conditions are met.

* Do not require player activation.

- **Triggered Abilities (Including Interrupts):**

* Activate automatically when their specific trigger conditions (defined on the card or by game rules) are met.

* Resolution follows the layered trigger resolution rules (Rulebook Section VII.A).

* Mandatory triggered abilities must resolve.

* Optional Interrupts may allow the player to choose to activate them, potentially by paying a cost (Rulebook Section VII.A).


#### **B. Ability Design and Balancing**

- **Concept and Theme:** Abilities must align with the card's overall concept, domain, subtype, and flavor. All distinct abilities should be clearly named in the rule box if they are complex or targetable by other effects.

- **Power Level and Balance:** The impact of an ability on the game state must be carefully considered. More powerful or versatile abilities should result in a higher CP cost for the card. The cost must be balanced against its effect on action economy, board state, and resource manipulation.

- **Clarity:** Ability text must be precise and unambiguous, using established game terminology consistently. Refer to "Precision Matters" in the Rulebook Core Principles.

- **Primer States and Payoffs**: Some domains, like Psionics, may utilize "primer" states such as Synaptic Mark. These states do nothing on their own but enable powerful "payoff" abilities. When designing these, the power must be split between the "enabler" card that applies the state and the "payoff" card that exploits it. An easy-to-apply primer should lead to moderately powerful payoffs, while a difficult-to-apply primer can justify a game-altering payoff.


### **VIII. Keywords and Their Impact on Gameplay**

Keywords are shorthand for specific, predefined abilities or characteristics that streamline card text and establish consistent mechanics. The impact of a keyword must be factored into a card's overall balance and CP cost.

If a new keyword is introduced, its rules must be clearly defined, either on the card itself if it's a one-off, or in the main Rulebook Glossary if it's intended for wider use.

The following is a list of official keywords in Quantum Nexus:

- **Bastion:** A specialized unit that occupies a battlefield quadrant to interact with an opponent's Assets. Bastion units generally cannot perform the "Declare an Attack" action; their specific methods for interacting with Assets are detailed in their individual rule boxes.

- **Horde:** When taking an “Attack” action with a unit that has the Horde keyword, you may select any number of other units with the Horde keyword in the same quadrant to attack. All attack values are added together for the purposes of combat resolution and all units are exhausted together.

- **Impact:** A persistent and accumulating value tracked by each unit and asset. When an effect "inflicts Impact X" on a target, X is added to that target's permanent accumulated Impact total. Immediately after a target's accumulated Impact total changes, if the new total is equal to or greater than the target's current Defense value, the target is destroyed.

- **Infiltrator:** You may deploy this unit directly into any of your Front Row quadrants. This overrides the general rule that units must be deployed to the Back Row.

- **Large:** A Large Unit is equal in size to two regular units. A quadrant can only hold 2 Large units.

- **Massive:** A Massive unit is equal in size to four regular units. A quadrant can hold only 1 Massive unit.

- **Nullify**: When this unit destroys a defending unit with the Static state as the result of an attack (A>D), that unit is removed from the game instead of being placed in the Discard Pile.

- **Phalanx:** This unit has +1 Defense for each adjacent friendly unit that also has the Phalanx keyword.

- **Skirmisher:** After this unit performs an Attack action, you may immediately move it to an adjacent friendly quadrant. This special move does not exhaust the unit and does not cost an action.

- **Small:** A Small unit is equal in size to a half of a regular unit. A quadrant can hold eight Small units.

- **Steadfast:** This unit cannot be moved from its quadrant by an opponent's card effects.

- **Swarm:** When taking a "Deploy a Card" action to deploy a unit with the Swarm keyword, you may also deploy any number of other units with the Swarm keyword from your hand into the same quadrant during the same action. You must pay the CP cost for all units deployed.

- **Taunt:** Enemy units that are able to attack must target a unit with Taunt if one is in range and a valid target.

- **Territorial:** Blocks enemy deployment and movement into any adjacent quadrant.

- **Tiny:** A Tiny unit is equal in size to a quarter of a regular unit. A quadrant can hold 16 Tiny units.


### **IX. Flavor Attributes**

Thematic elements are vital for an immersive experience.


#### **A. Name: Should be evocative, memorable, and reflect the card's theme and mechanics.**

#### **B. Image: Art descriptions provided by designers should be detailed enough to guide an artist, capturing theme, mood, domain elements, and action.**

#### **C. Flavor Text: Short, impactful text that adds lore or personality without affecting game mechanics.**

### **X. Synergies**

Designing for synergies creates strategic depth and rewards creative deck-building. This section illustrates how different synergistic approaches can be fostered through card design.


#### **A. Types of Synergies**

- **Theme-Based Synergies:** Cards sharing lore or conceptual themes can have abilities that naturally complement each other. Example: A "Scrap Welder" unit might get stronger if you have many "Mech" subtype cards in your discard pile. Consequence: Encourages thematic deck building but might be narrow if the theme isn't well-supported.

- **Domain Synergies:** Cards within the same domain (Technology, Magic, etc.) can be designed to enhance each other. Example: A Magic Asset might reduce the CP cost of Magic Events. A Biology Terrain might cause all friendly Biology units in that quadrant to gain Adapt (1). Consequence: Promotes domain-focused decks, potentially at the cost of inter-domain flexibility unless designed for.

- **Subtype Synergies:** Cards sharing a common subtype (e.g., "Drone," "Soldier," "Spirit") can have abilities that specifically benefit or are triggered by other cards of that subtype. Example: A "Drone Swarm Leader" might give +1 Attack to all other friendly "Drone" units. Consequence: Leads to strong tribal archetypes but can be vulnerable if the key "leader" or enabler is removed.

- **Leader Abilities:** Leaders should be designed with abilities that create clear strategic directions or synergize strongly with particular types of units, domains, or strategies. Example: A Leader might allow you to pay CP to ready exhausted units of its specific Faction subtype. Consequence: Makes the Leader a central, high-value target for the opponent.

- **Upgrade Interactions:** Upgrades should be designed to create powerful and interesting effects when attached to suitable Units or Assets. Example: An Upgrade granting "attacks target all units in target quadrant" would be very different on a low-attack unit versus a high-attack unit. Consequence: Adds a layer of resource management and decision-making about when and where to deploy Upgrades.

- **Event and Terrain Interactions:** Events can be designed to have amplified effects if certain Terrain types are in play, or if specific unit subtypes are present. Terrain can offer benefits tailored to certain domains or strategies. Example: An Event "EMP Burst" might destroy all Technology Assets, but if you control a "Shielded Command Center" Terrain, your Assets are protected. Consequence: Adds tactical depth based on board state.

- **Inter-Domain Synergies:** Design opportunities exist for cards that bridge domains, creating less obvious but potentially powerful interactions. Example: A Technology unit that benefits from the number of distinct spells (Magic) cast in a turn. Consequence: Encourages more complex, multi-domain deck building.

- **Ability Combos:** Design abilities on different cards that, when used in sequence or combination, produce a more powerful effect than if used separately. Example: Card A places a "Target Lock" on an enemy unit. Card B deals double damage to units with a "Target Lock." Consequence: Rewards skillful sequencing and can create powerful game-swinging moments, but requires drawing and playing multiple specific cards.


#### **B. Balancing Synergies**

Synergies should be rewarding but not so overwhelmingly powerful or easy to achieve that they stifle strategic diversity. Avoid infinite loops or game-breaking two-card combos unless they are extremely difficult to set up or are a core, intended high-risk/high-reward strategy. The power of abilities that enable strong synergies should be reflected in the card's overall cost and balance.


#### **C. Discovery and Exploration**

Aim to include some less obvious synergies that players can discover through experimentation, rewarding deeper game knowledge and creative deck-building.


#### **D. Playtesting and Feedback**

Thorough playtesting is essential to ensure synergies work as intended, are appropriately powerful, and do not lead to unintended negative play experiences.


### **XI. Card Creation Example**

This example uses the qualitative design principles outlined in this document to create the card **Telekineticist**.

- **Concept:** A psionic specialist who manipulates the battlefield by repositioning allies.

- **Card Type and Subtype:** Unit

- **Domain & DP:** The core concept is moving things with the mind, a classic Psionics theme. It's a tactical, supportive ability, not a direct attack or overwhelming control. This fits well within the **DP 2 Psionics** level: "A trained mind capable of tactical influence."

- **Card Feel Axes:**

* Malevolence: Benevolent. The ability helps friendly units.

* Utility: Utility-focused. It's all about repositioning for tactical advantage, not direct combat.

* Combat: Neutral/Defensive. It enables better combat positioning for others but doesn't directly engage.

* Impact: Constructive. It improves your board state without directly harming the opponent's.

- **Stats and Abilities:**

* Given its utility focus, its combat stats should be low. **Attack 1, Defense 2** seems appropriate. It's not meant to be a primary fighter.

* Its ability should reflect the concept. "Active: Pay 1 CP and exhaust this unit. Move target friendly unit with a CP cost of 3 or less to an adjacent quadrant."

* "**Active**" makes it a deliberate action, costing the player one of their turns in the Activation Sequence.

* "**Exhaust this unit**" is a standard cost for powerful active abilities on units, preventing it from being used and then attacking or moving in the same round.

* "**Pay 1 CP**" is a small resource cost, making it usable but not entirely free.

* "**Move target friendly unit... to an adjacent quadrant**" is the core effect.

* "...**with a CP cost of 3 or less**" is a crucial balancing restriction. It prevents the ability from easily repositioning the most powerful, game-ending units, focusing its utility on smaller, tactical pieces.

- **Final CP Cost:**

* The card has low stats (1/2).

* Its ability is purely utility and has multiple costs (Action, Exhaust, 1 CP) and a significant restriction (targets low-cost units).

* Based on this, a low CP cost is appropriate. A cost of **3 CP** seems fair. It's not a card you play for its body, but for its tactical effect, and 3 CP is a reasonable investment for that utility.

- **Resulting Card:**

* **Name:** Telekineticist

* **Type:** Unit

* **DP:** Psionics 2

* **CP Cost:** 3

* **Stats:** 1 Attack / 2 Defense

* **Range:** Mid (for targeting the ability, though it's not an attack)

* **Rule Box:** Active: Pay 1 CP and exhaust this unit. Move target friendly unit with a CP cost of 3 or less to an adjacent quadrant.


### **XII. Advanced Card Mechanics (Conceptual)**

These are ideas for designers to explore, ensuring they align with the core rules and balance.

- **Keywords and Status Effects:** Consider if new keywords (like "Stealth," "Precise," "Shielded X") or unique status effects (beyond "Suppressed") could add depth. Any new persistent keyword or status effect would need clear rules defined, potentially in the main Rulebook.

- **Combo Potential:** Design cards that might have non-obvious but powerful interactions.

- **Conditional Effects:** Abilities that trigger or vary based on game state (e.g., number of cards in hand, specific Mission Cards completed, presence of certain subtypes or domains in play).

- **Transforming Cards:** Units or Assets that might change into a different version of themselves (new stats/abilities) if certain conditions are met. This would require clear rules on how transformation occurs and how it's costed.


### **XIII. Design Considerations**

- **Balance:** Crucial. Strive for balance between card types, domains, individual card power, and strategies. The goal is a diverse and healthy metagame. Final balance comes from careful calibration and playtesting.

- **Originality:** Aim for innovative mechanics and thematic concepts.

- **Flavor:** Ensure mechanics, art, name, and flavor text create a cohesive and immersive whole.

- **Engagement:** Design cards that offer interesting decisions, promote interaction, and are enjoyable to play with and against.

- **Accessibility:** Card text should be clear and use consistent terminology. Complex abilities should be worded as unambiguously as possible.


### **XIV. Playtesting and Iteration**

Playtesting is non-negotiable.

- **Internal Playtesting:** Test new designs rigorously within the design team.

- **Wider Playtesting:** If possible, involve a broader group of trusted testers.

- **Iterative Refinement:** Be prepared to modify or discard designs based on playtest feedback to achieve balance and optimal playability.


### **XV. Mission Card Design**

The principles and specific parameters for designing Mission Cards (including balancing their CP values provided to players each round, objective complexity, passive effects, and any abilities they grant) are detailed in a separate, official "Quantum Nexus: Mission Card Creation Guidelines."

Designers assigned to create or revise Mission Cards must consult this dedicated document. These Card Creation Guidelines focus on the design of cards that form a player's main deck.


### **XVI. Conclusion**

The Quantum Nexus card creation process is a blend of creativity, strategic design, and rigorous refinement. By adhering to these guidelines, understanding the core Quantum Nexus Rulebook, and embracing iterative playtesting, designers can craft unique, balanced, and engaging cards that enrich this dynamic sci-fi universe.


### **Appendix**

#### **A. Glossary of Design Terms**

(This glossary is for designer use and may contain terms not in the player-facing Rulebook.)

- **Activation Sequence:** The part of a Game Round where players take alternating single actions. (Rulebook term)

- **Card Feel Matrix:** An internal design tool using axes like Malevolence, Utility, Combat, and Impact to guide a card's thematic and mechanical identity.

- **Command Points (CP):** The primary resource in the game, gained each round (primarily from Mission Cards) and spent to deploy cards and activate abilities. (Rulebook term)

- **Domain Points (DP):** A numerical value indicating a card's thematic connection to the six domains. DP are used in player-facing rules for Mission Card setup and Unit inclusion.

- **Internal Design Tags:** Terms like "Terrestrial," "Aerial," used by designers for thematic categorization, not as player-facing mechanics.


#### **B. Design Tips**

- **Start with a Clear Concept:** Define the card's role, theme, and intended interactions.

- **Prioritize Fun and Engagement:** Design cards that create interesting decisions and enjoyable gameplay moments.

- **Embrace Simplicity Where Possible:** Complex interactions are good, but individual card text should strive for clarity.

- **Consider All Game States:** How does the card perform in the early, mid, and late game? When ahead, behind, or at parity?

- **Design for the Rulebook:** All mechanics must function cleanly within the latest version of the Quantum Nexus Rulebook.

- **Iterate Relentlessly:** Playtesting will reveal what works and what doesn't. Be prepared to change any aspect of a card.

- **Vanilla Matters:** Don't be afraid of designing a card with no abilities.

- **Emergent Gameplay:** Keep abilities as simple as possible and as few as possible, this creates perfect scenarios for emergent Gameplay and helps drive the players gameplay narrative.
