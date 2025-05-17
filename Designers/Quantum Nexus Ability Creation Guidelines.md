# Quantum Nexus: Ability Creation Guidelines

## Note to the Reader

This is the Quantum Nexus: Ability Creation Guidelines. This document is not meant to explain any rules that a player would need; it is solely intended to aid designers in creating captivating and interesting card abilities and keywords for Quantum Nexus. Players are welcome to read this document, but please know that these guidelines are not applied to any in-game scenarios; they are solely intended for creating cards for Quantum Nexus.

This document is meant to be used in conjunction with the *Quantum Nexus: Detailed Rules*, the *Quantum Nexus: Card Creation Guidelines (CCG v2.0)*, and the *Quantum Nexus: Mission Card Creation Guidelines*. When designing cards, the abilities are created using this document and then applied to the cards being designed.

## I. Introduction

Welcome to the "Quantum Nexus: Ability Creation Guidelines"! This document is your comprehensive guide to understanding, designing, and describing the unique abilities that power the cards in the Quantum Nexus universe. Abilities are the driving force behind much of the game's strategic interaction, from the powerful capabilities of your Units and Assets to the impactful outcomes of Events.

Think of abilities as the special functions, powers, or characteristics that your cards possess. They add layers of strategic depth and tactical decision-making to every game. Whether you're designing a new Unit with unique combat prowess, an Asset that provides ongoing support, an Event that disrupts your opponent's plans, or a new Keyword that defines a common mechanic, understanding how to construct and conceptualize the "cost" of abilities is essential.

A core principle of Quantum Nexus design is balance, achieved through careful design and rigorous refinement. This guide provides a foundational framework for constructing abilities. The actual design budget valuation of these abilities, which influences a card's final Command Point (CP) cost, is determined by the **Progressive Budget Build (PBB)** system using **Design Budget (DB) points**, as detailed in the *Quantum Nexus: Card Creation Guidelines Version 2.0 (CCG v2.0)*. The official, calibrated DB costs for all ability components are maintained in the separate **Master DB Cost List(s)** by the design team. These Master Lists are living documents, updated as the game evolves through playtesting and balance adjustments.

In Quantum Nexus, abilities are carefully crafted combinations of seven core components:

