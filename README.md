# `SatisfiabilityInterface.jl` 

A [Julia](www.julialang.org) package for modelling discrete constraint satisfaction problems and encoding them to Boolean satisfiability (SAT) problems.

## Usage

See this [short video from JuliaCon 2021](https://www.youtube.com/watch?v=F5QuDrTkAow), 
which uses [this Pluto notebook](docs/satisfiability_juliacon_2021.pluto.jl).

See also the `examples` directory for basic usage. 



Currently for actually solving the resulting SAT problem you need to install the `CryptoMiniSAT5` SAT solver, e.g. with

`brew install cryptominisat`

on Mac.

In the future this will be installed automatically.


## Author

Copyright David P. Sanders 2021
