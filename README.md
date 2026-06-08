## Overview

This repository contains a dataset of equivalent and non-equivalent Dafny functions. These are designed to be used to benchmark program equivalence checkers. Each file contains at least one pair of equivalent Dafny functions. 

## Structure

The `Eq` and `Neq` directories contain the equivalent and non-equivalent tests respectively. Each directory is split into sub-directories according to where the tests they contain were taken from. The four sources are described below:

- `eqBench`: The CLEVER and REVE benchmarks in the EqBench dataset (https://github.com/shrBadihi/EqBench)
- `measureTransfer`: The dataset from the paper ["Proving Termination via Measure Transfer in Equivalence Checking"](https://doi.org/10.1007/978-3-031-76554-4_5)
- `self`: Self-written tests
- `stainless`: The program equivalence tests for the Stainless program verifier (https://github.com/epfl-lara/stainless/tree/main/frontends/benchmarks/equivalence)
