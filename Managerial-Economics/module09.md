# Strategic Thinking

In this Module we will discuss Economic Games and Strategic Behavior: Matrix games; Nash Equilibrium; Uber pricing and fairness; Decisions under uncertainty.

By the end of this module you should be able to...

- Solve standard matrix games (Prisoner's Dilemma and the Cournot-Nash Equilibrium) and apply them to managerial decisions
- Reward individuals working in a team "fairly" (e.g., Uber pricing).
- Calculate expected value when decisions are made under uncertainty.
- Derive cooperative solutions such as mergers and acquisitions and cartels (e.g., OPEC and recent oil price movements).

## Fairness  and reward structures 

- How is fairness defined?
- Is it fair for everybody in the society to have the same income?
- Is it fair not to envy each other? Is it fair to be rewarded according to your contributions?
- Is there a unique way to define fairness?
- How do we divide profits fairly?
- What is fair pricing? Is there a formula that can be used for fair pricing or a fair reward structure?

### Uber pricing

Amy, George and Jane decide to share an Uber pool taxi.

- If Amy goes by herself to Iowa City from U Iowa,  B-School she pays \$6.
- George is also at the B-School and goes to Coralville. By himself he will have to  pay \$12.
- Jane must pay \$42 as she lives in Cedar Rapids.

What should each one pay if they share an Uber Pool taxi?

- How does one compute a fair price?
- Would the price $2 for Amy, $5 for George and \$35 for Jane seem fair? How did I come up with such numbers? Did I use a formula? Yes the Shapley value.

**Intuitive-Shapley value solution**

- Amy: 6/3 = 2
- George: 2 + (12-6)/2 = 2 + 3 = 5
- Jane: 5 + (42-12) = 35

## Expected Profits/Utility

You are faced with the following choice:

- You could get a profit of \$100 for sure (with probability one). Or
- You can gamble to obtain a profit of $10,000 with probability 1 out 80 and $0 in 79 out of 80.

In other words, your **expected profit** for sure is:
100 X 1 = 100.

If you gamble your expected profit is: 10,000 X 1/80 + 0 X 79/80 = 125

## Decision making under uncertainty

**Incentive compatibility**: A trade is incentive compatible if you have no incentive to cheat someone else in order to become better off.

Is it possible to have incentive compatible trade?
Under what conditions trade is incentive compatible?

Example: There are there equally probable states {a, b, c} and two people Jane and George. Neither George nor Jane know which one of the 3 states will occur, but they need to make a trade ex-ante to become better off ex-post. They have the same utility functions. The table below indicates their initial resource of the good they posses before trade:

**Insurance Contracts, Incentives**

Example: There is one good denote by x, three equally probable states {a, b, c} and two people Jane and George. Neither George nor Jane know which one of the 3 states will occur, but they need to make a trade ex-ante to become better off ex-post. They have the same utility function which is x1/2 (i.e., square root of x). The table below indicates their initial resources of the good they posses before trade:

|        | a   | b   | c   |           |
| ------ | --- | --- | --- | --------- |
| Jane   | 5   | 5   | 0   | {a,b},{c} |
| George | 5   | 0   | 5   | {a,c},{b} |

If state c occurs Jane has nothing and if state b occurs George has nothing. What should they do? What insurance contract should their write? Is the contract below acceptable? Is it incentive compatible or do Jane or George have an incentive to cheat to become better off?

|        | a   | b   | c   |           |
| ------ | --- | --- | --- | --------- |
| Jane   | 5   | 2.5 | 2.5 | {a,b},{c} |
| George | 5   | 2.5 | 2.5 | {a,c},{b} |

Notice that both individuals become better off if they sign the above contract because the expected utility after trade is bigger than the one before trade.

The above contract is not incentive compatible because when state {a} occurs, Jane get 5 units but has an incentive to lie and claim it is state {c} in order to get another 2.5. Notice that George cannot distinguish state a from state c. Thus, expected utility is **not** necessarily incentive compatible.

However if both are ambiguous, i.e., they think what is the worse state that can occur, i.e., they consider the worst state in the events {a, b} and {a, c} ,i.e., min {a, b} and min{a, c},

Then they can write a better contact which is incentive compatible : The contract is:

|        | a   | b   | c   |           |
| ------ | --- | --- | --- | --------- |
| Jane   | 5   | 4   | 1   | {a,b},{c} |
| George | 5   | 1   | 4   | {a,c},{b} |

Notice that: if Jane lies now she doesn’t gain anything, i.e.,
If state {a} occurs and she says (i.e., lies) that it is {c} she gets:

    min{a, b}= min {6, 4} = 4

If she tell the truth she gets:

    min {5, 4} = 4.

Hence she has no incentive to lie.

## Conclusions & Summary

An acceptable or fair price is to pay for what is worth to you. The Shapley value is the method used for fair pricing, fair distribution of profits and fair salary structure.

Under the expected utility framework you cannot write contracts that are optimal and incentive compatible. However, you can do this if you are ambiguous, i.e., you take into account the worst possible state that can occur.
