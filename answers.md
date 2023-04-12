# CMPS 2200 Assignment 3
## Answers

**Name:** Tyler Simms


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**

  The recurrence formula for the work of this solution is W(n) = W(n-1) + 1. The recurrence formula for the span of this solution is S(n) = S(n-1) + 1. The Big Oh solution for both recurrence formulas is O(n). Iterate has no opportunity for parallelism.




- **d.**

  The recurrence formula for the work of the scan portion of this solution is W(n) = W(n/2) + n. The recurrence formula for the work of the reduce portion of this solution is W(n) = 2W(n/2) + 1. The recurrence formula for the span of the scan portion of this solution is S(n) = S(n/2) + 1. The recurrence formula for the span of the reduce portion of this solution is S(n) = S(n/2) + 1. The overall Big Oh solution for both work recurrence formulas is O(n). The overall Big Oh solution for both span recurrence formulas is O(logn).



- **f.**

  The recurrence formula for the work of this solution is W(n) = 2W(n/2) + 1. The recurrence formula for the span of this solution is S(n) = S(n/2) + 1. The Big Oh solution for the work recurrence formula is O(n). The Big Oh solution for the span recurrence formula is O(logn).