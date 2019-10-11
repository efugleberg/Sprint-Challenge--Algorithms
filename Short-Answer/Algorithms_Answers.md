#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n^2)


c) O(n)

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

```
Binary Search method with a time complexity of O(log n)

1)  Test the middle floor --> f/2
2)  If the egg breaks:
        divide the building into two parts, move to the middle of the lower floors
    If egg != break:
        divide the building into tow parts and move to the middle of the upper floors
3)  Repeat step 2) until there is only 1 floor remaining
```
