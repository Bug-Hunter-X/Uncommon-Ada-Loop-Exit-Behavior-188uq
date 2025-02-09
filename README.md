# Ada Uncommon Loop Exit Example
This repository demonstrates a subtle issue related to exiting loops in Ada when iterating over array ranges.  The `exit` statement is used inside a `for` loop iterating over an array, leading to premature termination.
The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides a corrected version with an explanation.