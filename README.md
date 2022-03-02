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
```bash
cd sat_symmetry
source .env
make third_party
make
cd ../simp
make rs
```
## Running
------
**BLISS**: ```bash 
            ./simp/runner/esbp_sel bliss CNF_FILE 
            ```

**SAUCY**: ```bash
            ./simp/runner/esbp_sel saucy CNF_FILE 
            ```

## Information:
```bash
    ./glucose --help 
```
