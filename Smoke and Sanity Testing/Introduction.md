# Smoke and Sanity Testing #
============================

Generally speaking, smoke testing and sanity testing refer to the same activity - performing a quick, shallow form of testing aimed at finding out if a product fulfills the most basic requirements.

## What can be learned from a smoke/sanity test? ##
* Whether the product can perform the basic functions or fulfill the basic requirements
* Whether it is reasonable to conduct further testing
* Whether it is possible to conduct further testing

## Example ##
A very commonly used method of sanity testing any development (or in some cases production) environment is to run a "Hello, world!" program. If the program fails to output "Hello, world!", then further testing cannot occur. If it does output "Hello, world!" but takes 3 hours to do so, then the environment has some configuration issues that will make it unreasonable to test any applications on it.

## Is differentiating between a Smoke Test and a Sanity Test pointless? ##

Michael Bolton certainly thinks so in his article - [http://www.developsense.com/blog/2011/11/smoke-testing-vs-sanity-testing/](Smoke Testing vs. Sanity Testing: What You Really Need to Know)

The only real difference I can think of is that to me, a smoke test has a clearer definition. If you see smoke, then something is burning. But what does "sanity test" really mean? Testing that a product is... sane?
