# Unexpected Calculation Result using CSS calc()

This repository demonstrates a bug where the CSS `calc()` function produces an unexpected result when calculating the width of an element based on the viewport width.  The expected width is not achieved, leading to layout issues.

## Bug Description

The `calc()` function is used to dynamically calculate the width of an element. However, the calculated width is consistently smaller than the expected value. This is likely caused by incorrect order of operations, missing units, or unexpected behavior with viewport units.

## Solution

The solution involves carefully checking the syntax and units within the `calc()` expression, ensuring correct operator precedence, and potentially using different units or alternative calculation methods to achieve the desired result.

## Setup

1. Clone the repository: `git clone <repository_url>`
2. Open `bug.css` to see the problematic code and `bugSolution.css` to see the solution.
3. Open the HTML file in a browser to observe the layout issues and the corrected layout.