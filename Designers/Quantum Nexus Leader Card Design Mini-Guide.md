# Quantum Nexus Leader Design Mini-Guide

## Leader Unit Creation Mini-Guide

This mini-guide walks you through creating a Leader unit card for Quantum Nexus. It incorporates the best practices and addresses the areas for improvement identified in the critique of the non-leader Unit Design Mini-Guide.

### 1. Start with a Concept ()

*   **Theme:** Begin with a clear idea of the Leader unit's role and purpose. What makes this Leader unique and compelling? What kind of player would include this Leader in their deck? ()
*   **Domain:** Which of the four domains (Technology, Magic, Psionics, Divinity) is central to this Leader's identity? The domain will significantly influence the Leader's abilities, stats, and overall feel. () 
*   **Visuals:** Envision the Leader's appearance. A captivating visual design is essential for a Leader unit. What striking details will capture the Leader's essence and make it stand out on the battlefield? ()

### 2. Determine Domain Points, Rarity, and Leadership Factor ()

*   **Domain Points (DP):**  Allocate DP based on the Leader's mastery of its domain(s). Remember that 1 DP signifies basic usage, 2 DP indicates intermediate mastery, 3 DP represents advanced command, and 4 DP signifies complete mastery of the domain.  Each domain can have a maximum of 4 DP allocated to it. If a domain is mentioned in the Leader's name, subtype, flavor text, or abilities, the card must have at least 1 DP in that domain. ()

*   **Rarity:** Decide on the Leader's rarity (Unique, Limited, Common). Rarity influences the card count, which dictates how many copies of the Leader card can be included in a player's deck. Rarer cards have lower counts, making them more valuable and sought-after. Rarity also impacts the bonus Ability Points (AP) the card receives during the calculation process. ()

*   **Leadership Factor:**  Since we are creating a Leader unit, the Leadership Factor is always **1**. This factor will be used later in the AP calculation. ()

### 3. Leader Gameplay Rules & Design Implications

Before detailing card feel, it's crucial to understand the specific rules governing Leaders in `Players/Quantum Nexus Full Game Rules.md` (FGR), as these heavily influence their design:

*   **Deployment:**
    *   Leaders are deployed onto the battlefield into one of your quadrants using the **'Deploy a Card' action** during your turn in the Activation Sequence (FGR, Section III.C.2).
    *   **One Leader Per Quadrant:** A player can only have one of their Leader units in any single one of their quadrants at a time. Another Leader controlled by the same player cannot be deployed into or moved into a quadrant already occupied by one of their Leaders (FGR, Section IV.A). This is a primary constraint to consider when designing Leader mobility or deployment-related abilities.
    *   **Simultaneous Entry:** If multiple game effects attempt to simultaneously cause more than one of a single player's Leader units to enter or exist in the same quadrant (e.g., through deployment, movement, or transformation), the player whose action or effect is causing the entries (or the player with initiative in case of simultaneous triggers) determines the order of resolution attempts. Each attempt is validated against the 'one Leader per quadrant' rule. If an attempt would result in a violation, that specific Leader is not deployed, moved, or transformed (FGR, Section IV.A).
*   **Deck Construction Limits:**
    *   A player's deck cannot contain more than **25 Command Points (CP) worth of Leader cards**.
    *   This 25 CP limit for Leaders counts towards the overall **exactly 200 CP total** for the main deck (FGR, Section II - Construction Basics and Section VII.D). This significantly constrains how many Leaders, and of what CP cost, can be included.
*   **Transformation Effects:**
    *   Units can become Leaders (and Leaders can lose their Leader status) through card-specific abilities or effects.
    *   When a unit becomes a Leader via an effect, it immediately becomes subject to all Leader limitations (like 'one Leader per quadrant'), unless the transforming card's text explicitly states otherwise (FGR, Section IV.A). Designers should be clear if a transformation effect is meant to bypass standard Leader rules.

### 4. Define Card Feel and Translate it to Mechanics ()

*   **Malevolence:** Is the Leader benevolent, malevolent, or neutral?  ()
*   **Utility:** Does the Leader prioritize utility, disruption, or maintain a balance between the two?  ()
*   **Combat:** Is the Leader designed for offense, defense, or a balanced approach? ()
*   **Impact:**  Will the Leader's presence on the battlefield be primarily constructive, destructive, or neutral? ()

Carefully consider how each of these card feel axes will manifest through the Leader's mechanics. Here's how you can translate card feel into the Leader's design:

*   **Abilities:** The Leader's abilities should reflect its card feel. For instance, a benevolent leader might have abilities focused on healing allies or strengthening their defenses.  A disruptive Leader, on the other hand, could have abilities that interrupt an opponent's actions or force them to discard cards.  ()

*   **Stats:**  The Leader's Attack and Defense stats should also align with its card feel. An offensive Leader will likely have a higher Attack stat, while a defensive Leader will have a more robust Defense stat. ()

*   **Keywords:** Keywords can further emphasize the Leader's card feel. A Leader with "Provoke," for example, reinforces its defensive nature by compelling enemies to attack it. A Leader with "Flying" could be more aligned with a utility or offensive role, allowing it to move freely around the battlefield or avoid ground-based threats. ()

### 4. Calculate Card Costs ()

*   **Base CP:** The Base CP is determined by the Leader's total DP. Multiply the total DP by 2.  ()
*   **Stat Points:**  Each point of Attack and Defense costs 0.5 CP.  Calculate the total stat point cost by adding the Leader's Attack and Defense together, then dividing the sum by 2. ()
*   **Adjusted CP:**  To determine the Adjusted CP, subtract half of the total stat point cost from the Base CP. ()

