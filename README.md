# Color Calculator

In this project we'll create a program that can combine and deconstruct colors according to the following tables

#### Color combining

| inputs | output |
| --- | --- |
| red + blue | purple |
| red + yellow | orange |
| blue + yellow | green |
| anything else | "error" |

#### Color deconstructing

| input | outputs |
| --- | --- |
| purple | red + blue |
| orange | red + yellow |
| green | blue + yellow |
| anything else | error |

We won't worry about any colors that are neither primary nor secondary colors.

## Your program

Your program should prompt the user for whether they want to combine colors or deconstruct a color (it's up to you what this user interface looks like exactly).

If the user chooses to combine, prompt them for two colors (one at a time). Combine the colors (using if, else if, and else statements) then log the result.

If the user chooses to deconstruct, prompt them for a single color. Deconstruct the color (using if, else if, and else statements) then log the result.

## Stretch goals

Remove the intial question about whether the user wants to combine or deconstruct. Instead, prompt the user a single time for colors. If the user inputs a single color (i.e.: "purple"), deconstruct it. If the user inputs two colors separated by a space, (i.e.: "red blue"), combine them.

To do this, check out the string method, `.includes()`: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes OR https://www.w3schools.com/jsref/jsref_includes.asp
