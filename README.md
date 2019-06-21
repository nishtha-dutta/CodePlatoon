# Instructor Challenge

Thanks for applying to be an instructor at Code Platoon! The first step is to take a coding challenge. Please fork this repo, finish it on your own, open a pull request against this repository's master branch and tag `@jyoung217` to let us know when you're finished.

# Optimal Change
You are writing a computer program to calculate the optimal change for an item's cost using object orientation. Feel free to use Javascript, Ruby, or Python to answer this question. You must also have unit tests to verify your code works as you expect.

Some specs:
- You will create a `ChangeMaker` class that will be initialized with a total price and the amount a user paid
- You're not limited to any number of methods, but the one we'll be looking at will be your `optimal_change` method which will operate as follows (the following example is in Python):

```
change_maker = ChangeMaker(62.13, 100)
change_maker.optimal_change()
> "The optimal change for an item that costs $62.13 with an amount paid of $100 is 1 $20 bill, 1 $10 bill, 1 $5 bill, 2 $1 bills, 3 quarters, 1 dime, and 2 pennies."

change_maker2 = ChangeMaker(31.51, 50)
change_maker2.optimal_change()
> "The optimal change for an item that costs $31.51 with an amount paid of $50 is 1 $10 bill, 1 $5 bill, 3 $1 bills, 1 quarter, 2 dimes, and 4 pennies."
```

### Remember
- Don't forget to account for plural denominations (i.e., quarters, dimes, pennies, bills) and punctuation (i.e., commas and the period at the end of a sentence) to delineate between different denominations.
- This is **optimal** change. Obviously, you can give the change in pennies, but we're looking for the most optimal (least amount of) change possible.
- Write at least 3-4 unit tests. Feel free to start with the two examples above!
