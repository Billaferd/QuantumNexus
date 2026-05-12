# **Quantum Nexus: Mission Card Creation Guide**

## **Section 1: The Philosophy of the Strategic Contract**

Mission Cards represent the most innovative and strategically defining element of Quantum Nexus. They are not merely components shuffled into a player's deck; they serve as the foundational blueprint for a player's entire strategy. By selecting up to six Mission Cards before the game begins, a player enters into a "Strategic Contract." This contract dictates the very nature of their game plan before the first card is ever drawn. This pre-game act of strategic architecture is a cornerstone of the Quantum Nexus experience, actively rewarding system mastery and deep, deliberate planning.

This guide establishes a comprehensive framework for designing Mission Cards that are mathematically balanced, thematically resonant, and strategically compelling. It integrates the overarching design philosophies of Narrative-First Design and Player Agency to ensure that every Mission Card functions as a rich and purposeful addition to the game's broader ecosystem. The ultimate goal is to create Missions that are not just balanced in their mathematical power output, but also serve as compelling narrative and strategic anchors for any deck construction.

### **The Mission Card as a Three-Fold Engine**

Each Mission Card inherently dictates your chronological progression through the global Theater System. Rather than acting as individual, isolated objectives, a Mission provides a base economic income representing Theater Level 1, a passive advantage representing Theater Level 2, and a massive one-time payoff representing Theater Level 3\. These higher-tier abilities trigger automatically as the combined Supremacy Points shared between all players on the board increase. This mechanic dictates the chronological pacing of a player's overall strategy.

The foundational attribute of any Mission Card is its Deckbuilding Resource, quantified as Domain Points (DP). The DP value establishes the deck's technological ceiling. Opting for a high-DP Mission allows a player access to the most powerful and devastating cards within a specific domain, but this vertical power often demands heavy mechanical taxation. Conversely, the Economic Engine of the card is represented by its Command Point (CP) value. The CP value dictates the Mission's literal contribution to the player's per-round resource income during the Start of Round step. This dynamic creates a critical strategic tension: a player must decide whether to choose Missions that grant high per-round income to fund a wide array of actions, or to sacrifice their economy to pay for the sheer access to high-tier Theater abilities.

## **Section 2: The Design Framework**

### **The Strategic Contract and the Economy of Scale**

The construction of every Quantum Nexus deck is governed by a single, immutable, and strictly enforced constraint: every deck must contain exactly 6 Domain Points (DP) worth of Mission Cards. Furthermore, no single domain may accumulate more than 4 DP across a player's selected Mission suite. This fixed budget ensures that all players operate on a fundamentally level playing field regarding their overall strategic weight, and it forces multi-domain synergies. The diversity of the game stems not from having access to more resources than an opponent, but from how effectively a player chooses to allocate this strictly fixed budget.

To support this fixed budget, the baseline CP income provided by individual Mission Cards scales directly with their DP cost. Quantum Nexus employs a Direct Conversion Formula to ensure that the internal income capacity provided by a Mission is sufficient to support the tier of technology it unlocks. The established conversion rate dictates that one Domain Point is intrinsically equal to three Command Points. This ratio exists because higher DP Missions unlock correspondingly higher-tier main deck cards that demand massive CP investments to deploy.

### **The Core Trade-Off: Vertical vs. Horizontal Power**

Because every player possesses the exact same total budget of 6 DP, the core strategic decision lies in the balance between Concentration and Distribution. High DP Missions represent Vertical Power. A Mission costing 3 or 4 DP consumes half or more of your entire deck-building budget. The strategic gain of this approach is immense: you unlock the game's absolute most powerful, high-tech cards. However, the severe cost is that you possess fewer remaining slots for other Missions, placing all of your strategic focus into a singular path and relying heavily on fewer passive abilities and fewer Climax triggers to secure victory.

In contrast, Low DP Missions represent Horizontal Versatility. A Mission costing only 1 or 2 DP consumes very little of your total budget. The advantage here is that you can equip a wide array of them, outfitting your deck with numerous different Mission Objectives and Rewards. This makes your strategy highly flexible and exceptionally difficult for an opponent to disrupt. The downside to this horizontal spread is that you are strictly limited to low-tech, low-cost cards. You must secure your Frontline Supremacy through intricate synergy and tactical versatility rather than through raw, overwhelming technological superiority.

