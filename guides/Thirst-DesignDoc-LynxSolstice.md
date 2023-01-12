<!-- It's not necessary to follow this format, as long as you provide a coherent and structured document -->

## Abstract

  Have you ever noticed the abundance of water and water carrying implements in-game? What if they had a use? That's where my idea comes in: A thrist system. It would add an addidtional system ontop of what we currently have, hunger! The hunger system currently decays naturally with time, being affected by bloodloss which (in my understanding of it) increases this decay rate. 
  The thirst system would take over this role, replacing the hunger system as a bloodloss-affected-decaying system, which would indirectly affect hunger. As thrist reduces, you would decay hunger faster, and since it would be affected by bloodloss, the overall impact of bloodloss could be lessened by staying hydrated during combat, which offers an incentive to utilize MREs on the field. Adding this utility to MREs would make it essential to provide a logistics chain for the comsumption of water, either through MREs being distributed by Req, or via Marines carrying their own water onto the field.
<!-- An abstract is a short blurb, about a paragraph or two, succinctly describing your feature. This should mostly be "why", but can include "what". -->

## Goals

1. Establish a system that is affected by the intake, or out-take of water via consumption, bloodloss, or natural decay. (a thirst system)
2. Incentivize logistics of food and water items (MREs, MST created meals, flasks, MST created drinks), by implementing a faster decay than the current hunger system, while also disconnecting the current hunger system from being directly affected by bloodloss.
3. Provide additional utility to under-used items (waterbottles, drinks, flasks.)
4. (This is more situational than the above points.) Foster roleplay situations by promoting down-time where Marines have to retrieve water from their fellow Marines (Req, MST, other grunts, APC crewmen, etc.).
5. Soul/realism/added depth.
<!-- This is a numbered list clearly detailing your goals for the feature. As per usual, this should be a mixture of both why and what. -->

## Non-goals

1. Implement slow-down from dehydration itself.
2. Implement HP damage from dehydration itself.
<!-- Just like goals, but the opposite! Every feature has boundaries it won't step over. These should be written as if they start with "We will not...". -->

## Content

Implement a system that is a duplicate to the current hunger system, change the sprite to that of the Wey-Yu waterbottle, or a flask. Change bloodloss to not affect hunger decay rate. Change the bloodloss system to affect the new thirst system. Have thirst affect the hunger system's decay rate. Implement a change water so it affects the thirst system. Implement alcohol dehydrating the player, increasing the rate at which thirst decays. The reason the thrist system would be implemented this way is to not unfairly penalize the pace of the gameplay or TDM players, while adding an additional layer to logistics and the medical system, while adding the potential for map creators to adjust passive thirst loss (for example on the desert maps you might lose thirst faster,) adding an additional dynamic system to be utilized.
<!-- Now's where you get into clear detail about everything your feature does. **You should still be explaining 'why' things are that way, *as* you describe what.** Be as detailed as possible. -->

## Alternatives

Keeping the old system as is or overhauling it to not be affected by bloodloss: The reason I didn't choose these alternatives, is that there would be no change from the current implementation from hunger, or in the case of having it not be affected by bloodloss, no reason to have it in the first place besides penalizing player speed at the beginning of the round.
<!-- Provide potential alternatives to your feature, either ones that align with your design values, or ones that don't that you suspect will be suggested. If you are including the latter, make sure to explain why you didn't choose that. -->

## Potential Changes

If the system affects the gameplay loop harshly, say it breaks the pacing, perhaps it's affect on hunger, or bloodloss' affect on it could be tweaked and lessened as needed.
<!-- Most of the time you're not going to get the best design first try. It helps to try your best to predict what *could* go wrong, and suggest alternatives that can be taken, without sacrificing your design. -->