*   **Rarity Bonus AP:** Calculate the bonus AP that the Leader receives based on its rarity using the formula: Bonus AP = 0.8 \* (1 / Card Count). ()  

*   **Total AP:**  The Total AP available for designing the Leader's abilities and keywords is calculated using the following formula: 

Adjusted CP + (Adjusted CP \* Rarity Bonus AP) + (Adjusted CP \* 0.5 \* Leadership Factor) ()

This AP pool is for balancing the Leader's abilities and keywords. The final printed CP cost of the Leader (derived from Base CP and Stat Points) is what players use for deployment and for adhering to the 25 CP deck construction limit for Leaders.

### 5. Design Abilities ()

*   **Concept and Theme:**  The Leader's abilities must align with its theme and domain.
*   **Types of Abilities (referencing FGR definitions):**
    *   **Active Abilities:** These are abilities that a player must choose to use as their action during their turn in the Activation Sequence by taking the **'Activate an Active Ability' action** (FGR, Section III.C.2). The card's text will specify any Command Point (CP) costs, exhaust requirements, or other costs.
    *   **Passive Abilities:** These abilities are always active and do not require being chosen as an action to use. Their effects apply as long as the Leader is in play and any specified conditions are met (FGR, Glossary).
    *   **Triggered Abilities (Interrupts):** These abilities trigger automatically in response to specific game events (FGR, Section VII.A).
*   **AP Costing for Design:** Determine the Ability Point (AP) cost of each ability using relevant AP tables (e.g., from the `Designers/Quantum Nexus Ability Creation Mini-Guide.md` or more detailed internal Card Creation Guidelines). Ensure the total AP cost of all abilities and keywords does not exceed the Leader's Total AP pool.
*   **Terminology:** Ensure all ability text uses current terminology from the `Players/Quantum Nexus Full Game Rules.md` (e.g., "Command Points," "Game Round," "Activation Sequence," "exhaust," "quadrant").

### 6. Add Keywords (Optional) ()

*   **Type:** Choose keywords that complement the Leader's strengths, mitigate weaknesses, or introduce unique mechanics. Ensure keyword effects align with FGR.
*   **AP Costing for Design:** Determine the AP cost of each keyword using specific keyword AP costing tables (e.g., from internal Card Creation Guidelines).

### 7. Determine Classification and Range ()

*   **Classification (Internal Design Term):** All Leader units are classified as **Terrestrial** for design purposes, signifying they are deployed onto the battlefield quadrants. (Note: "Terrestrial" is an internal design term and not a keyword or rule in the `Players/Quantum Nexus Full Game Rules.md`. Leaders are simply 'Unit' type cards with the 'Leader' subtype.)
*   **Range:** Decide on the Leader's attack range: Close, Mid, or Far (as defined in FGR Glossary). This should align with its tactical role.

### 8. Assign Attack and Defense Stats ()

*   **Balance:** The Leader's Attack and Defense stats should be in harmony with its CP cost, abilities, keywords, and intended role in a deck. A high Attack value generally comes at the cost of a lower Defense value, and vice-versa. ()
*   **Role:** The Leader's combat role—offensive, defensive, or balanced— will influence its stats.  Offensive Leaders will typically have a higher Attack stat, while defensive Leaders will boast a more substantial Defense stat. ()

### 9. Craft Flavor Attributes ()

*   **Name:** Choose a name that is not only memorable and evocative but also captures the essence of the Leader's theme and personality. ()
*   **Image:**  The image is crucial for establishing the Leader's visual identity. Create a detailed description that captures the Leader's theme, mood, and presence on the battlefield. ()
*   **Flavor Text:**  Flavor text adds depth and personality to the Leader. Use a concise and impactful quote or description that offers insights into the Leader's backstory, abilities, or significance within the Quantum Nexus universe. ()

### 10.  Playtest and Iterate ()

*   **Playtesting:** Rigorous playtesting is essential to refine your Leader unit. Test your Leader card against diverse opponents and decks to observe how it performs in actual gameplay scenarios. () 
*   **Iteration:** Be receptive to feedback from playtesting and adjust your Leader's stats, abilities, keywords, CP cost, or even the core concept based on the insights you gain. ()  Iteration is key to achieving a balanced and engaging Leader unit card.

**Important Considerations for Leader Unit Design:**

*   **Unique Identity:**  Leader units should stand out from non-leader units. Their abilities should be impactful, their presence on the battlefield should be noticeable, and their design should convey a sense of leadership and power.

*   **CP Cost Calculation & Design Valuation:** The "Leadership Factor" used in AP calculation (Section 4) reflects a design valuation for Leaders, allowing them potentially more impactful abilities for their calculated CP cost compared to non-Leader units. This is an internal design balancing mechanic. Players see and use the final printed CP cost on the card.
*   **Synergy with Deck Archetypes:** Consider how the Leader might synergize with specific deck archetypes.
*   **Adherence to FGR:** All aspects of the Leader's final design (abilities, stats, keywords) must function within and be consistent with the `Players/Quantum Nexus Full Game Rules.md`.

**Final Thoughts:**

Creating a compelling Leader unit card in Quantum Nexus requires a blend of creativity, strategic thinking, and careful attention to both these design guidelines and the official `Players/Quantum Nexus Full Game Rules.md`. Embrace the iterative process, experiment with different concepts and mechanics, and strive to create Leaders that will captivate players and leave a lasting mark on the game's universe.
