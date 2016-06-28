---
title: "Measuring How Performant Performance Standards Are"
author: Steve Simpson
tags: [Data Science]
---


When most of us think of outcomes being measured, often it is the outcome measures in view, that is, the performance measures students receive as they are assessed against a performance standard, incapsulated in an outcome statement. That's definitely one way to look at it.  But let's change the focal point and turn that microscope into a telescope. 

How well are our performance standards doing? What standards are our performance standards held up against? These are often the more meta questions we consider in the Data Science team. We're always trying to understand better how our tools work – to know what a dull knife looks like compared against a sharp one, as it were. When you hold a well-made tool in your hand, it almost does all the work for you.

Just like how we care about the difference between a fit statistic from of a chi-squared vs. a R-squared when testing for goodness of fit, we also care how well performance standards perform at their assessing.

Bloom's taxonomy is a common standard for checking if an outcome measures up. Well-formed outcome statements, at minimum, should contain a single action that is measurable. For it to be measurable, it needs to be observable. One cannot observe whether a student simply understands synonyms; one needs instead to elicit an action that gives evidence of understanding, such as through a task for correctly matching words that are synonyms. 

There are several versions and updates to Bloom's original 1956 taxonomy of cognitive skills. The Data Science team at Campus Labs is working to develop an enhanced Bloom's taxonomy that is comprehensive of the student as a whole person. But at their core, all these taxonomies are working from a first principle that outcome statements must contain a measurable action verb in order to be effective.


### Blooms as Basic Goodness of Fit

Above we referenced different statistical measures of goodness of fit. Goodness of fit, as we know, describes our model's ability to capture the variation in the data. Well-formed outcome statements enable one to represent the variation in student performance. A minimal measure of well-formedness would be whether or not an outcome statement can be categorized into a single level in the Bloom’s taxonomy.

If it cannot be categorized at all, it suggests that there is no student action to be observed, thus making it unmeasurable. Or if it can be categorized but into more than one Bloom’s level, then it suggests that the action one hopes to elicit from a student in order to assess their performance is overly complex (or ill-defined) and thus more prone to mismeasurement of various types. 

Our Bloom’s algorithm is designed to implement the above intuitions. Even without seeing our code, it should still be apparent that our math is guided by the same motivations that led Bloom to develop and publish his original taxonomy 60 years ago: make education work better. 

We think education working better can mean making the experience better too. Our algorithm manages the complexities in the backend so that the resulting experience feels and works better.
