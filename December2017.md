## 12/1 
Hours: 0 

## 12/2
### EWASM:
Hours: 5
 - WIP: Ethereum state tests transcompiled to EWASM at runtime and run through ethereumjs-vm: https://github.com/jwasinger/ethereumjs-vm#wip/ewasm

## 12/3
### EWASM:
Hours: 8
 - Attempted to transcompile ethereum tests to ewasm at runtime in ethereumjs-vm.  Spent time debugging a memory leak when invoking `evm2wasm` in nested asynchronous code.  Separate approach is to transcompile all the state tests to EWASM as part of a build process. See: https://github.com/jwasinger/ewasm-tests

## 12/4
### EWASM:
Hours: 8
  - Identifying/Debugging frustrating npm bug which doesn't download submodules correctly for packages listed under `devDependencies`

## 12/5

## 12/6

## 12/7

## 12/8

## 12/9

## 12/10

## 12/11
Hours: 9
### EthereumJS:
 - EthereumJS meeting
 - Fixing memory revamp PR: https://github.com/ethereumjs/ethereumjs-vm/pull/174
 - PR rebasing/review

## 12/12
Hours: 8
### EthereumJS:
 - PR Review
### Tests:
 - new test case for un-tested edge case: https://github.com/ethereum/tests/pull/382

## 12/13
Hours: 2
### EthereumJS:
 - PR reviews

## 12/14
Hours:
### EthereumJS:
 ...

### 12/15
Hours: 4

## 12/15
Hours: 

## 12/16
Hours: 4
### EthereumJS:
 - Fix to make ewasm-transcompiled state tests valid: https://github.com/jwasinger/ewasm-tests
 - PR review

## 12/17
Hours: 4
### Testing
 - trace equivalence tester for ethereumjs-vm

## 12/18
Hours: 8
### EthereumJS:
 - investigating https://github.com/ethereumjs/ethereumjs-vm/pull/159, working on fixing some issues I caused during a faulty rebase

## 12/19
Hours: 8
### EWASM:
 - weekly meeting
 - looking at evm2wasm prototype to determine how to port to C
 - seeing which parts of ethereumJS can be extracted and used in ewasm-kernel (statemanager, runState -> environment)

## 12/20
Hours: 8
### EthereumJS
 - PR Reviews for ethereumjs-vm and ethereumjs-tx

# 12/21
Hours: 3
### EWASM
 - eWasm debugging call with @cdetrio and @hugo-dc

# 12/26
Hours: 6
### EWASM
 - trying to figure out how to get a loop to work in eWASM.
 - Figuring out how to transcompile C to eWASM

# 12/27
Hours: 2
### EWASM
 - spent time trying to figure out how to get simple loop working before realizing that I was using an older version of wabt to compile ...
