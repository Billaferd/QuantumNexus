# **Quantum Nexus: A Beginner's Guide to Ability Creation**

Welcome to the exciting world of Quantum Nexus ability creation! This guide will walk you through the basics of designing abilities for your Quantum Nexus cards. Don't worry; it's easier than it looks. We'll start simple and focus on the core concepts, so you can start creating your own abilities in no time.

## **What is an Ability?**

In Quantum Nexus, abilities are the special powers or actions that your cards can perform. They're what make your units attack, your assets provide benefits, and your events shake up the game. Think of them as the "verbs" of your cards - they describe what the card *does*.

## **The Building Blocks of Abilities**

Every ability is made up of four key parts:

1.  **Effect:** What the ability actually *does*. Examples: Deal damage, draw cards, boost a unit's stats.
2.  **Target:** *Who* or *what* the ability affects. Examples: A unit, a player, a quadrant of the battlefield.
3.  **Trigger:** *When* the ability happens. Examples: When a unit is attacked, at the start of your turn, when you pay a cost.
4.  **Condition:** Any extra rules or requirements for the ability.  Example: "If you have less than 5 CP." We won't worry too much about conditions in this beginner's guide.

## **The Ability Point (AP) System**

To keep things balanced, Quantum Nexus uses an Ability Point (AP) system. Each part of an ability has an AP cost, and the total cost tells you how powerful the ability is. Stronger abilities cost more AP.

## **AP Tables**

### **Effects**

| Effect                    | AP Cost (Player) | AP Cost (Opponent) | Notes                                                                                       |
| :------------------------ | :--------------- | :---------------- | :------------------------------------------------------------------------------------------ |
| Deal 2 Damage             | -2                | 2                  | Reduces a unit's Defense.                                                                 |
| Heal 2                    | 2                 | -2                 | Restores a unit's Defense.                                                                |
| Boost Attack by +1        | 2                 | -2                 | Makes a unit stronger offensively.                                                       |
| Reduce Attack by -1       | -2                | 2                  | Makes a unit weaker offensively.                                                         |
| Draw 1 Card               | 2                 | -2                 | Get an extra card.                                                                      |
| Discard 1 Card            | -1                | 1                  | Lose a card. For the opponent, this means you get to choose a card for them to discard |
| Destroy a Card            | -4                | -6                 | Remove a card from the game.                                                               |
| Gain 2 CP                 | 2                 | -2                 | Get extra resources.                                                                   |
| Grant a Keyword (Simple) | 2                 | -2                 | Give a unit a special ability (like Flying or First-Strike).                              |
| Remove a Keyword          | -2                | 2                  | Take away a special ability.                                                             |

### **Triggers**

| Trigger                         | AP Cost (Player) | AP Cost (Opponent) | Notes                                                                                                                                             |
| :------------------------------ | :--------------- | :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| When this unit is attacked     | 2                 | -2                 | Activates when something attacks this unit.                                                                                                   |
| At the start of your turn      | 2                 | -2                 | Activates every time your turn begins.                                                                                                        |
| Pay 2 CP                       | -1                | 1                  | You must spend 2 CP to activate this ability.                                                                                                 |
| Activate this ability | 1                 | -1                 | Triggered by activating the card's own ability (usually with a tap or exhaust mechanic). |
| When a unit is deployed | 1                 | -1                 | Activates when any unit enters the battlefield. |
| When this unit attacks     | 2                 | -2                 | Activates when this unit is declared as an attacker. |

### **Targets**

| Target                | AP Cost (Player) | AP Cost (Opponent) | Notes                                                                   |
| :-------------------- | :--------------- | :---------------- | :---------------------------------------------------------------------- |
| Any Unit              | 2                 | -2                 | Can be any unit on the battlefield.                                   |
| This Unit             | 1                 | -1                 | Refers to the card that has this ability.                               |
| Any Quadrant          | 2                 | -2                 | Affects an entire section of the battlefield.                            |
| Player (Self)         | 1                 | N/A                 | Affects you                                                              |
| Opponent             | N/A                 | -1                 | Affects your opponent                                                   |

**Important Notes about AP Costs:**

