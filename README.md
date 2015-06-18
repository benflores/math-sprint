# math-sprint

This little web app dynamically generates multiple-choice algebra questions.
Each question (for now) follows this form:

if y = mx + b,
what is the value of x + c?

Four multiple choice answers are given to the user in random order. 
One is always correct, and the other three have some varying, but meaningful mathematical relationship to the problem. That is, the incorrect choices attempt to represent answers that a user could actually arrive at through mathematical error.

When a user selects an answer, they receive feedback about whether they have selected the correct answer, and are then able to display the next question.
