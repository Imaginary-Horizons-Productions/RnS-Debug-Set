# RnS-Debug-Set
Set of loot that assists with debugging in Rabbit and Steel Modding API Development

1. loots to note xpos/ypos
2. loots to inspect the vars of the first-slot loot
3. DataId Scanner to quickly get dataId's of loot
4. Attack Pattern Sampler to try out all the attack patterns (iterate them with primary/secondary/special/def)

For it_atk_pat_sampler, you can toggle attack patterns against allies/foes by switching the hidden vars0 set in onSquarePickup. In the Items.ini file you can also respectively set the str_mult to 0 so that way you don't get damaged-noises/visuals, and set the hbsType to a buff. Also, the order MOSTLY matches what's in the item API spreadsheet. I moved Ancient patterns to the end because THEY TEND TO CAUSE CRASHES WITHOUT A PET, on other classes

I also tabulated properties of the attack patterns under patterns.csv
