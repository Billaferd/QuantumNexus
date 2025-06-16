#  Quantum Nexus: Terrain Card Design Mini-Guide

This guide outlines the design of Terrain cards for Quantum Nexus, incorporating key gameplay rules from the `Players/Quantum Nexus Full Game Rules.md` (FGR).

## 1. Terrain Card Fundamentals & Gameplay Rules (FGR Section IV.E, III.C.2)

Before conceptualizing, understand how Terrain cards function:

*   **Deployment:**
    *   Terrain cards are played from hand by taking the **'Deploy a Card' action** during a player's turn in the Activation Sequence (FGR Section III.C.2).
    *   They are deployed into one of the **player's own quadrants** on their side of the Battlefield (FGR Section IV.E).
*   **Placement Limit:**
    *   A player can have a maximum of **two (2) of their own Terrain cards active in any single one of their quadrants** at any given time.
*   **Universal Defense Bonus (Fundamental Effect):**
    *   **ALL Terrain cards inherently provide +1 Defense** to any unit (friendly or an opponent's unit being targeted or affected in that quadrant) located in the same quadrant as the Terrain card.
    *   If two Terrain cards are active in the same quadrant, units in that quadrant gain a total of **+2 Defense** from this universal effect.
    *   This bonus is **in addition to any other abilities printed** in the Terrain card's rule box.
    *   **Combat Relevance (FGR Section III.C.2):** This defense bonus contributes to a unit's *Effective Defense*. Additionally, for units in a player's back row, Terrain in the quadrant directly *ahead* of them can also provide defensive bonuses to that back-row unit.
*   **Stacking and Conflicting Effects (FGR Section IV.E):**
    *   **Cumulative Effects:** If two Terrain cards are in the same quadrant, their effects (the universal +1 Defense from each, and their printed rule box effects) are cumulative unless specified otherwise. Numerical modifiers are combined (e.g., +1 Attack and -1 Attack result in +0 Attack).
    *   **Conflicting Non-Numerical Effects:** If a non-numerical effect from a Terrain card (or any source) active in a quadrant explicitly negates, prevents, or forbids an action, state, or condition that another non-numerical effect active in or targeting that same quadrant explicitly permits, enables, or creates, and the rules do not specify a hierarchy (e.g., 'card effects override game rules'), then **neither of those specific, directly conflicting effects is applied**. Other, non-conflicting effects from the involved cards still apply.

## 2. Conceptualize Your Terrain

*   **Theme:** Define the Terrain card's role, considering its inherent defensive bonus. Is it a desolate wasteland, a technologically advanced city, or a place of ancient magic? Who would benefit from this Terrain beyond the base defense?
*   **Domain Affinity:** Which domains (Technology, Magic, Psionics, Divinity) does this Terrain favor, hinder, or remain neutral to through its *printed abilities*?
*   **Visuals:** Craft a mental image that reflects its theme and effects.

## 3. Determine Domain Points and Rarity

*   **Domain Points (DP):**  Allocate DP to represent the Terrain's connection to the domains. 1 DP is basic, 2 DP is intermediate, 3 DP is advanced, and 4 DP signifies mastery. Each domain can have a maximum of 4 DP allocated to it. Remember, if a domain is mentioned in the Terrain's name, subtype, flavor text, or abilities, it must have at least 1 DP in that domain. The total DP cannot exceed 6.
*   **Rarity:**  Set the Terrain's rarity: Unique, Limited, or Common. Rarity affects the card count, which then influences the bonus AP the card receives. Rarer cards have lower counts and get bigger AP bonuses.

## 3. Establish Card Feel

*   **Impact:** Will the Terrain's presence be primarily constructive, destructive, or neutral? This considers the overall impact of the Terrain card's effects on the game.
*   **Translate Impact into Design:**  A constructive Terrain might enhance unit stats or grant beneficial abilities, while a destructive Terrain could impose penalties or hazardous conditions.

## 4. Calculate Card Costs

*   **Base CP:** Multiply the Terrain's total DP by 2 to get its Base CP cost.
*   **Rarity Bonus AP:** Use the formula: Bonus AP = 0.8 \* (1 / Card Count) to calculate the bonus AP based on the Terrain's rarity. (This is an internal design calculation).
*   **Total AP:** Add the Base CP and (Base CP \* Rarity Bonus AP) to get the Total AP available for designing the Terrain's *printed* abilities. Remember, the total AP cost of all printed abilities cannot exceed this Total AP pool. The Universal Defense Bonus is inherent and not part of this AP calculation for printed text.

## 5. Design Printed Abilities (Beyond the Universal Defense Bonus)

*   **Concept and Theme:** Align the Terrain's *printed* abilities with its theme, domain affinity, and card feel, keeping in mind it already provides a defense bonus.
*   **Types (FGR Definitions):**
    *   **Passive Abilities:** Most common for Terrain. These are always active, providing ongoing benefits or drawbacks to units or the quadrant itself, as long as the Terrain is in play (FGR Glossary). Example: "Units in this quadrant have +1 Attack."
    *   **Triggered Abilities (Interrupts):** Abilities that trigger automatically in response to specific game events (FGR Section VII.A). Example: "When a unit is deployed into this quadrant, its controller loses 1 CP."
    *   **Active Abilities:** Generally not suitable for Terrain cards, as they are not "activated" in the same way as Units or Assets once deployed.
*   **AP Costing for Design:** Use relevant AP tables (e.g., from `Designers/Quantum Nexus Ability Creation Mini-Guide.md` or internal guidelines) for the *printed abilities*.
*   **Terminology:** All ability text must use current FGR terminology (e.g., "Command Points," "Game Round," "Activation Sequence," "quadrant").

## 6. Integrate Keywords (Optional)

*   **Type:**  Select keywords that either reinforce the Terrain's strengths, mitigate its weaknesses, or introduce unique mechanics. Positive keywords add to the AP pool, negative keywords subtract from it, and neutral keywords always add to the pool.
*   **Costing:** Refer to the Keyword Cost Reference Table to find the AP cost of each keyword.

## 7. Craft Flavor Attributes

*   **Name:** Choose a name that is both memorable and evocative, accurately reflecting the Terrain's theme and impact on the game.
*   **Image:**  Provide a vivid description that captures the Terrain's visual identity, incorporating elements relevant to its domain affinity, such as technological structures, mystical landscapes, psionic energies, or divine symbols.
*   **Flavor Text:** Craft a concise and impactful quote or description that offers a glimpse into the Terrain's history, significance, or the events that transpired there.

## 8. Playtest and Iterate

*   **Playtesting:** Thoroughly test your Terrain card, ensuring its interactions (including the universal defense bonus and any printed abilities) adhere to the FGR.
*   **Iteration:** Be prepared to modify printed abilities, keywords, or AP cost based on playtesting.

**Example:  Designing a "Desolate Wasteland" Terrain Card:**

1.  **Concept:** A harsh, irradiated wasteland. Units here get the standard +1 Defense from this being a Terrain. Printed abilities will modify this further or add other effects.
2.  **Domain Affinity (for printed abilities):** Hinders Divinity and Magic; Favors Technology.
3.  **Card Feel:** Destructive.
4.  **Domain Points:** Technology (2), Psionics (1) - Total DP: 3
5.  **Rarity:** Limited.
6.  **Base CP (design):** 3 DP * 2 = 6 CP
7.  **Rarity Bonus AP (design):** (1/2) * 0.8 = 0.4
8.  **Total AP for printed abilities (design):** 6 + (6 * 0.4) = 8.4 AP
9.  **Inherent Effect:** Provides +1 Defense to all units in its quadrant.
10. **Printed Abilities (example):**
    *   **Passive Ability (3 AP):** Units with the Divinity or Magic domain in this quadrant get an additional -1 Attack. (Combined with inherent bonus, they get +1 Def, -1 Atk).
    *   **Passive Ability (4 AP):** Units with the Technology domain in this quadrant gain an additional +1 Defense. (Combined with inherent bonus, they get +2 Def total).
11. **Keywords:** None.
12. **Name:** Radioactive Ruins
13. **Image:** Twisted metal skeletons of buildings, ash-covered ground, strange glowing flora.
14. **Flavor Text:** "The echoes of a forgotten war linger, twisting life into new, unsettling forms."

**Design Considerations from Example:**
*   The card inherently makes units in its quadrant more survivable (+1 Defense).
*   Its printed abilities then layer on top of this, creating further strategic choices. For Technology units, the quadrant becomes significantly more defensive. For Divinity/Magic, it's a trade-off (more defense, but less offense).
*   Always remember the Universal Defense Bonus when balancing the AP cost of printed abilities.

Remember to playtest this example Terrain card. The goal is to create Terrain cards that enrich the Quantum Nexus experience, adding layers of strategy and immersing players in its dynamic universe, all while adhering to the `Players/Quantum Nexus Full Game Rules.md`.
