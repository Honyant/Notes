# Randomness and Probability

Law of large numbers: If we observe more and more repetitions of and random process, the proportion of times that a specific outcome approaches that probability of that outcome

expected/predicted % of successes in many, many trials.
Prob is between 0 and 1, 0 means impossible, 1 means guaranteed.
Beware of scientific notation.

If we roll 2 dice many, many times, the expected proportion of times where the sum is 7 is about 1/6.


Purpose of simulation: To estimate probabilities when they are difficult to calculate theoretically.

### How to perform a simulation
1. Describe how you will use randomness for one trial.
2. What you will record for the trial
3. Perform many, many trials.
4. Use results of the simulation to estimate the probability of the outcome.


Assign H as a correct answer and T as incorrect. flip a coin twelve times and record the # of H. This is one trial
Perform many, many trials and record the # of H.
This is 1 trial
perform many many trials.
Calculate the proportion of trials for which there were 11 or more Hs
Or assign 1 as correct and 2 as incorrect. Randomly generate 12 values from 1-12 allowing repeats.

Define complement:
$P(1^C)=1-P(1)$

Test for independence if  $ P(A|B)=P(A)$, then A is independent of B.

||A|not A| Total
-|-|-|-
B| | |30
Not B| | |70
Total| 60|40 | 100


**Mutually exclusive**
||A|not A| Total
-|-|-|-
B| 0| 30|30
Not B| 60|10 |70
Total| 60|40 | 100

**Independent**
||A|not A| Total
-|-|-|-
B| 18| 12|30
Not B| 42| 28|70
Total| 60|40 | 100

For Independent:
![picture 1](https://i.imgur.com/BAzo8x5.png)
$P(A \cup B)=1+2+3$
$P(A \cap B)=2$
$P(A)=1+2$
$P(B)=3+2$

### Conditional Probability
U can use tree diagrams to represent this situation.

Ex: prob someone hit snooze given they are late.
$P(A|B)=\frac{P(A\cap B)}{P(B)}$
$P(A \cap B)=P(A)P(B|A)$
Tree diagram as are good for conditional probability.




$\frac{0.05*0.99}{0.95*0.03+0.05*0.99}$


If 5% false positive rate among 100 people, then prob of at least 1 false positive is $1-(1-0.05)^{100}=0.994$

Lets say we have two locations that are really close to each other, and they are not independent, then we don't have enough info to determine $P(A \cap B)$.s



The probability is so small that it this is unlikely to occur by chance. Thus there is convincing evidence that 40% is too high. Don't put 5% in answer.