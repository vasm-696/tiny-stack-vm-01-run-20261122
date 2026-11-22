# tiny-stack-vm-01-run-20261122

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/vasm-696/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/vasm-696/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A faithful port of make.fun's reference VM for its tiny stack ISA
(`program/generator/subject/vm.mjs` in the kit): 32-bit wrapping arithmetic,
256-value stack, 64-deep call stack, 256 words of memory, input/output, and
all ten traps with their own exit codes, in the order ISA.md states them.
Runs all 40 instances in one Node 22 process, well inside the 60-second wall.

Local practice set: 40/40 instances byte-exact, score 1,000,000/1,000,000
(house baseline plain-vm 1.0.0 scores 670,000 on the same set).
