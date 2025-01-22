# Julia Function Bug
This repository demonstrates a subtle bug in a Julia function that exhibits unexpected behavior when the input is zero.

## Bug Description
The `myfunction` function is intended to return the square of a positive number and the negation of a negative number. However, it unexpectedly returns zero when the input is zero.

## How to Reproduce
1. Clone this repository.
2. Run `bug.jl`.
3. Observe the unexpected output for the input zero.

## Solution
The `bugSolution.jl` file contains the corrected function which handles the case where input is zero explicitly. 
