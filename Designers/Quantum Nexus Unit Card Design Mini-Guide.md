# Quantum Nexus: Unit Design Mini-Guide

## Designing Unit Cards in Quantum Nexus

This mini-guide will walk you through the process of creating a non-leader unit card for Quantum Nexus, using the best practices outlined in the sources.

### 1. Start with a Concept

*   **Theme:** Begin with a clear idea of the unit's role and purpose in the game. What makes it unique? What kind of player would use it?
*   **Domain:** Which of the four domains (Technology, Magic, Psionics, Divinity) does the unit belong to? This will influence its abilities, stats, and overall feel.
*   **Visuals:** Imagine the unit's appearance.

### 2. Determine Domain Points, Rarity, and FGR Alignment

*   **Domain Points (DP) - Internal Design:** Assign DP based on the unit's mastery of its domain(s) for internal balancing (e.g., 1 DP for basic, up to 4 for mastery).
*   **FGR Deck Construction Rule (Crucial - FGR Section II.C):** A Unit card's domain value for any given domain (e.g., Technology) **must be equal to or lower than the total points assigned to that same domain across all of the player's chosen Mission Cards**. If a player's Mission Cards provide a total of 0 points for a specific domain, any Unit card in their deck **must also have 0 points** in that domain. This is a hard constraint for players.
*   **Rarity:** The card's rarity (Unique, Limited, Common) affects its card count (for deck building) and can be used for internal AP calculation bonuses.

### 3. Define Card Feel

*   **Malevolence, Utility, Combat Focus, Impact:** These choices will influence the unit's abilities and stats. For example, a benevolent, utility-focused unit might have abilities that heal allies or draw cards. A malevolent, offensive unit might have high Attack and abilities that deal direct damage.

### 4. Calculate Card Costs (Internal Design Metrics)

*   **Base CP (Design):** Example: Multiply the total DP by 2.
*   **Rarity Bonus AP (Design):** Example: Bonus AP = 0.8 \* (1 / Card Count).
*   **Total AP (Design):** Example: Add Base CP and Rarity Bonus AP. This is an internal AP pool for abilities and keywords. The final printed CP cost is what players use.

### 5. Unit Gameplay Rules & Combat (Incorporating FGR)

Units are central to combat and board presence. Their design must align with these FGR rules:

*   **Deployment (FGR Section IV.A, III.C.2):**
    *   Units are deployed from hand by a player taking the **'Deploy a Card' action** during their turn in the Activation Sequence.
    *   They are deployed into one of the **player's own quadrants** on their side of the Battlefield.
    *   Multiple non-Leader units controlled by the same player can occupy the same quadrant. (Leader units have a 'one Leader per quadrant' restriction).
*   **Declare an Attack (Action - FGR Section III.C.2):**
    *   A player can choose one of their **ready units** to declare an attack as their action.
    *   The chosen unit then **exhausts**.
    *   **Targeting:** The attacking player may target **any enemy unit within the attacker's valid range** (Close, Mid, or Far – see Section 7). The previous "Front-Row Priority" rule is **REMOVED**.
    *   **Effective Defense Calculation:** The defender's effective Defense for this combat is calculated by summing:
        *   Its base Defense value.
        *   Universal Terrain Bonus: +1 Defense for each Terrain card in the defender's own quadrant (max +2 from this source).
        *   Additional Back-Row Bonuses (if applicable): +1 Defense if a friendly unit is in the front-row quadrant ahead; +1 Defense for each Terrain in the friendly front-row quadrant ahead (max +2 from this source).
        *   Any other defense modifiers from card effects.
    *   **Combat Resolution:** Compare Attacker's Attack (A) with Defender's *Effective Defense (D)*:
        *   **If A > D:** The defending unit is **destroyed** and sent to its owner's Discard Pile.
        *   **If A = D:** The defending unit becomes **"Suppressed"** (it becomes exhausted; if already exhausted, no additional immediate effect). Both units survive.
        *   **If A < D:** The attacking unit becomes **"Disordered"** (it receives -1 Defense until the start of its controller's next Game Round) AND is **"Pushed Back"** (its controller must move the unit one quadrant in a cardinal direction to an adjacent friendly quadrant, respecting Leader limits; if no valid move, it doesn't move). The defender is unaffected.
