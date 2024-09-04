# Teamfight Tactics Reddit Webscraper

## Overview

### I got tired of constantly checking the TFT meta via sites like r/CompetitiveTFT, so I created a script that summarizes the current patch for me using player opinionated data pulled from the "Daily Discussions".

### This project can potentially help game devs gain a different perspective on how to better balance the game. I debated using Riot's API, but frankly, I assumed that both players and devs regularly check that data through websites like Mobalytics.

### *"But numbers don't lie!"*

### From my perspective, a well-balanced game is fun to play. This does not necessarily mean everything has to be perfectly balanced. If everything is stale, player retention naturally dips. By using player opinions (Reddit comments, in this case) as grounds for deciding what to buff/nerf, game balancers can more optimally create fresh changes that will greatly appease the player base for a couple patches.

## Sample Summary

### I didn't have an OpenAPI key on hand, so to simulate the tokenization process found in my script, I broke the comments into chunks manually and fed them to a model online. This is the result:



**Patch Summary for 14.17**

- Veigar 2 Buff: Veigar 2 is now extremely stable, possibly too much so, which has led to some frustration among players.

- 3-Cost vs. 4-Cost Champions: There's a noticeable disparity in the risk/reward of rerolling for 2-star 3-cost champions versus 2-star 4-cost champions. Hitting 2-star 3-costs feels much more reliable and stable, while investing in reaching level 8 for 4-costs doesn’t always pay off.

- Ezreal Targeting Issues: Ezreal's ability targeting seems off, with him frequently missing a significant portion of the enemy team despite his ability to dash to the "ideal spot."

- Prismatic Augments & Utility Indicators: Players are struggling with the unpredictability of some prismatic augments, like "Forge," and forgetting whether they've purchased XP for the round, leading to suboptimal decisions.

- Hero Augment Interactions: There's a bug with attaching Yummi to champions who benefit from their Hero Augments, particularly highlighted with Poppy's Witchin' Wallop augment.

- Stage 3/Level 6 Decision Making: Many players are uncertain about when to roll down at level 6 to stabilize and how that impacts their ability to reach level 8 later on.

- Olaf’s Interaction with Traps: There’s confusion about a supposed interaction where trapping Olaf causes him to jump to the enemy backline.

- Vertical Frost Comp: Vertical Frost without an emblem feels difficult to pull off, especially at higher levels, leading to potential pivot strategies or reliance on specific augments.

- Fast 8 Flex Strategy: Players are finding it challenging to cap their boards when playing a fast 8 flex strategy, often leading to top 6-4 finishes but rarely securing top 3.

- Fae Trait Bug: There's a bug reported with the Fae trait where it can cause issues with bench space and item distribution, particularly when it says the bench is full without giving a Radiant item.

**Proposed Strategies to Climb**

- Prioritize Consistent Comps: Focus on comps that are stable in the mid-game, particularly those involving 2-star 3-cost champions, as they are more reliable to hit and can carry you through stage 3 and into stage 4.

- Careful with Prismatic Augments: Be cautious when selecting prismatic augments like "Forge." If you’re not confident, it might be better to choose a more straightforward augment that offers immediate and predictable benefits.

- Stage 3/Level 6 Strategy: Consider rolling down at level 6 if your board is weak, but keep enough gold to still reach level 8 at a reasonable time. If your opener is strong, aim for a fast level 8 to capitalize on higher-cost units.

- Fast 8 Flex Adaptation: When playing a fast 8 flex strategy, ensure you have a clear plan for capping your board. Prioritize champions that can use common items effectively (e.g., Kalista, Fiora, Gwen) to avoid being stuck with a weak board at level 8.

- Vertical Frost with Emblem or Pivot: If you’re playing Vertical Frost, prioritize finding the emblem. If not, consider pivoting to another comp at the third augment if you’re unable to hit key champions like Olaf or Diana.

**Proposed Balance Changes**

- Nerf Veigar 2: Consider reducing Veigar 2’s power slightly to prevent it from being overly dominant and too stable in the late game.

- Increase 4-Cost Reliability: Slightly buff the appearance rate or power of 4-cost champions to make reaching level 8 more rewarding, ensuring that the investment to level 8 feels worthwhile.

- Olaf Interaction Clarification: Either fix or clarify the interaction with Olaf and traps to prevent unintended behavior or confusion.

**Bugs That Need to Be Fixed**

Ezreal’s Targeting: Fix Ezreal’s targeting issues to ensure that his ability hits the intended targets more reliably.

- Yummi and Hero Augments: Resolve the bug where Yummi cannot be placed on champions benefiting from their Hero Augment, particularly with Poppy’s Witchin' Wallop augment.

- Fae Trait Bench Bug: Address the bug with the Fae trait where it inaccurately reports a full bench and disrupts item distribution.

- Prismatic Augment Dual Purpose Indicator: Implement an indicator to clarify the dual purposes or potential risk/reward of selecting prismatic augments, reducing the chances of players making regretful choices.