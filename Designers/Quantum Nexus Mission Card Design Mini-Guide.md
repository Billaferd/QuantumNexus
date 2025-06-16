## Quantum Nexus Mission Card Design Mini-Guide

Mission cards are crucial for shaping strategy, determining resource availability, and providing a path to victory in Quantum Nexus. This guide outlines their design based on the `Players/Quantum Nexus Full Game Rules.md` (FGR).

**1. Mission Card Fundamentals & Deck Construction (FGR Section II.B)**

*   **Purpose in Game:** Mission cards represent your objectives. Completing them provides benefits and can lead to victory. They also contribute to your available Command Points each round.
*   **Setup and Placement (FGR Section III.A & V.A):**
    *   At the very start of game setup, *before* the initial initiative flip, each player separates their chosen Mission Cards from their main deck.
    *   These Mission Cards are placed face-up in that player's **Mission Card Area**.
    *   This area allows all players to see each other's objectives and allows the owner to easily reference their mission progress.
*   **Deck Limits:**
    *   A deck can include a **maximum of six (6) mission cards**.
*   **Domain Point (DP) Allocation:**
    *   Mission cards have Domain Points (DP) in Technology, Magic, Psionics, and Divinity.
    *   The **total DP sum across all domains on ALL your chosen mission cards combined must equal exactly 6**.
    *   **No single domain's total DP (summed from all your mission cards) can exceed 4 points**.
    *   It is acceptable for a specific domain to have a total of 0 points across all your mission cards.
    *   **(Design Note):** While the FGR focus on totals, for individual card design, consider how a single card's DP contributes to these overall player totals. A single card having 0 DP in all domains, or more than 4 DP in one, would be unusual unless balanced by other mission cards.
*   **Impact on Unit Card Inclusion (FGR Section II.C):**
    *   The **total DP for a specific domain across all your Mission Cards** dictates the maximum value a Unit card in your deck can have in that same domain. For example, if your Mission Cards collectively provide 3 points in Technology, any Unit card in your deck cannot have more than 3 points in its Technology domain value.

**2. Command Point (CP) Contribution & Design**

*   **CP Value of a Mission Card (Design):** Each Mission Card will have a CP value, determined during its design (see "Adjusted CP" later). This is the value printed on the card.
*   **Contribution to In-Game CP (FGR Section II.B & III.A):**
    *   The **sum of the printed CP values of all your chosen Mission Cards** determines a base amount of Command Points you will calculate during each Game Round's **Start of Round Step**.
    *   This mission-derived CP is added to other sources of CP (like ongoing card effects) to form your CP pool for the round.
*   **Not Part of Main Deck CP Limit (FGR Section II - Construction Basics):**
    *   The CP values of Mission Cards do **not** count towards the 200 CP limit for the main deck (Units, Leaders, Assets, etc.).

**(Internal Design Note: The following "Base CP" calculation is for designing the CP value of a single mission card.)**
*   **Base CP (for one mission card's design):** Multiply the total DP assigned to that single mission card by 3: `BaseCP = Total DP on this card * 3`. This Base CP is a starting point for calculating the card's final printed "Adjusted CP".

**3. Challenge Design (Internal Design Considerations)**

*   Each mission card should have a unique challenge players must complete to unlock its abilities or count as "completed" for victory.
*   Consider various types of challenges: Domain-Specific, Generic, Resource Management, Deck Manipulation, Battlefield Control.
*   **Challenge Pacing:** Early-Game, Mid-Game, Late-Game.
*   **Negative Challenges:** These may require a player to perform a detrimental action, potentially balancing a stronger effect or lower mission CP cost.

**4. Mission Card Abilities (Align with FGR Definitions)**

*   Upon completion (or potentially before, if designed so), Mission Cards can provide benefits through abilities.
*   **Types of Abilities:**
    *   **Passive Abilities (FGR Glossary):** An ability that is always active once its condition is met (e.g., mission completed) and does not require being chosen as an action. Example: "Units you control gain +1 Attack."
    *   **Triggered Abilities (FGR Section VII.A):** An ability that automatically activates when a specific game event occurs. Example: "When this mission is completed, draw 2 cards." or "At the start of the Game Round, if this mission is completed, gain 1 CP."
    *   **Active Abilities (FGR Section III.C.2):** While less common for missions (as they aren't typically "activated" in the same way as units/assets), a mission could theoretically grant an action or ability to the player. If so, its use must conform to the 'Activate an Active Ability' rules.
*   **(Design Pattern Example):** A common design might be a significant one-time triggered effect upon completion, and/or an ongoing passive or roundly-triggered effect post-completion. The FGR (II.B) refers to "passive effects or powerful abilities."
*   **AP Costing for Design:** The AP cost for these abilities should be determined using relevant AP tables (e.g., from `Designers/Quantum Nexus Ability Creation Mini-Guide.md` or internal design guidelines) and factored into the mission card's overall "Adjusted CP".
*   **Terminology:** All ability text must use current FGR terminology (e.g., "Command Points," "Game Round," "Start of Round Step," "Activation Sequence," "exhaust").

**5. Adjusted CP (Final Printed CP for a Mission Card - Design Calculation)**

*   The "Adjusted CP" is the final CP value printed on the mission card. This value is what players sum up for their per-round CP gain from missions.
*   It's calculated by considering the card's Base CP (from its own DP), the design CP cost/benefit of its challenge, and the design CP cost of its abilities.
*   Formula example: `Adjusted CP = Base CP (design) + (Challenge CP (design) - Ability CP (design) * Sign(Challenge CP (design)))`.
*   **Constraint:** The final printed Adjusted CP of a mission card cannot be less than 0.
*   This value is critical as it directly impacts the player's resources each round.

**6. Mission Completion and Victory (FGR Section VI.B & VI.C)**

*   **Immediate Victory:** If a player completes all of their chosen Mission Cards, they **immediately win the game**. This takes precedence over all other game actions or pending effects.
*   **Simultaneous Completion:** If multiple players simultaneously meet the conditions for completing all of their respective Mission Cards (e.g., due to the same triggered effect), **all such players are declared winners**, and the game concludes.

**7. Playtesting and Iteration**

*   Playtesting is crucial for ensuring mission cards are balanced, their challenges are achievable within reasonable game flow, and their rewards are appropriate. All interactions must adhere to the FGR.
*   Gather feedback and iterate on CP costs, challenges, and abilities.

**Additional Design Tips**

*   **Card Feel:** Align the mission's challenge and abilities with a desired card feel (Malevolent, Benevolent, etc.).
*   **Theme & Narrative:** Develop a cohesive theme and integrate it with Quantum Nexus lore.
*   **Presentation:** Use a clear template for presenting mission card information.

By following this guide and the `Players/Quantum Nexus Full Game Rules.md`, you can create compelling mission cards that enrich the Quantum Nexus universe and provide strategic depth.
