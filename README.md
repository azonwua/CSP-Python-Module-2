# CSP-Python-Module-2

# Text Analyzer

## Project Overview

This project is a refactored version of a Python text analyzer. The program reads sample.txt and displays the total number of words, unique words, five most common words, and the number of words longer than three characters.

## How to Run

Make sure text_analyzer.py and sample.txt are in the same folder.

Open the terminal and run:


### PEP 8

I used snake_case , proper indentation, spacing, and descriptive names to make the code easier to read.

### Context Manager

I used a with statement to open the file. This automatically closes the file when finished and helps prevent errors.

### List Comprehension

I used a list comprehension to find words longer than three characters:

python
word for word in words if len(word)>3


This makes the code shorter and cleaner.

### Counter

I used collections.counter to count how often each word appears. This replaces the longer manual dictionary loop and makes it easier to find the most common words.

### Functions

I separated the program into smaller functions for reading the file, getting the words, counting words, finding long words, and analyzing the text.

## Files

* unpythonic_analyzer.py - Original code
* text_analyzer.py - Refactored code
* sample.txt - Test file
* README.md - Project information

## Video
Link: https://youtu.be/C7vlYp_3yj8
