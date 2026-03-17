# Math-Concepts-for-Developers---Project

This repository is for my SoftUni project, for the Math Concepts for Developers module.

The edits are marked with \* \*.

The purpose of this file is to document and show my thought process to the teachers.



Project Idea:

Explain the math that 18th century ship captains and navigators used to plan voyages and sail across the Atlantic. I will gradually introduce variables such as unfavorable wind, strong current, maybe even storms and see how the equations change and adapt. My idea is to first model the voyage under perfect conditions, allowing me to write the base python code, after which I will start introducing the variables one by one. The final model should show a voyage under horrible weather conditions, stretching both the math and code.



\*Project Idea Edit\*

While reading about 18 century sailors and the math they used, I found out that the mathematical concepts were different at that time. They were underdeveloped and not as fleshed out. It would take almost a century for the math, measurements and tables to be like the ones we use now. Because of that, I have decided to tweak my project idea and remove the historical accuracy constraints.

I will still describe the math behind a voyage across the Atlantic and then model it under different conditions, but I will use modern nautical navigation knowledge and concepts.



\*\*Project Idea Final Edit\*\*

Due to time constraints and difficulty grasping all of the topic's mathematics, as well as coding them in python, the final project focuses only on the first part of the original project idea - the calculations behind planning a journey across the Atlantic. I plan or returning to this project, as the topic and exercise it provides interest me.



Structure Pan:



1. Introduction
* Give some brief context into the time period. What did naval navigation look like; what tools were used; what did skilled navigators had to know.
* Explain the purpose of this project, along with its constraints.



2\. Mathematical concepts and calculations - planning a journey

* List and explain every mathematical concept and calculation that went into planning a journey.

(Let's take Cadiz, Spain - a historically busy port from which Spanish ships sailed from during that time and Santo Domingo, Dominican Republic - one of the first Spanish colonies founded by Columbus's brother, Bartholomew)



3\. Mathematical concepts and calculations - staying on course

* List and explain every mathematical concept and calculation that went into maintaining course and sticking to the plan.



4\. Voyage model

* 1st write a python model that puts the above explained math in action, assuming the weather conditions are pristine.
* 2nd write a python model that introduces a variable - unfavorable wind - and see how the model changes.
* 3rd write a python model that introduces another variable - unfavorable currents - and see how the model changes.
* 4th write a python model that combines the two variables - imagine a storm from beginning to end - and see how the model changes.



5\. Conclusion

* Write a summary of the above.



\*Structure Plan Edit\*



1. Introduction
* Explain the purpose of this project

\-math explainer/ tutorial type (explain what those are) of marine navigational mathematics (briefly go into detail here about what that is).

\-serving as "background" of the paper, I will plan a traditional (here meaning without the use of a GPS system or modern electronics) voyage across the Atlantic from Cadiz, Spain - Santo Domingo, Dominican Republic.

* Explain the limitations of this project - e.g. possibly ignoring historically proven sailing routes, ignoring the optimal months and currents for this journey, ignoring the difference in season.
* Talk about how the tiniest difference in calculations (e.g. 1 degree) can throw you off course completely - Hypothesis testing using the modals



2\. Mathematical concepts and calculations - planning a journey

* Plan the shortest route

\-spherical trigonometry (great circle arc) -> explain why we need those and what they are/ calculate the route and explain the calculations/ prove the formulas (maybe also calculate the distance as a straight line for comparison).

\-explain what is a nautical mile and how to calculate it.

\-talk about magnetic north and true north, as well as compass bearings.

* Introduce computational errors on purpose, to show how small mistakes can add up and throw you off course.





3\. Mathematical concepts and calculations - staying on course

* Dead reckoning
* Celestial navigation and sextant use
* Use of a chronometer
* Introduce computational errors on purpose, to show how small mistakes can add up and throw you off course.



4\.  Voyage model

* 1st write a python model that puts the above explained math in action, keeping in mind the restrictions outlined in the introduction.
* 2nd write a python model that introduces a variable - unfavorable wind - and see how the model changes.

\-set and drift

\-compass deviation

* 3rd write a python model that introduces another variable - unfavorable currents - and see how the model changes.
* 4th write a python model that combines the two variables - imagine a storm from beginning to end - and see how the model changes.



5\. Conclusion

Write a summary of the above.

