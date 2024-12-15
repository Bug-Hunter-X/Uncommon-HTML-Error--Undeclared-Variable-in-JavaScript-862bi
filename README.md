# Uncommon HTML Error: Undeclared Variable in JavaScript

This repository demonstrates a subtle error that can occur when embedding JavaScript within HTML. The error involves using a variable that hasn't been declared, which can lead to unexpected behavior in the browser.

## The Bug

The `bug.html` file contains a simple HTML structure with a `div` element and some JavaScript code. The JavaScript code attempts to set the `innerHTML` property of the `div` element to the value of a variable named `myVar`.  However, `myVar` is never declared, which can lead to a runtime error or unexpected behavior in some browsers.

## The Solution

The `bugSolution.html` file demonstrates the correct way to handle this situation. It declares the `myVar` variable and assigns it a value before using it in the JavaScript code.