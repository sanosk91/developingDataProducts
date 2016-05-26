---
title       : Guess The Number
subtitle    : A Shiny application to guess the number picked by the Computer
author      : Raju Tandukar
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Objective

The objective of this game is to guess an integer between 1 and 100 (inclusive) and try to match it with the computer's selection.

It is just a small program as a prototype of Shiny application

--- .class #id 

## How to play?

Playing the game is simple.

- Computer selects a number when you run the program

- You make a guess

- If the guess is right, you get a Correct! notification

- Else you get to know if the guessed number is lower or upper than the computer selected number

--- .class #id 

## The Build

This program is build using the simple prediction approach.


```r
#The computer guesses a random number between 1 and 100
number <- floor(runif(1,1,101))

#Below is displayed the random number guessed by the computer
print(number)
```

```
## [1] 54
```
After the computer completes guess, its the user who should guess

--- .class #id 

## Play yourself

Want to try yourself the game? 

Go to - https://rajutandukar.shinyapps.io/dataproducts/

Thank you!