* **Effects:** These are the fundamental actions or outcomes that an ability produces (e.g., inflicting Impact, modifying stats, drawing cards, applying states). They are the "what happens" part of an ability. (Detailed in Section II and Appendix A).
* **Targets:** These define what the effect is applied to (e.g., a specific Unit, a player, a quadrant). (Detailed in Section III and Appendix B).
* **Triggers:** These determine when or how an ability activates (e.g., as a player's action, or automatically when a specific game event occurs). (Detailed in Section IV and Appendix C).
* **Conditions:** These add "if-then" or "unless-then" logic, further defining whether an effect applies, how it's modified, or when it can be activated. (Detailed in Section V and Appendix D).
* **Duration:** This component specifies how long an applied effect persists in the game state. (Detailed in Section VI and Appendix E).
* **Frequency / Limitation:** This component defines how often an Active or Triggered ability can be used or can occur within defined game periods. (Detailed in Section VII and Appendix G).
* **Activation Cost (Gameplay Costs):** This component details any in-game resources (like CP, exhausting the card, discarding cards, etc.) a player must expend to use an ability, primarily for Active abilities. (Detailed in Section VIII and Appendix F).

By mastering these components and understanding how they interact—along with how they are budgeted within the PBB system (Section IX)—you can create abilities that are not only powerful and effective but also balanced and engaging. This guide will delve into each of these components, explore how they combine to form Keywords (Section X) and more complex Synergistic Mechanics (Section XI), and discuss other important design considerations. Our goal is to provide you with the knowledge and tools needed to craft the abilities that will define your Quantum Nexus creations.

## II. Effects

In the realm of Quantum Nexus abilities, **Effects** are the heart of the action. They dictate what happens when an ability is triggered, causing changes to the game state, influencing the Battlefield, and ultimately determining the fate of your cards and your opponent's.

Think of effects as the verbs in the sentences of your abilities. They are the actions that bring your cards to life, transforming them from static entities into dynamic forces that shape the course of the game. The duration for which an effect persists is determined by the **Duration** component (see Section VI and Appendix E), chosen separately.

### Categorizing Effects

Effects in Quantum Nexus are categorized into two main types based on their intended impact on the target:

* **Beneficial Effects:** These effects are intended to have a positive impact on their target. They might enhance, protect, provide resources, or otherwise improve the game state for the target's controller or the target card itself.
* **Detrimental Effects:** These effects are intended to have a negative impact on their target. They might directly attack resilience, weaken, destroy, remove resources, or otherwise hinder the target, creating an advantage for the player activating the ability.

*Important Note:* The categorization of an effect as beneficial or detrimental often depends on the target and context. Designers should primarily consider the intended use case when determining an effect's nature.

### Core Game Effects

The fundamental actions and changes that abilities can impose on the game are catalogued in **Appendix A: Core Game Effects Catalogue**. This catalogue serves as the primary palette for designers. Broadly, these effects can involve:

* Altering Card Attributes & States: Such as modifying Attack or Defense values, applying states like **Suppressed** or **Disordered**, changing a Unit's position, or granting/removing keywords.
* Managing Player Resources: Including gaining or causing the loss of Command Points (CP), drawing or discarding cards, and interacting with Decks or Discard Piles.
* Interacting with Game Flow & Rules: Such as negating other effects, influencing initiative, or directly impacting mission progression.
* Removing Cards or Changing Zones: Effects like destroying cards (sending them to the Discard Pile) or returning cards to a player's hand.

Designers must refer to **Appendix A** for a comprehensive list and specific descriptions of these core effects when constructing abilities. The DB cost of a chosen Effect (from the Master DB Cost List) will represent its base impact, which can then be modified by other components like Duration, Target scope, etc.

#### Examples of Effect Text (Duration would be chosen separately)

The following examples demonstrate how effects (as catalogued in Appendix A) might be worded. The persistence of these effects would be determined by the chosen **Duration** component.

* Applying a stat modification: `"Target friendly Unit gets +2 Defense."`
* Manipulating player resources: `"Draw 2 cards."`
* Applying a state: `"Apply Disordered to target Unit."`
* Destroying a card: `"Destroy target Terrain."`
* Manipulating card position: `"Return target friendly Unit to its owner's hand."`
* Testing resilience directly: `"Inflict Impact 2 on target Unit."`

### Building an Effect Component: Example for "Kinetic Pulse"

As we develop these guidelines, we will build a complete sample ability called "Kinetic Pulse" piece by piece, now using the 7-component structure. Here, we define its core **Effect component**.

**1. Define the Effect Text for "Kinetic Pulse":**
Drawing from Appendix A (specifically, an effect like "Inflict Impact X on Unit"), the primary effect for "Kinetic Pulse" will be:
`"Inflict Impact 1."`

The targets for this impact ("all other Units in this Unit's quadrant") will be defined by the **Target** component (Section III).

**2. Conceptual Breakdown & DB Costing (for this Effect Component Only):**
The Design Budget (DB) cost for this specific effect primitive would be sourced from the official, calibrated **Master DB Cost List(s)**. This list would value the base mechanical change.

* **Core Effect Primitive:**
    * Type: `Inflict Impact on Unit` (from Appendix A)
    * Specifics: Value of Impact = 1.
    * *DB Cost (from Master List, for "Inflict Impact 1" base effect):* For illustration, let's say **`1.0 DB`**.

This `1.0 DB` represents the cost of the raw "Inflict Impact 1" mechanical outcome, before considering who it hits, when it happens, how long any associated states last, how often it can happen, or what it costs to activate.

## III. Targets

In Quantum Nexus, an ability's effect typically acts upon one or more **Targets**. Targets define the specific cards, players, game elements, or even abstract concepts that an ability will influence. Clearly defining the Target(s) is crucial for creating abilities that are precise, strategically interesting, and function as intended within the game rules.

Think of targets as the specific recipients of an ability's action. Precise targeting is key to an ability's function and tactical application. Abilities must clearly specify what they can target (see *Quantum Nexus: Detailed Rules*, Section VII.A on Targeting for general principles).

### Core Game Targets

The fundamental entities, attributes, and zones that abilities can target within Quantum Nexus are catalogued in **Appendix B: Core Game Targets Catalogue**. This catalogue serves as the primary reference for designers. Broadly, these targets can include:

* **Cards:** Specific cards in various game zones (In Play, Hand, Deck, Discard Pile, Mission Card Area), often distinguished by type (Unit, Leader, Asset, etc.) or other properties.
* **Players:** The player controlling the ability (Self), an Opponent, any player, or players meeting certain conditions.
* **Game Elements & Zones:** Physical areas like Quadrants or Loadout Areas, or entire zones like a player's Deck or Discard Pile.
* **Abstract Game Concepts:** Such as a card's stats (Attack, Defense), a player's CP, keywords, or even other abilities (for negation or copying effects).

Designers must refer to **Appendix B** for a comprehensive list and specific descriptions of these core targets when constructing the targeting component of an ability.

**Note on Target Specificity:** Abilities often include conditions that refine targeting (e.g., "target Unit with Attack 3 or less," "target friendly Technology Unit"). These conditions are part of the ability's overall logic (see Section V: Conditions). The choice of Target, including its scope (e.g., single vs. multiple, specific area) and any conditional requirements, will influence its Design Budget (DB) cost, sourced from the Master DB Cost List.

#### Examples of Target Specifications in Abilities

The following examples demonstrate how targets (as catalogued in Appendix B) might be specified.

* `Effect: Inflict Impact 2.` `Target: Target Unit.`
* `Effect: Bolster Defense by 2.` `Target: Target friendly Asset.`
* `Effect: Grant -1 Attack.` `Target: All Units in target Quadrant.`
* `Effect: Draw 1 card.` `Target: You (the activating player).`
* `Effect: Discard 1 card from hand.` `Target: Target opponent.`

By carefully selecting and clearly defining the Target(s) for an ability using the elements catalogued in Appendix B, designers ensure its effects are applied precisely where intended.

### Defining a Target Component: Example for "Kinetic Pulse"

Continuing with "Kinetic Pulse":
* Effect component: `"Inflict Impact 1."` (Illustrative DB: `1.0 DB`)

**1. Identify the Target Component Text for "Kinetic Pulse":**
The effect of "Kinetic Pulse" is intended to hit multiple units in the vicinity of its source. The **Target component** is:
`"All other Units in this Unit's quadrant."`

This target specification combines several elements from Appendix B:
* Base Target: `Unit(s)` (Appendix B, Section I.A).
* Scope/Location: `Quadrant` (specifically "this Unit's quadrant" - relative to source) (Appendix B, Section III.A).
* Quantity: "All" (within the defined scope).
* Exclusion: "other" (implying the source Unit of the ability is not targeted by its own pulse).

**2. DB Costing (for this Target Component Only):**
The DB cost for this specific targeting scheme would be found on the Master DB Cost List. For illustration:

* *DB Cost (from Master List, for "All other Units in this Unit's quadrant"):* Let's say **`1.5 DB`**. This cost would account for the area-of-effect nature, the exclusion of self, and targeting multiple potential units.

**Illustrative Running Total DB for "Kinetic Pulse":**
* Effect (`1.0 DB`) + Target (`1.5 DB`) = **`2.5 DB`** (so far).

## IV. Triggers

In Quantum Nexus, **Triggers** are the catalysts that bring abilities to life. They define the specific conditions, game events, or player choices that must occur for an ability to activate. Think of triggers as the "when" or "how" an ability initiates its effects.

Triggers determine the precise moments abilities can be used or will automatically occur. The comprehensive list of defined trigger events and conditions available for ability design can be found in **Appendix C: Core Game Triggers Catalogue**. The chosen Trigger will have an associated DB cost from the Master DB Cost List, reflecting its reliability, frequency, and whether it consumes a player action. The actual number of times a triggered ability can resolve may be further refined by the **Frequency / Limitation** component (see Section VII and Appendix G).

### Types of Triggers

Conceptually, triggers in Quantum Nexus fall into two broad categories:

* **Active Triggers (Player Action):** These are associated with **Active Abilities**. They signify that a player must make a conscious decision to use the ability, typically by choosing it as one oftheir single actions during their turn in the Activation Sequence (see *Quantum Nexus: Detailed Rules*, Section III.C.2). This activation often involves paying specified gameplay costs (see Section VIII: Activation Costs). The fundamental trigger is `"As a Player Action (Activate this Ability)"` (Appendix C, Section I).
* **Event-Driven Triggers (Automatic/Conditional):** These triggers cause an ability to activate automatically whenever a specific game event occurs or a particular condition in the game state is met, without requiring the player to use one of their single actions. Examples include an ability triggering `"When this Unit is destroyed"` or `"At the Start of the Game Round."` The resolution of these triggered abilities follows the rules detailed in *Quantum Nexus: Detailed Rules*, Section VII.A. (See Appendix C, Section II).

### Understanding and Using Triggers from Appendix C

When designing an ability, you will select an appropriate trigger from Appendix C.

* **For Active Abilities:** The trigger will be `"As a Player Action (Activate this Ability)."`.
    * *Example Card Text Snippet (Active Ability):* `**Action:** Pay 2 CP and Exhaust this Unit to...` (Here, "Action:" signifies the "As a Player Action" trigger).

* **For Event-Driven Abilities:** The trigger will be a specific game event.
    * *Example Card Text Snippet (Event-Driven Trigger):* `**When** this Unit is deployed, you may draw 1 card.` (Draws from "When [This/Target/Any] Card is Deployed" in Appendix C, Section II.B).

### Key Considerations for Trigger Design

* **Timing and Relevance:** Does the trigger align with the ability's intended purpose and the strategic window for impact? Consider the Game Round structure (*Quantum Nexus: Detailed Rules*, Section III.C).
* **Clarity and Precision:** The trigger condition must be phrased clearly and unambiguously using established game terminology.
* **Interaction and Counterplay:** Consider how the trigger interacts with other game elements and opportunities for response (*Quantum Nexus: Detailed Rules*, Section VII.A).

By carefully selecting triggers from Appendix C, you can create abilities that are dynamic, interactive, and strategically engaging.

### Defining a Trigger Component: Example for "Kinetic Pulse"

Continuing with "Kinetic Pulse":
* Effect component: `"Inflict Impact 1."` (Illustrative DB: `1.0 DB`)
* Target component: `"All other Units in this Unit's quadrant."` (Illustrative DB: `1.5 DB`)
* Illustrative Running Total DB: `2.5 DB`.

For "Kinetic Pulse," we will design it as an Active Ability.

**1. Identify the Trigger Component for "Kinetic Pulse":**
The trigger is:
`"As a Player Action (Activate this Ability)"`
This is drawn from **Appendix C: Core Game Triggers Catalogue, Section I.**

**2. DB Costing (for this Trigger Component Only):**
The DB cost for this trigger type would be found on the Master DB Cost List.

* **Core Trigger Primitive:**
    * Type: `As a Player Action (Activate this Ability)` (from Appendix C, Section I).
    * *DB Cost (from Master List, for this trigger type):* For illustration, let's say **`1.0 DB`**. This reflects the opportunity cost of using a player's action.

**Illustrative Running Total DB for "Kinetic Pulse":**
* Effect (`1.0 DB`) + Target (`1.5 DB`) + Trigger (`1.0 DB`) = **`3.5 DB`** (so far).

## V. Conditions

In Quantum Nexus, **Conditions** add a layer of complexity and strategic depth to abilities. Conditions are criteria or checks against the current game state, card attributes, or player choices that determine whether an ability (or part of its effect) can activate, how it resolves, or if its costs are modified. They introduce "if-then" or "unless-then" logic.

Conditions act as filters or modifiers. The types of checks that can form a condition are catalogued in **Appendix D: Core Game Condition Types Catalogue**. Each Condition or combination of conditions will have a DB cost impact (often a modifier to the ability's gross DB cost) sourced from the Master DB Cost List.

### Conditional Phrasing & Logic

Abilities use conditional phrases to incorporate checks. Common structures include:

* **If [Condition is True], then [Effect Occurs / Modification Applies]:** The effect only happens if the condition (from Appendix D) is met.
    * *Example:* `"If this Unit is in a Front Row quadrant, its Attack is +1."`
* **Unless [Condition is True], then [Effect Occurs / Modification Applies]:** The effect happens *unless* the condition is met.
    * *Example:* `"Target opponent discards 1 card, unless their CP is 0."`

**Distinction from Triggers:**
Triggers (Appendix C) define *when an ability activates*. Conditions (Appendix D) are checks made *at trigger, activation, or resolution* to determine if or how an ability proceeds.

**Timing of Conditional Checks:**
Unless specified otherwise, conditions are checked:
* For Active Abilities: When declared as an action and when it begins to resolve.
* For Event-Driven (Triggered) Abilities: When the trigger event occurs and when the ability begins to resolve.

### Boolean Operators for Complex Conditions

Conditions can be combined using standard Boolean operators (AND, OR, NOT, XOR) drawing from Appendix D. The use of these operators will influence the DB cost modification from the Master DB Cost List.

### Examples of Conditions in Abilities

* Using a Card State Condition (Appendix D, Section II.C): `"If this Unit is Suppressed, it cannot be chosen as a target for opponent's Event cards."`
* Using a Player Resource Condition (Appendix D, Section III.A): `"If your CP is 3 or less, this ability's effect is doubled."`

Designers should strive for clarity when phrasing conditions.

### Defining a Condition Component: Example for "Kinetic Pulse"

Continuing with "Kinetic Pulse":
* Effect: `"Inflict Impact 1."` (Illustrative DB: `1.0 DB`)
* Target: `"All other Units in this Unit's quadrant."` (Illustrative DB: `1.5 DB`)
* Trigger: `"As a Player Action (Activate this Ability)"` (Illustrative DB: `1.0 DB`)
* Illustrative Running Total DB: `3.5 DB`.

Let's add a positional condition:

**1. Define the Condition Text for "Kinetic Pulse":**
`"If this Unit is in a friendly Front Row quadrant"`
This condition type is found in **Appendix D: Core Game Condition Types Catalogue, Section II.D** (Card Location).

**2. DB Costing (for this Condition Component Only):**
Conditions often act as modifiers. A restrictive condition like this might slightly reduce an ability's overall DB cost or justify its power level for a given DB. The Master DB Cost List would provide the specific modifier.

* **Core Condition Type:**
    * Type: `Card Location Check` (Unit's position) (from Appendix D, Section II.D).
    * Specificity: Requires being in one of three specific friendly quadrants (a moderate restriction).
    * *DB Cost Modifier (from Master List, for this condition):* For illustration, **`-0.5 DB`**. (This negative value suggests the condition restricts the ability, potentially making the overall ability slightly "cheaper" in DB).

**Illustrative Running Total DB for "Kinetic Pulse":**
* Effect (`1.0 DB`) + Target (`1.5 DB`) + Trigger (`1.0 DB`) + Condition (`-0.5 DB`) = **`3.0 DB`** (so far).

## VI. Durations

A critical aspect of any ability is its **Duration** – how long its effects persist in the game. Making Duration an explicit component allows for precise control over an ability's impact over time and is key to balancing one-shot effects against those that provide ongoing or long-term value.

The choice of Duration significantly influences an ability's strategic implications and its Design Budget (DB) cost. An effect that lasts for the entire game or as long as a card is in play is inherently more powerful (and thus more DB-expensive) than an effect that lasts only for a single combat or turn.

All standard Durations are catalogued in **Appendix E: Core Game Durations Catalogue**. Each listed Duration will have an associated DB cost or multiplier on the Master DB Cost List, which is applied to the ability's overall DB calculation.

### Types of Durations (Examples from Appendix E)

* **Instantaneous / Resolves Immediately:** For effects that apply and conclude immediately (e.g., "Gain X CP," "Destroy target Unit"). Often carries no additional DB cost beyond the effect itself.
* **This Combat Only:** For effects limited to the current combat. Low additional DB cost.
* **This Game Round:** For effects lasting until the end of the current Game Round. Moderate additional DB cost.
* **Until Your Next Start of Round Step:** Persists through opponent turns for one full cycle. High additional DB cost.
* **Ongoing While [Source Card] is in Play:** Key for Passive abilities and auras. Very high additional DB cost or multiplier.
* **Permanent:** For lasting changes like counters or transformations. Extremely high additional DB cost.

The choice of Duration is fundamental to defining an ability as Active (often shorter durations), Triggered (variable durations), or Passive (typically "Ongoing" durations).

### Defining a Duration Component: Example for "Kinetic Pulse"

Continuing with "Kinetic Pulse":
* Effect: `"Inflict Impact 1."` (Illustrative DB: `1.0 DB`)
* Target: `"All other Units in this Unit's quadrant."` (Illustrative DB: `1.5 DB`)
* Trigger: `"As a Player Action (Activate this Ability)"` (Illustrative DB: `1.0 DB`)
* Condition: `"If this Unit is in a friendly Front Row quadrant"` (Illustrative DB Mod: `-0.5 DB`)
* Illustrative Running Total DB: `3.0 DB`.

The "Inflict Impact" effect is generally instantaneous. If it applied a lingering state (e.g., "-1 Defense"), that state would have its own duration. For "Kinetic Pulse," the primary effect resolves immediately.

**1. Define the Duration Component for "Kinetic Pulse":**
The main effect ("Inflict Impact 1") is instantaneous.
`"Instantaneous / Resolves Immediately"`
This is drawn from **Appendix E: Core Game Durations Catalogue.**

**2. DB Costing (for this Duration Component Only):**
* **Duration Type:** `Instantaneous / Resolves Immediately`
    * *DB Cost (from Master List, for this duration):* For illustration, **`+0 DB`** (as it's often baseline for direct effects).

**Illustrative Running Total DB for "Kinetic Pulse":**
* Effect (`1.0 DB`) + Target (`1.5 DB`) + Trigger (`1.0 DB`) + Condition (`-0.5 DB`) + Duration (`0 DB`) = **`3.0 DB`** (so far).

## VII. Frequency / Limitation

The **Frequency / Limitation** component is crucial for balancing abilities, especially those that are Triggered or could be Activated multiple times. It defines how often a specific ability can be successfully used or resolved within certain game periods (e.g., per turn, per round, per game).

Without appropriate limitations, potent effects tied to common triggers or low-cost active abilities could dominate gameplay. Applying a Frequency/Limitation component allows designers to permit powerful effects on cards by controlling their rate of occurrence.

All standard Frequency/Limitation options are catalogued in **Appendix G: Core Game Frequency / Limitation Catalogue**. Each listed option will have an associated DB cost modifier on the Master DB Cost List (typically a negative modifier, reducing the ability's gross DB cost, or a multiplier).

### Types of Frequency / Limitations (Examples from Appendix G)

* **Unlimited (for the given Trigger):** The ability can occur every time its trigger is met. Default for many triggers; DB cost is inherent in trigger's own DB value + effect.
* **Once Per Game (Total):** A very restrictive limiter, significantly reducing DB cost.
* **Once Per Game Round (per card instance):** Common for balancing strong repeatable effects on persistent cards.
* **Once During Your Turn (per card instance):** Limits to player's own activations.
* **Only X Times Per Game/Round:** Allows a specific number of uses.

### Defining a Frequency / Limitation Component: Example for "Kinetic Pulse"

Continuing with "Kinetic Pulse":
* Effect: `"Inflict Impact 1."` (Illustrative DB: `1.0 DB`)
* Target: `"All other Units in this Unit's quadrant."` (Illustrative DB: `1.5 DB`)
* Trigger: `"As a Player Action (Activate this Ability)"` (Illustrative DB: `1.0 DB`)
* Condition: `"If this Unit is in a friendly Front Row quadrant"` (Illustrative DB Mod: `-0.5 DB`)
* Duration: `"Instantaneous"` (Illustrative DB: `0 DB`)
* Illustrative Running Total DB: `3.0 DB`.

"Kinetic Pulse" is an Active ability. Unless otherwise specified, Active abilities on persistent cards can generally be used once per turn if their costs (like exhausting) are met and they can ready on subsequent turns. If we want to ensure it's not overly spammable or define its intended use pattern more clearly:

**1. Define the Frequency / Limitation Component for "Kinetic Pulse":**
Let's assume the base "As a Player Action" trigger implies it can be done if the card is ready and costs can be paid. If the card Exhausts as part of its Activation Cost (see next section), that naturally limits it to once per readying. If we want to be more explicit or if Exhaust is not part of its cost:
`"Once During Your Turn (per card instance)"` (If it didn't exhaust) OR `"Unlimited (for the given Trigger)"` (if exhausting is its natural limiter).
For an Active ability that exhausts, "Unlimited (for the given Trigger)" is appropriate, as the exhaustion *is* the main frequency limiter per readying cycle. Let's assume "Kinetic Pulse" will have an Exhaust cost.

**Frequency / Limitation:** `"Unlimited (for the given Trigger)"` (its gameplay activation cost will limit it).
This is drawn from **Appendix G: Core Game Frequency / Limitation Catalogue.**

**2. DB Costing (for this Frequency / Limitation Component Only):**
* **Type:** `Unlimited (for given Trigger)`
    * *DB Cost Modifier (from Master List):* For illustration, **`+0 DB Modifier`** (the trigger cost itself and activation costs handle the balance here).

**Illustrative Running Total DB for "Kinetic Pulse":**
* Effect (`1.0`) + Target (`1.5`) + Trigger (`1.0`) + Condition (`-0.5`) + Duration (`0`) + Frequency (`0`) = **`3.0 DB`** (so far).

## VIII. Activation Costs (Gameplay Costs)

The **Activation Cost (Gameplay Costs)** component details any in-game resources a player must expend to use an ability, primarily for **Active Abilities** (those using an "As a Player Action" Trigger) but sometimes for optional Triggered abilities (e.g., "When X happens, you may pay Y to do Z").

These in-game costs are crucial for balancing. An ability that is "free" to activate is inherently more valuable than one requiring significant CP, card discards, or other sacrifices. The PBB system accounts for this by having Activation Costs provide a **negative DB modifier (a "rebate")** to the ability's gross design DB cost. The more a player pays in-game to use an ability, the more "DB budget" is effectively refunded, allowing the ability's core effects to be more powerful for a given net DB contribution to the card's PBB total.

All standard Activation Cost options are catalogued in **Appendix F: Core Game Activation Costs Catalogue**. Each will have a specific negative DB modifier on the Master DB Cost List.

### Types of Activation Costs (Examples from Appendix F)

* **No Additional Cost:** For passives or triggers that resolve automatically. DB Modifier: `-0 DB`.
* **Pay X Command Points (CP):** Significant DB rebate, scaling with X.
* **Exhaust This Card:** Moderate DB rebate.
* **Discard X Card(s) from Your Hand:** Significant DB rebate.
* **Destroy/Sacrifice a Friendly Card:** Very significant DB rebate.

### Defining an Activation Cost Component: Example for "Kinetic Pulse"

Completing "Kinetic Pulse":
* Effect: `"Inflict Impact 1."` (Illustrative DB: `1.0 DB`)
* Target: `"All other Units in this Unit's quadrant."` (Illustrative DB: `1.5 DB`)
* Trigger: `"As a Player Action (Activate this Ability)"` (Illustrative DB: `1.0 DB`)
* Condition: `"If this Unit is in a friendly Front Row quadrant"` (Illustrative DB Mod: `-0.5 DB`)
* Duration: `"Instantaneous"` (Illustrative DB: `0 DB`)
* Frequency: `"Unlimited (for given Trigger)"` (Illustrative DB Mod: `0 DB`)
* Illustrative Gross DB before Activation Cost: `3.0 DB`.

**1. Define the Activation Cost Component for "Kinetic Pulse":**
Let's give it a moderate cost befitting its area effect.
`"Pay 1 CP and Exhaust This Unit"`
This combines two cost types from **Appendix F: Core Game Activation Costs Catalogue.**

**2. DB Costing (for this Activation Cost Component Only):**
* **Cost Type 1:** `Pay 1 Command Point (CP)`
    * *DB Cost Modifier (from Master List):* For illustration, **`-4.0 DB`**.
* **Cost Type 2:** `Exhaust This Card`
    * *DB Cost Modifier (from Master List):* For illustration, **`-2.0 DB`**.
* **Total DB Modifier from Activation Costs:** `-4.0 DB + -2.0 DB = -6.0 DB`.

**Final Illustrative Net DB Cost for "Kinetic Pulse" ability:**
* Gross DB: `3.0 DB`
* Activation Cost DB Modifier: `-6.0 DB`
* **Net DB Cost for PBB:** `3.0 DB - 6.0 DB = -3.0 DB`.

A negative DB cost means this ability actually *contributes* budget back to the card it's on, allowing for better stats or other abilities for its final CP cost. This makes sense, as the ability is quite costly for the player to use in-game (an action, 1 CP, and exhausting a Unit) for a relatively modest "Impact 1" effect, even if AoE and conditional. If the effect was stronger (e.g., Impact 3), its gross DB would be higher, and the -6.0 DB rebate would still apply, resulting in a higher positive net DB.

This detailed 7-component structure, once all placeholder DBs are replaced with calibrated Master DB Cost List values, provides a highly granular and transparent way to design and budget abilities.

## IX. Ability Design Budgeting and Card Creation (Revised)

In Quantum Nexus, the creation of playable cards is governed by the **Progressive Budget Build (PBB) system**, detailed in the *Quantum Nexus: Card Creation Guidelines Version 2.0 (CCG v2.0, Section V.B)*. This section outlines how abilities, now constructed from seven core components, are budgeted within that system.

Abilities define how cards interact and influence strategy. Their design "cost" in **Design Budget (DB) points** is a critical factor.

**Key Principles (Aligning with CCG v2.0 and 7-Component Abilities):**

* **Abilities as Budgeted Features:** All abilities and keywords on a card consume a portion of its **Total Design Budget (TDB)**, which is derived from its Domain Points (DP), role (Leader), and rarity (CCG v2.0).
* **DB System for Costing:** The PBB system uses DB points. More powerful, complex, persistent, frequent, or "free-to-activate" abilities will have a higher net DB cost.
* **Contribution to Final Card CP Cost:** The sum of DB spent on a card's stats *and* the net DB cost of all its abilities/keywords (`Total_Actual_DB_Spent`) is converted into the card's final playable CP cost.
* **Master DB Cost List(s):** Specific DB costs and modifiers for every element within the seven components (Effects, Targets, Triggers, Conditions, Durations, Frequency/Limiters, Activation Costs) are officially defined and maintained by the design team in one or more **Master DB Cost List(s)**. These require ongoing calibration through playtesting.
* **Synergy and Balance:** The ultimate balance is assessed through DB costs (from Master Lists) and confirmed via playtesting.

### Determining an Ability's Net Design Budget (DB) Cost

The net DB cost of an ability designed using the 7-component framework is determined by:
1.  Summing the base DB costs of its chosen **Effect(s)** (App A) and **Target(s)** (App B).
2.  Adding the DB cost of its **Trigger** (App C).
3.  Applying any DB modifier from its **Condition(s)** (App D).
4.  Adding the DB cost (or applying a multiplier) for its chosen **Duration** (App E).
5.  Applying any DB modifier from its **Frequency / Limitation** (App G).
6.  Applying the (typically negative) DB modifier from its chosen **Activation Cost (Gameplay Costs)** (App F).

**Net Ability DB = DB<sub>Effect</sub> + DB<sub>Target</sub> + DB<sub>Trigger</sub> + Mod<sub>Condition</sub> + DB<sub>Duration</sub> + Mod<sub>Frequency</sub> + Mod<sub>ActivationCost</sub>**

### Example: Determining the Net DB Cost for "Kinetic Pulse" (Revised)

Let's use our finalized "Kinetic Pulse" ability.

**Full Conceptual Text for "Kinetic Pulse":**
"As a Player Action: Pay 1 CP and Exhaust this Unit. If this Unit is in a friendly Front Row quadrant, inflict Impact 1 on all other Units in this Unit's quadrant. This effect is Instantaneous and has no special Frequency Limiter beyond its Activation Cost."

**Component Breakdown & Illustrative DB Costs/Modifiers:**
(Sourced from our conceptual Master DB Cost Lists for each Appendix A-G)

1.  **Effect (App A):** `"Inflict Impact 1."`
    * *Illustrative DB:* `1.0 DB`
2.  **Target (App B):** `"All other Units in this Unit's quadrant."`
    * *Illustrative DB:* `1.5 DB`
3.  **Trigger (App C):** `"As a Player Action (Activate this Ability)"`
    * *Illustrative DB:* `1.0 DB`
4.  **Condition (App D):** `"If this Unit is in a friendly Front Row quadrant"`
    * *Illustrative DB Modifier:* `-0.5 DB`
5.  **Duration (New App E):** `"Instantaneous / Resolves Immediately"`
    * *Illustrative DB Cost/Modifier:* `+0 DB`
6.  **Frequency / Limitation (New App G):** `"Unlimited (for given Trigger)"` (Natural limit from Exhaust in Activation Cost)
    * *Illustrative DB Modifier:* `+0 DB`
7.  **Activation Cost (Gameplay Costs) (New App F):** `"Pay 1 CP and Exhaust This Unit"`
    * Cost "Pay 1 CP": Illustrative Modifier `-4.0 DB`
    * Cost "Exhaust This Unit": Illustrative Modifier `-2.0 DB`
    * *Total Activation Cost Modifier:* `-6.0 DB`

**Illustrative Net Design Budget (DB) Cost for the "Kinetic Pulse" ability:**
`1.0 (Effect) + 1.5 (Target) + 1.0 (Trigger) - 0.5 (Condition) + 0 (Duration) + 0 (Frequency) - 6.0 (Activation Cost) = -3.0 DB`

**Integration into Card's Progressive Budget Build:**
This net `-3.0 DB` for the "Kinetic Pulse" ability would be part of the `DB_Spent_On_Abilities` for the Unit card it's on. If this is the only ability, then `DB_Spent_On_Abilities = -3.0 DB`.
This would be added to the `DB_Spent_On_Stats`. For example, if the Unit had A2/D2 (costing `2*3 (A) + 2*3 (D) = 12 DB` with current stat costs):
`Total_Actual_DB_Spent = 12 DB (Stats) - 3.0 DB (Ability) = 9.0 DB`.
This `9.0 DB` must be within the card's TDB. Its final CP would be `9.0 DB / 5 = 1.8 CP` -> `2 CP`.

This demonstrates that abilities with significant gameplay activation costs can effectively "refund" DB to the card's budget, allowing for better stats or ensuring the card remains cheap despite having a complex mechanical ability. Conversely, Passive abilities with "Ongoing" Durations, no Activation Costs, and Unlimited Frequency would have very high positive net DB costs.

## X. Keywords

Keywords in Quantum Nexus are standardized terms representing specific, predefined abilities or characteristics. They streamline card text and ensure consistent application of common mechanics. Attaching a keyword to a card grants it the associated abilities or modifies its function in a known way. Official keywords are listed in the *Quantum Nexus: Detailed Rules* glossary or on cards if unique.

### Keywords and the Design Budget (DB) System (Revised for 7 Components)

A keyword is a pre-packaged ability or set of rules. Each keyword has an associated **Net Design Budget (DB) cost** on the **Master DB Cost List(s)**. This DB cost is pre-calculated based on the keyword's underlying Effects, Targets, Triggers, Conditions, Durations, Frequency/Limiters, and Activation Costs (if any).

When a card is designed with a keyword:
* The keyword's defined net DB cost (from the Master List) is added to that card's `DB_Spent_On_Abilities`.
* This contributes to the card's `Total_Actual_DB_Spent` in the PBB system.

**DB Cost of Keywords:**
* **Positive Keywords** (granting advantages): Will have a positive net DB cost.
* **Negative Keywords** (imposing drawbacks): May have a negative net DB cost (refunding TDB) or a low positive cost.
* **Neutral Keywords** (defining modes of operation): Will have a DB cost reflecting their mechanical impact/complexity.

### Example: "Steadfast" Keyword (Revised Conceptual Costing)
1.  **Mechanic:** `*Steadfast* - This Unit cannot be Pushed Back.`
2.  **Implicit Components:**
    * Effect: Unit is immune to "Pushed Back" mechanic.
    * Target: Self (This Unit).
    * Trigger: Implicit (Passive - always active while card has keyword).
    * Condition: None.
    * Duration: Ongoing while card has keyword / is in play.
    * Frequency/Limitation: N/A (Passive).
    * Activation Cost: None.
3.  **Net DB Cost (from Master List):** The design team analyzes the impact of continuously being immune to "Pushed Back."
    * *Illustrative Net DB for "Steadfast" keyword:* `1.5 DB` (This value represents the total budgeted cost for this passive benefit).

## XI. Designing Synergistic Mechanics and Interconnected Abilities (Revised)

Strategic depth in Quantum Nexus often emerges from **synergistic mechanics** – abilities, keywords, and rules designed for potent interaction. This involves thinking beyond individual cards to how they combine.

When designing such systems, each individual ability or keyword contributing to the synergy is still broken down and budgeted using the 7-component framework. The PBB system, through the sum of these DB costs, accounts for the card's contribution to potential synergies.

### Example System: The "Invoke/Chant/Ritual" Mechanic (Revised for 7 Components)

**Overall Concept:** Powerful "Invoke" Units require a "Ritual" fulfilled by "Chanting" Units.

**Part 1: The "Invoke" Keyword (on powerful Units)**
* **Mechanic:** Cannot be deployed normally via "Deploy a Card" action. Deployed from hand when its specified `Ritual` (detailed in its ability text) is met. Deployment via `Invoke` doesn't inherently cost CP unless specified.
* **Implicit Components to determine its Net DB cost on Master List:**
    * Effect (Restriction): "Cannot be deployed normally."
    * Effect (Alternate Deployment Method): "May be deployed if Ritual met."
    * Duration (of restriction/alternate method): Ongoing while in hand/deck.
    * Activation Cost (for Invoke): Often none, beyond meeting the Ritual. The Ritual *is* the cost.
    * *Illustrative Net DB for `Invoke` keyword (base restriction, highly dependent on assumed Ritual difficulty):* Significant Negative DB Modifier (e.g., `-5.0 DB` to `-10.0 DB`), allowing the Invoked Unit a much larger TDB for its stats/other abilities.

**Part 2: The "Perform Chant" Active Ability (for supporting Units)**
* **Conceptual Text:** "As a Player Action: Exhaust this Unit. This Unit becomes 'Chanting' until your next Start of Round Step."
* **7-Component Breakdown & Illustrative Net DB (`2.0 DB`):**
    1.  Effect: Apply "Chanting" state. (Base DB for applying a simple, defined state: `1.5 DB`)
    2.  Target: This Unit (Self). (`+0 DB`)
    3.  Trigger: As a Player Action. (`+1.0 DB`)
    4.  Condition: None. (`+0 DB`)
    5.  Duration: "Until your next Start of Round Step." (For a simple marker state, this duration might add `+1.5 DB`)
    6.  Frequency/Limitation: Unlimited (natural limit from Exhaust). (`+0 DB`)
    7.  Activation Cost: Exhaust this Unit. (`-2.0 DB` rebate)
    * Net: `1.5 + 1.0 + 1.5 - 2.0 = 2.0 DB`.

**Part 3: The "Ritual" (Condition on the `Invoke` Unit)**
* **Example Text:** "`Ritual:` If you control 3 or more friendly Units that are currently 'Chanting'."
* This is a **Condition** component (Appendix D) for the `Invoke` keyword's alternate deployment effect. Its complexity influences the DB rebate given by the `Invoke` keyword. A harder Ritual justifies a larger rebate.

**Balancing & DB Costing:** The PBB system, using the 7-component breakdown for each part (`Invoke` keyword, `Perform Chant` ability), allows such interconnected mechanics to be designed and budgeted in a structured manner, with the Master DB Cost Lists providing the calibrated values.

## XII. Mission Challenges (Guidance Note)

The design of Mission Cards – including their **Mission Challenges**, inherent abilities, passive effects, and the determination of their CP values – are detailed in the separate, official **"Quantum Nexus: Mission Card Design Document."**

This "Ability Creation Guidelines" document primarily focuses on abilities for cards in a player's main deck (Units, Assets, Events, Upgrades, Terrain). Mission Challenges have unique roles and balancing considerations addressed in their specific guide.

## XIII. Additional Considerations (Revised)

When crafting abilities using the 7-component framework, keep these factors in mind:

* **Game Round Structure and Ability Timing:**
    * The choice of **Trigger**, **Duration**, **Frequency/Limitation**, and **Activation Cost** profoundly interacts with the Start of Round Step and the alternating Activation Sequence detailed in the *Quantum Nexus: Detailed Rules* (Section III.C).
    * Consider how these components make an ability impactful at strategically important moments.
* **Card Interactions and Synergies:**
    * Think about how an ability's full 7-component definition might create interesting combos or counterplay. The goal is strategic depth and rewarding deck construction (*CCG v2.0*, Section X).
* **Playtesting and Balance (Master List Calibration):**
    * The true test is playtesting. The DB costs for all seven components on the Master DB Cost List(s) must be rigorously calibrated based on observed in-game impact to ensure overall game balance.
* **Thematic Integration:**
    * All seven components should contribute to a cohesive thematic feel, aligning with the card's concept, name, art, and domain.

## XIV. Appendices for Ability Creation

This section will detail the catalogues of core game components used to construct card abilities. Each appendix (A through G) lists elements for one of the seven core components of an ability. Designers will use these catalogues in conjunction with the **Master DB Cost List(s)**, which provide the official Design Budget (DB) point valuations for each element.

---
## Appendix A: Core Game Effects Catalogue
*(Formerly Appendix E in original ACG draft)*

**Introduction:**
This catalogue provides a comprehensive list of core game effects available for ability design in Quantum Nexus. These effects are derived from the game's foundational rules and mechanics. Designers should use this list as a palette when constructing card abilities. The chosen **Duration** (Appendix E), **Target** (Appendix B), **Trigger** (Appendix C), **Conditions** (Appendix D), **Frequency/Limitation** (Appendix G), and **Activation Cost** (Appendix F) will further define the ability's final DB cost and function. The DB costs listed here are for the *base effect primitive* and assume a default, often instantaneous or very short, duration unless specified.

**I. Effects Primarily Affecting Cards in Play (Units, Assets, Terrain, Upgrades)**

| Effect Description                                     | Notes                                                                                                                                                              | Illustrative Base DB Cost |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| **A. Stat & Attribute Modification** |                                                                                                                                                                    |                           |
| Set Attack to X                                        | Sets a Unit's Attack value to X. Base effect; actual duration from App E. *Assumes X is the final value.* | `X * 0.5`                 |
| Modify Attack by +/- X                                 | Increases or decreases a Unit's Attack value by X. Base effect; actual duration from App E.                                                                        | `X * 0.75`                |
| Set Defense to X                                       | Sets a Unit's or Asset's Defense value to X. Base effect; actual duration from App E. *Assumes X is the final value.* | `X * 0.4`                 |
| Modify Defense by +/- X                                | Increases or decreases a Unit's or Asset's Defense value by X. Base effect; actual duration from App E.                                                             | `X * 0.6`                 |
| Grant Attack Range [Close/Mid/Far]                     | Unit gains the specified attack range. Base effect; actual duration from App E. (Cost depends on range value, e.g., Close: 2.0, Mid: 4.0, Far: 6.0 if primary range) | `2.0 - 6.0`               |
| Remove Target Unit's Attack Range                      | Unit loses a specific attack range profile it has. Base effect; actual duration from App E. (Significant if removing only range).                                    | `2.0`                     |
| **B. Applying States & Conditions** | (The applied state itself may have an inherent duration, or an explicit Duration from App E is chosen)                                                              |                           |
| Exhaust Target Card (Unit, Asset, Terrain)             | Target Card becomes Exhausted.                                                                                                                                     | `2.5` (for Unit)          |
|                                                        |                                                                                                                                                                    | `1.5` (for Asset/Terrain) |
| Ready Target Card (Deactivate)                         | Changes an exhausted card to ready.                                                                                                                                | `3.5`                     |
| Apply Suppressed to Target Unit                        | Target Unit becomes Suppressed (and thus Exhausted).                                                                                                               | `2.5`                     |
| Apply Disordered to Target Unit                        | Target Unit becomes Disordered (-1D until its controller's next Start of Round Step).                                                                              | `1.0`                     |
| Apply [Custom Defined State Name] to Target Card       | Applies a specifically defined state (whose rules & duration are detailed elsewhere or by choice from App E). DB for application only.                             | `1.0`                     |
| Remove [State Name: Suppressed/Disordered/Custom] from Target Card | Removes a specified state.                                                                                                                               | `1.0 - 2.5` (Dep. on state) |
| **C. Movement & Positioning (Units, Terrain)** |                                                                                                                                                                    |                           |
| Move Target Unit X friendly cardinal quadrant(s)       | Unit moves. Specify if it Exhausts (normal) or not (more DB costly). X=1, no exhaust: `2.0`. X=1, exhausts: `0.5`.                                                | `0.5 - 2.0`               |
| Pushed Back Target Unit                                | Controller moves the Unit one friendly cardinal quadrant (as per Rulebook).                                                                                        | `1.5`                     |
| Swap Position of Two Target Friendly Units             | Exchanges the quadrants of two specified friendly Units. Specify if they exhaust.                                                                                  | `1.5` (if they exhaust)   |
| Deploy a [Card Type] card from hand into valid zone    | Effect allows deployment. *Assumes CP cost of card is paid separately unless specified.* | `1.0`                     |
| **D. Modifying Abilities & Keywords** |                                                                                                                                                                    |                           |
| Grant Keyword [Keyword Name] to Target Card            | Target card gains a specified keyword. Base effect; actual duration from App E. (Cost depends on Keyword's own DB value + this application fee).                     | `Keyword DB + 0.5`        |
| Remove Keyword [Keyword Name] from Target Card         | Target card loses a specified keyword. Base effect; actual duration from App E.                                                                                    | `Avg. Keyword DB * 0.75`  |
| Target Card Gains [Ability Text]                       | Target card gains a specified rules text ability. Base effect; actual duration from App E. (DB for application; granted ability's own conceptual DB adds more).       | `1.5`                     |
| Target Card Loses [Specific Ability Text / All Abilities] | Target card loses ability/abilities. Base effect; actual duration from App E. "All Abilities" is very high DB.                                                    | `2.0` (specific) / `6.5` (all) |
| **E. Transformation & Type Change** | (These effects are typically "Permanent" or "Ongoing" via Duration choice from App E)                                                                              |                           |
| Target Unit becomes a Leader                           | Changes Unit's subtype to Leader (respecting limits).                                                                                                              | `5.0`                     |
| Target Card's Subtype becomes/is also [New Subtype]    | Changes/adds a subtype.                                                                                                                                            | `0.5 - 2.0`               |
| **F. Attachment (Upgrades)** |                                                                                                                                                                    |                           |
| Attach an Upgrade card from hand to valid target       | Effect allows attachment. *Assumes CP cost of Upgrade is paid separately unless specified.* | `0.75`                    |
| Detach Target Upgrade                                  | Removes an Upgrade (it goes to Discard Pile).                                                                                                                      | `1.0` (opponent's)        |
|                                                        |                                                                                                                                                                    | `0.25` (friendly)         |
| Transfer Target Upgrade to another valid target        | Moves an attached Upgrade.                                                                                                                                         | `0.75`                    |
| **G. Destruction & Removal from Play** |                                                                                                                                                                    |                           |
| Inflict Impact X on Unit                               | Compare X to target Unit's Defense. If X > D, destroy. If X = D, Suppress. If X < D, no effect.                                                                   | `(X * 1.0) + 0.5`         |
| Destroy Target [Card Type: Unit/Asset/Terrain/Upgrade] | Target is moved to its owner's Discard Pile. Unit: `4.0`, Asset: `3.0`, Terrain: `2.0`, Upgrade: `1.0`.                                                            | `1.0 - 4.0`               |
| Return Target Card from Play to Owner's Hand           | "Bounce" effect. Specify card type for base. Unit: `2.5`, Asset: `2.0`, Terrain/Upgrade: `1.5`.                                                                   | `1.5 - 2.5`               |
| Place Target Card from Play on Top/Bottom of Owner's Deck | (Top is stronger than bottom). Specify card type.                                                                                                                  | `1.0 - 2.5`               |
| Shuffle Target Card from Play into Owner's Deck        |                                                                                                                                                                    | `1.0`                     |

**II. Effects Primarily Affecting Player Resources & Zones (Hand, Deck, Discard Pile, CP)**

| Effect Description                                     | Notes                                                                                                                                                              | Illustrative Base DB Cost |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| **A. Command Points (CP)** |                                                                                                                                                                    |                           |
| Gain X CP                                              | Player gains X CP for the current Game Round. (This is for a single instance of gain).                                                                             | `X * 4.5`                 |
| Target Player Loses X CP                               | Target player loses X CP from their current CP pool.                                                                                                               | `X * 5.0`                 |
| Modify CP Cost of [Card Play/Ability Activation Criteria] by +/- X | For next instance or specified duration (from App E). (Cost reduction is positive DB).                                                                     | `X * 3.5` (for player)    |
|                                                        |                                                                                                                                                                    | `X * 4.0` (for opponent)  |
| **B. Card Draw & Hand Manipulation** |                                                                                                                                                                    |                           |
| Player Draws X Card(s)                                 | Player draws X cards.                                                                                                                                              | `X * 4.0`                 |
| Target Player Discards X Card(s) from Hand (Player Choice) | Specified player chooses and discards.                                                                                                                             | `X * 3.0`                 |
| Target Player Discards X Card(s) from Hand (Random)    | Random discard is more disruptive.                                                                                                                                 | `X * 4.0`                 |
| Target Player Discards X Card(s) from Hand (Effect Controller Choice from Revealed Hand) | Most disruptive non-random discard. (Requires hand reveal effect first or as part).                                                                  | `X * 4.5`                 |
| Look at Target Player's Hand                           | Information gain.                                                                                                                                                  | `1.0`                     |
| **C. Deck Manipulation** |                                                                                                                                                                    |                           |
| Target Player Searches their Deck for [Card Criteria]  | Player searches, reveals (usually), adds to hand (usually), then shuffles. (Powerful "Tutor" effect).                                                              | `5.0` (for 1 specific type) |
|                                                        |                                                                                                                                                                    | `7.0+` (any card)         |
| Target Player Shuffles their Deck                      | Basic utility/disruption.                                                                                                                                          | `0.5`                     |
| Look at Top X Cards of [Player]'s Deck                 | Info gain. Specify what happens next (reorder, bottom, one to hand – those actions add DB). DB for "look" only.                                                      | `0.25 + (0.25 * X)`       |
| Target Player Discards Top X Cards of their Deck ("Mill") | Moves cards from Deck to Discard Pile.                                                                                                                             | `X * 1.5`                 |
| **D. Discard Pile Interaction** |                                                                                                                                                                    |                           |
| Return Target Card from [Player]'s Discard Pile to Hand | Recursion. Specify card type for base. Unit: `3.0`, Asset: `2.5`, Event: `2.0`, Upgrade/Terrain: `1.5`.                                                            | `1.5 - 3.0`               |
| Deploy Target Card from [Player]'s Discard Pile into Play | *Assumes CP cost is paid separately unless specified.* Unit: `4.0`, Asset: `3.0`.                                                                                  | `3.0 - 4.0`               |

**III. Effects Primarily Affecting Game State, Rules & Flow**

| Effect Description                                     | Notes                                                                                                                                                              | Illustrative Base DB Cost |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| **A. Modifying Actions & Activations** |                                                                                                                                                                    |                           |
| Player may take an Additional Single Action this Activation Sequence | Breaks action economy.                                                                                                                               | `7.0`                     |
| Target Card may Activate its Active Ability an Additional Time | Bypasses typical limits for that activation (e.g. if exhausted). Specify duration/instance.                                                                  | `2.5`                     |
| Prevent Target Card from [Action: Activating Abilities/Attacking/Moving] | Specify duration via App E.                                                                                                                            | `1.0 - 2.0` (per action type) |
| **B. Modifying Game Rules (Specific Instances)** | (These are often "Ongoing" via Duration choice from App E and thus very costly)                                                                                    |                           |
| Modify Targeting Rules for [Criteria]                  | E.g., "Opponent's cards lose 'cannot be targeted'..." Base effect; actual duration from App E.                                                                     | `3.0 - 6.0`               |
| Modify Deployment Rules for [Criteria]                 | E.g., "You may deploy Units into opponent's empty Front Row quadrants." Base effect; actual duration from App E.                                                   | `Varies Highly`           |
| **C. Interacting with Mission Cards** | (Most Mission interaction will be via Challenges/Rewards on Missions themselves)                                                                                   |                           |
| Auto-Complete Target Mission Card                      | Potentially game-winning.                                                                                                                                          | `15.0+`                   |
| **D. Game Flow & End States** |                                                                                                                                                                    |                           |
| End the current Game Round                             | Prematurely ends round. Massive disruption.                                                                                                                        | `8.0`                     |
| Player Wins/Loses the Game                           | Direct game end. Extremely high DB, usually via complex conditions not just this effect.                                                                           | `25.0+`                   |
| **E. Copying & Negating** |                                                                                                                                                                    |                           |
| Copy Target [Event/Ability Effect]                     | Effect of copied item resolves. Specify targeting. (Cost ~75% of original effect's DB).                                                                           | `Varies`                  |
| Negate (Counter) Target [Event/Ability Effect]         | Targeted effect/ability does not resolve. Powerful reactive play.                                                                                                  | `4.5`                     |
| **F. Initiative Manipulation** |                                                                                                                                                                    |                           |
| [Player] Gains Initiative for the Next Game Round      | Overrides standard initiative.                                                                                                                                     | `3.0`                     |

---
## Appendix B: Core Game Targets Catalogue
*(Formerly Appendix F in original ACG draft)*

**Introduction:**
This catalogue provides a comprehensive list of core game targets for abilities. The "Illustrative DB Cost (Additive/Modifier)" column indicates a conceptual adjustment to an Effect's base DB cost or the Trigger/Condition component. Targeting opponent's elements or broader scopes generally increases value (positive DB modifier), while targeting only specific friendly elements might be neutral or slightly negative.

**I. Target: Cards** *(Specify zone: In Play, Hand, Deck, Discard Pile, Mission Card Area. "In Play" includes Battlefield & Loadout Area)*

| Target Description                                     | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **A. Cards in Play** |                                                                                                                                                                    |                                          |
| Card in Play                                           | Any single card. Usually further specified by type.                                                                                                                | `+0.25`                                  |
| Unit                                                   | A single Unit card on the Battlefield.                                                                                                                             | `0.0` (often baseline)                   |
| Leader                                                 | A single Unit with 'Leader' subtype. (Higher value target).                                                                                                        | `+0.5`                                   |
| Asset                                                  | A single Asset in a Loadout Area.                                                                                                                                  | `0.0`                                    |
| Upgrade                                                | A single Upgrade card attached.                                                                                                                                    | `-0.25` (often less impactful than host) |
| Terrain                                                | A single Terrain card on the Battlefield.                                                                                                                          | `0.0`                                    |
| X number of [Card Type(s) in Play]                     | Specific number (X) of cards.                                                                                                                                      | `+0.5` per additional target beyond 1st  |
| All [Card Type(s) in Play] [Scope: Friendly/Opponent's/All Battlefield/Loadout] | All cards of type(s) in scope.                                                                                                                     | `+2.0` to `+10.0+` (dep. on scope/type)  |
| **B. Cards in Hand** |                                                                                                                                                                    |                                          |
| Card(s) in [Player]'s Hand                             | For discard, reveal. Specificity (random, player choice, controller choice) part of Effect.                                                                       | `0.0`                                    |
| **C. Cards in Deck** |                                                                                                                                                                    |                                          |
| Card(s) in [Player]'s Deck                             | For search, reveal, mill.                                                                                                                                          | `0.0` to `+0.25` (if specific for search)|
| Top/Bottom X Card(s) of [Player]'s Deck                |                                                                                                                                                                    | `0.0`                                    |
| **D. Cards in Discard Pile** |                                                                                                                                                                    |                                          |
| Card(s) in [Player]'s Discard Pile                     | For recursion, removal from game.                                                                                                                                  | `0.0`                                    |
| **E. Cards in Mission Card Area** |                                                                                                                                                                    |                                          |
| Mission Card                                           | A specific Mission Card.                                                                                                                                           | `+1.0` (high impact if affected)         |
| **F. Other Card-Specific Targets** | (These often act as filters on broader categories like "Unit")                                                                                                     |                                          |
| Card with [Specific Keyword/Subtype/CP Cost/Stat Value/Name] | Adds specificity to another target type.                                                                                                                         | `+0.1` to `+0.25` per specificity        |
| This Card (Self-reference)                             | The card generating the ability.                                                                                                                                   | `-0.25` (generally less DB than other targets) |

**II. Target: Players & Player-Controlled Attributes**

| Target Description                                     | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| Player (Self / "You")                                  | The player controlling/activating the ability.                                                                                                                     | `0.0`                                    |
| Player (Opponent / "Target Opponent")                  | A single chosen opponent.                                                                                                                                          | `+0.25`                                  |
| Player ("Each Opponent")                               | All opponents.                                                                                                                                                     | `+1.5` (or more in >2 player games)      |
| Player (Any)                                           | Any player, including self.                                                                                                                                        | `+0.1`                                   |
| Player who [Met Condition from App D]                  | E.g., "player with most CP."                                                                                                                                       | `+0.25`                                  |
| Player's Command Points (CP)                           | A player's CP pool.                                                                                                                                                | `0.0`                                    |
| Player's Hand / Deck / Discard Pile (as entities/attributes for global effects) | E.g., for effects related to hand size, deck size.                                                                                               | `0.0`                                    |

**III. Target: Game Elements, Zones & Areas**

| Target Description                                     | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **A. Battlefield Areas** | (Specify friendly/opponent if not clear from context or effect)                                                                                                    |                                          |
| Quadrant                                               | A single quadrant.                                                                                                                                                 | `+0.5` (base for AoE targeting)          |
| Row (Front/Back)                                       | All three quadrants in a player's Row.                                                                                                                             | `+2.5` (over single quad)                |
| Column (Left/Center/Right)                             | Both quadrants in a player's Column.                                                                                                                               | `+1.5` (over single quad)                |
| Player's Battlefield (All 6 of their Quadrants)        | All quadrants on one player's side.                                                                                                                                | `+5.0` (over single quad)                |
| All Battlefields                                       | All quadrants of all players.                                                                                                                                      | `+8.0` (over single quad)                |
| **B. Other Zones (as entities)** |                                                                                                                                                                    |                                          |
| Player's Loadout Area                                  |                                                                                                                                                                    | `0.0`                                    |
| Player's Mission Card Area                             |                                                                                                                                                                    | `0.0`                                    |

**IV. Target: Abstract Game Concepts & Properties**

| Target Description                                     | Notes                                                                                                                                                              | Illustrative DB Cost (Additive/Modifier) |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **A. Stats & Values** |                                                                                                                                                                    |                                          |
| Attack/Defense/CP Cost Value (of a Card)               | The numerical stat/cost.                                                                                                                                           | `0.0`                                    |
| Number (e.g., "X", chosen by player or from game state) | An abstract number used as input for an effect.                                                                                                                    | `0.0`                                    |
| **B. Keywords & Abilities (Instances or Definitions)** |                                                                                                                                                                    |                                          |
| Keyword (on a Card)                                    | A specific keyword possessed by a card.                                                                                                                            | `0.0`                                    |
| Ability (on a Card / Instance of an Ability being Resolved) | A specific ability (printed or granted) or an ability currently resolving (e.g., for negation/copying).                                                          | `0.0`                                    |
| **C. Game Mechanics** |                                                                                                                                                                    |                                          |
| Initiative                                             | The concept of initiative.                                                                                                                                         | `0.0`                                    |
| A Game Rule (for effects that ignore/modify them)      | Rarely targeted directly.                                                                                                                                          | `Varies Highly`                          |
| **D. Choices** |                                                                                                                                                                    |                                          |
| Choice (from a list of options provided by an ability) | For modal abilities ("Choose one: A; or B;").                                                                                                                      | `+0.5 to +1.5` (adds to ability value)   |

---
## Appendix C: Core Game Triggers Catalogue
*(Formerly Appendix G in original ACG draft. Simplified if Frequency/Limitation (New App G) handles repetition details.)*

**Introduction:**
This catalogue lists core game events or player decisions that can trigger abilities. The DB cost reflects the trigger event occurring. The **Frequency / Limitation** component (New Appendix G) will further modify the DB cost if the trigger is limited beyond its natural occurrence.

**I. General Active Ability Trigger**

| Trigger Description                             | Notes                                                                                                                                                              | Illustrative Base DB Cost |
| :---------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| As a Player Action (Activate this Ability)      | Ability activated as a single action during player's turn in Activation Sequence, subject to **Activation Costs** (New App F). Consumes a player action.                | `1.0`                     |

**II. Event-Driven Triggers (Automatic / Conditional)**
*(DB cost reflects value of effect occurring without consuming a player action, and base trigger reliability. Frequency/Limitation from New App G modifies this.)*

| Trigger Description                                    | Notes                                                                                                                                                              | Illustrative Base DB Cost |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------ |
| **A. Game Phase & Step Triggers** |                                                                                                                                                                    |                           |
| At the Start of the Game Round                         | Triggers during Start of Round Step (Rulebook III.C.1.c).                                                                                                          | `2.0`                     |
| When [Player] Gains CP                                 | Triggers when specified player gains CP.                                                                                                                           | `0.75`                    |
| When [Player] Draws [X] Card(s)                        | Triggers when specified player draws card(s).                                                                                                                      | `0.75`                    |
| At the Start of [Player]'s Activation Sequence Turn    | Triggers when it's specified player's turn to act.                                                                                                                 | `1.0`                     |
| When [Player] Passes their Action                      | Triggers when specified player "Passes".                                                                                                                           | `0.25`                    |
| At the End of the Activation Sequence / Game Round     | Triggers when Activation Sequence ends.                                                                                                                            | `1.0`                     |
| **B. Card State & Zone Change Triggers** |                                                                                                                                                                    |                           |
| When [This/Target/Any Type of] Card is Deployed        | Triggers on successful deployment.                                                                                                                                 | `1.0`                     |
| When [This/Target/Any Type of] Card is Destroyed       | Triggers when card is destroyed.                                                                                                                                   | `0.75`                    |
| When [This/Target/Any Type of] Card Leaves Play        | Triggers when card moves from Battlefield/Loadout.                                                                                                                 | `1.0`                     |
| When [This/Target/Any Type of] Card Enters [Zone: Hand/Discard/Deck] | Triggers on zone change.                                                                                                                               | `0.5`                     |
| When [This/Target/Any Type of] Card Becomes Exhausted/Ready | Triggers on state change.                                                                                                                                        | `0.25`                    |
| When [This/Target/Any Type of] Unit Becomes Suppressed/Disordered | Triggers on combat state change.                                                                                                                           | `0.5`                     |
| **C. Combat-Related & Impact Triggers** |                                                                                                                                                                    |                           |
| When [This/Target/Any Type of] Unit Declares an Attack | Triggers on attack declaration.                                                                                                                                    | `0.75`                    |
| When [This/Target/Any Type of] Unit is Declared as a Defender | Triggers when unit is targeted by an attack.                                                                                                                     | `0.75`                    |
| When [This/Target/Any Type of] Unit Destroys another Unit (via Attack/Impact) |                                                                                                                                                    | `1.0`                     |
| When [This/Target/Any Type of] Unit is Destroyed (via Attack/Impact) |                                                                                                                                                    | `0.75`                    |
| **D. Player Action & Resource Triggers** |                                                                                                                                                                    |                           |
| When [Player] Plays a [Card Type/Subtype/Name] Card    | Triggers on successful play from hand.                                                                                                                             | `0.75`                    |
| When [Player] Activates an Active Ability              | Triggers on successful activation.                                                                                                                                 | `0.5`                     |
| When an Opponent's Effect Targets [Your Card/Player]   | Defensive trigger.                                                                                                                                                 | `1.0`                     |

---
## Appendix D: Core Game Conditions Catalogue
*(Formerly Appendix H in original ACG draft)*

**Introduction:**
This catalogue outlines common condition types for abilities, adding "if/unless" logic. Conditions typically apply a **DB cost modifier** (often negative if restrictive, positive if it enables much greater flexibility or power modes) to an ability's gross DB cost.

**I. Game State Conditions** (Illustrative DB Modifier)
* If it is the Start of Round Step: `-1.0`
* If it is the Activation Sequence: `-0.25`
* If it is [Player]'s turn in the Activation Sequence: `-0.5`
* If [Player] has Initiative: `-0.25`
* If a [Specific Trigger Event from App C] has occurred this Game Round: `-0.25 to -1.0`
* If it is Game Round X or later: `-0.5 to -1.5`

**II. Card-Specific Conditions** (Illustrative DB Modifier)
* **A. Card Identity & Type**
    * If [This/Target] Card is [Card Name]: `-1.0 to -2.0`
    * If [This/Target] Card is a [Unit/Leader/Asset/Terrain/Upgrade]: `-0.25`
    * If [This/Target] Card has [Subtype/Keyword/Domain]: `-0.5 to -1.0`
* **B. Card Stats & Cost**
    * If [This/Target] Card's [Stat/Cost] is [Comparison] X: `-0.25 to -1.0`
* **C. Card State**
    * If [This/Target] Card is Exhausted/Ready/Suppressed/Disordered: `-0.25 to -0.5`
* **D. Card Location (Zone/Position)**
    * If [This/Target] Card is in [Zone: Hand/Deck/Discard/Loadout/Battlefield]: `-0.25 to -0.75`
    * If [This/Target] Unit is in [Player]'s [Quadrant/Row/Column]: `-0.25 to -1.0`

**III. Player-Specific Conditions** (Illustrative DB Modifier)
* **A. Player Resources**
    * If [Player]'s CP is [Comparison] X: `-0.25 to -1.5`
    * If [Player]'s Hand contains [Number/Type of] Card(s): `-0.25 to -1.0`
    * If [Player]'s Deck/Discard has [Number/Type of] Card(s): `-0.25 to -1.0`
* **B. Player Control & Board Presence**
    * If [Player] Controls [Number/Type/Criteria of] Card(s): `-0.25 to -1.0`
    * If [Player] Controls more/fewer [Card Type] than Opponent(s): `-0.5`
    * If [Player] has completed [X/Specific] Mission Card(s): `-1.0 to -2.0`

**IV. Comparison & Counting Conditions** (Illustrative DB Modifier)
* If [Value A] is [Comparison Operator] [Value B]: `-0.1 to -0.5` (depends on values being compared)
* If the number of [Game Element Type] [Scope] is [Comparison] X: `-0.25 to -1.0`
* If [Criteria A] AND/OR/NOT [Criteria B] is true: `Varies` (AND often more restrictive, OR more flexible. Base `+/- 0.25` for the operator itself, conditions add their own mods).

**V. Cost & Choice-Related Conditions (Often part of ability text allowing player agency)**
* *(These often interact with the Activation Cost component from New App F. If an effect happens "If you pay X," the payment is an Activation Cost providing a DB rebate; the "If" is just linking them.)*
* "Unless [Player] Pays [X CP / Other Resource Cost]" (Punisher effect): `+0.5 to +1.5` (Value is in forcing opponent's choice/loss).

---
## Appendix E: Core Game Durations Catalogue
*(Newly Proposed Appendix)*

**Introduction:**
This catalogue lists standard durations for ability effects. Each chosen Duration applies a DB cost multiplier or a flat additive DB cost to the base Effect's DB value, sourced from the Master DB Cost List. Shorter durations are cheaper; ongoing/permanent durations are significantly more expensive.

| Duration Description                                   | Notes / Common Use Case                                                                                                                                      | Illustrative DB Cost Impact (Multiplier on Effect DB / Flat Additive DB) |
| :----------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------- |
| 1. Instantaneous / Resolves Immediately                | Effect applies and concludes immediately (e.g., Gain CP, Draw Cards, Destroy Unit).                                                                          | `x1.0` or `+0 DB` (Baseline)                                             |
| 2. This Combat Only                                    | Effect persists only for the current combat sequence.                                                                                                        | `x0.75` or `Small Flat DB`                                               |
| 3. This Action / This Ability Resolution Only          | Effect persists for the current action/ability chain resolution.                                                                                             | `x0.75` or `Small Flat DB`                                               |
| 4. This Turn (Current Player's Activation Sequence Turn) | Effect persists until the end of the current player's turn.                                                                                                  | `x1.0` or `Moderate Flat DB`                                             |
| 5. This Game Round                                     | Effect persists until the very end of the current Game Round.                                                                                                | `x1.25` or `Moderate-High Flat DB`                                       |
| 6. Until Your Next Start of Round Step                 | Effect persists through opponent's turns until your next round begins. (Common for buffs/debuffs).                                                             | `x1.75` or `High Flat DB`                                                |
| 7. Ongoing While [Source Card] is in Play              | Effect is continuously active while the source card is operational. (Hallmark of Passive abilities/auras).                                                     | `x3.0 - x5.0+` or `Very High Flat DB`                                    |
| 8. Ongoing While [Specific Condition from App D] is Met | Effect is continuously active, but only if a separate condition holds.                                                                                       | `x2.5 - x4.0` or `High Flat DB` (Slightly less than unconditional Ongoing) |
| 9. Permanent                                           | The change is lasting and does not naturally expire (e.g., permanent stat counter, transformation).                                                          | `x4.0 - x6.0+` or `Extremely High Flat DB`                               |
| 10. Until [Specific Future Trigger from App C] Occurs  | Effect persists until a different game event happens.                                                                                                        | `Varies` (Depends on terminator trigger's likelihood)                    |

---
## Appendix F: Core Game Activation Costs Catalogue (Gameplay Costs)
*(Newly Proposed Appendix)*

**Introduction:**
This catalogue lists common in-game costs players might pay to use abilities (primarily Active abilities, or optional Triggers). Each chosen Activation Cost applies a **negative DB modifier (rebate)** to the ability's gross design DB cost. Higher gameplay costs provide larger DB rebates.

| Activation Cost Description                           | Notes / Common Use Case                                                                                                                                    | Illustrative DB Modifier (Negative DB) |
| :---------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------- |
| 1. No Additional Cost                                 | For Passive abilities or Triggers that resolve automatically without player choice/payment.                                                                | `-0 DB`                                |
| 2. Pay X Command Points (CP)                          | Player spends X CP from their pool.                                                                                                                        | `-(X * 4.0 DB)`                        |
| 3. Exhaust This Card                                  | The card providing the ability becomes Exhausted.                                                                                                          | `-2.5 DB`                              |
| 4. Discard X Card(s) from Your Hand (Player Choice)   | Player chooses X cards from their hand to discard.                                                                                                         | `-(X * 3.0 DB)`                        |
| 5. Discard X Card(s) from Your Hand (Random)          | X cards are discarded randomly from player's hand.                                                                                                         | `-(X * 4.0 DB)`                        |
| 6. Destroy/Sacrifice a Friendly Unit You Control (This Card) | The card providing the ability is destroyed.                                                                                                             | `-5.0 DB`                              |
| 7. Destroy/Sacrifice Another Target Friendly [Card Type] You Control | Player chooses another friendly card of specified type to destroy.                                                                                         | `Varies` (`-3.0` to `-8.0+` Dep. on Type)|
| 8. Remove X [Resource/Counter Type] from This Card/Player | If game uses other countable resources/markers as costs.                                                                                                 | `Varies`                               |
| 9. Target Opponent Gains X CP / Draws X Card(s)       | A cost that benefits an opponent.                                                                                                                          | `Very High Negative DB` (e.g., `-(X * 6.0 DB)`) |
| 10. Pay Half Your Current CP (Rounded Up/Down)        | A scaling CP cost.                                                                                                                                       | `Varies` (avg. CP paid * -4.0 DB)      |

---
## Appendix G: Core Game Frequency / Limitation Catalogue
*(Newly Proposed Appendix)*

**Introduction:**
This catalogue lists standard frequency limiters for Active or Triggered abilities. These generally apply a **negative DB modifier** to the gross DB cost of an ability that could otherwise be used/triggered more often, reflecting its reduced overall availability or impact. "Unlimited" might be a baseline or even carry a positive modifier if the base trigger is very benign.

| Frequency / Limitation Description                    | Notes / Common Use Case                                                                                                                                    | Illustrative DB Modifier / Multiplier |
| :---------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------ |
| 1. Unlimited (for the given Trigger)                  | Ability can activate every time its Trigger (App C) is met, subject only to its Conditions (App D) and Activation Costs (App F).                             | `+0 DB Modifier` (Baseline for many triggers) |
| 2. Once Per Game (Total, from this card instance)     | Ability can resolve successfully only once for the entire game from this specific card.                                                                    | `x0.25` Multiplier on Gross Ability DB  |
|                                                       |                                                                                                                                                            | or `Large Flat Negative DB`             |
| 3. Once Per Game Round (per card instance)            | Ability can resolve at most once per complete Game Round.                                                                                                  | `x0.5` Multiplier on Gross Ability DB   |
|                                                       |                                                                                                                                                            | or `Moderate Flat Negative DB`          |
| 4. Once During Your Turn (per card instance)          | Ability can resolve at most once during your current turn in the Activation Sequence.                                                                      | `x0.65` Multiplier on Gross Ability DB  |
| 5. Only X Times Per Game/Round (e.g., "3 Uses")       | Ability has a specific number of "charges" per period.                                                                                                     | `Varies` (Highly dep. on X and period)  |
| 6. "You may only activate/trigger one ability named '[This Name]' per turn/round." | Prevents stacking same named ability from multiple copies of card.                                                                                         | `Small-Moderate Negative DB Mod`        |
| 7. Cannot Be Activated/Triggered if [Meta-Condition]  | E.g., "Cannot use if you have played an Event this turn." A condition *on the allowance* of activation/triggering beyond normal ability conditions.           | `Variable Negative DB Mod`              |
| 8. The First Time [Trigger from App C] Occurs Each Round/Turn | Limits a common trigger to only its first instance in a period.                                                                                            | `Significant Negative DB Mod`           |