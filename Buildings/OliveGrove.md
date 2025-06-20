# Olive Grove

## Regional Building

### Stats

 - Replaces the Farm.
 - Cost: 80 wood
 - Hit Points: 240
 - Food capacity: 900
 - Remaining stats identical to Farm.
 - Not affected by Horse Collar, Heavy Plow and Crop Rotation - civilizations with access to Olive Groves don't get those techs.

### History

 - Olives are slow to grow and start yielding, but when they do the trees can produce crops for centuries if not destroyed.
 - Olives can grow on rocky terrain where conventional grain farming would not be feasible, and as such were the primary food crop in many Mediterranean communities, most notably in Palestine and Malta.
 - Destruction of historic olive groves has been used to devastate and uproot settled Palestinian communities, as showcased in the reduced hit points, increased cost and slower gather rate.

### Appearance

 - I imagine this as being 4 olive trees (possibly with some variance in appearance) roughly evenly spaced within the square.
- Since the release of Pastures, we see more buildings that have walkable and non-walkable segments, so implementing an around each tree where units could not walk would add to the aesthetic, as well as incentivize their destruction, which external occupiers frequently did.

### Gameplay

 - Access to Olive Groves gives significant resource savings from skipping Mill upgrades and not needing to reseed as often, but your farming economy will be more vulnerable and your gather rate per villager slightly lower due to missing Heavy Plow.
 - While a net positive in resources, even accounting for the reduced gather rate, access to Olive Groves will require a different build order to a civilization with access to Farms.

### Loose Threads

- Are Olive Groves underpowered?
   - Even with the additional cost and vulnerability, they still don't yield as much food as fully upgraded Sicilian farms, and those aren't considered overpowered, or even a significant bonus to the civilization. This does kick in earlier and have some savings on techs, but on the other hand you also gather slower.
   - I wanted to make the farms *different* rather than just *better*, but I'm not sure how big of an impact this would be.  
   (Warning, maths ahead, read **bold** for cliffnotes.)  
   - A generic civilization **in Feudal Age** with Horse Collar and Double-bit Axe needs about one lumberjack for every (250 food on farm / ~18 food per minute) / (60 wood per farm / ~20 wood per minute) = 13.(8) / 3 ~=4.5 farmers to keep them consistently reseeding.  
   A civilization with Olive Groves, on the other hand, need one lumberjack for every (900 food / 18 food per minute) / (80 wood per farm / ~20 wood per minute) = 50 / 4 = 12.5 farmers. Reversing the calculation, that means that for every farm you have, you save about 1/4.5 - 1/12.5 = 0.(2) - 0.08 ~= 0.14 ~= 1/7 of a lumberjack compared to the generic civ, or, **for every 7 farms, you have a free villager you can send somewhere else that a generic civ would need to keep on wood**.  
   - The calculation gets even less favourable for the Olive Groves **in the late game**, where their gather rate on farms will lag behind other civilizations. I couldn't find accurate gather rates for Villagers with Hand Cart but not Heavy Plow (since that's a situation that basically never happens except maybe to Nicov), but **even with the most generous interpretation that farmers in that situation already bump into the farms' built in food production limit** (and thus the late game farming rates being the same), a generic civilization needs one lumberjack per (550 food per farm / 23.25 food per minute) / (60 wood per farm / 28 wood per minute) = ~23,5 / 2.14 ~= 11 farmers, whereas for the Olive Groves this is (900 food per farm / 23.25 food per minute) / (80 wood per farm / 28 wood per minute) = ~38.7 / 2.85 ~= 13.5 farmers. Reversing the calculation again, this means that for every Olive Grove you need 1/11 - 1/13.5 + 0.(09) - 0.(074) ~= 0.016 farmers, meaning that **you only get an extra villager you don't need to have on wood compared to a generic civilization for every 60 farmers**.
   - In Feudal or early Castle Age you can probably get a villager or even two working somewhere else, which is comparable to the impact of the Persian bonus up to that point (though with more resources invested to get there), but by late game this still ends up being only about one extra villager compared to a generic civ, which is not a lot in a 200 pop game. 
   - The impact is significantly greater **if your enemy doesn't get** (or doesn*t have) access to **Crop Rotation** (which a lot of pros argue is almost never worth it anyway since it takes too long to pay for its cost), since then your enemy will need one lumberjack for every (375 food per farm / 23.25 food per minute) / (60 wood per farm / 28 wood per minute) = 16.12 / 2.14 ~= 7.5 farmers, so **you are at an advantage of** 1/7.5 - 1/13.5 = 0.13 - 0.074 = 0.06 lumberjacks per farm, or **one lumberjack free per 16 farms** compared to the enemy. This is easily a third of the impact of Mahayana for free in the late game, on top of everything before.
   - Weirdly, this puts you in the situation where you may be at a greater advantage against a pro who chooses to not get Crop Rotation, over a low elo legend who gets it without realising it will take ~40 minutes to pay for itself.
   - The main impact is in Castle Age, when the first farms your enemy has placed are coming up to be reseeded, whereas yours won't be for another ~15 minutes, and you have what is effectively a villager advantage. This is giving you a resource advantage at a time when you can pull off literally almost any Castle Age strategy due to your very open tech tree.
   - It seems to me like no matter how I slice this the impact in late game is going to be minor, and it's primarily a timing bonus (maybe to help you put down your first Castles and get on the **Pilgrims** train). Is that okay? It is definitely weaker than the Persian, Malay, or Viking bonuses in the mid game (and it's supposed to be, those are all top tier bonuses), but I worry that you are not saving many resources, just freeing up villagers, and that this will not have a large impact at all and not make it worth the 3 maluses you get. (How) should I address this? Remove the higher cost maybe?