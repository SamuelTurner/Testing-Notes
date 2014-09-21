# Domain Testing

Domain testing involves running tests chosen to increase the chances of exposing a bug. Typically this means using extreme values, which reduces the credibility of the tests - stakeholders are generally more concerned with realistic failures.

For example, when testing two input fields that are related (both input values have an effect on one output value), the list of tests that could be run when factoring in all combinations of possible inputs is enormous. Domain testing involves assessing the list and choosing a subset of those tests, typically choosing the highest risk tests.

Domain testing is not concerned with test realism, merely what happens when things happen.