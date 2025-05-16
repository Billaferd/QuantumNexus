# Quantum Nexus: Ability Creation Guidelines

## Note to the Reader

This is the Quantum Nexus: Ability Creation Guidelines, this document is not meant to explain any rules that a player would need, it is solely intended to aid designers in creating captivating and interesting card abilities and keywords for Quantum Nexus. Players are welcome to read this document, but please know that these rules are not applied to any in-game scenarios, they are solely intended for creating cards for Quantum Nexus.

This document is meant to be used in conjunction with the Quantum Nexus: Card Creation Guidelines and the Quantum Nexus: Mission Card Creation Guidelines. When designing cards the abilities are created using this document and then applied to the cards being designed.

## I. Introduction

Welcome to the "Quantum Nexus: Ability Creation Guidelines"! This document is your comprehensive guide to understanding, designing, and describing the unique abilities that power the cards in the Quantum Nexus universe. Abilities are the driving force behind much of the game's strategic interaction, from the powerful capabilities of your Units and Assets to the impactful outcomes of Events.

Think of abilities as the special functions, powers, or characteristics that your cards possess. They add layers of strategic depth and tactical decision-making to every game. Whether you're designing a new Unit with unique combat prowess, an Asset that provides ongoing support, an Event that disrupts your opponent's plans, or a new Keyword that defines a common mechanic, understanding how to construct and conceptualize the "cost" of abilities is essential.

A core principle of Quantum Nexus design is balance, which is achieved through careful design and rigorous playtesting. This guide provides a foundational framework for constructing abilities. The actual design budget valuation of these abilities, which influences a card's final Command Point (CP) cost, is determined by the **"Progressive Budget Build" (PBB) system** using **Design Budget (DB) points**, as detailed in the "Quantum Nexus: Card Creation Guidelines Version 2.0" (CCG v2.0). While this document uses *illustrative placeholder DB values* in its examples to demonstrate costing concepts, the official, calibrated DB costs for all ability components are maintained in the separate **Master DB Cost List(s)** by the design team. These Master Lists are living documents, updated as the game evolves through playtesting and balance adjustments.

In Quantum Nexus, abilities are carefully crafted combinations of core components:

