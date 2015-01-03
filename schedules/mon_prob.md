# Week 6
## Building A Game

| Objectives |
| :--- | 
| become more familiar with DOM manipulation using jQuery |
| utilize JS to synthesize a client side application |
| practice pair programming and document research |


We will be building a simple typing game using jQuery.

## Phase 1: Appending and Time

* Build a client side application using jQuery that appends a `div` to the page that displays a random character `a-z`.
* Modify your application to append an element to the page every second.
* Modify your application to use jQuery to append a `div` with `id` of `gameBoard`, and then append all characters to the gameboard.

### Bonus

* Create CSS classes `red`, `blue`, and `green` that just have the style for the respective background colors. 
* As you append characters to the `gameBoard` add a random class of `red`, `green`, or `blue`.

## Phase 2: Using events

* Modify your application to listen for a keypress.
	* Use the incoming event to find the key that was pressed and alert it. 
* Modify your application to find the `first` div that has a matching character in the `gameBoard` and remove it from the `gameBoard`.

### Bonus 

* Add a `data` attribute to the `div` that saves the `charCode`.
* Implement your own remove method using the DOM `removeChild` method.


## Phase 3: Making Animations

We want our character divs to move from right to left on the gameBoard, but this might be hard to right away with our current application.

Let's start a new HTML file with a script that tries to do the following:

### Part 1

* Use jQuery to put a `div` on the page that says `Hello, World!`. Give the `div` a width and height of `100px`.
* Use `setInterval` or `setTimeout` to move the `div` from left to right the page across the page. 
* Find the `width` of the window and when the div reaches the right of the window remove it from the page.


### Part 2

* Modify part 1 by using jQuery to append a `gameBoard` div to the page and then appending the `Hello, World` div to the `gameBoard`. Give the gameBoard a width of `90%`, a left and right margin of `5%`, and a height of `500px`.
* Use the width of the gameBoard and it's position left to determine when the moving div leaves the `gameBoard`. Then remove the div from the gameBoard.

### Part 3

Use your practice from part 1 and 2 to modify your game from phase 2 to animate characters to move from left to right across the gameBoard.

## Phase 4: Style it up and Add Bonus features

* Give the divs a random top positioning relative to the gameBoard.
* Add buttons to slow down or speed how fast the characters are moving across the `gameBoard`. Hint this will be harder if you've used `setInterval`.