The resulting baseline archetype structure classifies Missions into four distinct tiers based on their DP cost. A Titan mission costs 4 DP, provides a base capacity of 12 CP, serves as the absolute tech ceiling, and occupies the vast majority (66 percent) of your deck strategy, granting access to the domain's ultimate units. A Major mission costs 3 DP, provides a base capacity of 9 CP, and functions as the standard core anchor for a deck's identity. A Minor mission costs 2 DP, yields a base capacity of 6 CP, and typically provides support or economy-focused utility challenges to support a larger strategy. Finally, a Basic mission costs 1 DP, yields a base capacity of 3 CP, and acts as filler that grants minimal tech access while allowing the player to slot in specific, highly niche utility effects.

| Mission Weight | Base CP Capacity | Role & Intent |
| :---- | :---- | :---- |
| Titan (4 DP) | 12 CP | The Tech Ceiling. Grants access to the domain's ultimate units. Occupies 66% of your deck strategy. |
| Major (3 DP) | 9 CP | The Core. A standard "Main" mission that anchors a deck's identity. |
| Minor (2 DP) | 6 CP | The Support. Often provides utility or economy-focused challenges to support a larger strategy. |
| Basic (1 DP) | 3 CP | The Filler. Grants minimal tech access but allows the player to slot in specific, niche utility effects. |

## **Section 3: Critical System Evaluations and Domain Identities**

Before outlining domain identities, it is paramount to address and correct several mechanical ambiguities regarding phase structures and combat persistence that must heavily inform your design process.

### **Critical Evaluation 1: The Timing of the Theater 3 Climax**

Theater 3 Climax abilities trigger precisely when the global board reaches 14 combined Supremacy Points. As dictated by the core rules, Supremacy Points are tallied exclusively during the Scoring Step. The Scoring Step strictly occurs immediately following the consecutive passes that end the Activation Sequence. Therefore, Climax abilities trigger when the action phase of the round is effectively over. Designing a Climax that grants an "immediate extra Action" fundamentally violates the game's phase structure. Any Climax intended to manipulate action economy must be written to affect the subsequent round, such as stating that during the next round's Activation Sequence, you may take two actions before passing.

### **Critical Evaluation 2: The "Opponent's Turn" Fallacy**

The Quantum Nexus core rules establish an Activation Sequence where players take single, alternating actions until all pass. There are no extended "turns" in the traditional card game sense. Designing a passive ability that references playing cards "during the opponent's turn" is mechanically invalid. Such abilities must be strictly phrased around the action system, for example stating that you may play Event cards as a direct reaction to an opponent resolving an action.

### **Critical Evaluation 3: The Mechanics of Healing**

The core rules state that units do not retain standard damage. An attack is either ineffective, results in Suppression, or completely destroys the unit. The only exception is the accumulation of permanent counters via the Impact keyword. Therefore, assigning a CP cost to "Healing" in a vacuum is illogical. In Quantum Nexus, "Healing" must be explicitly defined in card text as the removal of Impact counters or the removal of Suppression tokens.

### **Domain Identities and Token Generation**

Every Mission must strictly adhere to the thematic and mechanical identity of its corresponding domain. Furthermore, if a Mission dictates the creation of tokens, it must explicitly reference the standardized token statistics provided in the core rulebook to maintain mathematical integrity.

The Technology domain acts as the Blueprint of Industry, focusing on establishing rigid order, building resilient infrastructure, and asserting dominance through superior, calculated firepower. Escalation abilities in Theater 2 should involve deploying specific quantities of Assets, maintaining high defensive thresholds across the board, dealing persistent Impact damage, or heavily controlling specific territorial quadrants. Climax abilities in Theater 3 should provide a massive influx of resources, the systemic repair of damaged units by removing Impact counters, or devastating, symmetrical long-range bombardments. Token generation for Technology is restricted to the Construct, which possesses 1 Attack, 1 Defense, and no keywords, acting as mechanical infantry for holding ground.

The Magic domain performs the Arcane Ritual, representing the unlocking of forbidden knowledge, weaving complex sequences of spells, and fundamentally altering the fabric of reality. Escalation abilities should challenge the player to cast specific sequences of Event cards, manage a precise threshold of spells in their discard pile to fuel Arcane Recall, or maintain fragile units with high Attack but exceptionally low Defense. Climax abilities should grant the free casting of powerful spells directly from the discard pile, drastically alter unit positions through Strategic Re-routing, or heavily disrupt the standard rules of engagement. Token generation for Magic is restricted to the Golem, which features 2 Attack, 1 Defense, and no keywords, serving as magical infantry tailored for offensive assaults.

