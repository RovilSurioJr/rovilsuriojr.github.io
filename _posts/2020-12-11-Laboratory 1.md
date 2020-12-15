---
published: true
---
## Basic activities with Python

![]({{site.baseurl}}/LAB1.1.jpg)
![]({{site.baseurl}}/images/LAB1.1.jpg)

The block of code was created and executed to present the three possible parties. Using the create_party (party, candidates) function given, a block of code was created that displaying the possible parties while keeping the original members of the 'party' list when the function was called. It was achieved by appending one by one of the selected Pokémon from the 'pick' variable from cell 2. The process includes accessing their index and appending the first pokemon from the 'pick' list which is 'Unown' to the 'party' list using the code “party.append(pick[0])” and printing the current elements of the 'party' list. Next is removing 'Unown' by the code “party.remove(“Unown”)” and replace it with 'Magikarp' by the code “party.append(pick[1])” and print again the current elements of the 'party' list. Lastly, replacing 'Magikarp' by 'Feebas' using these codes “party.remove(“Magikarp”)” and “party.append(pick[2])”. Now that the three possible parties are completed, calling the function to execute the block code shows the identical output to what is presented in the problem.
