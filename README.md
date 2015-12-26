# Julia Experiments
A small collection of Julia experiments I created while learning Julia. Please take that into consideration while reviewing the code, I am open to any optimizations as long as they don't obliterate the code.

## Finished experiments
### zeckendorf.jl
A small piece of code implementing Zeckendorf's theorem. Who does not know of it, *[Zeckendorf's theorem](https://en.wikipedia.org/wiki/Zeckendorf%27s_theorem)* is a proven theorem stating that every non-negative integer N can be represented by a sequence of Fibonacci numbers which can be encoded as a binary string.

## How to run
Every experiment folders contains one or more source files and at least one test files. Most of the experiments are made for the REPL-use, so feel free to `include` the main source file (the one with the experiment's name).

You can test the experiments by running `julia [experiment]_test.jl` and replace `[experiment]` with the experiment.

> **Example:** To test the zeckendorf.jl experiment run `julia zeckendorf_test.jl`
