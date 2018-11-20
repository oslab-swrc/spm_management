# spm_management

## Function-splitter
Function-splitter is a source code transformation tool for function-level code management on Scratchpad Memories, built on LLVM and Clang.

To use these files, first download and build LLVM and Clang from source.

Copy directory `tools/function-split` of this repo into Clang's tools directory, e.g. `(LLVM_DIR)/tools/clang/tools`, and build clang again. 

## Function Inlining/Outlining for SPM Management
It is an extension of function-splitter, whihch exploits both of function outlining (splitting) and inlining. 

## Proactive Function Loading
Proactive Function Loading is a technique to improve the parallelism between DMA and CPU by prefetching functions before its execution.
