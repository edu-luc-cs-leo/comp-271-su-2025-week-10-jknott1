# Reflection - Week 09 #

I this week went pretty well! However, I will say that in terms of programming concepts, this was definetely the hardest and most confusing thus far. Although I think I did what needed to be done, there are a few inconsistencies between my code and the solutions. 

The biggest difference between our solutions is in the `findMax` method. Although it does find the maximum of the given array recursively, I used the `mergeSort` method to get that result. I think that I took the hint in the directions the wrong way - but I noticed that the maximum element could be taken from a list that had already been sorted. So, I used the recursion that already gave me the maximum and plucked the last element from that list. However, I do realize that this was more of a shortcut rather than anything else.

There are a couple more differences in a couple methods, but nothing that I think affects the outcome too much. However, they moreso showed some shortcomings in my understanding of recursion in programming. For example - in the `countOccurances` method, rather than only advancing the index and adding to the count based on a conditional statement, I had my method return the count for each element each time it recursed (returns 0 or 1) and tacked that onto the count in the first recursion. 

Though I didn't initially have a good handle on recursion, I think that as I worked though this assignment and had a chance to look at the solutions, I think that I have a pretty good grip on it now. 