The Psionics domain initiates the Mind War, relying entirely on infiltrating the enemy's plans, subverting their will, and strictly controlling the flow of information. Escalation abilities should focus on forcing the opponent to discard cards from their hand, correctly predicting the opponent's subsequent actions, or ensuring that units with the Phantom keyword survive deep within enemy territory. Climax abilities should provide highly proactive shielding by stripping specific cards from the opponent's hand, temporarily seizing control of enemy units to disrupt their formation, or forcing the opponent to skip their next available action in the sequence. Token generation for Psionics is restricted to the Echo, which possesses 0 Attack, 1 Defense, and the Illusion keyword, meaning it immediately dies if targeted by any effect or attack.

The Divinity domain embarks on the Holy Crusade, defined by spreading faith, enduring immense hardship, and overwhelming unbelievers with righteous zeal. Escalation abilities should revolve around having units survive fatal damage through the Zeal keyword, intentionally sacrificing your own units to trigger Martyrdom effects, or overwhelming the board by controlling a massive phalanx of units. Climax abilities should manifest as literal divine interventions, such as rendering friendly units completely indestructible for a specific duration, executing mass resurrections of fallen units directly from the discard pile, or manifesting massive token swarms. Token generation for Divinity is restricted to the Spirit, which possesses 2 Attack, 2 Defense, and boasts both the Flying and Ethereal keywords.

Additionally, Neutral cards, which are not tied to specific DP constraints, can generate the Scrap token, representing improvised cover with 0 Attack, 1 Defense, and the Immobile keyword.

## **Section 4: The Costing Algorithms and Variance Modeling**

To accurately determine the final CP income of a Mission Card, you must calculate its precise mechanical market value based on the game's fundamental economy. Every passive and climax ability functions as a "Tax" that is assessed against the Mission's Base Capacity.

### **The Baseline and Variance Formula**

To allow for structural fluctuations in CP based on the strength and utility of the selected abilities while retaining a steady meta-average across a fixed deck budget, you must utilize the "Baseline \+ Variance" modifier formula.

First, determine the **Base CP Capacity** by multiplying the Domain Points (DP) by 3\. This establishes the raw, pre-tax power budget of the card.

Second, calculate the **CP Modifier**. The CP Modifier is equal to the Base CP minus the combined sum of the Tier 2 (Passive) tax and the Tier 3 (Climax) tax.

Finally, determine the **Final CP Income**, which is the value printed on the card and generated each round. The Final CP is equal to the Base CP plus the CP Modifier.

This structure dictates that abilities functioning perfectly "at budget" yield a modifier of zero, meaning the Final CP perfectly matches the Base CP. Flavor cards designed to significantly overshoot the base costs will produce a negative modifier, pulling the Final CP down as the player pays heavily for premium abilities. Cards intentionally undershooting the base costs will yield a positive modifier, generating surplus CP to account for a "neutral cards tax" and providing immense economic liquidity in exchange for weaker Theater effects.

Under the Zero-Floor rule, no Mission card may have a Final CP of less than zero. If the mathematical calculation results in a negative final income, the income is hard-capped at 0\. Furthermore, the absolute value of any negative ability functioning as a rebate cannot exceed the card's base CP capacity, meaning a card's maximum expanded internal budget is strictly capped at double its base allowance (DP multiplied by 6).

### **The Market Rate Baseline**

Before costing complex abilities, you must establish the intrinsic value of the atomic effects that constitute them. These values are firmly derived from the baseline costs of existing Event and Unit cards.

Inflicting 1 point of targeted damage holds an estimated market value of 1.0 CP, referencing the efficiency of standard bombardment cards. Removing 1 Impact counter, operating as Healing, is valued at 0.5 CP, as restorative effects are deliberately costed lower than destructive effects. Drawing a single card from the deck is valued heavily at 3.0 CP, reflecting the extreme importance of intellect gathering and hand advantage. Forcing a targeted discard from an opponent's hand demands a steep 9.0 CP due to the premium nature of precision thought extraction. Revealing hand information without discarding, mimicking basic mind scanning operations, is valued at 3.0 CP. Inflicting a Stun or Exhaust effect to shut down an active unit is valued at 3.0 CP. Generating a standard token with 1 Attack and 1 Defense stats, without keywords, costs 1.5 CP, establishing that generated tokens are inherently discounted compared to fully drafted 2 CP units. Finally, generating an economy of actions—the calculated premium value of executing an effect without expending one of your precious actions during the Activation Sequence—is valued at approximately 4.0 CP.

