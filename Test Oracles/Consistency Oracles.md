# Consistency Oracles

Consistency oracles determine whether a product is consistent with some fallable expectation. James Bach and Michael Bolton produced the following list in their [Testing Without a Map](http://www.developsense.com/articles/2005-01-TestingWithoutAMap.pdf) paper:

>* History: The feature's or function's current behavior should be consistent with its past behavior, assuming that there is no good reason for it to change. This heuristic is especially useful when testing a new version of an existing program.
>* Image: The product's look and behavior should be consistent with an image that the development organization wants to project to its customers or to its internal users. A product that looks shoddy often is shoddy.
>* Comparable products: We may be able to use other products as a rough, de facto standard against which our own can be compared.
>* Claims: The product should behave the way some document, artifact, or person says it should. The claim might be made in a specification, a Help file, an advertisement, an email message, or a hallway conversation, and the person or agency making the claim has to carry some degree of authority to make the claim stick.
>* Users' expectations: A feature or function should behave in a way that is consistent with our understanding of what users want, as well as with their reasonable expectations.
>* The Product itself: The behavior of a given function should be consistent with the behavior of comparable functions or functional patterns within the same product unless there is a specific reason for it not to be consistent.
>* Purpose: The behavior of a feature, function, or product should be consistent with its apparent purpose.
>* Statutes: The product should behave in compliance with legal or regulatory requirements.