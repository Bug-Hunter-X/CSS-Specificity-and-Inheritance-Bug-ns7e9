# CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug in CSS related to specificity and inheritance.  The bug involves unexpected font size inheritance when a more specific selector overrides a less specific one, but the expected inheritance doesn't occur.

The `bug.css` file contains the buggy CSS code. The `bugSolution.css` file provides a solution.

## Bug Description

A `<p>` element with the class `special` nested inside a `.container` div unexpectedly inherits the `font-size` from a more general selector instead of the more specific one, which should take precedence.