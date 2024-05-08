# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: I want one button to run both the function which adds numbers to the points as well as the function which updates the screen.
 - Solution1.1: Add semicolons [failure]
 - Solution1.2: Integrate both functions into one overarching function [failure]
 - Solution1.3: Start drinking [failure]
 - Solution1.4: In the function I only established the existance of the functions but didn't run them. I pulled out the establishing functions out of the overarching function and replaced them with simple run functions. I had also forgotten to add colons to the onclick property. 

2. Problem: I want to be able to replace a string of text at the click of a button using a function. Said function is supposed to replace a string of text with an empty string if the variable contains a specific message and vice versa, but it refuses to work.
 - Solution2.1: Just doing it [failure]
 - Solution2.2: see Solution1.3
 - Solution2.3: Had the same name for the function as the variable, so I changed one of them. Replaced the "+=" with just "=".

3. Problem: If a person stands, while the computer has already stood, then can draw another card, which it shouldn't be able to.
 - Solution 3.1: The relevant conditions needed to be written with two "=" instead of one
