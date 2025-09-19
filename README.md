# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary



## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
This is because the rules of kmaps state that only one variable may change when moving vertically or horizonatally by 1, which is still the case when going across edges. In other words, the Kmap is cylindrical (as we heard in class).


### Why are the names Sum of Products and Products of Sums?
These are the names because when doing a sum of products, you take the sum of any row that produces a 1 ("or" them together), and after that is completed, you have a bunch of boolean equations that you can take the product of ("and" them together) and get an equation that describes the behavior desired of the truth table.

As for products of sums, you take the products of any row that produces a 0, with reversed inputs, and sum them together. After doing this for all rows you again have a bumch of boolean equations that you can now take the addition of to get the behavior desired of the truth table.

### Open the test.v file – how are we able to check that the signals match using XOR?

