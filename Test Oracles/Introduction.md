# Introduction

Cem Kaner said in his [Black Box Software Testing](http://www.testingeducation.org/BBST/) course:

> Two definitions used to be commonly used:
> * An oracle is a mechanism for determining whather the program passed or failed a test. (E.G: A specification.)
> * An oracle is a reference program. If you give the same inputs to the software under test and the oracle, you can tell whether the software under test passed by comparing its results and the oracle's. (We can tell if a spreadsheet calculates results correctly by comparing it to another spreadsheet.)

## The Limitations of Test Oracles

Throughout history oracles were seen as very wise or knowledgable people who could provide council and predict the future. Sometimes oracles were though of as conduits between people and their gods. All definitions show them as holding some mental knowledge or skill greater than the general population.

In testing however, an oracle is a much simpler definition. In the case of the reference oracle above, when comparing the behaviour of the program under test to the reference oracle's you need to question if the behaviour of the reference oracle is correct or not. They could both be wrong, or the program under test could be correct, and the reference oracle could be wrong.

Cem Kaner summarised four problems with testing oracles in his [BBST course](http://www.testingeducation.org/BBST/), to which I've added further summary:
>* Our expectations are not necessarily correct - When we rely on specifications to set our expectations, we often find the spec is wrong or outdated. Similarly when we find that a program doesn't work the same way as a reference program, that's often because the reference program has a bug.
>* Our expectations are not complete - Even if a program and the oracle match there could still be a bug. No reference program covers all aspect of a comparison. No specification is complete. If the program reports 2+3=5 we get the expected result, but if it takes 5 hours, that may be a bug.
>* A mismatch between result and expectation might not be serious enough to report - A font rendering bug might be trivial in Wordpad (a basic word processor for basic use), but serious in Word (a serious word processor for professional work).
>* Our expectations are not nexessarily credible - When you say a program isn't working correctly, why should anyone believe you? Maybe no-one will challenge you if the oracle is a specification or a respected reference, but what do you do when the program misbehaves in a way that isn't covered by an oracle that someone else told you to use, do you ignore it? Do you report it but hope that you don't have to defend it?

## Test Oracles are Fallable

For a given test, the result must be compared to an oracle for us to judge the outcome of the test. This introduces a large human influence to the equation, as first we judged what the correct test was, then what the correct oracle for that test was, then whether the outcome of the test was positive, negative or otherwise when compared to the oracle. This means that the results of our tests, our test data and test reports are all fallable.