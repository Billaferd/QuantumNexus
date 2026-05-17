# **Quantum Nexus: Core Set Design & Mechanics Introduction**

This document provides a holistic, rigorous overview of the design principles, core mechanics, and strategic direction for the First Core Set of the Quantum Nexus Trading Card Game. It synthesizes the foundational rules, high-level design philosophy, and the specific architectural blueprint for the 264 cards that will establish the game's mechanical and narrative identity.

This blueprint reflects the strategic decision to launch with four primary domains: Technology, Magic, Psionics, and Divinity. The Biology and Entropy domains are deliberately reserved for future major expansions to prevent mechanical dilution and ensure a "Deep and Narrow" launch metagame characterized by intensely focused faction identities.

## **Part I: Core Game Mechanics**

A precise understanding of the game's foundational rules and victory conditions is essential to contextualize the design philosophy of the Core Set.

### **1.1 The Objective: Frontline Supremacy and Theater Escalation**

The ultimate objective in Quantum Nexus is the total systemic collapse of the opponent's military infrastructure. This is not achieved through a simple, binary board wipe, but rather through the calculated accumulation of territorial dominance over time, a concept known as Frontline Supremacy.

The game concludes immediately when a player accumulates ten (10) Supremacy Points during a Scoring Step. Additionally, a player is instantly eliminated if they are forced to draw from an empty deck, a condition colloquially known as "decking out." If multiple players reach the ten-point threshold simultaneously, the player with the highest overall score is declared the victor; a perfect tie under these conditions results in a draw.

Supremacy Points are generated exclusively during the Scoring Step. A player earns exactly one Supremacy Point for every quadrant they occupy within the neutral Contested Zone (Row 3) during the Scoring Step. Players may also execute a 'Secure Objective' action during their turn to claim player-placed Strategic Directives for immediate 3-point bursts, forcing lateral expansion and flanking. 

