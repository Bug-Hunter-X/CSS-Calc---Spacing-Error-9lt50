# CSS Calc() Spacing Bug

This repository demonstrates a common, subtle bug in CSS that arises from unexpected spacing requirements within the `calc()` function.  Incorrect spacing can lead to unexpected results or parsing errors, making it hard to debug.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` demonstrates the correct solution.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected width of the element.  Compare with expected results as shown in bugSolution.css

## Solution

The solution involves removing any unnecessary spaces around the operators within the `calc()` function.