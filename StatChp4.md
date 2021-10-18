# Chapter 4

- [Chapter 4](#chapter-4)
  - [Vocab](#vocab)
  - [Ways to get random samples](#ways-to-get-random-samples)
    - [Examples](#examples)
  - [More vocab](#more-vocab)

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
- **Retrospective:** Examine existing data
- **Prospective:** Example into the future (now, in 5 years, then in 15 years)

Response: weight lost, explanatory: financial incentive. $\textcolor{red}{\mathrm{too \space vague}}$

**Confounding** - When the effect of two or more variables on the response variable cannot be separated from each other.

**Experiment** - When the researcher intentionally changes one or more factors and measures outcomes.

**Placebo** - A treatment that cannot be differentiated from a "real" treatment but doesn't actually do anything.
