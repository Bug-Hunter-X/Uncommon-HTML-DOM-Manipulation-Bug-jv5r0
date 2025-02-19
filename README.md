# Uncommon HTML DOM Manipulation Bug

This repository demonstrates a subtle bug related to manipulating the Document Object Model (DOM) in HTML.  The issue occurs when attempting to access and modify DOM elements before the page has fully loaded.  This can lead to unexpected behavior or errors.

The `bug.html` file shows the problematic code. The `bugSolution.html` file provides a corrected version, ensuring that the DOM manipulation occurs after the page has completely loaded.

This example highlights the importance of using appropriate event listeners (like `DOMContentLoaded` or `load`) to ensure that DOM elements are ready before interacting with them.