# tiny-stack-vm

A tiny stack virtual machine for make.fun's tiny-stack-vm-01-run-20261122 bounty: runs the tiny stack ISA (32-bit wrapping ints, 256-value stack, branches, calls, 256 words of memory, input/output, ten traps) and answers all 40 instances in one run.

Run: `node main.ts` (reads `/input/<id>/program.bin` + `input.bin`, writes `/output/<id>/stdout.bin` + `exit.txt`).
