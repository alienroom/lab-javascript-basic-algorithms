![logo_ironhack_blue 7](https://github.com/alienroom/ALIENROOM-Logos-png/blob/main/arReadMe.png)

# LAB | JS Basic Algorithms 

Welcome to your first exercise at AlienRoom!

The goal of this exercise is to get you familiarized with the primitive data structures in JavaScript, be curious and use Google to explore multiple solutions.

Ready?

## Introduction

For this **pair-programming** activity we are going to use a [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop). You can find a REPL that runs in the browser for programming languages as JavaScript in [https://repl.it/languages/babel](https://repl.it/languages/babel).

Ready to start?


## Requirements

- Fork this repo
- Clone this repo
- Go to [repl.it](https://repl.it/languages/nodejs) and create an account (or login if you have one)
- Type this in the *Code Editor* (left panel)

  ```javascript
  console.log("I'm ready!");
  ```
- Press `run ►`
- If you can see the message in the right side panel, you are really ready!

  <!-- ![](https://i.imgur.com/4TQislb.png) -->
  ![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_17f095b9bb4fa4bd1bee1c017c043327.png)


## Submission

Upon completion, run the following commands:
```
$ git add .
$ git commit -m "done"
$ git push origin master
```

## Instructions

### Iteration 1: Names and Input

	1.1 Create a variable `hacker1` with the driver's name.

	1.2 Print `"The driver's name is XXXX"`.

  	1.3 Create a variable `hacker2` with the navigator's name.

  	1.4 Print `"The navigator's name is YYYY"`.

### Iteration 2: Conditionals
  2.1. Depending on which name [is longer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length), print:
  <br>
	  - `The driver has the longest name, it has XX characters.` or <br>
	  - `It seems that the navigator has the longest name, it has XX characters.` or <br>
	  - `Wow, you both have equally long names, XX characters!`.

### Iteration 3: Loops
  3.1 Print all the characters of the driver's name, separated by a space and [in capitals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase)
  i.e. `"J O H N"`
  
  3.2 Print all the characters of the navigator's name, in reverse order. 
  i.e. `"nhoJ"`
  
  3.3 Depending on the [lexicographic order](https://en.wikipedia.org/wiki/Lexicographical_order) of the strings, print: <br>
    - `The driver's name goes first.` <br>
    - `Yo, the navigator goes first definitely.` <br>
    - `What?! You both have the same name?`

### Bonus Time!

#### Bonus 1:
Go to [lorem ipsum generator](http://www.lipsum.com/) and:
  - Generate 3 paragraphs. Store the text in a variable type of string.
  - Make your program count the number of words in the string.
  - Make your program count the number of times the Latin word [`et`](https://en.wiktionary.org/wiki/et#Latin) appears.

#### Bonus 2:
Create a new variable `phraseToCheck` and have it contain some string value. Write a code that will check if the value we assigned to this variable is a [Palindrome](https://en.wikipedia.org/wiki/Palindrome). Here are some examples of palindromes: 
  - "A man, a plan, a canal, Panama!"
  - "Amor, Roma"
  - "race car"
  - "stack cats"
  - "step on no pets"
  - "taco cat"
  - "put it up"
  - "Was it a car or a cat I saw?" and "No 'x' in Nixon".
  
  __Hint__: If you use Google to help you to find solution to this iteration, you might run into some solutions that use advanced string or array methods (such as _join()_, _reverse()_, etc.). However, try to apply the knowledge you currently have since you can build pretty nice solution with just using `for` loop, `if-else` statements with some `break` and `continue`... Just sayin' :smiley: 

## Extra Resources

- [String - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [if - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [while - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [for - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)


__ALIENROOM CodeLab happy coding!__ :alien: :flying_saucer: :heart:
