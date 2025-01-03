# CSS calc() Issue in Media Queries

This repository demonstrates a common issue with the CSS `calc()` function when used with percentages inside media queries. The issue is that the `calc()` function doesn't directly support percentages in this context.

## Bug
The `bug.css` file shows the erroneous implementation. The media query attempts to use `calc(100% - 50px)`, which doesn't work as expected.

## Solution
The `bugSolution.css` file provides the correct implementation. Instead of using percentages directly with `calc()`, it uses viewport units (`vw`) to achieve the desired behavior.

## How to reproduce

1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Observe the behavior.
4. Switch to `bugSolution.html` to see the fix.