| "Atomic" Effect | Estimated Market Value (CP) | Source / Logic |
| :---- | :---- | :---- |
| Damage (1 Point) | 1.0 CP | Standard bombardment allows paying 1 CP per 1 Impact. |
| Healing (Remove 1 Impact) | 0.5 CP | Healing/repair is generally cheaper than raw damage. |
| Card Draw (1 Card) | 3.0 CP | Standard intellect gathering events cost roughly 3 CP per card. |
| Discard (Targeted) | 9.0 CP | Precision thought extraction is highly premium. |
| Hand Info (Reveal) | 3.0 CP | Basic mind scanning operations. |
| Suppress / Exhaust | 3.0 CP | Applying suppression or mental static to shut down a unit. |
| Token (1/1 stats) | 1.5 CP | Standard 1/1 units cost 2 CP; generated tokens are inherently discounted. |
| Action (Economy) | \~4.0 CP | The premium value of executing an effect without passing an action turn. |

### **Costing Novel Climaxes (The Output Tax)**

When inventing a new Theater 3 Climax, you must calculate its designated tax using a strict mathematical formula: the Climax Tax is equal to the Base Effect Value multiplied by the Scope Multiplier, plus any applicable Novelty Premium.

First, determine the Base Effect Value. Utility effects, such as moving a unit or swapping positions, command a base of 1 to 2 CP. Soft Control effects, including suppression or applying negative statistical modifiers, command a base of 3 to 4 CP. Hard Removal or Creation effects, such as outright destroying a unit or generating large tokens, command a base of 5 to 8 CP.

Second, apply the Scope Multipliers. If the effect targets a single unit, the multiplier is 1.0. If the effect targets two specific units, or utilizes a cleave mechanic, the multiplier is 1.5. If the effect impacts an entire Quadrant or operates as an Area of Effect, the multiplier increases drastically to 2.5. If the effect is completely Global, impacting all units on the board, the multiplier is set at 4.0.

Finally, assess the Novelty Premium. If the effect operates within standard parameters, the premium is 0 CP. If the effect bends core rules, such as ignoring Line of Sight, add a 1 CP premium. If the effect completely breaks fundamental game rules, such as granting absolute invulnerability, add a steep 3 CP premium.

### **Costing Novel Passives (The Engine Tax)**

Passives are inherently difficult to mathematically balance. You must determine their ongoing tax by calculating the Expected Value over a standard 5-Round game. The Passive Tax formula dictates that the Value per Trigger is multiplied by the estimated Triggers per Round, and that product is then multiplied by a Reliability Discount.

First, identify the Value per Trigger using the established Market Rate Baseline. Second, objectively estimate how often a typical deck will trigger this effect during a single round. If it is hard-capped to once per round, the multiplier is 1.0. If it is likely to trigger 1 to 2 times, the multiplier is 1.5. If it relies on uncapped swarm tactics and triggers frequently, the multiplier is 3.0 or higher.

Third, apply a Reliability Discount based on how guaranteed the trigger is to resolve. If the trigger is absolutely guaranteed (e.g., Start of Round), the multiplier remains 1.0. If it relies on a common occurrence (e.g., playing a Unit card), the multiplier is 0.8. If it relies on an uncommon occurrence (e.g., specific keywords), the multiplier drops to 0.6. If it is dependent on the opponent taking a specific action, the multiplier is reduced to 0.4. Always round the final CP tax up to account for the psychological deterrence value the passive exerts on the opponent.

## **Section 5: The Component Database**

To assemble a final Mission Card, you must use the database below to apply the ultimate Baseline \+ Variance formula, establishing the base capacity and evaluating the precise CP tax values for your chosen Theater 2 Passives and Theater 3 Climaxes.

### **Passive Ability Tax Values**

Passive abilities located in Theater 2 are categorized into tiers based on their game impact.

Tier 0 passives are focused on thematic flavor and formatting, possessing negligible mechanical impact and carrying a 0 CP tax. Examples include granting Construct tokens \+1 Health, giving Spirit tokens the Flying keyword, or stipulating that a Leader counts as a Construct, all typically rooted in the Technology domain.

Tier 1 passives provide minor economic and utility advantages. Increasing your maximum hand size by 1 is a Magic or Technology utility that incurs a 1.5 CP tax. Reducing the cost of the first Asset deployed each round by 1 CP is a Technology utility that carries a 2.0 CP tax. Altering the core Mulligan rule to grant 6 cards instead of 5 is a neutral utility that carries a highly efficient 1.0 CP tax.

Tier 2 passives fundamentally alter combat math, providing a significant board advantage. Granting all Front Row units an automatic \+1 Defense is a Divinity or Technology trait that costs 3.0 CP. Giving Far Range units \+1 Attack is a Technology trait that costs 3.0 CP. Forcing all enemy units to enter play Suppressed and exhausted unless the opponent pays an additional 1 CP is a massive Psionics tempo advantage costing 3.5 CP.

