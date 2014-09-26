# Introduction

Cem Kaner said in his [Black Box Software Testing](http://www.testingeducation.org/BBST/) course:

> Two definitions used to be commonly used:
> * An oracle is a mechanism for determining whather the program passed or failed a test. (E.G: A specification.)
> * An oracle is a reference program. If you give the same inputs to the software under test and the oracle, you can tell whether the software under test passed by comparing its results and the oracle's. (We can tell if a spreadsheet calculates results correctly by comparing it to another spreadsheet.)

## The Limitations of Test Oracles

Throughout history oracles were seen as very wise or knowledgable people who could provide council and predict the future. Sometimes oracles were though of as conduits between people and their gods. All definitions show them as holding some mental knowledge or skill greater than the general population.

In testing however, an oracle is a much simpler definition. In the case of the reference oracle above, when comparing the behaviour of the program under test to the reference oracle's you need to question if the behaviour of the reference oracle is correct or not. They could both be wrong, or the program under test could be correct, and the reference oracle could be wrong.

## Test Oracles are Fallable

For a given test, the result must be compared to an oracle for us to judge the outcome of the test. This introduces a large human influence to the equation, as first we judged what the correct test was, then what the correct oracle for that test was, then whether the outcome of the test was positive, negative or otherwise when compared to the oracle. This means that the results of our tests, our test data and test reports are all fallable.