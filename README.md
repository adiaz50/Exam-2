# Exam-2

Problem 3 - Arithmetic Slides 
Step 1)
For this problem the way I would solve it recursively would be to first solve it with loops. 
So since the problem is if the list >= 3 and the difference between 2 consecutive elements is the same then return.
We first need to check for the first condition and return if false. Just if length of list is < 3 then return.
Then we need two for loops to do this one, one to go through the first list(we'll call this i) it will begin at 2 to be able to get the difference later on and the second to go through the same but 1 ahead of the first list(we'll call this j).
Once we have done that we can start getting the second condition which is the difference between 2 consecutive elements.
We need to hold the value of the first difference and then the second to then be able to see if they are the same.
So now that, that works we can change the 2 for loops and replace them for recursion.
We put them with the same if statement where we compare the 2 differences so if first difference is == to second difference 
then call Arithmetic_slides and increase i and j and update the differences.
To solve sub-problems in this case we had 2 sub-problems where we did the first part checking for the first condition which is if it is bigger than or equal to 3 if it is anything less than that then it will not work.
The second sub-problem is the one where we need to get the differences so first we get the first difference and then the second difference which is just the difference of 2 less indecies of i.

Problem 5 - Maximum Length of Pair Chain
For this problem the way to do it without recursion is to use for loops and also have them ordered. So for dynamic programming it is almost the same thing just a little changes.
So after we have ordered the pairs(ordered by the first element which is always the smallest between the tuples) we then compare if b is smaller than c then we add it to the chain and do recursion and move on to the next element else if it is not true then we leave the elements or the same pair and compare that to the next pair until it ends or it can finally add another to the chain.
The sub-problems in this problem are the ordering to decrease the amount of time it takes to find the pairs.
The way to order them would be to order the pairs by the first element which is the smallest of the pair.

Problem 8 - Perfect Squares
For this problem the way to do it would be to first make a list to hold the values.
The next thing is to add a perfect square number j*j to a sum of perfect square numbers that equals to i and so that it can be generized as i-j*j + j*j. 
So the least number of perfect square numbers that sum up to i-j*j is dp[i-j*j] While doing that we would be doing recursive to be in a loop.
We also need to find the least number of squares.
One of the subproblems was making a list to hold the values and not having to do the same thing over and over again.
So we store the calculations.


Problem 7 - Minimum Falling Path Sum 

