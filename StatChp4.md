# Chapter 4

- [Chapter 4](#chapter-4)
  - [Vocab](#vocab)
  - [Ways to get random samples](#ways-to-get-random-samples)
    - [Examples](#examples)
  - [More vocab](#more-vocab)
- [Experimental design](#experimental-design)
    - [Example](#example)

## Vocab

**Census** - Collection of data from every member of a population usually very expensive in money or time

**Convenience sample** - easy to get (rarely represents the whole pop).

- results in convenience bias.

**Bias** - using a method that is likely to result in an overestimate or an underestimate of the value for the population (not an unlucky sample)

For your answer do one of these:

1. How members might respond different from the general population

2. How this difference would lead to an overestimate or underestimate

**Voluntary response sample** - allows people to self-select to participate invitation (generally people who might feel strongly about an issue - extreme view)

- results in **voluntary response bias**

They have to take the action to participate- voluntary response bias

## Ways to get random samples

**Stratified random sample** - pop split into groups determined by shared characteristic. Then do a random sample from each group.
Sample upper school St. Marks: 2 freshmen 2 sophomores 3 juniors 3 seniors.

- *Pros:* This is more likely to produce a sample mean closest to the population mean bcs every part of pop that could have diff attitude or results is represented.
- *Cons:* More expensive

**Cluster random sample** - Population is split into groups (clusters) often geographic in natures. randomly select one or more clusters and use all in those clusters for samples.

- *Pros:* Cheaper than random sample. Saving time and money.
- *Cons:* can get samples that have strong bias

**Systematic random sample** - take every kth item from the pop (randomly select the first one).

### Examples

**Simple random sample:**
Assign values 1-20000 to the books.
using `randIntNoRep`, select 500 values from 1 to 20000.
Then use those values to select the books for the sample.

**Stratified random sample:** 
Group by topic, for each type, randomly select ~$\frac{500}{\# of types of books}$

**Cluster:** assign numbers to each shelf 400 shelves grouped by location, randomly pick 10 shelves from the 400
## More vocab

**Sampling Frame** - List of items and assigned ids

**Undercoverage** -  some members are the population are less likely to be chosen by sampling method.

**Nonresponse** - an individual is selected for a sample but cant be reached or refuses to participate. Results in nonresponse bias. We can fix this with follow up, give them money.

**Response Bias** - Something about the order or phrasing of the questions affects the outcome.

- Would you do x vs. would you not do x
- "lying answer": you give a socially acceptable answer. (Have you cheated on your spouse)
- order of questions (prior questions may make someone feel some way and answer a question a certain way)

**Observational Study** -  variables are measure without researcher attempting to influence the response

**Retrospective:** Examine existing data

**Prospective:** Example into the future (now, in 5 years, then in 15 years)

Response: weight lost, explanatory: financial incentive. $\textcolor{red}{\mathrm{too \space vague}}$

**Confounding** - When the effect of two or more variables on the response variable cannot be separated from each other.

**Experiment** - When the researcher intentionally changes one or more factors and measures outcomes.

**Placebo** - A treatment that cannot be differentiated from a "real" treatment but doesn't actually do anything.

**Treatment** - A specific condition applied to an individual in the experiment.

**Experimental unit/subject** - an object or individual to which a treatment is applied. All of them form the sample.

**Factor** - an explanatory variable that is being manipulated.

**Level** - Different values that can be assigned to a factor.

# Experimental design

How to address other sources of variability in an experiment.

- comparison
  - vary explanatory variable
- *blinding (not necessary)
  - double-blind: subjects and researchers in contact with the subjects do not know which treatment.
  - single-blind: either subjects or the researchers in contact with the subjects know which treatment, but not both.
- random assignment
  - this is to balance out the effect of other variables among the treatment groups.
  - reduces the impact of confounding
  - two people following your instructions should do the same thing
  - 1. How randomness is used
  - 2. How do you deal with repeats "ignore repeats" or "generate 5 distinct numbers"
  - 3. which group is assigned to which treatment
- control
  - Provide a baseline for comparison; it helps account for confounding.
  - This group gets the "do-nothing" treatment (this is either placebo or no action)
  - placebo effect is when subjects respond favorably to any treatment, even one that isn't doing anything
  - keep other variables outside the treatment constant for all experimental units.
- replication
  - is about using enough subjects
After you do all those things, if there is an association between the variables, and the difference in response is bigger than the chance variation, u can conclude cause and effect.

If less than 5% of the the random chance is strong than what you get, then there is significant evidence of cause and effect.

### Example
**Completely randomized design to compare online and classroom SAT prep courses.**

- Label each student alphabetically 1 to 20.
- Generate 10 distinct random numbers between 1 and 20.
- Assign the students with these 10 numbers to the online class and the remaining 10 students in the classroom class.
- Calculate the change in SAT score for each student and compare the two groups.

If some people are in different levels of math you could

- only use precal students
- use blocking (basically stratified random sample)

**Account for variability** created by differences in class level by subtracting the difference between the 3 blocks.
Precal improved 86-20=60 more than Geo, so subtract 66 from each precal value.
$x_{new}=x_{old}- (\bar x-\overline{lowest})$