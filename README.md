# Voting-System

This is a simple web-based voting system that allows users to select their favorite programming language from a list of options. The system displays the percentage of votes each option has received after a user has made a selection.

Features
Dynamic Poll Display: The question and answers are dynamically rendered from JavaScript.
Real-time Voting Results: When a user selects an option, the percentage of votes is immediately updated and displayed with a smooth animation.
Responsive Design: The poll is centered and designed to be responsive on different screen sizes.

Key Functions

markAnswer(i)

This function is triggered when a user clicks on one of the poll answers. It updates the selectedAnswer in the poll object and highlights the selected answer.

showResults()

This function calculates the percentage of votes each answer received and updates the width of the corresponding percentage bar. It also displays the percentage value next to each answer.
