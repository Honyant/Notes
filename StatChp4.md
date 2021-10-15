# Chapter 4

- [Chapter 4](#chapter-4)
  - [Vocab](#vocab)
  - [Ways to get random samples](#ways-to-get-random-samples)
    - [Examples](#examples)

## Vocab

**Census** - Collection of data from every member of a population usually very expensive in money or time

**Convenience sample** - easy to get (rarely represents the whole pop).

- results in convenience bias.

**Bias** - using a method that is likely to result in an overestimate or an underestimate of the value for the population (not an unlucky sample)

For your answer do one of these:

1. How members might respond different from the general population

2. How this difference would lead to an overestimate or underestimate

**Voluntary response sample** - allows people to self-select to participate invitation (generally people who might feel strongly about an issue - extreme view)

- results in voluntary response bias

They have to take the action to participate- voluntary response bias

## Ways to get random samples

**Stratified random sample** - pop split into groups determined by shared characteristic. Then do a random sample from each group.
Sample upper school St. Marks: 2 freshmen 2 sophomores 3 juniors 3 seniors.
This is more likely to produce a sample mean closest to the population mean bcs every part of pop that could have diff attitude or results is represented.

**Cluster random sample** - Population is split into groups (clusters) often geographic in natures. randomly select one or more clusters and use all in those clusters for samples.
Cheaper than random sample. Saving time and money.

**Systematic random sample** - take every kth item from the pop (randomly select the first one).

### Examples

**Simple random sample:**
Assign values 1-20000 to the books.
using `randIntNoRep`, select 500 values from 1 to 20000.
Then use those values to select the books for the sample.

**Stratified random sample:** 
Group by topic, for each type, randomly select ~$\frac{500}{\# of types of books}$

**Cluster:** assign numbers to each shelf 400 shelves grouped by location, randomly pick 10 shelves from the 400
