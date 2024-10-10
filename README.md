# APAI-LAB03: Basics of Embedded Programming on PULP

## Summary:
The target device for the lab sessions is the multi-core [PULP](https://github.com/pulp-platform/pulp) platform.
The PULP Virtual Platform simulator GVSOC, which is included within the [PULP SDK](https://github.com/pulp-platform/pulp-sdk), will be used during the class.

- **Subject(s)**: hello-world, vector sum, matrix-vector mul, profiling code execution;
- **Programming Language**: C;
- **Lab duration**: 3h
- **Objective**: Embedded programming & profiling. You will learn basics of embedded programming, the pulp architecture, basic operations (sum & matmul), and how to profile your code execution (MAC, cycles) !


## How to deliver the assignment:

Use Virtuale, upload only the assignment file named as follows: LAB#_APAI_yourname.ipynb


**Assignment DEADLINE: 18/10/2023 (at 14:30)**

___

## Quickstart

### How to set the environment

1. Open the VirtualBox virtual machine
2. Open a terminal (CTRL+T or open terminal)
3. Launch the commands (clone repo, move into folder, open Visual Studio Code):
```
git clone https://github.com/EEESlab/APAI24-LAB02-PULP-Embedded-Programming
cd APAI24-LAB02-PULP-Embedded-Programming/
code .
```
4. Now you're ready to start!

#### How to run the code
**[DO NOT FORGET]** Every time you open a new terminal run:

`source setup_pulp_sdk.sh`

To run the code enter in a terminal

`make clean all run`
