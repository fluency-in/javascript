# JavaScript Exercises

Each subdirectory in this repository is an exercise.

Each exercise consists of a README.md and some automated tests.

These tests use jasmine-node, which is a testing framework written for Node.js.

You will need:

* Node.js
* The Node Package Manager (NPM)
* jasmine-node

You can install both Node.js and NPM with a download from nodejs.org: https://nodejs.org/en/download

Use NPM to install jasmine-node:

    npm install jasmine-node -g

To work on an exercise, change to the directory of the exercise:

    cd hello-world

This contains the files for the exercise.

    .
    ├── README.md
    └── hello-world.spec.js

To run a test file, pass it as an argument to the `jasmine-node` command:

    jasmine-node hello-world.spec.js



## Exercises

These are ordered roughly in order of difficulty.
The README.md file for each exercise explains in more detail what the exercise is about.

  **leap**
  Write a program that will take a year and report if it is a leap year.

  **hamming**
  Write a program that can calculate the Hamming difference between two DNA strands.

  **rna-transcription**
  Write a program that, given a DNA strand, returns its RNA complement (per RNA transcription).

  **bob**
  Bob is a lackadaisical teenager. In conversation, his responses are very limited.

  **gigasecond**
  Write a program that calculates the moment when someone has lived for 10^9 seconds.

  **word-count**
  Write a program that given a phrase can count the occurrences of each word in that phrase.

  **isogram**
  Determine if a word or phrase is an isogram.

  **pangram**
  Determine if a sentence is a pangram.

  **beer-song**
  Write a program which produces the lyrics to that beloved classic, that field-trip favorite: 99 Bottles of Beer on the Wall.

  **phone-number**
  Write a program that cleans up user-entered phone numbers so that they can be sent SMS messages.

  **anagram**
  Write a program that, given a word and a list of possible anagrams, selects the correct sublist.

  **food-chain**
  Write a program that generates the lyrics of the song 'I Know an Old Lady Who Swallowed a Fly'

  **grade-school**
  Write a small archiving program that stores students' names along with the grade that they are in.

  **robot-name**
  Write a program that manages robot factory settings.

  **etl**
  We are going to do the `Transform` step of an Extract-Transform-Load.

  **space-age**
  Write a program that, given an age in seconds, calculates how old someone is in terms of a given planet's solar years.

  **grains**
  Write a program that calculates the number of grains of wheat on a chessboard given that the number on each square doubles.

  **triangle**
  Write a program that can tell you if a triangle is equilateral, isosceles, or scalene.

  **clock**
  Implement a clock that handles times without dates.

  **acronym**
  Convert a long phrase to its acronym

  **scrabble-score**
  Write a program that, given a word, computes the scrabble score for that word.

  **roman-numerals**
  Write a function to convert from normal numbers to Roman Numerals.

  **circular-buffer**
  A data structure that uses a single, fixed-size buffer as if it were connected end-to-end.

  **binary**
  Write a program that will convert a binary number, represented as a string (e.g. '101010'), to its decimal equivalent using first principles

  **prime-factors**
  Compute the prime factors of a given natural number.

  **raindrops**
  Write a program that converts a number to a string, the contents of which depends on the number's factors.

  **allergies**
  Write a program that, given a person's allergy score, can tell them whether or not they're allergic to a given item, and their full list of allergies.

  **strain**
  Implement the `keep` and `discard` operation on collections. Given a collection and a predicate on the collection's elements, `keep` returns a new collection containing those elements where the predicate is true, while `discard` returns a new collection containing those elements where the predicate is false.

  **atbash-cipher**
  Create an implementation of the atbash cipher, an ancient encryption system created in the Middle East.

  **accumulate**
  Implement the `accumulate` operation, which, given a collection and an operation to perform on each element of the collection, returns a new collection containing the result of applying that operation to each element of the input collection.

  **crypto-square**
  Implement the classic method for composing secret messages called a square code.

  **trinary**
  Write a program that will convert a trinary number, represented as a string (e.g. '102012'), to its decimal equivalent using first principles.

  **sieve**
  Write a program that uses the Sieve of Eratosthenes to find all the primes from 2 up to a given number.

  **simple-cipher**
  Implement a simple shift cipher like Caesar and a more secure substitution cipher

  **octal**
  Write a program that will convert a octal number, represented as a string (e.g. '1735263'), to its decimal equivalent using first principles (i.e. no, you may not use built-in or external libraries to accomplish the conversion).

  **luhn**
  Write a program that can take a number and determine whether or not it is valid per the Luhn formula.

  **pig-latin**
  Implement a program that translates from English to Pig Latin

  **pythagorean-triplet**
  There exists exactly one Pythagorean triplet for which a + b + c = 1000. Find the product a * b * c.

  **series**
  Write a program that will take a string of digits and give you all the contiguous substrings of length `n` in that string.

  **difference-of-squares**
  Find the difference between the sum of the squares and the square of the sums of the first N natural numbers.

  **secret-handshake**
  Write a program that will take a decimal number, and convert it to the appropriate sequence of events for a secret handshake.

  **linked-list**
  Implement a doubly linked list

  **wordy**
  Write a program that takes a word problem and returns the answer as an integer.

  **flatten-array**
  Write a program that will take a nested list and returns a single list with all values except nill/null

  **hexadecimal**
  Write a program that will convert a hexadecimal number, represented as a string (e.g. "10af8c"), to its decimal equivalent using first principles (i.e. no, you may not use built-in or external libraries to accomplish the conversion).

  **largest-series-product**
  Write a program that, when given a string of digits, can calculate the largest product for a contiguous substring of digits of length n.

  **kindergarten-garden**
  Write a program that, given a diagram, can tell you which plants each child in the kindergarten class is responsible for.

  **binary-search**
  Write a program that implements a binary search algorithm.

  **binary-search-tree**
  Write a program that inserts numbers and searches in a binary tree.

  **matrix**
  Write a program that, given a string representing a matrix of numbers, can return the rows and columns of that matrix.

  **robot-simulator**
  Write a robot simulator.

  **nth-prime**
  Write a program that can tell you what the nth prime is.

  **palindrome-products**
  Write a program that can detect palindrome products in a given range.

  **pascals-triangle**
  Write a program that computes Pascal's triangle up to a given number of rows.

  **say**
  Write a program that will take a number from 0 to 999,999,999,999 and spell out that number in English.

  **custom-set**
  Create a custom set type.

  **sum-of-multiples**
  Write a program that, given a number, can find the sum of all the multiples of particular numbers up to but not including that number.

  **queen-attack**
  Write a program that positions two queens on a chess board and indicates whether or not they are positioned so that they can attack each other.

  **saddle-points**
  Write a program that detects saddle points in a matrix.

  **ocr-numbers**
  Write a program that, given a 3 x 4 grid of pipes, underscores, and spaces, can determine which number is represented, or whether it is garbled.

  **meetup**
  Calculate the date of meetups.

  **bracket-push**
  Make sure the brackets and braces all match.

  **two-bucket**
  Given two buckets of different size, write a program to demonstrate how to measure an exact number of liters.

  **bowling**
  Score a bowling game


## Source

These exercises are from the [JavaScript][javascript] track on [Exercism][exercism]

[exercism]: http://exercism.io
[javascript]: http://exercism.io/languages/javascript
