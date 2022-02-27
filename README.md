=====================================================================
# Implementation of ESBP_SEL a SAT solver Symmetric Explanation Learning (SEL) with Cosy library.
=====================================================================

## Directory overview:
-------------------

`core/` A core version of the solver glucose (no main here)  
`experiments/` An extended solver with simplification capabilities  
`mtl/` MiniSat Template Library  
`parallel/` A multicore version of glucose **! Not compatible with SEL ! **  
`simp/` An extended solver with simplification capabilities  
`testfiles/` Some test cnfs with a corresponding symmetry file  
`utils/` MiniSat util files  
`README`  
`LICENCE`  
`Changelog`  

## Building
-------
`cd sat_symmetry`

`source .env`

`make third_party`

`make`

`cd ../simp`  

`make rs`
## Running
------
**BLISS**: `./simp/runner/esbp_sel CNF_FILE bliss `

**SAUCY**: `./simp/runner/esbp_sel CNF_FILE saucy `

## Information:
`./glucose --help`  