*   **Move a Unit (Action - FGR Section III.C.2):**
    *   A player can choose one of their **ready units** to move as their action.
    *   The unit moves one quadrant in a cardinal direction (Forward, Backward, Left, or Right) to an adjacent **friendly quadrant** (respecting Leader limits; destination can be occupied by other friendly non-Leaders).
    *   The unit that moved then becomes **exhausted**.

### 6. Design Abilities (Aligning with FGR)

*   **Concept and Theme:** Abilities should align with the unit's theme and domain.
*   **Types (FGR Definitions):**
    *   **Active Abilities:** Chosen by the player as an **'Activate an Active Ability' action** (FGR III.C.2). Costs (CP, exhaust, etc.) are specified on the card.
    *   **Passive Abilities:** Always active; do not require an action (FGR Glossary).
    *   **Triggered Abilities (Interrupts):** Activate automatically on specific game events (FGR Section VII.A).
*   **AP Costing for Design:** Use relevant AP tables (e.g., from `Designers/Quantum Nexus Ability Creation Mini-Guide.md` or internal guidelines).
*   **Terminology:** All ability text must use current FGR terminology (e.g., "Command Points," "Game Round," "Activation Sequence," "exhaust," "quadrant," "Suppressed," "Disordered," "Pushed Back").

### 7. Add Keywords (Optional)

*   **Type:** Choose keywords that enhance strengths or mitigate weaknesses. Ensure keyword effects align with FGR.
*   **AP Costing for Design:** Use specific keyword AP costing tables.

### 8. Define Attack Ranges (Align with FGR Section VIII - Glossary)

*   All Units that can attack have an Attack stat and a defined range. (The "Rank" system described in previous versions of this guide distinguishing units with/without Attack based on "Terrestrial, Aerial, Orbital, Interstellar" is not part of the FGR for units; all units deploy to the standard battlefield quadrants and are subject to standard rules unless their card text specifies otherwise).
*   **Attack Ranges:**
    *   **Close Range:** Can target its **own current quadrant** AND one existing quadrant directly Forward, Backward, Left, and Right. (Up to 5 quadrants).
    *   **Mid Range:** Can target one existing quadrant directly Forward, Backward, Left, Right, and all four direct diagonals (Forward-Left, etc.). Does **not** include the attacking unit's own current quadrant.
    *   **Far Range:** Units in a player's Front Row target all quadrants in the opponent's Back Row. Units in a player's Back Row target all quadrants in the opponent's Front Row. Does **not** include the attacking unit's own current quadrant.
*   Design a unit's range based on its intended role (e.g., brawler, skirmisher, artillery).

### 9. Assign Attack and Defense Stats

*   **Balance:** Stats should be balanced with the unit's CP cost, abilities, keywords, and its FGR-defined combat role. Consider the combat resolution outcomes (A>D, A=D, A<D) when assigning stats.
*   **Role:** A unit's intended role (offensive, defensive, balanced) will influence its stats. All standard units have both Attack and Defense values (FGR Section IV.A).

### 9. Craft Flavor Attributes

*   **Name:** Choose a name that is evocative, memorable, and reflects the unit's theme.
*   **Image:** Create a detailed description of the card's artwork.
*   **Flavor Text:** Write a short quote or description that adds personality and lore.

### 10. Playtest and Iterate

*   Playtesting is crucial! Test your card against a variety of opponents and decks to see how it performs.
*   Based on playtesting feedback, adjust the unit's stats, abilities, keywords, or even its concept to achieve balance and strategic depth.

**Remember:** This guide provides a framework. The creative possibilities for designing non-leader unit cards in Quantum Nexus are vast! Don't be afraid to experiment, break conventions, and create cards that are unique, engaging, and contribute to the rich tapestry of the game's universe.