*   **Positive and Negative:** A positive AP cost is generally *good* for the player using the ability. A negative AP cost is generally *bad* for the player using the ability (but good for their opponent!).
*   **Player vs. Opponent:** Some effects have different costs depending on whether they target you or your opponent. For example, dealing damage to your opponent is good for you (positive AP cost), but dealing damage to yourself is bad (negative AP cost).

## **Creating Your First Ability**

Let's create a simple ability together, step-by-step:

### **Example 1: "Strike"**

1.  **Effect:** Deal 2 damage. (From the Effects table, this costs **-2 AP (Player)** and **2 AP (Opponent)**)
2.  **Target:** Any Unit. (From the Targets table, this costs **2 AP (Player)** and **-2 AP (Opponent)**)
3.  **Trigger:** Pay 2 CP. (From the Triggers table, this costs **-1 AP (Player)** and **1 AP (Opponent)**)

**Total AP Cost:**

*   **Player Perspective:** -2 + 2 - 1 = **-1 AP**
*   **Opponent Perspective:** 2 - 2 + 1 = **1 AP**

**How to Write the Ability:**

"Pay 2 CP: Deal 2 damage to any unit."

### **Example 2: "Battle Cry"**

1.  **Effect:** Boost Attack by +1. (From the Effects table, this costs **2 AP (Player)** and **-2 AP (Opponent)**)
2.  **Target:** This Unit. (From the Targets table, this costs **1 AP (Player)** and **-1 AP (Opponent)**)
3.  **Trigger:** When this unit is attacked. (From the Triggers table, this costs **2 AP (Player)** and **-2 AP (Opponent)**)

**Total AP Cost:**

*   **Player Perspective:** 2 + 1 + 2 = **5 AP**
*   **Opponent Perspective:** -2 - 1 - 2 = **-5 AP**

**How to Write the Ability:**

"When this unit is attacked, it gets +1 Attack."

### **Example 3: "Orbital Laser"**

1.  **Effect:** Deal 2 damage. (From the Effects table, this costs **-2 AP (Player)** and **2 AP (Opponent)**)
2.  **Target:** Any Quadrant. (From the Targets table, this costs **2 AP (Player)** and **-2 AP (Opponent)**)
3.  **Trigger:** Activate. (From the Triggers table, this costs **1 AP (Player)** and **-1 AP (Opponent)**)

**Total AP Cost:**

*   **Player Perspective:** -2 + 2 + 1 = **1 AP**
*   **Opponent Perspective:** 2 - 2 - 1 = **-1 AP**

**How to Write the Ability:**

"Activate: Deal 2 damage to any quadrant."

**Tips for Beginners:**

*   **Start Small:** Don't try to create overly complicated abilities at first. Stick to simple effects and triggers.
*   **Use the Tables:** Keep the AP tables handy and refer to them often.
*   **Think About Balance:** If an ability has a very high AP cost, it should have a powerful effect. If it has a low AP cost, the effect should be less powerful. If an ability has a negative AP cost for you, it should provide a significant advantage to make up for that.
*   **Playtest!:** The best way to see if your abilities work well is to playtest them. Create some cards with your abilities and try them out in a game.

## **Creating Keywords (Simple)**

Keywords are basically shorthand for abilities. For example, the keyword "Flying" might mean "This unit can't be blocked by units without Flying."

To create a simple keyword:

1.  **Write out the ability:** Figure out what you want the keyword to do.
2.  **Calculate the AP cost:** Use the tables to find the AP cost of the ability.
3.  **Give it a name:** Choose a cool and descriptive name for your keyword.

### **Example:**

Let's say you want to create a keyword called "Shielded" that gives a unit +2 Defense.

1.  **Ability:** This unit gets +2 Defense. (This is similar to boosting a stat, so we can use that as a guide).
2.  **AP Cost:** Using the "Boost Stats" entry and the "This Unit" target you would have 2 + 2 + 1 + 1 = **6 AP**
3.  **Name:** Shielded

Now, whenever you put "Shielded" on a card, it means that unit gets +2 Defense. You would add 6 to that card's total AP cost for its abilities.

**You're Ready to Create!**

You now have the basic knowledge to start creating your own abilities for Quantum Nexus. Experiment, have fun, and don't be afraid to try new things! Remember that playtesting is crucial, so try out your creations and see how they work in action. Good luck, and have fun designing!