Furthermore, the accumulation of these points serves a dual purpose: it acts as a pacing mechanism known as Theater Escalation. By calculating the Combined Supremacy Score (the sum of all players' current Supremacy Points), the game dynamically shifts through three distinct phases.

The game begins at Theater Level 1: Logistics. During this phase, which lasts while the Combined Supremacy Score is between zero and five, all players receive a standardized universal baseline salary of 15 Command Points (CP) at the start of every single round, completely divorced from Mission Card selection. The game enters Theater Level 2: Escalation the exact moment the combined score reaches six (6) points. At this threshold, all passive abilities printed on players' Mission Cards become available, provided the player pays the dynamic runtime CP upkeep cost associated with the ability during their Activation Sequence, fundamentally altering the strategic landscape. Finally, when the combined board state reaches ten (10) points during the Scoring Step (provided no player has achieved an individual 10 SP victory first), the game enters Theater Level 3: Climax. This detonation threshold allows the player to manually execute the massive, one-time rewards printed on the Mission Cards by sacrificing the required runtime CP cost as a proactive action during the *following* round's Activation Sequence, often dictating the absolute conclusion of the match.

### **1.2 Deck Construction: The Strategic Foundation**

Deck construction in Quantum Nexus is an exercise in strict economic engineering, governed by a rigid set of mathematical constraints that force deliberate, competitive choices.

The paramount constraint is the 200 Requisition Point (RP) Budget. The main deck—which includes all Unit, Leader, Asset, Event, Upgrade, and Terrain cards—must contain exactly 40 to 60 physical cards with a maximum total RP value of 200. The mathematical cost dictates the power density, while the 40 to 60 card limit mathematically bounds the physical volume to ensure competitive consistency. Within this 200 RP limit, players are restricted to a maximum of 25 RP dedicated to Leader subtype cards, ensuring that powerful, game-altering personalities do not oversaturate the battlefield while maintaining isolation from the live runtime economy.

Separate from the main deck budget is the Mission Roster. Players select up to six Mission Cards prior to the game. These missions must adhere to a strict Domain Point (DP) requirement: the combined DP cost of a player's chosen missions must equal exactly 6 DP, and no more than 4 DP may be allocated to any single domain. This enforces multi-domain strategy and prevents monolithic, homogenous builds.

Finally, players may bring a Sideboard to competitive matches. The Sideboard represents a reserve cache of adaptive tools and is governed by two simultaneous constraints: it may contain a maximum of 10 physical cards, and the combined RP value of those cards must not exceed 40 RP. Furthermore, the cards within the sideboard must legally align with the domain restrictions established by the player's primary 6 DP Mission roster.

### **1.3 Spatial Capacity, Impassable Frontlines, and Native Traits**

To eliminate cognitive overload and maintain board clarity across the 5x3 grid, spatial geometry is governed by a strict, visual capacity system combined with native unit behaviors.

Every quadrant on the battlefield is governed by a strict limit of 3 Weight. A unit's designated physical size determines its Weight: Small Units possess 1 Weight, Large Units possess 2 Weight, and Massive Units possess 3 Weight. 

Crucially, opposing units may never mix or co-occupy the same quadrant under any circumstances, rendering enemy-occupied spaces strictly impassable. Because these enemy quadrants act as physical walls, a unit's size classification grants it an inherent Native Trait to interact with the grid:
* **Evasion (Small Units):** Agile flankers that are the only entities permitted to move diagonally. Crucially, friendly units and friendly-occupied quadrants never obstruct your own physical Line of Sight.
* **Pushback (Large Units):** Linebreakers that can force a defending unit to retreat into an empty adjacent quadrant upon inflicting an Impact counter, or deal 1 additional Impact if no empty quadrant exists.
* **Quadrant Damage (Massive Units):** Overwhelming forces whose Attack value is simultaneously compared against the Defense of up to two chosen units in the target quadrant, preserving the viability of infantry formations against heavy armor.

### **1.4 Standardized Token Statistics**

To maintain board clarity and ensure predictable mathematical interactions, the Core Set heavily utilizes standardized tokens across the four domains. It is strictly mandated that effects generating these specific tokens adhere flawlessly to the established combat statistics and keywords.

The Technology domain utilizes the Construct, which serves as a basic mechanical infantry unit possessing Small Size (1 Weight), 1 Attack, 1 Defense, and no inherent keywords. The Divinity domain utilizes the Spirit, representing highly evasive manifestations of pure faith with Small Size (1 Weight), 2 Attack, 2 Defense, and both the Flying and Ethereal keywords. The Psionics domain creates the Echo, a fragile psychic projection meant to confuse enemies; it has Small Size (1 Weight), 0 Attack, 1 Defense, and the updated Illusion keyword, meaning it acts as a targeting tax that forces the attacker to redirect their attack without consuming their action. Echo tokens uniquely enter play ready, but cannot move or act on the turn they enter. The Magic domain generates the Golem, an aggressive magical construct boasting Small Size (1 Weight), 2 Attack, 1 Defense, and no keywords. Finally, Neutral card effects can create Scrap, representing improvised static cover with Small Size (1 Weight), 0 Attack, 1 Defense, and the Immobile keyword.

The following table serves strictly as an illustrative summary of the token statistics described above.

| Token Designation | Affiliated Domain | Size (Weight) | Combat Statistics | Range | Innate Keywords | Tactical Role |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Construct | Technology | Small (1 Weight) | 1 Attack / 1 Defense | Range 1 | None | Ground holding and attritional infantry. |
| Spirit | Divinity | Small (1 Weight) | 2 Attack / 2 Defense | Range 1 | Flying, Ethereal | Highly evasive, resilient physical manifestations. |
| Echo | Psionics | Small (1 Weight) | 0 Attack / 1 Defense | Range 1 | Illusion | Fragile decoys that force attack redirection. Enters ready, cannot act/move on entry turn. |
| Golem | Magic | Small (1 Weight) | 2 Attack / 1 Defense | Range 1 | None | Offensively slanted magical constructs. |
| Scrap | Neutral | Small (1 Weight) | 0 Attack / 1 Defense | Range 1 | Immobile | Improvised, static defensive cover. |

## **Part II: Phase Structure and Action Economy**

Quantum Nexus relies on a highly kinetic, alternating action economy that rewards spatial awareness and tempo manipulation. A standard Game Round is divided into structured sequences.

The Start of Round Step represents a simultaneous reset for all players. First, players ready all exhausted cards, clear temporary effect tokens, and reset their Command Point pools to zero. Following this refresh, players secure their Income by gaining a standardized base salary of exactly 15 Command Points (CP), plus any Command Points banked via the Reserve system. At the end of the previous round, players may designate up to 5 unspent CP as Reserve, carrying it forward for a strict maximum ceiling of 20 CP in a single round. 

Third, players execute their Draw phase; every player automatically draws exactly two (2) cards from their deck. Additionally, the Reinforcement Draw mechanic dictates that if a player trails their opponent by 4 or more Supremacy Points at the start of the Draw phase, they draw one extra card to help stabilize their board. A player's default Maximum Hand Size is 5. At the end of the round, if you hold more cards than your Maximum Hand Size, you must discard down to the limit.

The game then transitions to the Activation Sequence. This is the core tactical phase where players take alternating, single actions. During the Activation Sequence, Initiative operates on a strict alternation mechanic: the Initiative token simply passes back and forth between players at the start of every new round, allowing for predictable tactical forecasting. 

A player may only perform one legal action per turn—such as deploying a card, moving a unit (orthogonally, or diagonally if Small), executing a Tactical Advance (moving and attacking with a strict -1 Attack penalty), attacking with a unit, activating a distinct ability, executing an unlocked Theater 3 Climax, or utilizing the **Draw Intel** action (spending exactly 3 CP to draw 1 card). Action parity is strictly enforced: secondary units deployed via the Swarm keyword enter exhausted, and Horde attacks cannot utilize units deployed in the same round. Furthermore, units utilizing the Skirmisher keyword to reposition after an attack remain exhausted and cannot be readied for the remainder of the round. Claiming a Strategic Directive token (which are restricted exclusively to Row 3) via the 'Secure Objective' action requires the unit to have begun the Game Round already occupying the Contested Zone, preventing Turn 1 deployment exploits.

Combat fluidity within this sequence is fiercely maintained via the **Momentum Rule**: if an attacking unit completely clears a target quadrant of all enemy units, it may immediately move into that quadrant as part of the same Activation at no additional CP cost, preventing static gridlock.

The strategic pinnacle of this phase revolves around the "Pass" action. When a player possesses no profitable actions or wishes to force the opponent's hand, they may pass (or safely bank up to 5 remaining CP into their Reserve). If all players pass consecutively, the Activation Sequence immediately ends. 

Once the Activation Sequence concludes, the game immediately enters the Scoring Step. Supremacy Points are tallied, Theater Escalation is checked based on the 6 and 10 Combined Supremacy thresholds, and the Initiative token passes to the opposing player to ensure strict alternation for the subsequent round.

## **Part III: Design Philosophy \- Interactive Duality**

The Core Set is built upon the foundational philosophy of "Interactive Duality" and horizontal design. We do not design isolated threats; we engineer an ecosystem of corresponding answers operating dynamically across the fluid frontline. 

Every potent strategy introduced in this set is matched with a distinct counter-measure available within the game's broader economy. If the Magic domain presents an oppressive, non-interactive combo sequence (a Threat), the Psionics domain is supplied with the exact hand disruption and action-denial tools required to dismantle it (the Answer). The strict action parity enforced across swarm and horde mechanics prevents unanswerable burst-turns. This philosophy ensures that the metagame remains a dynamic puzzle rather than a static race. Balance is not merely about adjusting RP drafting costs and CP deployment costs; it is about ensuring that a player's agency is preserved through comprehensive sideboard options and diverse strategic responses to the prevailing Threat Matrix.

## **Part IV: The Domains and Their Identities**

The four launch domains are defined by strict mechanical boundaries and narrative themes, ensuring a deep, highly asymmetrical competitive environment.

### **4.1 Technology**

The Technology domain represents absolute, entrenched defensive superiority and systemic efficiency. It seeks to establish an unbreakable fortress, utilizing heavy armor and relentless, systematic advancement. Technologists employ the Impact keyword to represent precise, persistent damage accumulation, distributing damage counters that inevitably breach a target's printed Defense threshold.

Its primary threats involve the gradual accumulation of unassailable value. It utilizes heavy fortifications and Area-of-Effect artillery to punish aggressive swarm strategies, perfectly complementing the native Quadrant Damage trait of their Massive units (which is strictly capped at targeting a maximum of two units per attack to prevent geometry invalidation). Furthermore, their Range 3+ artillery is never blinded by their own heavily fortified Vanguards, as friendly units do not obstruct Line of Sight. Conversely, Technology is highly susceptible to "Non-Destruction" removal; bouncing an expensive, heavily armored unit back to a player's hand via Magic completely negates the immense CP investment required to deploy it. Its Mission Cards heavily reward controlling specific quadrant geometry and generating logistical superiority.

### **4.2 Magic**

Magic is the domain of volatile energy, complex synergy, and explosive tempo manipulation. It relies heavily on combining specific spell sequences to generate overwhelming, sudden advantages rather than relying on resilient board presence. The Arcane Recall mechanic is central to its identity, allowing players to cast spells from their graveyard, effectively turning their discard pile into a secondary, highly dangerous hand. The newly implemented up to 5 CP Reserve allows them to safely bank resources for massive Arcane Recall turns.

Magic players utilize powerful "Bounce" and transformational effects to completely bypass the defensive armor and destruction-triggered abilities of Technology and Divinity. However, because Magic relies so heavily on specific card combinations and graveyard access, it is inherently vulnerable to hand disruption, targeted discard, and graveyard-exile effects—tools heavily utilized by Psionics.

### **4.3 Psionics**

Psionics embodies the pinnacle of control, psychological warfare, and action denial. This domain does not seek to out-muscle the opponent; it seeks to systematically remove the opponent's capacity to participate in the game. It utilizes hand disruption to strip key pieces before they can be played and leverages the Synaptic Mark keyword to lock down enemy units, exhausting them and actively denying their participation in the alternating action sequence. 

Psionics acts as the natural predator to Magic's combo strategies by destroying the necessary components before execution. They fully exploit the native Evasion trait of Small units, sliding diagonally past impenetrable enemy walls to strike high-value assets. They also utilize the updated Illusion keyword to force attack redirections rather than locking out actions, and employ Skirmisher hit-and-run tactics (which now strictly leave the unit exhausted and unreadyable for the rest of the round to prevent infinite kiting). However, Psionics relies heavily on expensive, precise, single-target removal. This precision makes the domain wildly inefficient when facing the overwhelming numbers and highly redundant token-generation of a Divinity swarm strategy.

### **4.4 Divinity**

Divinity is the domain of relentless attrition, inevitable scale, and the terrifying resilience of the horde. It utilizes overlapping synergy to turn every loss into an advantage. Units in this domain frequently possess the Zeal keyword, which strictly triggers only after the printed base Defense of their Phalanx formations has been completely breached by accumulated Impact counters. They also rely on the Martyrdom keyword, which triggers powerful effects upon their inevitable death. Furthermore, their units grow stronger through mechanics like Adapt, which is strictly hard-capped to trigger only the first time a unit survives combat each Game Round to prevent infinite mathematical scaling.

Divinity thrives in long, grinding conflicts. They organize their units into Phalanx formations, gaining immense statistical survival thresholds through spatial adjacency while perfectly managing the 3-Weight quadrant capacity limit with defensive Phalanx lines and offensive Horde swarms. By swarming the board with Spirit tokens, Divinity easily overwhelms the precise, single-target defenses of Psionics. Their major weakness, however, is mass-damage artillery; a single, well-placed Technology board-wipe can decimate a heavily invested Phalanx in a single action.

## **Part V: Metagame Archetypes (The Quad-Cycle)**

The mechanical interplay of these four domains is mathematically engineered to foster four distinct, high-level metagame archetypes. These strategies rely on pairing specific domains to cover inherent weaknesses.

The Siege archetype represents the ultimate control strategy, locking down the board and starving the opponent of resources. It pairs the impenetrable defensive walls of Technology with the relentless hand disruption and action-denial of Psionics to create a suffocating board state.

The Crusade archetype is a midrange strategy built on resilient, inevitable advancement. It combines the persistent, undying nature of Divinity's Zeal keyword with the heavy Armor and combat efficiency of Technology, creating an army that simply refuses to yield ground.

The Storm archetype is a pure combo engine. It seeks to draw rapidly through the deck to assemble specific spell sequences, casting them repeatedly. It utilizes Magic's Arcane Recall for recursion and relies on Psionics to stall the opponent and protect the combo pieces until detonation.

Finally, the Swarm archetype is a blistering aggressive strategy. It seeks to flood the board with cheap units and bypass defensive lines entirely. It utilizes Divinity's highly evasive Spirit tokens for raw numbers while leveraging Magic's precise removal and "Bounce" effects to clear away any heavy blockers that Technology might deploy.

The following table summarizes these intended launch archetypes, serving strictly to illustrate the relationships detailed above.

| Archetype | Core Philosophy | Primary Domain Pairings |
| :---- | :---- | :---- |
| The Siege (Control) | Lockdown the board and deny resources. Uses Tech's walls and Psi's disruption. | Technology / Psionics |
| The Crusade (Midrange) | Resilient units that advance up the board. Uses Div's Zeal and Tech's Armor. | Divinity / Technology |
| The Storm (Combo) | Dig for specific spells and cast them repeatedly. Uses Mag's Recall and Psi's stall. | Magic / Psionics |
| The Swarm (Aggro) | Flood the board with tokens and bounce blockers. Uses Div's spirits and Mag's removal. | Divinity / Magic |

## **Conclusion**

The First Core Set for Quantum Nexus is not merely a collection of mathematically balanced game pieces; it is the forging of the game's intellectual and strategic soul. By committing to a four-domain launch architecture, we ensure deep, meaningful strategic options and razor-sharp identities for every faction.

The integrated "Quad-Cycle" metagame ensures that every constructed deck possesses a natural predator within the ecosystem, while the strict sideboard parameters guarantee that players have the tools to adapt and survive. Supported by a dynamic escalation system tied intrinsically to territorial control and fiercely fluid combat mechanics, this design establishes a powerful, highly interactive foundation that will allow the Quantum Nexus platform to thrive, scale, and evolve.