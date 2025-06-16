# Quantum Nexus Asset Card Design Mini-Guide

## Mini-Guide for Creating an Asset Card in Quantum Nexus

This mini-guide will guide you through creating an Asset card for Quantum Nexus, drawing upon the best practices and addressing points of improvement noted in previous critiques of similar mini-guides.

### 1. Conceptualize Your Asset

*   **Theme:** Start with a clear understanding of your Asset's role and purpose in the game. Is it designed to enhance specific strategies, disrupt opponents' plans, or offer versatile utility? What kind of player would benefit from this Asset?
*   **Domain:** Which of the four domains (Technology, Magic, Psionics, Divinity) is central to this Asset's identity? The chosen domain will significantly impact the Asset's abilities, flavor, and overall feel.
*   **Visuals:** Imagine the Asset's appearance. Is it a piece of advanced technology, a mystical artifact, a psionic conduit, or a divine manifestation? Create a mental picture of the Asset, considering its domain and theme.

### 2. Define Domain Points and Rarity (and Internal Rank)

*   **Domain Points (DP):** Allocate DP to reflect the Asset's connection to its chosen domain. A higher DP allocation indicates greater mastery and potential for powerful abilities within that domain. Each domain can have a maximum of 4 DP allocated to it. Remember that if a domain is mentioned in the Asset's name, subtype, flavor text, or abilities, it must have at least 1 DP in that domain. 
*   **Rarity:** Determine the Asset's rarity: Unique, Limited, or Common. Rarity affects the card count, which in turn influences the bonus AP the card receives during calculation. Rarer cards have lower counts and therefore receive higher AP bonuses.
*   **Rank (Internal Design Concept):** Asset cards can be internally classified as Orbital or Interstellar for design purposes. Orbital Assets might be designed to affect entire quadrants, while Interstellar Assets could be conceptualized with a broader impact. (Note: These "Rank" classifications are for design guidance and are not keywords or rules found in the `Players/Quantum Nexus Full Game Rules.md`. The actual scope and targets of an Asset's abilities must be explicitly stated in its card text.)

### 3. Asset Gameplay Fundamentals & Card Feel

**Deployment and Location:**
*   Assets are brought into play from a player's hand by taking the **'Deploy a Card' action** during their turn in the Activation Sequence (see `Players/Quantum Nexus Full Game Rules.md`, Section III.C.2).
*   Upon deployment, an Asset is placed into its controller's **Loadout Area** (FGR, Section V.D).
*   Assets in the Loadout Area are immune to direct attacks from enemy units. However, they can still be targeted and affected by card abilities or effects that specify Assets as valid targets (FGR, Section IV.B).

**Card Feel:**
*   **Malevolence:** Is the Asset inherently benevolent, malevolent, or neutral?
*   **Utility:**  Does the Asset prioritize utility, disruption, or a balance of both?
*   **Combat Role:** Assets have a Defense value but no Attack value by default. **Crucially, Assets inherently cannot perform the 'Declare an Attack' action**, even if an effect (e.g., from an Upgrade) grants them an Attack value. Their influence is through their abilities, not direct combat participation as attackers (FGR, Section IV.B).
*   **Impact:** Will the Asset's presence be primarily constructive, destructive, or neutral?

Translate these card feel axes into the Asset's design through its abilities. A benevolent Asset, for example, might provide healing or defensive buffs to allies, while a disruptive Asset could hinder opponents' actions or force them to discard cards.

### 4. Calculate Card Costs

*   **Base CP:** Multiply the Asset's total DP by 2 to determine its base CP cost.
*   **Stat Points:** Assets only have a Defense stat. Each point of Defense costs 0.5 CP. 
*   **Adjusted CP:** Subtract half the Asset's Defense cost from its Base CP to determine the Adjusted CP.
*   **Rarity Bonus AP:** Use the formula: Bonus AP = 0.8 \* (1 / Card Count) to calculate the bonus AP based on the Asset's rarity and card count.
*   **Total AP:** The Total AP available for designing the Asset's abilities is calculated as follows: Adjusted CP + (Adjusted CP \* Rarity Bonus AP). Remember that the AP cost of all abilities cannot exceed this Total AP pool.

### 5. Design Abilities

*   **Concept and Theme:** The Asset's abilities should align with its chosen theme, domain, and card feel. A Technology Asset, for instance, might have abilities that enhance other Technology units or disrupt opponents' technological infrastructure.
*   **Types of Abilities:**
    *   **Active Abilities:** These are abilities that a player must choose to use as their action during their turn in the Activation Sequence by taking the **'Activate an Active Ability' action** (FGR, Section III.C.2). The card's text will specify any Command Point (CP) costs, exhaust requirements, or other costs needed to use the ability.
    *   **Passive Abilities:** These abilities are always active and do not require being chosen as an action to use. Their effects apply as long as the Asset is in play and any specified conditions are met (FGR, Glossary definition for "Passive Ability").
    *   **Triggered Abilities (Interrupts):** Assets can also have abilities that trigger automatically in response to specific game events (e.g., "When an opponent plays an Event card..."). These are covered under "Triggered Abilities" in the FGR (Section VII.A).
*   **AP Costing for Design:** Determine the Ability Point (AP) cost of each ability using the relevant AP tables (e.g., from the `Designers/Quantum Nexus Ability Creation Mini-Guide.md` or more detailed internal Card Creation Guidelines if available). Ensure that the total AP cost of all abilities does not exceed the Asset's Total AP pool. If an ability has an activation cost (CP, exhausting, discarding cards, etc.), this is factored into its design AP cost and its overall balance.
*   **Terminology:** Ensure all ability text uses current terminology found in the `Players/Quantum Nexus Full Game Rules.md` (e.g., "Command Points," "Game Round," "Activation Sequence," "exhaust").

### 6. Integrate Keywords (Optional)

*   **Type:** Select keywords that enhance the Asset's strengths, mitigate potential weaknesses, or introduce unique mechanics.
*   **AP Costing for Design:** Refer to specific keyword AP costing tables (e.g., from internal Card Creation Guidelines) to determine the AP cost for each keyword. Remember that the effects of keywords must align with the `Players/Quantum Nexus Full Game Rules.md`.

### 7. Assign a Defense Stat

*   **Resilience:** The Asset's Defense stat determines how much damage it can withstand from effects that target it. As mentioned in Section 3, Assets are in the Loadout Area and cannot be directly attacked by units but can be affected by other card abilities.
*   **Balance:** The Defense stat should align with its CP cost, abilities, keywords, and overall role. A higher Defense makes the Asset more resilient but might mean less AP for abilities or a higher CP deployment cost.
*   **Impact:** An Asset with potent effects might have lower Defense to balance it, while a supportive Asset might have higher Defense to ensure it persists.

### 8. Craft Flavor Attributes

*   **Name:** Select a name that is not only evocative and memorable but also effectively conveys the Asset's theme and function within the game.
*   **Image:** Provide a detailed description that captures the Asset's visual identity. Use elements that are relevant to the Asset's domain, such as technological components, magical symbols, psionic emanations, or divine iconography.
*   **Flavor Text:** Use a concise and impactful quote or description that provides insights into the Asset's backstory, abilities, or significance within the Quantum Nexus universe.

### 9. Playtest and Iterate

*   **Playtesting:** Thoroughly test your Asset card against a variety of opponents and deck archetypes to observe its performance in actual gameplay scenarios, ensuring all interactions adhere to the `Players/Quantum Nexus Full Game Rules.md`. This will help you identify any strengths, weaknesses, or unexpected interactions.
*   **Iteration:** Based on playtesting feedback, be prepared to adjust the Asset's stats, abilities, keywords, CP cost, or even its core concept to achieve optimal balance and strategic depth. Iteration is crucial for creating an Asset card that is not only engaging and fun to play but also contributes meaningfully to the overall Quantum Nexus experience.

By following these steps and utilizing the resources provided (like this guide and the `Players/Quantum Nexus Full Game Rules.md`), you can design unique and compelling Asset cards that enrich the game's strategic possibilities and immerse players in its vibrant universe.
