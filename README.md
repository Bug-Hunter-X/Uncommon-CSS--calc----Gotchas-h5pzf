# Uncommon CSS `calc()` Gotchas
This repository demonstrates some uncommon issues that can arise when using the CSS `calc()` function. The `bug.css` file showcases the problems, while `bugSolution.css` provides corrected versions.

**Issues Covered:**
* Unexpected results when `calc()` is used with percentages and fixed values in situations where the container's dimensions are dynamically determined by its content.
* Errors caused by incorrectly mixing units without proper parenthesization.
* Misinterpretations due to incorrect operator precedence.
* Potential browser compatibility problems related to the usage of `calc()`.

**How to Reproduce:**
1. Clone this repository.
2. Open `bug.html` in a web browser to see the issues in action.
3. Refer to `bugSolution.css` for the corrected code and explanations. 