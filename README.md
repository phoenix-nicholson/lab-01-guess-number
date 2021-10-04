# Alchemy Bootstrap Template

## Making a plan

## HTML Elements (View - what is static and what is dynamic?)
Title: static
Header: s
Explain rules: s
Input of type number for specifying guess: d
Submit button: s
Display of number of tries remaining: d
Display of guess too high or too low: d
Display of lose and win result: d

## State:
Initial states:
    - Number of tries remaining: 3
Input number type: Between 1-20 (including both)/ Use compareNumbers to compare guessed number to actual number
Number of tries remaining: If they guess correct or use up guesses, disable further input and display an endlose or win message (decrement tries remaining)
Guess too high/low: Display message "You guessed (too high or too low)
Lose result: display lose message, diable game play and try again
win result: display win message, disable game play and try again

(bolded steps are mandatory, unbolded are for more advanced projects)

1) **Make a drawing of your app. Simple "wireframes"**
2) **Once you have a drawing, name the HTML elements you'll need to realize your vision**
3) **For each HTML element ask: Why do I need this?**
4) Ask which of out HTML elements are hard coded, and which are dynamically generated?
5) **Once we know _why_ we need each element, think about how to implement the "Why" as a "How"**
6) Is there some state we need to initialize?
7) **Find all the 'events' (user clicks, form submit, on load etc) in your app. Ask one by one, "What happens when" for each of these events. Does any state change?**
8) **Think about how to validate each of your steps**
9) Ask: should any of this work be abstracted into functions? (i.e., is the work complicated? can it be resused?)
10) Consider your data model. What objects will you be using? What are the key/value pairs? What arrays do you need? What needs to live in local storage?
11) **Consider what features _depend_ on what other features. Use this dependency logic to figure out what order to complete tasks.**


## To Run Cypress Tests
* `npm install`
* `npm test`
* Cypress will open -- you should then click "run <#> integration spec(s)"
    ![](cypress.png)
* Make sure all tests pass