Tier 3 passives represent rule-breaking, game-warping power. Allowing a player to play Event cards as a reaction to an opponent's action, while costing an extra 1 CP to do so, is a Magic domain trait incurring a severe 5.0 CP tax. Passively looking at any card an opponent draws outside the Start of Round step is a Psionics trait that commands a steep 4.0 CP tax.

| Passive Effect (Theater 2\) | CP Tax | Domain Fit | Tier Classification |
| :---- | :---- | :---- | :---- |
| Your Construct tokens have \+1 Defense. | 0 CP | Technology | Tier 0: Flavor |
| Your Leader counts as a Construct. | 0 CP | Technology | Tier 0: Flavor |
| Maximum hand size is increased by 1\. | 1.5 CP | Magic / Tech | Tier 1: Utility |
| The first Asset deployed each round costs 1 less CP. | 2.0 CP | Technology | Tier 1: Utility |
| Mulligan grants 6 cards instead of 5\. | 1.0 CP | Neutral | Tier 1: Utility |
| Front Row units have \+1 Defense. | 3.0 CP | Divinity / Tech | Tier 2: Combat Math |
| Far Range units have \+1 Attack. | 3.0 CP | Technology | Tier 2: Combat Math |
| Enemy Units enter play Suppressed unless opponent pays 1 CP. | 3.5 CP | Psionics | Tier 2: Combat Math |
| Look at any card an opponent draws (except Start of Round). | 4.0 CP | Psionics | Tier 3: Rule Breaking |
| Play Event cards as a reaction to an opponent's action (+1 CP). | 5.0 CP | Magic | Tier 3: Rule Breaking |

### **Climax Payoff Tax Values**

Climax payoffs located in Theater 3 represent the culmination of the game when combined Supremacy reaches 14\.

Tier 1 Climaxes provide minor value and simple efficiency. Drawing 1 card is a neutral trait that carries a minimal 1.0 CP tax. Removing up to 3 Impact counters from a unit or Asset acts as healing for the Technology or Divinity domains and costs 1.0 CP. Creating a single neutral Scrap token with 0 Attack, 1 Defense, and the Immobile keyword for cover incurs a mere 0.5 CP tax.

Tier 2 Climaxes generate significant mid-game tempo and creation swings. Generating two 1/1 Construct tokens for the Technology domain demands a 3.0 CP tax. Dealing a flat 3 damage to a target unit bypasses normal combat mechanics for the Magic or Technology domains and costs 2.5 CP.

Tier 3 Climaxes offer major value and hard removal. The outright destruction of a target unit as a neutral action carries a heavy 5.0 CP tax. Creating an overwhelming board state by generating three 2/2 Spirit tokens possessing the Flying and Ethereal keywords for the Divinity domain incurs a steep 6.0 CP tax.

Tier 4 Climaxes represent the game-ending Bombs. Initiating a total board wipe that destroys all units in the Front Row for the Technology or Magic domains commands a massive 8.0 CP tax. Granting absolute invulnerability, ensuring your units take zero damage and cannot be destroyed during the current sequence for the Divinity or Technology domains, costs 8.0 CP. Finally, altering the fundamental flow of the subsequent round by granting the player the Temporal Shift ability to take two consecutive actions on their first turn next round incurs the highest penalty of a 9.0 CP tax for the Magic domain.

| Climax Effect (Theater 3\) | CP Tax | Domain Fit | Tier Classification |
| :---- | :---- | :---- | :---- |
| Create one Scrap token (0/1 Immobile). | 0.5 CP | Neutral | Tier 1: Minor Value |
| Draw 1 Card. | 1.0 CP | Neutral | Tier 1: Minor Value |
| Remove 3 Impact Counters from target Unit/Asset. | 1.0 CP | Tech / Div | Tier 1: Minor Value |
| Deal 3 Damage to target Unit. | 2.5 CP | Magic / Tech | Tier 2: Tempo Swing |
| Create two 1/1 Construct tokens. | 3.0 CP | Technology | Tier 2: Tempo Swing |
| Destroy target Unit. | 5.0 CP | Neutral | Tier 3: Major Removal |
| Create three 2/2 Spirit tokens (Flying, Ethereal). | 6.0 CP | Divinity | Tier 3: Major Removal |
| Board Wipe: Destroy all Units in the Front Row. | 8.0 CP | Tech / Magic | Tier 4: The "Bomb" |
| Invulnerability: Your Units cannot be destroyed this sequence. | 8.0 CP | Divinity / Tech | Tier 4: The "Bomb" |
| Temporal Shift: Take two consecutive actions on your first turn next round. | 9.0 CP | Magic | Tier 4: The "Bomb" |
