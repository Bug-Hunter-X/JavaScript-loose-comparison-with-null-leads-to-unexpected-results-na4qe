# JavaScript Loose Comparison Bug

This repository demonstrates a common JavaScript bug involving loose comparison (==) with null. The `foo` function demonstrates unexpected behavior when comparing numbers with `null`.  The issue arises from JavaScript's type coercion during loose comparisons, leading to unexpected outcomes.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version using strict equality (===).