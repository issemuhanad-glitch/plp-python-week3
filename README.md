
# Week 3 Assignment: Grade Reporter & Bug Hunt

## Files

- grade_reporter.py: Uses a for loop and conditions to calculate learner grades, pass count, fail count, and average score.
- bug_hunt.py: Fixes three bugs in a while loop program that calculates the sum of numbers from 1 to 5.

## Bug Hunt Reflection

The hardest bug to find was the loop condition because the program could run without an error but produce the wrong answer. The program originally stopped at 4 and calculated 10 instead of 15. I knew something was wrong because the expected answer was 15, so I changed the condition from count < 5 to count <= 5.