# Simple Operating System

The simulation of major components in a simple operating system, for example, scheduler synchronization, related operations of physical memory and virtual memory.

## Prerequisites

- `Ubuntu` 22.04 LTS

## Commands

- `make all`: compile the whole source code.
- `./os [path to configure file]`: run simulation  
`[path to configure file]` in folder **input**
```sh
make all
./os os_0_mlq_paging
```

## Project structure

```py
 ┣ 📂docs           # Documentation for this repo.
 ┣ 📂include        # Header files.
 ┣ 📂input          # Samples input used for verification.
 ┣ 📂obj            # Include objects file after run make all.
 ┣ 📂output         # Samples output of the operating system.
 ┣ 📂src            # Source files.
 ┣ 📜Makefile       # Include scripts to compile source code. 
```
