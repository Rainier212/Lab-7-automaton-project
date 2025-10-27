Project: automaton
Aothors: David J. Barnes and Michael Kölling

This project is part of the material of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 7.


**Answers to questions:**

27. Yes, the same pattern emerges after I repeated the process in the previous exercise.

28. The fill method of the java.util.Arrays class sets the cells to zero and the middle cell to 1.

29. There will be different patterns because we now have multiple starting points, but the patterns will still be deterministic since it is the same starting state, therefore, it will produce the same pattern evolution.

31. We create a new array so that it keeps all the old values so every calculation is correct. So if we don't create a new array and directly update state, it will mess up the values and will break the automation.

32. I don't really have a solution, but I think creating a new array is the best solution since it is super simple and easy to understand. If we were to do something else, we would have to add more code and it will be way more complicated than just creating a new array.

35. Since there are 8 possible combinations and 2 possible ouputs, there are only 256 possible unique rules.