* **Effects:** These are the fundamental actions or outcomes that an ability produces (e.g., inflicting Impact, modifying stats, drawing cards, applying states). They are the "what happens" part of an ability. (Detailed in Section II and Appendix E).
* **Targets:** These define what the effect is applied to (e.g., a specific Unit, a player, a quadrant). (Detailed in Section III and Appendix F).
* **Triggers:** These determine when or how an ability activates (e.g., as a player's action, or automatically when a specific game event occurs). (Detailed in Section IV and Appendix G).
* **Conditions:** These add "if-then" or "unless-then" logic, further defining whether an effect applies, how it's modified, or when it can be activated. (Detailed in Section V and Appendix H).

By mastering these components and understanding how they interact—along with how they are budgeted within the PBB system (Section VI)—you can create abilities that are not only powerful and effective but also balanced and engaging. This guide will delve into each of these components, explore how they combine to form Keywords (Section VII) and more complex Synergistic Mechanics (Section VIII), and discuss other important design considerations. Our goal is to provide you with the knowledge and tools needed to craft the abilities that will define your Quantum Nexus creations.

## II. Effects

In the realm of Quantum Nexus abilities, effects are the heart of the action. They dictate what happens when an ability is triggered, causing changes to the game state, influencing the Battlefield, and ultimately determining the fate of your cards and your opponent's.

Think of effects as the verbs in the sentences of your abilities. They are the actions that bring your cards to life, transforming them from static entities into dynamic forces that shape the course of the game. Whether it's an energy blast targeting an enemy unit, a surge of psionic power manipulating the Battlefield, or a divine blessing bolstering your defenses, effects are what make Quantum Nexus abilities so captivating and strategically rich. Many effects will require a specified duration (e.g., "this Game Round," "until the next Start of Round Step," or "while this card is in play on the Battlefield/in the Loadout Area").

### Categorizing Effects

Effects in Quantum Nexus are categorized into two main types based on their intended impact on the target:

* **Beneficial Effects:** These effects are intended to have a positive impact on their target. They might enhance, protect, provide resources, or otherwise improve the game state for the target's controller or the target card itself.
* **Detrimental Effects:** These effects are intended to have a negative impact on their target. They might directly attack resilience, weaken, destroy, remove resources, or otherwise hinder the target, creating an advantage for the player activating the ability.

*Important Note:* The categorization of an effect as beneficial or detrimental often depends on the target and context. Designers should primarily consider the intended use case when determining an effect's nature.

### Core Game Effects

The fundamental actions and changes that abilities can impose on the game are catalogued in **Appendix E: Core Game Effects Catalogue**. This catalogue serves as the primary palette for designers. Broadly, these effects can involve:

* Altering Card Attributes & States: Such as modifying Attack or Defense values, applying states like **Suppressed** or **Disordered**, changing a Unit's position, or granting/removing keywords.
* Managing Player Resources: Including gaining or causing the loss of Command Points (CP), drawing or discarding cards, and interacting with Decks or Discard Piles.
* Interacting with Game Flow & Rules: Such as negating other effects, influencing initiative, or directly impacting mission progression.
* Removing Cards or Changing Zones: Effects like destroying cards (sending them to the Discard Pile) or returning cards to a player's hand.

Designers should refer to **Appendix E** for a comprehensive list and specific descriptions of these core effects when constructing abilities.

#### Examples of Effects in Action (Illustrative)

The following examples demonstrate how effects (as catalogued in Appendix E) might be worded within an ability. Durations and specific conditions would be part of the full ability text.

* Applying a stat modification: `"Target friendly Unit gets +2 Defense this Game Round."`
* Manipulating player resources: `"Draw 2 cards."`
* Applying a state: `"Apply Disordered to target Unit."`
* Destroying a card: `"Destroy target Terrain."`
* Manipulating card position: `"Return target friendly Unit to its owner's hand."`
* Testing resilience directly: `"Inflict Impact 2 on target Unit."` (If the target Unit's Defense is 1, it's destroyed. If 2, it's Suppressed. If 3+, no effect).

### Building an Effect Component: Example for "Kinetic Pulse"

As we develop these guidelines, we will build a complete sample ability called "Kinetic Pulse" piece by piece. Here, we define its core **effect component**.

**1. Define the Effect Text for "Kinetic Pulse":**
Drawing from the types of effects listed in Appendix E (specifically, an effect like "Inflict Impact X on Unit"), the primary effect for "Kinetic Pulse" will be:
`"Inflict Impact 1 on all other Units in this Unit's quadrant."`

This effect combines a resilience-testing primitive with a specific targeting scope (targeting will be further detailed in Section III: Targets).

**2. Conceptual Breakdown & Illustrative DB Costing (for this Effect Component Only):**
This section provides a preview of the costing approach that will be fully detailed in Section VI. The Design Budget (DB) costs shown here are **purely illustrative placeholders** to demonstrate the concept of costing constituent parts. Actual DB costs for game design must be sourced from the official, calibrated **Master DB Cost List(s)**.

The effect component `"Inflict Impact 1 on all other Units in this Unit's quadrant"` could be conceptually broken down for DB estimation as follows:

* **A. Core Effect Primitive:**
    * Type: `Inflict Impact on Unit` (from Appendix E)
    * Specifics: Value of Impact = 1.
    * *Illustrative Placeholder DB for "Inflict Impact 1 instance":* `1.0 DB`
* **B. Target Scope Aspect of the Effect:**
    * Implicit Target: "all other Units in this Unit's quadrant." (While targets are detailed in Section III, the effect's phrasing defines its reach).
    * *Illustrative Placeholder DB for the targeting scope "all other Units in this Unit's quadrant":* `+1.5 DB` (This value notionally accounts for the area-of-effect nature, excluding self, and affecting multiple potential targets.)

**Illustrative Estimated DB Cost for this Effect Component:**
`1.0 DB (Base Impact primitive) + 1.5 DB (Target Scope aspect) = 2.5 DB`

**Important Disclaimer:**
This `2.5 DB` is an illustrative, conceptual cost for *only the effect portion* (including its inherent targeting scope) of our "Kinetic Pulse" example. The final DB cost of the complete "Kinetic Pulse" ability will also depend on its Trigger (Section IV) and any Conditions (Section V). All component costs would be officially sourced from the Master DB Cost List(s) for actual card design. This example serves to show the thinking process of identifying an effect from the catalogue and estimating its design budget weight based on its constituent parts. The full methodology for ability costing using the Progressive Budget Build system will be detailed in Section VI.

## III. Targets

In Quantum Nexus, an ability's effect typically acts upon one or more **targets**. Targets define the specific cards, players, game elements, or even abstract concepts that an ability will influence. Clearly defining the target(s) is crucial for creating abilities that are precise, strategically interesting, and function as intended within the game rules.

Think of targets as the specific recipients of an ability's action. Whether it's a single enemy Unit being struck by an energy pulse, a friendly Asset receiving a defensive enhancement, cards in a player's Discard Pile being returned to their hand, or an entire quadrant on the Battlefield being altered by a Terrain effect, precise targeting is key to an ability's function and tactical application. Abilities must clearly specify what they can target (see Rulebook Section VII.A on Targeting for general principles).

### Core Game Targets

The fundamental entities, attributes, and zones that abilities can target within Quantum Nexus are catalogued in **Appendix F: Core Game Targets Catalogue**. This catalogue serves as the primary reference for designers. Broadly, these targets can include:

* **Cards:** Specific cards in various game zones (In Play, Hand, Deck, Discard Pile, Mission Card Area), often distinguished by type (Unit, Leader, Asset, etc.) or other properties.
* **Players:** The player controlling the ability (Self), an Opponent, any player, or players meeting certain conditions.
* **Game Elements & Zones:** Physical areas like Quadrants or Loadout Areas, or entire zones like a player's Deck or Discard Pile.
* **Abstract Game Concepts:** Such as a card's stats (Attack, Defense), a player's CP, keywords, or even other abilities (for negation or copying effects).

Designers must refer to **Appendix F** for a comprehensive list and specific descriptions of these core targets when constructing the targeting component of an ability.

**Note on Target Specificity:** Abilities often include conditions that refine targeting (e.g., "target Unit with Attack 3 or less," "target friendly Technology Unit"). These conditions are part of the ability's overall logic and are discussed further in Section V: Conditions. The choice of target, including its scope and any conditional requirements, will influence its Design Budget (DB) cost within the Progressive Budget Build system.

#### Examples of Targets in Abilities (Illustrative)

The following examples demonstrate how targets (as catalogued in Appendix F) might be specified within an ability's text.

* `"Inflict Impact 2 on target Unit."` (Targeting a `Unit` from Appendix F, Section I.A).
* `"Bolster Defense of target friendly Asset by 2 this Game Round."` (Targeting an `Asset`, further specified as `friendly`, from Appendix F, Section I.A).
* `"All Units in target Quadrant get -1 Attack this Game Round."` (Targeting a `Quadrant` from Appendix F, Section III.A, with the effect applying to `Unit` cards within that `Quadrant`).
* `"You (the activating player) draw 1 card."` (Targeting `Player (Self)` from Appendix F, Section II).
* `"Target opponent discards 1 card from their hand."` (Targeting `Player (Opponent)` from Appendix F, Section II, with the effect interacting with `Card(s) in Hand` from Appendix F, Section I.B).
* `"Return target Unit with CP cost 3 or less from your Discard Pile to your hand."` (Targeting a `Card(s) in Discard Pile`, specifically a `Unit` meeting certain conditions, from Appendix F, Section I.D and I.F).

By carefully selecting and clearly defining the target(s) for an ability using the elements catalogued in Appendix F, designers ensure its effects are applied precisely where intended, contributing to strategic depth and clear gameplay.

### Defining a Target Component: Example for "Kinetic Pulse"

Continuing with our sample ability, "Kinetic Pulse," its defined effect component (from Section II) is: `"Inflict Impact 1 on all other Units in this Unit's quadrant."`

**1. Identify the Target Component Text for "Kinetic Pulse":**
From the full effect phrase, the **target component** is:
`"all other Units in this Unit's quadrant."`

This target specification can be understood as a combination of target primitives or a defined targeting scheme that would be catalogued or constructible from elements in **Appendix F: Core Game Targets Catalogue**. For instance, it involves targeting:
* Multiple `Unit` cards (Appendix F, Section I.A).
* Scoped to a specific `Quadrant` (Appendix F, Section III.A) relative to the source ("this Unit's quadrant").
* With an exclusion ("other Units," implying the source Unit is not targeted).

**2. Conceptual Breakdown & Illustrative DB Costing (for this Target Component Only):**
This section provides a preview of the costing approach that will be fully detailed in Section VI. The Design Budget (DB) costs shown here are **purely illustrative placeholders** to demonstrate the concept of costing constituent parts. Actual DB costs for game design must be sourced from the official, calibrated **Master DB Cost List(s)**.

The target component `"all other Units in this Unit's quadrant"` could be conceptually broken down for DB estimation as follows. The Master DB Cost List might offer a pre-defined cost for this common targeting pattern or provide costs for the constituent primitives that combine to form it:

* **A. Base Target Primitive(s):**
    * Targets: `Unit(s)` (from Appendix F, Section I.A).
    * *Illustrative Placeholder DB for base "Targets Unit(s)" aspect:* `0.5 DB`
* **B. Scope/Location Modifier:**
    * Scope: "in this Unit's quadrant" (targeting relative to the source Unit's `Quadrant`, as per Appendix F, Section III.A).
    * *Illustrative Placeholder DB for scope "in source's quadrant":* `+0.5 DB`
* **C. Quantity Modifier:**
    * Quantity: "all" (within the defined scope).
    * *Illustrative Placeholder DB for quantity "all within defined scope":* `+0.75 DB`
* **D. Exclusion Modifier:**
    * Exclusion: "other" (excludes the source Unit itself).
    * *Illustrative Placeholder DB for "excludes self" refinement:* `-0.25 DB` (This negative modifier reflects a slight reduction in impact/complexity compared to affecting *all* including self).

**Illustrative Estimated DB Cost for this Target Component:**
`0.5 DB (Base: Unit) + 0.5 DB (Scope: Source's Quadrant) + 0.75 DB (Quantity: All in Scope) - 0.25 DB (Exclusion: Other) = 1.5 DB`

**Important Disclaimer:**
This `1.5 DB` is an illustrative, conceptual cost for *only the target portion* of our "Kinetic Pulse" example. The previous section (Section II) illustratively costed the "Inflict Impact 1 instance" effect primitive at `1.0 DB`. Thus, the combined effect + target parts of "Kinetic Pulse" would illustratively be `1.0 DB + 1.5 DB = 2.5 DB` so far.

The final DB cost of the complete "Kinetic Pulse" ability will also depend on its Trigger (Section IV) and any further Conditions (Section V). All component costs for actual card design must be officially sourced from the Master DB Cost List(s). This example serves to demonstrate the thinking process of breaking down a target specification into finer aspects—all of which are now catalogued in Appendix F—to estimate its design budget weight. The full methodology for ability costing using the Progressive Budget Build system will be detailed in Section VI.

## IV. Triggers

In Quantum Nexus, **triggers** are the catalysts that bring abilities to life. They define the specific conditions, game events, or player choices that must occur for an ability to activate. Think of triggers as the "when" or "how" an ability initiates its effects. They add a layer of strategic timing, decision-making, and reactivity to the game.

Triggers determine the precise moments abilities can be used or will automatically occur, shaping the flow of interaction and strategic possibilities. The comprehensive list of defined trigger events and conditions available for ability design can be found in **Appendix G: Core Game Triggers Catalogue**.

### Types of Triggers

Conceptually, triggers in Quantum Nexus fall into two broad categories:

* **Active Triggers:** These are associated with **Active Abilities**. They signify that a player must make a conscious decision to use the ability, typically by choosing it as one of their single actions during their turn in the Activation Sequence (see Rulebook Section III.C.2). This activation often involves paying specified gameplay costs (like CP or exhausting the card), which are part of the ability's text but separate from the trigger itself. The fundamental trigger for these is "As a Player Action (Activate this Ability)" (Appendix G, Section I).
* **Event-Driven Triggers (Passive/Automatic):** These triggers cause an ability to activate automatically whenever a specific game event occurs or a particular condition in the game state is met, without requiring the player to use one oftheir single actions. Examples include an ability triggering "When this Unit is destroyed" or "At the Start of the Game Round." The resolution of these triggered abilities follows the rules detailed in Rulebook Section VII.A. A full list of such triggers can be found in Appendix G, Sections II.A through II.D.

### Understanding and Using Triggers from Appendix G

When designing an ability, you will select an appropriate trigger from Appendix G that dictates when the ability can or will activate.

* **For Active Abilities:** The trigger will be "As a Player Action (Activate this Ability)." The ability's rule text will then specify any gameplay costs (CP, exhausting, etc.) and the effects.
    * *Example Card Text Snippet (Active Ability):* "**Action:** Pay 2 CP and Exhaust this Unit to..." (Here, "Action:" signifies the "As a Player Action" trigger).

* **For Event-Driven Abilities:** The trigger will be a specific game event.
    * *Example Card Text Snippet (Event-Driven Trigger):* "**When** this Unit is deployed, you may draw 1 card." (Draws from "When [This/Target/Any] Card is Deployed" in Appendix G, Section II.B).
    * *Example Card Text Snippet (Event-Driven Trigger):* "**At the Start of the Game Round,** if you control more Units than any opponent, gain 1 CP." (Draws from "At the Start of the Game Round" in Appendix G, Section II.A, with an additional condition).

Designers should refer to **Appendix G: Core Game Triggers Catalogue** for the comprehensive list of available triggers.

### Key Considerations for Trigger Design

* **Timing and Relevance:** Does the trigger align with the ability's intended purpose and the strategic window in which it should be impactful? Consider the flow of a Game Round (Start of Round Step, Activation Sequence actions) as defined in Rulebook Section III.C.
* **Frequency and Impact:** How often is the trigger likely to occur? Frequent triggers for powerful effects can be unbalancing, while very niche triggers for minor effects might render an ability useless. The DB cost of a trigger (from the Master DB Cost List) will reflect its potential frequency and game impact.
* **Clarity and Precision:** The trigger condition must be phrased clearly and unambiguously, using established game terminology from the Rulebook and Appendices. This ensures consistent interpretation and resolution.
* **Interaction and Counterplay:** Consider how the trigger interacts with other game elements and if there are reasonable opportunities for opponents to play around it or respond to the ability once triggered (as per Rulebook Section VII.A on resolving triggered abilities).

By carefully selecting triggers from Appendix G and considering these design principles, you can create abilities that are dynamic, interactive, and strategically engaging.

### Defining a Trigger Component: Example for "Kinetic Pulse"

Continuing with our sample ability, "Kinetic Pulse":
* Its Effect component is: `"Inflict Impact 1 on all other Units in this Unit's quadrant."` (Illustrative DB cost so far for effect+target: `2.5 DB`)

Now, we define its **trigger component**. For "Kinetic Pulse," we will design it as an Active Ability that a player must choose to use.

**1. Identify the Trigger Component for "Kinetic Pulse":**
The trigger for "Kinetic Pulse," as an Active Ability, is:
`"As a Player Action (Activate this Ability)"`
This is drawn from **Appendix G: Core Game Triggers Catalogue, Section I.** This means a player must use one of their single actions during their turn in the Activation Sequence to use Kinetic Pulse, and they would also pay any gameplay activation costs defined in Kinetic Pulse's full ability text (which we will finalize later but assume for now include paying CP and exhausting).

**2. Conceptual Breakdown & Illustrative DB Costing (for this Trigger Component Only):**
This section provides a preview of the costing approach that will be fully detailed in Section VI. The Design Budget (DB) cost shown here is a **purely illustrative placeholder**. Actual DB costs for game design must be sourced from the official, calibrated **Master DB Cost List(s)**.

The trigger component `"As a Player Action (Activate this Ability)"` has an intrinsic design budget cost because it consumes one of the player's limited actions during the Activation Sequence.

* **A. Core Trigger Primitive:**
    * Type: `As a Player Action (Activate this Ability)` (from Appendix G, Section I).
    * *Illustrative Placeholder DB for this trigger type:* `1.0 DB` (This conceptual cost reflects the opportunity cost of using a player's action.)

**Illustrative Estimated DB Cost for this Trigger Component:** `1.0 DB`

**Important Disclaimer:**
This `1.0 DB` is an illustrative, conceptual cost for *only the trigger portion* of our "Kinetic Pulse" example.
So far, for "Kinetic Pulse":
* Effect + Target components: Illustrative `2.5 DB`
* Trigger component: Illustrative `1.0 DB`
* Running Illustrative Total DB: `3.5 DB`

The final DB cost of the complete "Kinetic Pulse" ability will also depend on any Conditions (Section V) and any specific gameplay activation costs (like CP or exhausting the source Unit) which might influence the DB values assigned in the Master DB Cost List. All component costs for actual card design must be officially sourced from the Master DB Cost List(s). This example serves to demonstrate how a trigger is selected from Appendix G and how its nature contributes to the ability's design budget weight. The full methodology for ability costing will be detailed in Section VI.

## V. Conditions

In Quantum Nexus, **conditions** add a layer of complexity and strategic depth to abilities. Conditions are essentially criteria or checks against the current game state, card attributes, or player choices that determine whether an ability (or part of its effect) can activate, how it resolves, or if its costs are modified. They introduce "if-then" or "unless-then" logic, allowing abilities to be versatile and responsive.

Think of conditions as the specific requirements or circumstances that must be true (or false) for an ability to function in a particular way. They act as filters or modifiers, adding strategic nuance to every action. Whether an ability only works if a Unit is in a specific quadrant, or if a player controls a certain type of card, or unless an opponent pays a cost, conditions are key to dynamic and interactive gameplay. The types of checks that can form a condition are catalogued in **Appendix H: Core Game Condition Types Catalogue**.

### Conditional Phrasing & Logic

Abilities use conditional phrases to incorporate checks against the game state. The most common are:

* **If [Condition is True], then [Effect Occurs / Modification Applies]:**
    This is the most straightforward conditional structure. The specified effect or modification only happens if the stated condition (drawn from the types in Appendix H) is met at the relevant time (usually upon activation or resolution of the ability).
    * *Example:* `"If this Unit is in a Front Row quadrant, it gains +1 Attack this Game Round."` (The condition is "this Unit is in a Front Row quadrant" – see Appendix H, Section II.D).
* **Unless [Condition is True], then [Effect Occurs / Modification Applies]:**
    This reverses the logic. The effect or modification happens *unless* the stated condition is met.
    * *Example:* `"Target opponent discards 1 card, unless their CP is 0."` (The condition is "opponent's CP is 0" – see Appendix H, Section III.A).

**Distinction from Triggers:**
It's important to distinguish conditions from triggers (see Section IV and Appendix G).
* **Triggers** (e.g., "When X happens," "After Y occurs," "At the start of Z") define *when an ability activates or attempts to resolve.*
* **Conditions** (e.g., "If A is true," "Unless B is met") are checks made *at the point of a trigger, activation, or resolution* to determine if or how an ability proceeds.
    While some trigger phrases like "When..." might seem conditional, they define the actual event that initiates the ability. A condition, on the other hand, is a secondary check. For instance, in `"When this Unit is deployed, if you control a Leader, draw a card,"` "When this Unit is deployed" is the trigger, and "if you control a Leader" is the condition.

**Timing of Conditional Checks:**
Unless specified otherwise, conditions are checked:
* For Active Abilities: When the ability is declared as an action and when it begins to resolve. If a condition is not met at activation, the ability cannot be activated. If it's not met at resolution (due to changes in game state), the conditional part of the effect may not occur.
* For Event-Driven (Triggered) Abilities: When the trigger event occurs and when the ability begins to resolve.

### Boolean Operators for Complex Conditions

To create more intricate logic, conditions can be combined using standard Boolean operators. These allow for multiple checks to determine an outcome. Refer to Appendix H for the types of conditions that can be combined.

* **AND:** Both (or all) connected conditions must be true.
    * *Example:* `"If this Unit is in a Front Row quadrant AND you have 5 or more CP, its activated abilities cost 1 CP less to activate this Game Round."`
* **OR:** At least one of the connected conditions must be true.
    * *Example:* `"If this Unit is Exhausted OR it is Disordered, it gets +2 Defense."`
* **NOT:** The specified condition must be false.
    * *Example:* `"If you do NOT control any Terrain cards, reduce the cost of the next card you play this Game Round by 1 CP."`
* **XOR (Exclusive OR):** Exactly one of the connected conditions must be true (but not both). While less common, this logic can be used for mutually exclusive effects.
    * *Example:* (Hypothetical advanced usage) `"XOR: If this Unit is in your leftmost friendly quadrant, it gains +1 Attack; if this Unit is in your rightmost friendly quadrant, draw a card."`

### Examples of Conditions in Abilities (Illustrative)

These examples showcase how different condition types from Appendix H might be used:

* Using a Card State Condition (Appendix H, II.C): `"If this Unit is Suppressed, it cannot be chosen as a target for opponent's Event cards."`
* Using a Player Resource Condition (Appendix H, III.A): `"Activate this ability. If your CP is 3 or less, this ability's effect is doubled."`
* Using a Board Presence Condition (Appendix H, III.B): `"Unless you control a 'Technology' subtype Unit, the CP cost to play this card is increased by 2."`
* Using a Comparison Condition (Appendix H, IV): `"If this Unit's Attack is greater than its Defense, it gains 'Attacks made by this Unit cannot be responded to by Interrupts.'" (Illustrative new keyword).`
* Using a Cost-Related Condition (Appendix H, V): `"You may discard 2 cards. If you do, destroy target Unit."`

Designers should strive for clarity when phrasing conditions, ensuring that the check being made and its consequences are unambiguous. The Design Budget (DB) cost/modifier for a condition (from the Master DB Cost List) will reflect its impact on an ability's power, flexibility, and likelihood of being met.

### Defining a Condition Component: Example for "Kinetic Pulse"

Continuing with our sample ability, "Kinetic Pulse":
* Effect component: `"Inflict Impact 1 on all other Units in this Unit's quadrant."` (Illustrative DB: `2.5` for effect+target)
* Trigger component: `"As a Player Action (Activate this Ability)"` (Illustrative DB: `1.0`)
* Running Illustrative Total DB so far: `3.5 DB`

Let's add a simple **condition component** to "Kinetic Pulse" to make its use more tactical.

**1. Define the Condition Text for "Kinetic Pulse":**
We will add a positional condition:
The ability will now conceptually be: "_As a Player Action: **If this Unit is in a friendly Front Row quadrant,** inflict Impact 1 on all other Units in this Unit's quadrant._"

The condition component is: `"If this Unit is in a friendly Front Row quadrant"`
This condition type is found in **Appendix H: Core Game Condition Types Catalogue, Section II.D** (Card Location).

**2. Conceptual Breakdown & Illustrative DB Cost/Modifier (for this Condition Component Only):**
This section provides a preview of the costing approach that will be fully detailed in Section VI. The Design Budget (DB) costs shown here are **purely illustrative placeholders**. Actual DB costs/modifiers for game design must be sourced from the official, calibrated **Master DB Cost List(s)**.

Conditions often act as modifiers to an ability's base DB cost or are factored into the DB cost of a pre-defined ability template from the Master List. A condition that restricts an ability's use might slightly reduce its overall DB cost (or allow a more powerful base effect for the same total DB) compared to an unconditional version. Conversely, a condition that enables an unusually powerful effect might have its "cost" subsumed into the high DB cost of that powerful effect.

For this specific condition:
`"If this Unit is in a friendly Front Row quadrant"`

* **A. Core Condition Type:**
    * Type: `Card Location Check` (Unit's position) (from Appendix H, Section II.D).
    * Specificity: Requires being in one of three (out of six) specific friendly quadrants. This is a moderate restriction.
    * *Illustrative Placeholder DB Modifier for this condition:* `-0.5 DB` (This negative value suggests the condition *restricts* the ability, potentially making the overall ability slightly "cheaper" in DB or justifying its current power level. The Master List would clarify how such restrictions translate to DB adjustments.)

**Illustrative Estimated DB Cost / Modifier for this Condition Component:** `-0.5 DB`

**Important Disclaimer:**
This `-0.5 DB` is an illustrative, conceptual modifier for the condition portion of "Kinetic Pulse."
So far, for "Kinetic Pulse":
* Effect + Target components: Illustrative `2.5 DB`
* Trigger component: Illustrative `1.0 DB`
* Condition component: Illustrative `-0.5 DB` (modifier)
* **New Running Illustrative Total DB for "Kinetic Pulse":** `2.5 + 1.0 - 0.5 = 3.0 DB`

The final DB cost of the complete "Kinetic Pulse" ability would be determined by summing the official DB costs of all its components (sourced from the Master DB Cost List(s)) and any specific gameplay activation costs (like CP or exhausting the source Unit) which also influence these values. This example illustrates how a condition (defined from Appendix H) is incorporated and how its restrictiveness might influence the ability's overall design budget. The full methodology for ability costing will be detailed in Section VI.

## VI. Ability Design Budgeting and Card Creation

In Quantum Nexus, the creation of playable cards (Units, Assets, Events, Upgrades, Terrain) is a meticulous process. It involves careful balancing of a card's stats (if any), its abilities, and its overall Command Point (CP) cost to ensure a fair and engaging gameplay experience. This entire process is governed by the **"Progressive Budget Build" (PBB) system**, which is detailed in the "Quantum Nexus: Card Creation Guidelines Version 2.0" (CCG v2.0, Section V.B).

These Ability Creation Guidelines focus on the art and science of crafting the abilities themselves – their effects, targets, triggers, and conditions. Once an ability is conceptually designed using the principles and catalogues in Sections II-V and Appendices E-H of this document, its "cost" in terms of design complexity and power is quantified using **Design Budget (DB) points**. This DB cost for abilities then feeds directly into the card's overall PBB calculation.

### The Interplay of Abilities and the Progressive Budget Build System

Abilities, in their various forms (Active, Event-Driven (Triggered/Passive), or encapsulated as Keywords), are the functional heart of cards. They define how cards interact with the game and influence its strategic landscape. The design cost of these abilities, expressed in DB, is a critical factor within the PBB system.

**Key Principles (Aligning with CCG v2.0):**

* **Abilities as Budgeted Features:** All abilities and keywords on a card consume a portion of its **Total Design Budget (TDB)**. This TDB is established for each card based on its foundational nature, Domain Points (DP), role (e.g., Leader), and rarity (duplicate limit), as detailed in CCG v2.0.
* **DB System for Costing:** The PBB system uses Design Budget (DB) points to quantify the "cost" of each ability and keyword. More powerful, complex, or versatile abilities will have a higher DB cost.
* **Contribution to Final Card CP Cost:** The sum of DB spent on a card's stats *and* all its abilities/keywords (`Total_Actual_DB_Spent`) is converted into the card's final playable CP cost using a `CP_Conversion_Factor`. This process ensures a direct link between a card's designed power/complexity and its in-game CP cost.
* **Master DB Cost List(s):** The specific DB cost for any given game effect (Appendix E), target specification (Appendix F), trigger mechanism (Appendix G), condition type (Appendix H), keyword, or complete ability template is **not** definitively set within these Ability Creation Guidelines. Instead, these values are officially defined and maintained by the design team in one or more **"Master DB Cost List(s)."** These lists are essential companion documents to CCG v2.0 and will require ongoing calibration through rigorous playtesting. The illustrative DB values used in the examples within this ACG are for conceptual demonstration only.
* **Synergy and Balance:** While these guidelines help structure ability creation, the ultimate balance and synergistic potential of abilities are assessed through their DB costs (from the Master Lists) and confirmed via playtesting. The PBB system aims to provide a framework where even highly synergistic abilities are appropriately budgeted.

### Determining an Ability's Design Budget (DB) Cost

The DB cost of a custom-designed ability is determined by evaluating and summing the DB costs of its constituent components:
1.  Its core **Effect(s)** (as catalogued in Appendix E and selected/combined for the ability)
2.  The **Target(s)** it affects (as catalogued in Appendix F and specified for the ability)
3.  Its **Trigger(s)** (as catalogued in Appendix G and chosen for the ability)
4.  Any **Condition(s)** that modify its activation or resolution (as catalogued in Appendix H and applied to the ability)

Each of these components will have an associated DB cost (or cost modifier) obtainable from the Master DB Cost List(s).

**Guiding Principles for DB Costs (Reflected in the Master DB Cost List(s)):**
The Master DB Cost List(s) will assign DB values based on principles such as:

* **Effect Potency & Versatility:** More impactful or flexible effects have higher DB costs.
* **Target Scope & Difficulty:** Broader or more advantageous targeting (e.g., multiple opponent's cards vs. a single friendly card) increases DB cost.
* **Trigger Frequency & Reliability:** More frequent or automatic triggers generally increase DB cost compared to restrictive or player-action-dependent triggers. The "As a Player Action" trigger itself has a base DB cost reflecting the use of a player's limited action.
* **Conditional Impact:** Conditions that make an ability easier to use or more potent can increase DB cost, while restrictive conditions might reduce the effective DB cost of the ability's core effect or be factored into a lower overall package cost.
* **Benefit vs. Detriment (Self vs. Opponent):** The DB cost will reflect whether an ability's components are beneficial to the controller, detrimental to an opponent, or involve a trade-off.
* **Gameplay Activation Costs (for Active Abilities):** As stated in CCG v2.0 (V.C), gameplay activation costs (e.g., paying CP, exhausting the card) are separate from an ability's design DB cost. However, the presence and magnitude of such gameplay costs *will influence* the DB cost assigned to that ability structure on the Master DB Cost List(s). An Active Ability with a high gameplay CP cost is expected to have a lower DB design cost than a similar ability with no gameplay CP cost.

### Example: Determining the DB Cost for "Kinetic Pulse"

Let's assemble our running example ability, "Kinetic Pulse," and determine its illustrative total DB cost based on its components.

**Full Conceptual Text for "Kinetic Pulse":**
"As a Player Action: Pay 1 CP and Exhaust this Unit. If this Unit is in a friendly Front Row quadrant, inflict Impact 1 on all other Units in this Unit's quadrant."

**Component Breakdown & Illustrative DB Costs:**
(Reminder: These DB values are illustrative placeholders. Actual values from Master DB Cost List(s) are used for official design.)

1.  **Effect Component:** `"Inflict Impact 1 on all other Units in this Unit's quadrant."`
    * Primitive Effect: `Inflict Impact 1 instance` (from Appendix E)
        * *Illustrative Placeholder DB:* `1.0 DB`
    * Target Scope Aspect: `all other Units in this Unit's quadrant` (built from Appendix F concepts)
        * *Illustrative Placeholder DB:* `+1.5 DB`
    * **Subtotal for Effect + Target Components:** `2.5 DB`

2.  **Trigger Component:** `"As a Player Action (Activate this Ability)"` (from Appendix G)
    * *Illustrative Placeholder DB:* `1.0 DB` (reflecting use of a player's action)

3.  **Condition Component:** `"If this Unit is in a friendly Front Row quadrant"` (built from Appendix H concepts)
    * *Illustrative Placeholder DB Modifier:* `-0.5 DB` (as a restriction, this might slightly reduce the ability's budget cost or justify its power level for a given DB total).

**Illustrative Total Design Budget (DB) Cost for the "Kinetic Pulse" ability:**
`DB (Effect+Target) + DB (Trigger) + DB_Modifier (Condition)`
`2.5 DB + 1.0 DB - 0.5 DB = 3.0 DB`

**Consideration of Gameplay Activation Costs:**
"Kinetic Pulse" has gameplay activation costs: "Pay 1 CP" and "Exhaust this Unit." The illustrative `3.0 DB` for this ability assumes that the Master DB Cost List(s) would value an ability with these characteristics (Impact 1, specific AoE, positional condition, active action trigger) at `3.0 DB` *when it also has these fairly standard gameplay activation costs*. If "Kinetic Pulse" had, for example, a 0 CP gameplay activation cost or didn't require exhaustion, its DB design cost on the Master List would likely be significantly higher.

**Integration into Card's Progressive Budget Build:**
This `3.0 DB` (or the official value from the Master List) for the "Kinetic Pulse" ability would be part of the `DB_Spent_On_Abilities` for the Unit card it's on. This sum, along with the DB cost for the Unit's stats (e.g., Attack and Defense), contributes to the card's `Total_Actual_DB_Spent`. This total must be within the card's overall **Total Design Budget (TDB)** (determined by its DP, rarity, and Leader status as per CCG v2.0). Finally, the `Total_Actual_DB_Spent` is divided by the `CP_Conversion_Factor` to arrive at the Unit's printed CP cost.

## VII. Keywords

Keywords in Quantum Nexus are standardized terms that represent specific, predefined abilities or characteristics. They function as shorthand, streamlining card text and ensuring consistent application of common game mechanics. Attaching a keyword to a card grants it the associated abilities or modifies its function in a known way.

Think of keywords as established special traits. They can range from simple modifications like **"Steadfast"** (preventing a common game mechanic like being Pushed Back) to more complex abilities that define how a card interacts in combat or with other game elements. All official keywords and their precise mechanical definitions will be listed in the main Quantum Nexus Rulebook glossary (Rulebook Section VIII) or on the cards themselves if unique.

### Types of Keywords (Conceptual)

For design purposes, keywords can be broadly conceptualized by their impact:

* **Positive Keywords:** These keywords grant beneficial effects or advantages to the card they are on (e.g., enhancing its power, resilience, or utility).
* **Negative Keywords:** These keywords impose drawbacks, limitations, or vulnerabilities on the card (e.g., restricting its actions, making it easier to affect by opponent's abilities).
* **Neutral Keywords:** These keywords define a specific mode of operation or interaction that isn't inherently beneficial or detrimental on its own but adds unique mechanical properties or enables specific synergies.

### Keywords and the Design Budget (DB) System

A keyword is, in essence, a pre-packaged ability or set of rules with a specific name. As such, each keyword has an associated **Design Budget (DB) cost** that reflects its impact on gameplay, its power level, and its strategic value. This DB cost is determined by the design team and recorded in the **Master DB Cost List(s)** (as referenced in CCG v2.0, Section VIII).

When a card is designed to have a keyword:
* The keyword's defined DB cost (from the Master List) is added to that card's `DB_Spent_On_Abilities`.
* This contributes to the card's `Total_Actual_DB_Spent`, which, under the Progressive Budget Build system, helps determine the card's final printed Command Point (CP) cost.

The DB cost of keywords is determined by their nature:
* **Positive Keywords:** Will have a positive DB cost, consuming part of the card's Total Design Budget (TDB).
* **Negative Keywords:** May have a conceptual "negative" DB cost (i.e., they effectively *refund* DB to the card's TDB, allowing for better stats or other abilities for its CP cost) or a very low positive DB cost if their drawback is minor or situational. This will be specified in the Master DB Cost List.
* **Neutral Keywords:** Will typically have a positive DB cost, reflecting the value of their unique mechanics, even if not directly a benefit/drawback.

### Keywords and Strategic Depth

Keywords add a significant layer of strategic depth to Quantum Nexus. They create clear synergies (e.g., cards that enhance other cards with a specific keyword), define archetypes, and provide players with quick-to-understand indicators of a card's capabilities. Understanding the keywords on both your own and your opponent's cards is crucial for effective tactical play.

### Defining and Costing a New Keyword (Illustrative Example)

While most keywords will be established and have their DB costs listed in the Master DB Cost List(s), designers might propose new keywords. If a new keyword is created, its game rules must be precisely defined. Its DB cost would then be carefully assessed based on the impact of those rules, similar to how custom abilities are evaluated, and added to the Master List.

Let's consider a simple, new positive keyword: **"Steadfast."**

1.  **Define the Keyword's Mechanic:**
    `*Steadfast* - This Unit cannot be Pushed Back.`
    *(This directly counters one of the negative outcomes for an attacker if its Attack is less than the defender's effective Defense, as per Rulebook Section III.C.2).*

2.  **Determine its DB Cost (Conceptual - for Master List Calibration):**
    The design team would analyze the impact of "Steadfast":
    * **Effect:** Prevents the "Pushed Back" mechanic. This is a clear benefit, as it keeps the Unit in its current position after an unsuccessful attack and avoids potential repositioning disadvantages.
    * **Frequency/Applicability:** Applies specifically to Units when they attack and their Attack < defender's Defense.
    * **Impact:** Moderate defensive benefit. It doesn't prevent the "Disordered" state but negates the forced movement.

    Based on this analysis, the **"Steadfast"** keyword would be assigned a specific DB cost in the Master DB Cost List(s). Let's assume, for pure illustration:
    * *Illustrative Placeholder DB for "Steadfast" keyword:* `1.5 DB`

3.  **Using the Keyword on a Card:**
    If a designer creates a Unit card and wants to give it the "Steadfast" keyword:
    * They add "Steadfast" to the Unit's rule box (or keyword line).
    * The illustrative `1.5 DB` (or the official value from the Master List) is added to that Unit card's `DB_Spent_On_Abilities`.
    * This `1.5 DB` then factors into the card's total PBB calculation for its final CP cost.

This example shows that keywords, once defined and their DB cost established in the Master List, become straightforward additions to a card's design, with their budget impact being consistently applied.

## VIII. Designing Synergistic Mechanics and Interconnected Abilities

While the previous sections have detailed how to construct individual abilities from their core components (Effects, Targets, Triggers, Conditions), much of the strategic depth and unique feel of Quantum Nexus will come from **synergistic mechanics**—sets of abilities, keywords, and game rules designed to interact in specific and interesting ways. This section explores how designers can approach the creation of such interconnected systems.

Designing for synergy involves thinking beyond a single card's function and considering how multiple cards or abilities can combine to produce an effect greater or more distinct than the sum of their parts. This often leads to the creation of unique faction identities, deck archetypes, and rewarding gameplay patterns for players to discover and master.

### Example System: The "Invoke/Chant/Ritual" Mechanic

To illustrate the process of designing an interconnected system, let's develop a thematic mechanic where powerful "Invoked" Units can only be brought into play by fulfilling a "Ritual" that requires other friendly Units to be actively "Chanting."

**Overall Concept:** Certain potent Units (bearing the "Invoke" keyword) are too powerful or unique to be deployed via normal means (i.e., by paying their CP cost during a "Deploy a Card" action). Instead, they require a specific set of conditions—a Ritual—to be met, often involving other Units taking specific actions ("Chanting").

Let's break down the components:

**Part 1: The "Invoke" Keyword**
This keyword will be placed on the powerful Units that require the special summoning condition.

* **Keyword Name:** `Invoke`
* **Core Mechanic:**
    1.  A Unit with `Invoke` cannot be deployed using the standard "Deploy a Card" action by paying its CP cost.
    2.  It can only be deployed from its owner's hand when the conditions of its specified `Ritual` (detailed in its ability text) are met.
    3.  Deploying a Unit via `Invoke` does not inherently cost CP unless the `Invoke` ability or Ritual itself specifies a CP cost. The card's printed CP cost might be relevant for other game effects or for alternative ways to get it into play if specific card abilities allow it, but not for its primary `Invoke` deployment.
* **Constituent Components (Conceptual):**
    * **Effect Element 1 (Restriction):** "This Unit cannot be deployed using the 'Deploy a Card' player action." (This involves modifying deployment rules – see Appendix E, Section III.B).
    * **Effect Element 2 (Alternate Deployment):** "This Unit may be deployed from your hand if its `Ritual` condition is met." (This enables a special deployment – see Appendix E, Section III.B).
    * **Condition Element (for Effect 2):** The specific `Ritual` detailed on the card (see Part 3 below).
* **Illustrative Design Budget (DB) Consideration:**
    The restriction ("cannot be deployed normally") is a significant drawback. As per CCG v2.0 (Section VIII) and our discussion in Section VII of these guidelines, such a restrictive keyword would likely have a **negative DB cost** on the Master DB Cost List(s).
    * *Illustrative Placeholder DB for `Invoke` keyword (base restriction, before Ritual complexity):* `-5.0 DB`
    This negative DB cost effectively increases the Total Design Budget (TDB) available for the Invoked Unit's stats and its other abilities, allowing it to be more powerful once successfully brought into play, to compensate for its difficult summoning method. The complexity of its specific Ritual condition will further influence this value.

**Part 2: The "Chant" Active Ability (for supporting Units)**
This ability will be placed on other, likely less powerful, Units that can contribute to the Ritual.

* **Ability Name (Example):** `Perform Chant`
* **Full Conceptual Text:** "As a Player Action: Exhaust this Unit. This Unit becomes 'Chanting' until your next Start of Round Step or until it leaves play or becomes un-Ready through an opponent's effect. A Unit that is 'Chanting' can contribute to a Ritual."
* **Component Breakdown:**
    * **Trigger Component (from Appendix G, Section I):** `"As a Player Action (Activate this Ability)"`
        * *Illustrative Placeholder DB:* `1.0 DB`
    * **Effect Component 1 (Cost):** `"Exhaust this Unit"` (from Appendix E, Section I.B)
        * *Illustrative Placeholder DB (for including this as an effect/cost):* `0.5 DB` (Note: Exhausting as part of an Active Ability's cost is common and might be bundled into the base DB for Active Triggers in the Master List, or costed separately like this.)
    * **Effect Component 2 (Apply State):** `"This Unit becomes 'Chanting' [duration]."` ('Chanting' would be a defined, temporary state or marker. See Appendix E, Section I.B for "Apply State" if 'Chanting' becomes a formal named state, or this is a custom effect granting a temporary property).
        * *Illustrative Placeholder DB for applying this custom 'Chanting' state/marker:* `1.0 DB`
* **Illustrative Total DB Cost for `Perform Chant` ability:** `1.0 DB (Trigger) + 0.5 DB (Exhaust Effect/Cost) + 1.0 DB (Chanting State Effect) = 2.5 DB`
    This ability would consume `2.5 DB` from the TDB of the Unit it is on.

**Part 3: The "Ritual" (as the Condition for the "Invoke" Keyword)**
This condition would be written into the rule box of the Unit possessing the `Invoke` keyword.

* **Ritual Condition Example Text (on the `Invoke` Unit):** "`Invoke` - This Unit cannot be deployed normally. `Ritual:` If you control 3 or more friendly Units that are currently 'Chanting', you may deploy this Unit from your hand without paying its CP cost."
* **Component Breakdown of the Condition:**
    * **Condition Component (from Appendix H, Section III.B & IV):** `"If you control 3 or more friendly Units that are currently 'Chanting'"`
        * This involves checking player control, counting specific game elements (Units), and checking for a specific state ('Chanting') on those elements.
    * **Illustrative Design Budget (DB) Consideration for the Condition:**
        This condition's difficulty directly influences the justification for `Invoke` having a negative DB cost. A very easy condition would mean `Invoke` shouldn't grant much (if any) budget back. A difficult condition like this one (requiring 3 other specific units to have acted and maintained a state) makes the negative DB cost of `Invoke` viable. The Master DB Cost List would provide guidance on how various complexities of conditional checks affect an ability's overall DB valuation, or how they modify the DB cost of keywords like `Invoke`. For this system, the `Invoke` keyword's overall negative DB cost inherently accounts for the assumed difficulty of its linked Ritual.

**Part 4: Synergies and System Design**

* **Synergy:** The `Perform Chant` ability on multiple supporting Units directly enables the `Ritual` condition for the `Invoke` keyword on a powerful Unit. This creates a clear strategic goal for a player: protect their "Chanting" Units to bring forth a game-changing "Invoked" Unit. Opponents, in turn, have a clear counter-strategy: disrupt the "Chanting" Units.
* **Balancing Considerations:**
    * The power level of the "Invoked" Unit must be significant to justify the effort of the Ritual. Its high stats or powerful unique abilities are "paid for" by the negative DB cost of its `Invoke` keyword.
    * The Units with `Perform Chant` should be reasonably costed for their stats and this supporting ability. The `2.5 DB` (illustrative) for `Perform Chant` is a small cost, appropriate for an enabling ability on a potentially less impactful Unit.
    * The number of "Chanting" Units required for the Ritual (e.g., 3 in this example) is a key balancing lever.
* **Design Iteration:** Playtesting might reveal that 3 "Chanting" Units is too hard or too easy, or that the "Chanting" state needs to last longer or shorter, or that the "Invoked" units are over or underpowered. These observations would lead to adjustments in:
    * The definition of the Ritual condition.
    * The DB cost of the `Invoke` keyword (and thus the TDB available for the Invoked unit).
    * The DB cost of the `Perform Chant` ability.
    * The stats/abilities of the involved Units.

This "Invoke/Chant/Ritual" example demonstrates how designers can combine basic ability components (defined in Appendices E-H) into keywords and abilities that work together to create a unique, thematic, and strategically rich mechanic. The Progressive Budget Build system, using DB costs from the Master DB Cost List(s) for each component, allows for such complex interactions to be designed and budgeted for in a structured way.

## IX. Mission Challenges (Guidance Note)

Mission Cards are a unique and integral part of Quantum Nexus, providing players with overarching objectives, contributing to their Command Point (CP) generation each Game Round, and offering a distinct path to victory (see Rulebook Sections I.A, II.B, VI.B). The core of each Mission Card is its **Mission Challenge** – the specific set of conditions or objectives a player must achieve to complete that mission.

While the abilities found on other card types (Units, Assets, Events, etc.) are designed using the detailed effect, target, trigger, and condition frameworks outlined in Sections II-V of these Ability Creation Guidelines (and are costed using the Progressive Budget Build system via Design Budget points), Mission Cards and their Challenges have their own specialized design parameters.

These parameters include, but are not limited to:
* The complexity and nature of the challenge itself.
* The balance of Domain Points across a player's set of chosen Mission Cards.
* The passive effects or abilities Mission Cards might grant while in play or upon completion.
* The calculation of a Mission Card's own CP value, which contributes to a player's resources each Game Round (as per Rulebook Section II.B and III.C.1).

**Important Guidance for Designers:**

The principles, specific parameters, and balancing methodologies for designing Mission Cards – including their **Mission Challenges**, inherent abilities, passive effects, and the determination of their CP values – are detailed in a separate, official **"Quantum Nexus: Mission Card Design Document."**

Designers assigned to create or revise Mission Cards **must consult this dedicated document.** The "Quantum Nexus: Ability Creation Guidelines" (this document) primarily focuses on the creation and DB costing of abilities intended for cards that form a player's main deck (Units, Assets, Events, Upgrades, Terrain).

Attempting to design or cost Mission Challenges using only the general ability creation framework herein would not be appropriate, as Mission Cards have unique roles and balancing considerations within the overall game structure that are addressed in their specific design guide.

## X. Additional Considerations

When crafting abilities in Quantum Nexus, it's essential to consider how they interact with the broader game mechanics and strategic landscape. Beyond the specific choice of effects, targets, triggers, and conditions, here are some key factors to keep in mind to create compelling and well-integrated abilities:

* **Game Round Structure and Ability Timing:**
    Quantum Nexus gameplay unfolds in **Game Rounds**, each consisting of a **Start of Round Step** and an **Activation Sequence** (see Rulebook Section III.C). Understanding this structure is crucial for designing abilities with relevant and impactful timing:
    * **Start of Round Step:** This step involves simultaneous actions for all players (deactivating cards, gaining CP, drawing cards) followed by specific windows for triggered abilities (Rulebook Section III.C.1.b and III.C.1.c). Abilities designed to trigger "At the Start of the Game Round" or in response to the actions within this step (like drawing a card) must be clearly defined as such (see Appendix G).
    * **Activation Sequence:** This is where players take alternating single actions (Deploy a Card, Activate an Active Ability, Declare an Attack, Play an Event Card, Move a Unit, or Pass).
        * **Active Abilities** are chosen by a player as their single action. Their impact is immediate but consumes one of the player's limited actions for that turn within the sequence.
        * **Event-Driven (Triggered/Passive) Abilities** can activate at many points during the Activation Sequence in response to game events (e.g., a card being deployed, an attack being declared, an ability being activated). The resolution order for simultaneously triggered abilities is detailed in Rulebook Section VII.A, which designers should be familiar with.
    Consider how an ability's timing aligns with the game's flow and whether it offers advantages or interactions at strategically important moments within these distinct parts of the Game Round.

* **Card Interactions and Synergies:**
    Abilities don't exist in isolation. They interact with other cards, abilities, and game elements. Consider how your abilities might synergize with other cards (your own or potentially even your opponent's in unexpected ways), create interesting combos, or provide strategic counterplay opportunities against prevalent strategies. Well-designed synergies enhance strategic depth and reward thoughtful deck construction (see also CCG v2.0, Section X on Synergies).

* **Playtesting and Balance:**
    The true test of an ability's effectiveness, clarity, and balance lies in rigorous playtesting. Observe how your abilities perform in actual gameplay across various matchups and game states. Gather feedback from playtesters and be prepared to make adjustments to the ability's mechanics, its DB cost (on the Master DB Cost List), or even the card it's on, to ensure it is fair, engaging, and contributes positively to a dynamic and healthy gameplay experience. This aligns with the core principle that the PBB/DB system and its associated Master Lists require ongoing calibration (CCG v2.0, Section V.B).

* **Thematic Integration:**
    While functionality and balance are crucial, don't neglect the thematic element. Abilities should align with the card's overall concept, name, art, domain (Technology, Magic, Psionics, Divinity), and any associated lore or flavor. A Psionics-focused card, for instance, should have abilities that evoke mental powers or psychic phenomena, while a heavily armored 'Mech' Unit's abilities might emphasize resilience or firepower. Strong thematic integration makes cards more immersive and memorable.

By keeping these additional considerations in mind, alongside the detailed component design outlined in previous sections, you can create abilities that are not only mechanically sound but also thematically resonant, strategically engaging, and contribute positively to the rich tapestry of the Quantum Nexus universe.

## XI. Appendices for Ability Creation

This section provides a guide to the appendices contained within these "Quantum Nexus: Ability Creation Guidelines." These appendices offer detailed catalogues of core game components that designers will use to construct card abilities.

---
## Appendix E: Core Game Effects Catalogue

**Introduction:**
This catalogue provides a comprehensive list of core game effects available for ability design in Quantum Nexus. These effects are derived from the game's foundational rules and mechanics. Designers should use this list as a palette when constructing card abilities.

**I. Effects Primarily Affecting Cards in Play (Units, Assets, Terrain, Upgrades)**

| Effect Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------- |
| **A. Stat & Attribute Modification** |                                                                                                                                                                    |                      |
| Set Attack to X (this Game Round)                        | Sets a Unit's Attack value to X for the current Game Round. *Assumes X is the final value.* | X * 0.75             |
| Set Attack to X (ongoing while this effect is active)    | Sets a Unit's Attack value to X as long as the source of this effect remains active/in play. *Assumes X is the final value.* | X * 1.5              |
| Modify Attack by +/- X (this Game Round)                 | Increases or decreases a Unit's Attack value by X for the current Game Round.                                                                                        | X * 1.0              |
| Set Defense to X (this Game Round)                       | Sets a Unit's or Asset's Defense value to X for the current Game Round. *Assumes X is the final value.* | X * 0.5              |
| Set Defense to X (ongoing while this effect is active)   | Sets a Unit's or Asset's Defense value to X as long as the source of this effect remains active/in play. *Assumes X is the final value.* | X * 1.0              |
| Modify Defense by +/- X (this Game Round)                | Increases or decreases a Unit's or Asset's Defense value by X for the current Game Round.                                                                              | X * 0.75             |
| Set Attack Range to [Close/Mid/Far] (for a duration)     | Changes a Unit's attack range for a specified duration. (Cost depends on new range relative to base and its intrinsic DB cost, and duration)                       | *Varies* |
| Grant Attack Range [Close/Mid/Far] (for a duration)      | Grants an additional attack range or replaces current range for a specified duration. (Baseline for Close: 2.0, Mid: 4.0, Far: 6.0 if primary range)                  | 2.0 - 6.0            |
| Remove Target Unit's Attack Range (any single range profile it has, ongoing) | Removes a specific attack range from a Unit as long as this effect is active. (Significant detrimental effect if used on an opponent).                 | 2.0                  |
| **B. Applying States & Conditions** |                                                                                                                                                                    |                      |
| Exhaust Target Unit (or Apply Suppressed to Target Unit) | Target Unit becomes Exhausted (Rulebook: Suppressed units become Exhausted). Significant tempo impact.                                                                 | 3.0                  |
| Exhaust Target Non-Unit Card (e.g., Asset, Terrain if they can exhaust) | Target non-Unit card becomes Exhausted. Generally less impactful than exhausting a Unit.                                                                   | 2.0                  |
| Ready Target Card (Deactivate)                           | Changes an exhausted card to ready. Powerful tempo gain.                                                                                                             | 4.0                  |
| Remove Suppressed from Target Unit                       | If a Unit is Suppressed (and thus exhausted), it becomes ready. (Specific readying effect).                                                                          | 3.5                  |
| Apply Disordered to Target Unit                          | Target Unit gets -1 Defense until its controller's next Start of Round Step (as per Rulebook Section III.C.2).                                                         | 1.0                  |
| Remove Disordered from Target Unit                       | Removes the -1 Defense penalty and Disordered state. (Value is primarily negating the 1.0 DB effect).                                                                | 1.0                  |
| Apply [Custom Defined State] to Target Card              | Applies a specifically defined temporary or ongoing state to a card. This DB cost is for the *application* of the state only. The state's own effects must be costed. | 1.0                  |
| Remove [Custom Defined State] from Target Card           | Removes a specifically defined state from a card. *Design Note: This baseline assumes removal of a non-keyworded, temporary custom state of average impact.* | 1.0                  |
| **C. Movement & Positioning (Units, Terrain)** |                                                                                                                                                                    |                      |
| Move Target Unit 1 friendly cardinal quadrant. That Unit becomes Exhausted. | Effect causes movement and standard exhaustion, similar to a "Move a Unit" action but potentially as part of an event or another ability.                 | 1.0                  |
| Move Target Unit 1 friendly cardinal quadrant. That Unit does NOT become Exhausted from this move. | More valuable as it preserves the unit's readiness for other actions.                                                                                    | 2.5                  |
| Pushed Back Target Unit                                  | Controller moves the Unit one friendly cardinal quadrant (as per Rulebook Section III.C.2). (Forced repositioning).                                                    | 1.5                  |
| Swap Position of Two Target Friendly Units (both become Exhausted as part of this effect) | Exchanges the quadrants of two specified friendly Units; both become exhausted. More complex repositioning.                                                | 2.0                  |
| Put a Terrain card from your hand into a valid friendly quadrant (CP Paid Separately) | *Design Note: This effect's DB cost assumes the Terrain card's own printed CP cost is paid separately by the player.* | 1.0                  |
| Put a Terrain card from your hand into a valid friendly quadrant. You do not pay its CP cost. | Bypasses the Terrain's CP cost. *Assumes Average Terrain CP=2 (thus 9.0 DB for CP bypass).* | 1.0 + (Avg_CP*4.5) = 10.0 |
| Move Target Terrain to different Quadrant                | Moves an existing Terrain card to another valid friendly quadrant. Repositioning influential Terrain is tactically valuable.                                       | 1.0                  |
| **D. Modifying Abilities & Keywords** |                                                                                                                                                                    |                      |
| Grant Keyword [Keyword Name] to Target Card (for a duration) | Target card gains a specified keyword for a duration. (Cost = DB cost of Keyword + application fee)                                                                  | *Keyword DB + 1.0* |
| Remove Keyword [Keyword Name] from Target Card (ongoing) | Target card loses a specified keyword. (Cost should reflect average impact of removing a keyword).                                                                   | 2.0                  |
| Target Card Gains [Ability Text] (for a duration)        | Target card gains a specified rules text ability for a duration. This DB is for the *application*; the ability itself must be costed per ACG and Master List.      | 1.5                  |
| Target Card Loses [Specific Ability Text] (ongoing)      | Target card loses a specified ability for a duration.                                                                                                                | 2.0 per ability      |
| Target Card Loses All Abilities (ongoing)                | Target card loses all its printed abilities for a duration. ("Silence" effect, powerful).                                                                            | 6.5                  |
| Negate Target Card's Passive/Triggered Abilities (for a duration) | Specified abilities on the target card do not function for a duration.                                                                                           | 2.5 - 4.5            |
| **E. Transformation & Type Change** |                                                                                                                                                                    |                      |
| Target Unit becomes a Leader (ongoing)                   | Changes a Unit's subtype to Leader (respecting quadrant limits). Significant upgrade and strategic impact.                                                             | 5.0                  |
| Target Leader Unit is no longer a Leader (ongoing)       | Removes Leader subtype. Significant downgrade and strategic impact.                                                                                                    | 4.0                  |
| Change Target Card's Subtype to [Subtype] (for a duration/ongoing) | Changes a card's subtype. (Cost depends on new subtype's mechanical implications and duration)                                                                 | 0.5 - 2.0            |
| **F. Attachment (Upgrades)** |                                                                                                                                                                    |                      |
| Attach an Upgrade card from your hand to a valid friendly target (CP Paid Separately) | *Design Note: Assumes Upgrade's own CP cost is paid separately.* | 0.75                 |
| Attach an Upgrade card from your hand to a valid friendly target. You do not pay its CP cost. | Bypasses the Upgrade's CP cost. *Assumes Average Upgrade CP=1 (thus 4.5 DB for CP bypass).* | 0.75 + (Avg_CP*4.5) = 5.25 |
| Detach Target Opponent's Upgrade                         | Removes an opponent's Upgrade from the card it's attached to (it goes to Discard Pile unless specified).                                                               | 1.5                  |
| Detach Target Friendly Upgrade                           | Removes a friendly Upgrade. Less impactful, might be for synergy or to free up an attachment slot.                                                                   | 0.25                 |
| Transfer Target Upgrade to another valid Unit/Asset      | Moves an attached Upgrade to another valid target. (Combines detach and re-attach logic).                                                                              | 1.0                  |
| **G. Destruction & Removal from Play** |                                                                                                                                                                    |                      |
| Inflict Impact X on Unit                                 | Compare X to target Unit's Defense. If X > D, destroy Unit. If X = D, Unit Suppressed. If X < D, no effect. (Reflects potential for destroy/suppress).           | (X * 1.5) + 1.0      |
| Destroy Target Unit                                      | Target Unit is moved to its owner's Discard Pile.                                                                                                                      | 4.0                  |
| Destroy Target Asset                                     | Target Asset is moved to its owner's Discard Pile.                                                                                                                     | 3.0                  |
| Destroy Target Terrain                                   | Target Terrain is moved to its owner's Discard Pile.                                                                                                                   | 2.0                  |
| Destroy Target Upgrade                                   | Target Upgrade is moved to its owner's Discard Pile.                                                                                                                   | 1.0                  |
| Return Target Card to Owner's Hand                       | Target card in play (or other specified zone) is returned to its owner's hand. (Specify Unit: 2.5; Asset: 2.0; Terrain: 1.5; Upgrade: 1.0 for base)               | 1.0 - 2.5            |
| Place Target Card on Top/Bottom of Owner's Deck          | Target card from play/hand/discard is placed on top or bottom of its owner's Deck. (Top is stronger than bottom).                                                     | 1.0 - 2.0            |
| Shuffle Target Card into Owner's Deck                    | Target card from play/hand/discard is shuffled into its owner's Deck. (Delays, but doesn't remove permanently).                                                        | 1.0                  |
| **H. Interactions with Other Cards in Play** |                                                                                                                                                                    |                      |
| Activate an Active Ability of Target Card                | Causes an Active Ability on another card to activate (specify cost payment responsibilities). (Complex, depends on ability being activated)                        | *Varies* |
| Trigger a Triggered Ability of Target Card               | Causes a specified Triggered Ability on another card to meet its trigger condition and resolve. (Complex, depends on ability being triggered)                      | *Varies* |

**II. Effects Primarily Affecting Player Resources & Zones (Hand, Deck, Discard Pile, CP)**

| Effect Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------- |
| **A. Command Points (CP)** |                                                                                                                                                                    |                      |
| Gain X CP                                                | Player gains X CP for the current Game Round. (Aligned with ~4.5-5.0 DB = 1 CP conversion).                                                                          | 4.5 per X            |
| Target Player Loses X CP                                 | Target player loses X CP from their current CP pool. (Resource denial, slightly more impactful than self-gain).                                                       | 5.0 per X            |
| Reduce CP Cost of [Criteria] by X                        | The CP cost to play a card (next card, specific type, name) is reduced by X for a duration or instance. (Conditional CP gain).                                       | 3.5 per X            |
| Increase CP Cost of [Criteria] for Target Player by X    | Target player must pay X additional CP to play cards meeting criteria for a duration or instance. (Conditional CP denial).                                             | 4.0 per X            |
| Set CP Cost of [Criteria] to X                           | Sets the CP cost to play a card meeting criteria to a specific value X for a duration or instance. (Cost relative to typical cost and new X value's implication).      | *Varies* |
| **B. Card Draw & Hand Manipulation** |                                                                                                                                                                    |                      |
| Player Draws X Card(s)                                   | Player draws X cards from their Deck. (Card advantage is very powerful).                                                                                             | 4.0 per X            |
| Target Player Discards X Card(s) from Hand, chosen by that player | Specified player chooses and discards X cards from their hand.                                                                                                 | 3.0 per X            |
| Target Player Discards X Card(s) from Hand at random     | Specified player discards X cards from their hand at random. (More disruptive than player choice).                                                                     | 4.0 per X            |
| Target Player Discards X Card(s) from their *revealed* Hand, chosen by controller of this effect | Controller of effect chooses X cards for target player to discard from their *revealed* hand. (Most disruptive non-random discard if hand is known).            | 4.5 per X            |
| Look at Target Player's Hand                             | Player looks at the cards in another player's hand. (Information gain).                                                                                              | 1.0                  |
| Target Player's Maximum Hand Size becomes X (for Start of Round draw) | Modifies hand size limit for drawing during Start of Round Step (Rulebook III.C.1.a.iii draws to 5). (Impact depends on X vs 5 and duration).                 | *Varies* |
| **C. Deck Manipulation** |                                                                                                                                                                    |                      |
| Target Player Searches their Deck for [Card Criteria]    | Player searches their deck for card(s) meeting criteria, reveals it (usually), adds to hand (usually), then shuffles. ("Tutor" effect, very strong).                | 4.0 - 7.0            |
| Target Player Shuffles their Deck                        |                                                                                                                                                                    | 0.5                  |
| Look at Top X Cards of [Player's/Opponent's] Deck        | Player looks at top cards. Specify what happens next (e.g., put back in any order, discard some, put on bottom, add one to hand). (DB for look only; action adds more). | 0.5 + *cost of action* |
| Target Player Discards Top X Cards of their Deck ("Mill")| Moves cards from top of Deck to Discard Pile. (Direct attack on a win condition).                                                                                    | 1.5 per X            |
| Reorder Top X Cards of [Player's/Opponent's] Deck        | Changes the order of the top cards of a deck. (Moderate utility/setup).                                                                                              | 1.0                  |
| Place Card from Hand/Discard on Top/Bottom of [Player]'s Deck | Moves a card from one zone to a specific part of a deck. (Top of deck more impactful than bottom).                                                                 | 0.5 - 1.5            |
| **D. Discard Pile Interaction** |                                                                                                                                                                    |                      |
| Return Target Card from [Player]'s Discard Pile to Hand  | Recursion is strong. (Cost varies by card type: e.g., Unit `3.0`, Asset `2.5`, Event `2.0`, Upgrade/Terrain `1.5`).                                                    | 1.5 - 3.0            |
| Return Target Card from [Player]'s Discard Pile to Deck  | Specify top/bottom or shuffle in. (Less immediate than to hand).                                                                                                     | 1.0                  |
| Deploy Target Card from [Player]'s Discard Pile into Play (CP Paid Separately) | Card is put onto the Battlefield/Loadout Area. *Assumes CP cost is paid unless specified otherwise*.                                                       | 2.0 - 4.0 (by type)  |
| Deploy Target Card from [Player]'s Discard Pile into Play. You do not pay its CP cost. | Powerful "reanimation." Cost must reflect bypassed CP. *DB = Base_Deploy_Cost + (Card's_CP * 4.5)* | *Varies Significantly*|
| Remove Target Card in Discard Pile from the Game         | Card is removed from Discard Pile and game. (Permanent removal from recursion).                                                                                      | 1.0                  |

**III. Effects Primarily Affecting Game State, Rules & Flow**

| Effect Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------- |
| **A. Modifying Actions & Activations** |                                                                                                                                                                    |                      |
| Player may take an Additional Single Action this Activation Sequence | Allows a player an extra single action from the standard list. (Very Powerful, breaks action economy).                                                       | 7.0                  |
| Target Card may Activate its Active Ability an Additional Time this Game Round | Allows a card's active ability to be used again, bypassing typical "once per round" or exhaustion limits for that activation.                              | 2.5                  |
| Prevent Target Card from Activating Active Abilities (for a duration) | Target card cannot use its Active Abilities for a duration.                                                                                                      | 2.0                  |
| Prevent Target Card from Attacking (for a duration)      | Target Unit cannot be chosen to Declare an Attack for a duration.                                                                                                    | 2.0                  |
| Prevent Target Card from Moving (for a duration)         | Target Unit cannot perform a Move action or be moved by other card effects for a duration.                                                                           | 1.0                  |
| **B. Modifying Game Rules (Specific Instances)** |                                                                                                                                                                    |                      |
| Modify Targeting Rules for [Player/Card Type] (for a duration) | E.g., "Cards opponent controls lose 'cannot be targeted by abilities' this Game Round." (Powerful, depends on scope of rule modified).                             | 3.0 - 6.0            |
| Modify Deployment Rules for [Player/Card Type] (for a duration) | E.g., "You may deploy your next Unit this Game Round as if its CP cost were 0." (Effectively CP gain, very strong).                                               | *Varies (High)* |
| Modify Combat Impact (for a duration)                    | E.g., "Impact inflicted by your Units is +1 this Game Round," or "Reduce Impact inflicted by opponent's Units by 1 this Game Round." (Global effect).             | 3.0 per +/-1         |
| **C. Interacting with Mission Cards** |                                                                                                                                                                    |                      |
| Add/Remove Progress Counter to/from a Mission Card       | (Assumes missions might use counters if not binary completion). (Depends on mission value and counter system if implemented).                                        | *Varies* |
| Auto-Complete Target Mission Card                        | Instantly fulfills and completes a Mission Card. (Potentially game-winning, depends on mission difficulty/reward).                                                     | 10.0 - 20.0          |
| Negate Passive Effect(s) of Target Mission Card (for a duration) | Specified Mission Card's ongoing effect(s) are nullified for a duration.                                                                                         | 3.0                  |
| **D. Game Flow & End States** |                                                                                                                                                                    |                      |
| End the current Game Round                               | Prematurely ends current Game Round; new Game Round begins. (Massive disruption).                                                                                    | 8.0                  |
| End the current Player's Turn in Activation Sequence     | Current player immediately finishes their turn; play proceeds to next player.                                                                                        | 2.0                  |
| Player Wins the Game                                     | Directly causes a player to win (Immediate Victory applies). (Extremely high cost, likely highly conditional).                                                       | 25.0+                |
| Player Loses the Game                                    | Directly causes a player to lose (Immediate Loss applies). (High cost, likely conditional, or major drawback).                                                      | *Varies (High)* |
| **E. Copying & Negating** |                                                                                                                                                                    |                      |
| Copy Target [Event Card Effect / Active Ability Effect / Triggered Ability Effect] | Effect of copied card/ability resolves. Specify targeting. (Cost ~75% of original effect's DB is a guideline for Master List).                            | *Varies* |
| Negate (Counter) Target [Event Card Effect / Active Ability / Triggered Ability] | Targeted effect/ability does not resolve / is prevented. ("Counterspell," powerful reactive play).                                                     | 4.0 - 6.0            |
| **F. Initiative Manipulation** |                                                                                                                                                                    |                      |
| [Player] Gains Initiative for the Next Game Round        | Specified player takes first action next Game Round, overriding standard initiative.                                                                                 | 3.0                  |

---
## Appendix F: Core Game Targets Catalogue

**Introduction:**
This catalogue provides a comprehensive list of core game targets available for ability design in Quantum Nexus. The **"Illustrative DB Cost (Additive/Modifier)"** column indicates a conceptual adjustment to an Effect's base DB cost. Official DB costs/modifiers for targets will be in the **Master DB Cost List(s)**. Targeting opponent's things or broader scopes generally increases value.

**I. Target: Cards**

| Target Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **A. Cards in Play** | Cards on Battlefield or Loadout Area.                                                                                                                              |                                          |
| Card in Play                                             | Any single card in play. (More specific types below are generally used).                                                                                             | +0.25                                    |
| Unit                                                     | A single Unit card on the Battlefield. (Often baseline for Effect cost).                                                                                             | 0.0 (often part of effect's base DB)     |
| Leader                                                   | A single Unit card with 'Leader' subtype. (Higher value target).                                                                                                   | +0.5                                     |
| Asset                                                    | A single Asset card in a player's Loadout Area.                                                                                                                      | 0.0                                      |
| Upgrade                                                  | A single Upgrade card attached to a Unit or Asset.                                                                                                                   | -0.25 (often less impactful to target directly than the host) |
| Terrain                                                  | A single Terrain card on the Battlefield.                                                                                                                            | 0.0                                      |
| X number of [Card Type(s) in Play]                       | A specific number (X) of cards of specified type(s) in play. (Multiplier per target beyond first is a guideline).                                                    | +0.5 per additional target beyond first  |
| All [Card Type(s) in Play] [Scope: Player's Battlefield / Opponent's Battlefield / All Battlefields] | All cards of specified type(s) in the defined scope. (Significant increase over single target).                                                                      | Large Flat Additive (e.g., +8.0 to +15.0 depending on scope and type) |
| **B. Cards in Hand** |                                                                                                                                                                    |                                          |
| Card(s) in Hand (for discard/reveal by owner/random)     | One or more cards in a player's hand. *Note: Controller of effect cannot choose from opponent's hidden hand per Core Principles unless revealed.* | 0.0 (Choice method for discard costed in Effect) |
| **C. Cards in Deck** |                                                                                                                                                                    |                                          |
| Card(s) in Deck (for search/reveal)                      | One or more cards within a player's Deck.                                                                                                                            | +0.25 (if specific type for search)        |
| Top/Bottom X Card(s) of Deck                             | The specified top or bottom X cards of a player's Deck.                                                                                                              | 0.0                                      |
| **D. Cards in Discard Pile** |                                                                                                                                                                    |                                          |
| Card(s) in Discard Pile                                  | One or more cards in a player's Discard Pile.                                                                                                                        | 0.0                                      |
| **E. Cards in Mission Card Area** |                                                                                                                                                                    |                                          |
| Mission Card                                             | A specific Mission Card in a player's Mission Card Area. (High impact if affected).                                                                                  | +1.0                                     |
| **F. Other Card-Specific Targets** |                                                                                                                                                                    |                                          |
| Card with [Specific Keyword]                             | Any card (specify zone) possessing a given keyword. (Adds specificity).                                                                                              | +0.25                                    |
| Card with [Specific Subtype]                             | Any card (specify zone) of a given subtype. (Adds specificity).                                                                                                      | +0.25                                    |
| Card with [Specific CP Cost / Stat Value / Name]         | Any card (specify zone) meeting a specific CP cost, stat value, or name. (Adds specificity).                                                                         | +0.25                                    |

**II. Target: Players & Player-Controlled Attributes**

| Target Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| Player (Self)                                            | The player controlling/activating the ability ("You").                                                                                                             | 0.0                                      |
| Player (Opponent)                                        | An opponent. Specify if "target opponent" or "each opponent." ("Each opponent" has higher DB).                                                                     | +0.5 (target) / +2.0 (each opponent)     |
| Player (Any)                                             | Any player in the game, including self.                                                                                                                              | +0.25                                    |
| Player who [Met Condition]                               | A player who meets a specific condition (e.g., "player with most CP").                                                                                               | +0.5                                     |
| Player's Command Points (CP)                             | A player's current CP pool (for effects that gain/lose/set CP).                                                                                                      | 0.0                                      |
| Player's Hand (as an entity/attribute)                   | The cards collectively in a player's hand (e.g., for effects related to hand size).                                                                                  | 0.0                                      |
| Player's Deck (as an entity/attribute)                   | A player's Deck (e.g., for effects related to deck size).                                                                                                            | 0.0                                      |
| Player's Discard Pile (as an entity/attribute)           | A player's Discard Pile (e.g., for effects related to its size or contents generally).                                                                               | 0.0                                      |

**III. Target: Game Elements, Zones & Areas**

| Target Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **A. Battlefield Areas** |                                                                                                                                                                    |                                          |
| Quadrant                                                 | A single quadrant on any player's side. Specify friendly/opponent, specific location if needed.                                                                    | 0.0                                      |
| Row (Front/Back)                                         | All three quadrants in a player's Front or Back Row. Specify friendly/opponent. (Targets multiple zones).                                                          | +1.5                                     |
| Column (Left/Center/Right)                               | Both quadrants in a player's Left, Center, or Right column. Specify friendly/opponent. (Targets multiple zones).                                                    | +1.0                                     |
| Player's Battlefield                                     | All six quadrants on one player's side of the Battlefield. (Targets many zones).                                                                                     | +2.5                                     |
| All Battlefields                                         | All quadrants of all players. (Global scope).                                                                                                                        | +4.0                                     |
| **B. Other Zones (as entities)** |                                                                                                                                                                    |                                          |
| Player's Loadout Area                                    | A specific player's Loadout Area.                                                                                                                                    | 0.0                                      |
| Player's Mission Card Area                               | A specific player's Mission Card Area.                                                                                                                               | 0.0                                      |
| Player's Deck (Zone)                                     | A player's entire Deck as a zone (e.g., for shuffling).                                                                                                              | 0.0                                      |
| Player's Discard Pile (Zone)                             | A player's entire Discard Pile as a zone.                                                                                                                            | 0.0                                      |

**IV. Target: Abstract Game Concepts & Properties**

| Target Description                                       | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **A. Stats & Values** |                                                                                                                                                                    |                                          |
| Attack Value (of a Card)                                 | The numerical Attack stat of a Unit (e.g., for an effect that says "double target Unit's Attack Value").                                                             | 0.0                                      |
| Defense Value (of a Card)                                | The numerical Defense stat of a Unit or Asset.                                                                                                                       | 0.0                                      |
| CP Cost (of a Card)                                      | The printed Command Point cost of a card (e.g., for effects that check or use this value).                                                                           | 0.0                                      |
| Number (e.g., X)                                         | An abstract number, often chosen by a player or determined by a game state, used as input for an effect.                                                             | 0.0                                      |
| **B. Keywords & Abilities** |                                                                                                                                                                    |                                          |
| Keyword (on a Card)                                      | A specific keyword possessed by a card (e.g., for removal or conditional checks).                                                                                    | 0.0                                      |
| Ability (on a Card)                                      | A specific printed or granted ability on a card (e.g., to negate or copy it).                                                                                        | 0.0                                      |
| Triggered Ability (instance)                             | A specific triggered ability that has just met its trigger condition (e.g., for a counter effect).                                                                   | 0.0                                      |
| Activated Ability (instance)                             | A specific active ability as it's being activated (e.g., for a counter effect).                                                                                      | 0.0                                      |
| Event Card Effect (instance)                             | The effect of an Event card as it's resolving (e.g., for a counter effect).                                                                                          | 0.0                                      |
| **C. Game Mechanics** |                                                                                                                                                                    |                                          |
| Initiative                                               | The abstract concept of initiative (e.g., for an effect that states "target player gains Initiative").                                                               | 0.0                                      |
| A Game Rule                                              | Rarely targeted directly, but abilities may state "ignore [specific game rule] for this effect/card." (Cost based on rule's impact).                                 | *Varies* |
| **D. Choices** |                                                                                                                                                                    |                                          |
| Choice (from a list of options provided by an ability)   | When an ability says "Choose one: A; or B," the "Choice" is the target of the player's decision. (Flexibility adds value to overall ability).                        | +0.5 to +1.0 (if choices are distinct & valuable) |

---
## Appendix G: Core Game Triggers Catalogue

**Introduction:**
This catalogue provides a comprehensive list of core game triggers available for ability design. Triggers define when an ability activates. Official, calibrated DB costs for all trigger types will be in the **Master DB Cost List(s)**.

**I. General Active Ability Trigger**

| Trigger Description                                      | Notes                                                                                                                                                              | Illustrative DB Cost |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------- |
| As a Player Action (Activate this Ability)               | Ability activated as a single action during player's turn in Activation Sequence, paying all specified costs. (Rulebook Section III.C.2). Consumes a player action. | 1.0                  |

**II. Event-Driven Triggers (Passive / Automatic)**
(DB cost reflects value of effect occurring without consuming a player action, and trigger frequency/reliability.)

| Trigger Description                                      | Notes                                                                                                                                                              | Illustrative DB Cost |
| :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------- |
| **A. Game Phase & Step Triggers** |                                                                                                                                                                    |                      |
| At the Start of the Game Round                           | Triggers during Start of Round Step, after III.C.1.a actions and III.C.1.b triggers. (Reliable, once per round).                                                     | 2.0                  |
| When [Player] Gains CP                                   | Triggers when specified player gains CP (Start of Round or card effect). (Can be frequent).                                                                        | 1.0                  |
| When [Player] Draws [X] Card(s)                          | Triggers when specified player draws one or more cards. (Common).                                                                                                    | 1.0                  |
| When [Player's] Activation Sequence Turn Begins          | Triggers when it's specified player's turn to act. (Reliable, once per player per round).                                                                            | 1.5                  |
| When [Player] Chooses to Pass their Action               | Triggers when specified player "Passes" their single action. (Less common as a benefit source).                                                                      | 0.5                  |
| At the End of the Activation Sequence                    | Triggers when all players consecutively pass, ending Activation Sequence. (Reliable, once per round).                                                                | 1.5                  |
| At the End of the Game Round                             | (Effectively same as "At the End of the Activation Sequence").                                                                                                       | 1.5                  |
| **B. Card State & Zone Change Triggers** | (Self-affecting triggers often cheaper than opponent-affecting, unless trigger is detrimental to self).                                                              |                      |
| When [This/Target/Any] Card is Deployed                  | Triggers when specified card (or type/criteria) is successfully deployed. ("This card": 1.5, "Any friendly card of type X": 2.0, "Any opponent's card of type X": 2.5). | 1.5 - 2.5            |
| When [This/Target/Any] Card is Destroyed                 | Triggers when specified card is destroyed. ("This card": 1.0, "Any friendly Unit": 1.5, "Any opponent's Unit": 2.0).                                                   | 1.0 - 2.0            |
| When [This/Target/Any] Card Leaves Play                  | Triggers when specified card moves from Battlefield/Loadout to any other zone. (Broader than destroy. "This card": 1.5).                                             | 1.5 - 2.5            |
| When [This/Target/Any] Card Enters [Zone]                | Triggers when specified card enters a specific zone (e.g., "Discard Pile," "Hand from play"). (Depends on zone/frequency).                                          | 0.5 - 2.0            |
| When [This/Target/Any] Card Becomes Exhausted            | Triggers when specified card changes from Ready to Exhausted. (Common event).                                                                                        | 0.5                  |
| When [This/Target/Any] Card Becomes Ready                | Triggers when specified card changes from Exhausted to Ready.                                                                                                        | 0.5                  |
| When [This/Target/Any] Unit Becomes Suppressed           | Triggers when specified Unit becomes Suppressed.                                                                                                                     | 0.75                 |
| When [This/Target/Any] Unit Becomes Disordered           | Triggers when specified Unit becomes Disordered.                                                                                                                     | 0.75                 |
| When [This/Target/Any] Card's [Stat] is Modified         | Triggers when a specified stat (e.g., Attack) of the card is changed. (Can be frequent).                                                                             | 0.5                  |
| When [This/Target/Any] Card Gains/Loses a Keyword        | Triggers when a keyword is added to or removed from specified card.                                                                                                  | 0.5                  |
| When an Upgrade is Attached to [This/Target/Any] Card    | Triggers when an Upgrade card becomes attached to specified card.                                                                                                    | 0.75                 |
| When an Upgrade is Detached from [This/Target/Any] Card  | Triggers when an Upgrade card is removed from specified card.                                                                                                        | 0.5                  |
| **C. Combat-Related & Impact Triggers** | (See Rulebook Section III.C.2 for combat outcomes).                                                                                                                  |                      |
| When [This/Target/Any] Unit Declares an Attack           | Triggers when specified Unit is declared as an attacker. ("This Unit": 1.0, "Any Friendly Unit": 1.5, "Any Opponent Unit": 2.0).                                       | 1.0 - 2.0            |
| When [This/Target/Any] Unit is Declared as a Defender    | Triggers when specified Unit is chosen as target of an attack. ("This Unit": 1.0, "Any Friendly Unit": 1.5, "Any Opponent Unit": 2.0).                                  | 1.0 - 2.0            |
| When [This/Target/Any] Unit Destroys another Unit (via Attack/Impact) | Triggers if specified Unit destroyed another Unit. ("This Unit": 1.5).                                                                                       | 1.5 - 2.5            |
| When [This/Target/Any] Unit is Destroyed (via Attack/Impact) | Triggers if specified Unit was destroyed by attack/impact. ("This Unit": 1.0).                                                                                     | 1.0 - 2.0            |
| When [This/Target/Any] Unit Suppresses another Unit (via Attack/Impact) | Triggers if specified Unit Suppressed another Unit. ("This Unit": 0.75).                                                                                     | 0.75 - 1.5           |
| When [This/Target/Any] Unit is Suppressed (via Attack/Impact) | Triggers if specified Unit was Suppressed by attack/impact. ("This Unit": 0.5).                                                                                    | 0.5 - 1.0            |
| When [This/Target/Any] Attacking Unit Becomes Disordered | Triggers if specified attacking Unit became Disordered. ("This Unit": 0.5).                                                                                          | 0.5 - 1.0            |
| When [This/Target/Any] Attacking Unit is Pushed Back     | Triggers if specified attacking Unit was Pushed Back. ("This Unit": 0.5).                                                                                            | 0.5 - 1.0            |
| When [This/Target/Any] Unit Inflicts Impact              | Triggers when specified Unit resolves "Inflict Impact" (regardless of outcome). ("This Unit": 0.75).                                                                 | 0.75 - 1.5           |
| When [This/Target/Any] Unit is targeted by an "Inflict Impact" effect | Triggers when specified Unit is chosen as target of "Inflict Impact" (before resolution). ("This Unit": 0.75).                                                  | 0.75 - 1.5           |
| When [This/Target/Any] Unit Moves Quadrant(s)            | Triggers when specified Unit moves quadrant (via Move action or card effect). ("This Unit": 0.5).                                                                    | 0.5 - 1.0            |
| **D. Player Action & Resource Triggers** |                                                                                                                                                                    |                      |
| When [Player] Plays [Card Type/Subtype/Name] Card        | Triggers when specified player successfully plays a card from hand. (Friendly play: 1.0, Opponent play: 1.5).                                                         | 1.0 - 1.5            |
| When [Player] Activates an Active Ability                | Triggers when specified player successfully activates any Active Ability. (Friendly: 0.75, Opponent: 1.0).                                                             | 0.75 - 1.0           |
| When [Player]'s CP becomes/is [Condition] X              | Triggers when specified player's CP total meets a condition. (Situational).                                                                                          | 0.5 - 1.5            |
| When [Player]'s Hand Size becomes/is [Condition] X       | Triggers when specified player's number of cards in hand meets a condition. (Situational).                                                                         | 0.5 - 1.5            |
| When [Player]'s Deck has X or Fewer Cards                | Triggers when cards in specified player's Deck drops to X or below. (Late game relevance).                                                                           | 0.75                 |
| When [Player]'s Deck Becomes Empty                       | Triggers when player must draw from empty deck (resolves before loss). (Game-ending relevance).                                                                    | 1.0                  |
| When [Player] Completes a Mission Card                   | Triggers when specified player completes one of their Mission Cards. (Significant event).                                                                            | 2.0                  |
| When [Player] Targets [Criteria] with an Ability/Attack  | Triggers when specified player targets card/player meeting criteria. (Can be common).                                                                                | 0.75                 |
| When an Effect from an Opponent's Card Targets [This/Target/Any Owned] Card | Triggers when an opponent's card effect targets specified card(s) you control. (Defensive trigger).                                                      | 1.5                  |

---
## Appendix H: Core Game Condition Types Catalogue

**Introduction:**
This catalogue outlines common condition types for abilities. Conditions add "if/unless" logic. Restrictive conditions usually apply a **negative DB modifier** (reducing ability's DB cost or justifying stronger effect). Enabling conditions (rare) might add positive DB. Official DB costs/modifiers for conditions will be in the **Master DB Cost List(s)**.

**I. Game State Conditions**

| Condition Type Description                                           | Examples of Phrasing / Notes                                                                                                                               | Illustrative DB Cost / Modifier |
| :------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------ |
| **A. Timing Within Game Round** |                                                                                                                                                            |                                 |
| If it is the Start of Round Step                                       | Checks if game is in this step (Rulebook III.C.1). (Highly restrictive timing).                                                                              | -1.0                            |
| If it is the Activation Sequence                                       | Checks if game is in Activation Sequence (Rulebook III.C.2). (Less restrictive).                                                                             | -0.25                           |
| If it is [Player]'s turn in the Activation Sequence                    | Checks if specified player is acting. (Restricts to specific player's turn).                                                                               | -0.5                            |
| If [Player] has Initiative                                             | Checks if specified player holds initiative (Rulebook III.D). (Moderately restrictive).                                                                      | -0.25                           |
| **B. General Game State Checks** |                                                                                                                                                            |                                 |
| If a [Specific Trigger Event from App. G] has occurred this Game Round | E.g., "If a friendly Unit was destroyed this Game Round." (Depends on event rarity/impact).                                                                  | -0.25 to -1.0                   |
| If no [Specific Trigger Event from App. G] has occurred this Game Round| E.g., "If you have not drawn any cards this Game Round, other than during Start of Round Step." (Can be enabling or restrictive).                             | +/-0.25 to +/-0.5               |
| If total CP spent by [Player] this Game Round is [Comparison] X        | E.g., "If you have spent 5 or more CP this Game Round." (Variable restriction).                                                                              | -0.25 to -0.75                  |
| If it is the first/second/etc. Game Round                              | Checks current Game Round number. (Highly restrictive for later rounds).                                                                                     | -0.5 to -1.5                    |

**II. Card-Specific Conditions**

| Condition Type Description                                           | Examples of Phrasing / Notes                                                                                                                               | Illustrative DB Cost / Modifier |
| :------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------ |
| **A. Card Identity & Type** |                                                                                                                                                            |                                 |
| If [This/Target/Specified] Card is [Card Name]                       | Checks for a specific named card. (Very restrictive).                                                                                                      | -1.0 to -2.0                    |
| If [This/Target/Specified] Card is a [Unit/Leader/Asset/Terrain/Upgrade] | Checks card's primary type. (Moderate restriction).                                                                                                        | -0.25                           |
| If [This/Target/Specified] Card has [Subtype]                        | E.g., "If this Unit is a 'Mech'." (Moderate to high restriction).                                                                                            | -0.5 to -1.0                    |
| If [This/Target/Specified] Card has [Keyword]                        | Checks if card possesses a specific keyword. (Moderate restriction).                                                                                       | -0.5                            |
| If [This/Target/Specified] Card is of [Domain]                       | Checks card's Domain affinity. (Moderate restriction).                                                                                                     | -0.5                            |
| **B. Card Stats & Cost** |                                                                                                                                                            |                                 |
| If [This/Target/Specified] Card's [Attack/Defense/CP Cost] is [Comparison] X | E.g., "If target Unit's Attack is 5 or more." (Variable restriction).                                                                                      | -0.25 to -1.0                   |
| If [This/Target/Specified] Card's [Stat A] is [Comparison] its [Stat B] | E.g., "If this Unit's Attack is greater than its Defense." (Specific condition).                                                                             | -0.5                            |
| **C. Card State** |                                                                                                                                                            |                                 |
| If [This/Target/Specified] Card is Exhausted                         | Checks if card is currently exhausted.                                                                                                                     | -0.25                           |
| If [This/Target/Specified] Card is Ready                             | Checks if card is currently ready.                                                                                                                         | -0.1                            |
| If [This/Target/Specified] Unit is Suppressed                        | Checks if Unit is currently Suppressed.                                                                                                                    | -0.5                            |
| If [This/Target/Specified] Unit is Disordered                        | Checks if Unit is currently Disordered.                                                                                                                    | -0.5                            |
| If [This/Target/Specified] Card is Attached (for Upgrades)           | Checks if an Upgrade is currently attached.                                                                                                                | -0.1                            |
| If [This/Target/Specified] Card has an Upgrade Attached              | Checks if Unit or Asset has any (or specific type of) Upgrade attached.                                                                                    | -0.25                           |
| If [This/Target/Specified] Card has [X] [Counter Type] on it         | Checks for presence/number of specific game counters (if introduced).                                                                                      | *Varies* |
| **D. Card Location (Zone/Position)** |                                                                                                                                                            |                                 |
| If [This/Target/Specified] Card is in [Zone]                         | Checks if card is in specific zone (Hand, Deck, Discard Pile, Loadout Area, Battlefield). (Contextual restriction).                                         | -0.25 to -0.75                  |
| If [This/Target/Specified] Unit is in [Player]'s [Quadrant Name/Row/Column] | E.g., "If this Unit is in your Front Row." (Positional, "Front Row" example was -0.5).                                                                     | -0.25 to -1.0                   |
| If [This/Target/Specified] Card is the Top Card of [Player]'s [Deck/Discard Pile] | (Specific, potentially enabling combos).                                                                                                                     | -0.25                           |
| If [Quadrant] is Occupied/Empty                                      | Checks if specified quadrant contains any Units (or specific types).                                                                                       | -0.25                           |
| If [Quadrant] contains a [Terrain Type/Keyword] Terrain              | Checks properties of Terrain in a quadrant.                                                                                                                | -0.5                            |

**III. Player-Specific Conditions**

| Condition Type Description                                                     | Examples of Phrasing / Notes                                                                                                                               | Illustrative DB Cost / Modifier |
| :--------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------ |
| **A. Player Resources** |                                                                                                                                                            |                                 |
| If [Player]'s CP is [Comparison] X                                           | E.g., "If your CP is 0." (Can be very restrictive, or enabling for "low CP" bonuses).                                                                      | -0.25 to -1.5                   |
| If [Player]'s Hand contains [Number/Type/Criteria of] Card(s)                | E.g., "If your hand is empty," "If you have 3+ Event cards in hand." (Variable restriction).                                                               | -0.25 to -1.0                   |
| If [Player]'s Deck has [Number] or [Fewer/More] Cards                        | E.g., "If your Deck has 10 or fewer cards." (Typically late-game restrictive).                                                                               | -0.5 to -1.0                    |
| If [Player]'s Discard Pile contains [Number/Type/Criteria of] Card(s)        | E.g., "If there are 5+ Unit cards in your Discard Pile." (Enables graveyard strategies).                                                                   | -0.25 to -0.75                  |
| **B. Player Control & Board Presence** |                                                                                                                                                            |                                 |
| If [Player] Controls [Number/Type/Criteria of] Card(s)                       | E.g., "If you control a Leader," "If opponent controls no Units." (Common condition type).                                                                 | -0.25 to -1.0                   |
| If [Player] Controls more/fewer [Card Type] than Opponent(s)                 | E.g., "If you control more Ready Units than target opponent." (Comparative, dynamic).                                                                      | -0.5                            |
| If [Player] has completed [X / Specific Name / Type of] Mission Card(s)      | Checks Mission Card completion. (Significant milestone, can gate powerful effects).                                                                        | -1.0 to -2.0                    |
| If [Player] controls a Unit in every friendly Front Row quadrant               | Checks for specific board presence configurations. (Can be difficult to achieve).                                                                            | -1.0                            |
| **C. Player Status** |                                                                                                                                                            |                                 |
| If [Player] was Attacked this Game Round                                     | Checks if player was recipient of an attack declaration. (Reactive condition).                                                                             | -0.5                            |
| If [Player] has Activated X or more Abilities this Game Round                | Checks frequency of ability activations. (Tracks player activity).                                                                                         | -0.25 to -0.75                  |

**IV. Comparison & Counting Conditions**

| Condition Type Description                                                     | Examples of Phrasing / Notes                                                                                                                               | Illustrative DB Cost / Modifier |
| :--------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------ |
| If [Value A] is [Comparison Operator] [Value B]                              | Comparison operators: Equal To, Not Equal To, Greater Than, etc. Values can be stats, CP, card counts. (Generic, cost depends on specifics).                | -0.1 to -0.5                    |
| If the number of [Game Element Type] [Scope] is [Comparison] X                 | E.g., "If number of Exhausted Units you control is 3+." (General counting).                                                                                | -0.25 to -1.0                   |
| If [Criteria A] is true AND/OR/NOT [Criteria B] is true                      | For combining multiple conditional checks. (AND is more restrictive (-DB), OR is less restrictive (+DB if very flexible for valuable modes)).                 | *Varies* |

**V. Cost & Choice-Related Conditions (Often part of ability text allowing player agency)**

| Condition Type Description                                                     | Examples of Phrasing / Notes                                                                                                                               | Illustrative DB Cost / Modifier |
| :--------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------ |
| If [Player] Pays [X CP / Other Resource Cost] as an additional cost            | Effect resolves/enhanced if optional additional cost is paid. E.g., "You may pay 2 CP. If you do..." (This cost *reduces* the base effect's DB).              | *-(DB value of cost paid)* |
| Unless [Player] Pays [X CP / Other Resource Cost]                            | Effect occurs unless cost is paid by specified player. E.g., "Target opponent discards 1 card unless they pay 3 CP." (Punisher, value in forcing choice).     | +0.5 to +1.5                    |
| If [Player] Discards [Number/Type of] Card(s) as an additional cost          | E.g., "You may discard a Technology card. If you do..." (Discarding cards is a significant cost, reduces base effect's DB).                                  | *-(~2.5-3.5 per card discarded)* |
| Unless [Player] Discards [Number/Type of] Card(s)                            | E.g., "This Unit cannot attack unless you discard a card." (This is a drawback, effectively refunds DB to card's budget).                                     | *Varies (negative DB)* |
| If [Player] Chooses [Option A over Option B]                                 | For abilities with modal choices. E.g., "Choose one — If you chose A, then..." (Flexibility adds value to base effect).                                      | +0.5 to +1.5 (based on choices) |
