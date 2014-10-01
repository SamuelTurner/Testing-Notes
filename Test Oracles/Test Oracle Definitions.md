# Test Oracle Definitions

## Oracle
An oracle in software testing is a mechanism of determining whether a test passed or failed.

## Reference Program
When comparing the behaviour of the program under test to a second similar program, the second program is the reference program, or reference oracle.

## Comparator
The comparator is the software or person that compares the program under test to the reference oracle.

## Oracle assumption
Many definitions exist to try to describe the oracle assumption, but here is one of the simpler ones which, unfortunately, I can't find the source of:

> "The oracle assumption states that the tester routinely knows what the correct answer is supposed to be, which is fundamental to testing."

In short, the oracle assumption is the assumption that an oracle can be found for any test. However, this is often not the case. Sometimes the outcome of a test can't be quantified or understood easily, so we can't be sure if the outcome of a test was positive or negative, and therefore limits what we can learn about the program under test.

## Heuristic oracles
A heuristic oracle is an oracle that relies on fallable, experience-based method of determining the outcome.

## Consistency oracles
A consistency oracle is an oracle that determines whether a product is consistent with any heuristic oracle.