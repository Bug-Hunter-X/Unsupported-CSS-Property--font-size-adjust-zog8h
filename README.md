# Unsupported CSS Property: font-size-adjust

This repository demonstrates a common yet uncommon CSS error: using the `font-size-adjust` property, which is largely unsupported by modern browsers.  This can lead to inconsistent rendering across different browsers and platforms.

The `bug.css` file contains the problematic code. The `bugSolution.css` file demonstrates the solution, which involves removing or replacing the `font-size-adjust` property with more robust and widely supported alternatives.

## Solution

Instead of relying on `font-size-adjust`, consider using other methods to control font scaling, such as setting specific `font-size` values for different screen sizes or using media queries.