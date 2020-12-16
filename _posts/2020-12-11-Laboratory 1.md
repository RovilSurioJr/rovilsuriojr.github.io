---
published: true
---
## Basic activities with Python

This laboratory activity aims to practice the students in implementing the principles and techniques needed in getting started with coding using the Python programming language.

The practices of this activity include the implementation of methods and functions of Python. This activity teaches and implies the usage of the function and method. The deliverables are to perform operations on arrays and to plot the vectors. Lastly, it was achieved by reading the documentation of the functions and methods.

![]({{site.baseurl}}/images/LAB1.1.jpg)

The code snippet above shows how to print a string from a list in which the format is shown above. It was achieved by using the function zip() to put together the two lists and convert them together into a string by using the join string method. Also, the word 'at level' was added in-between of the Pokémon names and level in the positional argument from the format string method so that when it prints, it will follow the format that was assigned which is the ("{} {} {}".format(party, ‘at level’, levels). So, the first index from the 'party', will go to the first ‘{}’ to be followed by the word ‘at level’ into the second ‘{}’ then lastly the first index from the ‘level’ list into last ‘{}’. This process is in a loop until it reached the last index of the list or ‘Abra’ and level 14 in the ‘levels’ list.

![]({{site.baseurl}}/images/LAB1.2.jpg)

The code above is the example of accessing and manipulating elements from a collection. To begin, a variable ‘pick’ was defined as a list as shown in the first line of code in Figure 2 and the ‘reserves’ list was sorted out into descending order by using the reverse keyword as one of a parameter of the sort method. It was set to True because the default value of reverse is False. Also, a lambda expression or anonymous function was used as the second parameter of the sort method to set the location of the index that will be accessed from the list of tuple/Pokémon with levels that contain 0 and 1 index. The sorting of the list of tuple/pokemon with levels by their 2nd index was possible because of the indication in the lambda expression to access the second index which is in code is “key=lambda x: x[1]”. Therefore, If the lambda expression was not used, the sort method will sort the list alphabetically based on the 0 index which is the names of Pokémon. Lastly, after sorting it, the first 3 elements were appended to the variable ‘pick’ empty list that been defined, and by printing it, the output shows the 3 Pokémon parties desired.

![]({{site.baseurl}}/images/LAB1.3.jpg)

The block of code was created and executed to present the three possible parties in connection with the activities above. Using the create_party (party, candidates) function given, a block of code was created that displaying the possible parties while keeping the original members of the 'party' list when the function was called. It was achieved by appending one by one of the selected Pokémon from the 'pick' variable from cell 2. The process includes accessing their index and appending the first pokemon from the 'pick' list which is 'Unown' to the 'party' list using the code “party.append(pick[0])” and printing the current elements of the 'party' list. Next is removing 'Unown' by the code “party.remove(“Unown”)” and replace it with 'Magikarp' by the code “party.append(pick[1])” and print again the current elements of the 'party' list. Lastly, replacing 'Magikarp' by 'Feebas' using these codes “party.remove(“Magikarp”)” and “party.append(pick[2])”. Now that the three possible parties are completed, calling the function to execute the block code shows the identical output to what is presented in the problem.

## Note:

The advantage of using python is that it has a lot of documentation and its community is big so there are a lot of tutorials. Also, comparing to other languages, Python programming language is more flexible in terms of syntax. Likewise, in Jupyter Notebook, it is extremely useful in data science because of its capability to produce such graphs and vectors which is a good representation of many things.

## You can access the codes here:

[Laboratory 1 Repository](https://github.com/RovilSurioJr/-Laboratory-1)
